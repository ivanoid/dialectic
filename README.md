# Dialectic

[![skills.sh](https://skills.sh/b/ivanoid/dialectic)](https://skills.sh/ivanoid/dialectic)

An Agent Skill for sustained reflective dialogue that helps a person form, examine, and own their thinking without the model thinking in their place.

Dialectic grew from a simple dissatisfaction with many "Socratic" prompts: they often become questionnaires, manufacture tension, or reward the assistant for sounding insightful. This skill instead treats success as movement in the user's own thought—a sharper distinction, a revised premise, a better question, or an honest decision to leave something unresolved.

Its governing principle is **formation before testing**.

## Modes

- **Maieutic mode** helps a half-formed thought acquire its own language. It follows the user's wording, makes one conversational move at a time, and resists premature interpretation.
- **Open-page mode** gives the user uninterrupted room when questions begin to constrain expression. Reflection comes only after the account is complete.
- **Elenctic mode** pressure-tests a sufficiently formed position: one premise, definition, counterexample, consequence, or conflict at a time. Unrequested pressure is announced before it is applied.
- **Lateral mode** changes a constraining frame after there is enough form to know what must be preserved. It may shift an assumption, boundary, scale, mechanism, analogy, or problem formulation, then return the promising movement to articulation, research, or testing.

The modes are adaptive, not a fixed sequence. A position exposed as under-formed may return from elenchus to maieutics; testing may reveal a need for lateral reframing; a lateral route must eventually return to ownership and grounding. The dialogue may also stop without resolution when further probing would produce only compliance or repetition.

## Install

```bash
npx skills add https://github.com/ivanoid/dialectic --skill dialectic
```

Or copy the [`skills/dialectic`](skills/dialectic/) directory into an Agent Skills-compatible skills folder.

The skill follows the [Agent Skills specification](https://agentskills.io/specification). `agents/openai.yaml` adds Codex-facing display metadata and enables implicit invocation; other compatible agents may ignore it.

## Use

Explicit invocation is the most reliable:

```text
Use $dialectic to help me develop this thought without thinking in my place: ...
```

You can also ask for a particular mode or pressure level:

```text
Use maieutic mode. I have an intuition, but I do not yet know what I mean by it.

Open-page mode: let me write this out across several messages before you respond.

Switch to hard elenchus and test the strongest version of this belief.

Use lateral mode. Keep the central question and constraints intact, but help me see whether the current frame is limiting the possible answers.
```

## What it tries to avoid

- ending every reply with a question;
- hopping between locally interesting questions without a sustained inquiry;
- attributing hidden motives or experience to the user;
- testing a thought before the user can articulate it;
- manufacturing a binary or contradiction for dramatic effect;
- mistaking an idea dump, arbitrary random stimulus, or decorative analogy for lateral movement;
- hardening a cue into a claim or collapsing several live inquiries into the neatest one;
- replacing reflection with advice, diagnosis, coaching, or a polished assistant synthesis;
- treating an elegant synthesis as the discovered truth of the user's experience;
- introducing a developmental or relational lens because a framework makes it available rather than because the user's wording calls for it;
- scoring developmental maturity or inferring what the user is withholding;
- confusing discomfort, eloquence, agreement, or response length with insight;
- turning rest, beauty, play, or aimless experience into another technique for producing insight.

## Literature

Literary and philosophical references are deliberately rare. A bridge should appear only after an idea has matured, when one precise essay or article genuinely bears on the question and fits the user's reading practice. Books belong only in a requested deeper-reading path. Authority should widen the inquiry, never decide what an experience means.

## Evaluation and feedback

See [EVALUATION.md](EVALUATION.md) for prompts and a rubric. The central question is not "Was the model impressive?" but "Did the user's own representation of the problem move?"

Feedback and counterexamples are welcome through [GitHub Issues](https://github.com/ivanoid/dialectic/issues). Especially useful reports include the triggering prompt, several dialogue turns, what changed in the user's thinking, and where the method felt mechanical, leading, or inert. Please remove personal or identifying material before posting.

## Conceptual influences

The skill's discipline around preserving early cues, keeping several inquiry routes alive, seeking the smallest useful movement, and knowing when to stop or reopen was sharpened through engagement with Anatoly Levenchuk's [First Principles Framework](https://github.com/ailev/FPF). Dialectic adapts those ideas lightly for natural conversation; it does not implement FPF or expose its formal vocabulary to the user.

A second selective influence comes from Veraksa, Basseches, and Brandão's account of [dialectical thinking as differentiation and provisional integration](https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2022.710815/full), and Otto Laske's [pointing–elaborating–linking sequence and context/process/relationship/transformation lenses](https://integralleadershipreview.com/15338-422-new-approach-dialog-teaching-dialectical-thought-form-framework-part-ii-dialoging-tools-dialectic/). Dialectic uses these as cue-led fallback heuristics, not as a thought-form taxonomy, cognitive profile, or developmental ranking.

Lateral mode takes its practical vocabulary of displacement and movement from Edward de Bono's [original distinction between lateral and vertical thinking](https://onlinelibrary.wiley.com/doi/10.1002/j.2162-6057.1969.tb00124.x), while treating creativity as an iterative generative and exploratory process rather than a final brainstorming stage. Its guardrails reflect evidence that [arbitrary random stimuli may not improve creative search](https://wrap.warwick.ac.uk/159029/) and that [LLM assistance can raise individual output quality while reducing diversity across outputs](https://doi.org/10.1126/sciadv.adn5290). The mode therefore favors anchored, [differentiated search](https://pubsonline.informs.org/doi/10.1287/orsc.2023.18430) and human selection over generic requests for more ideas.

## License

[MIT](LICENSE)
