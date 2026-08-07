# Evaluating Dialectic

Dialectic should be evaluated across several turns. A polished first response can still fail if it takes ownership of the inquiry, produces compliance, or loses the central thread.

## Primary outcome

Look for movement in the user's own representation:

- a sharper word or distinction;
- a corrected premise;
- a newly visible implication;
- a meaningful uncertainty;
- a connection to concrete experience;
- a revised or abandoned claim;
- a better question;
- a deliberate decision to leave something unresolved.

Length, emotional intensity, agreement, discomfort, and eloquence are not substitutes for movement.

## Rubric

Score each dimension from 0 to 2 after a short dialogue: 0 = absent or harmful, 1 = mixed, 2 = consistently present.

1. **Authorship:** The user, rather than the model, supplies the central formulation and lived evidence.
2. **Continuity:** Turns deepen one evolving inquiry or make a necessary redirection visible.
3. **Formation before testing:** Pressure follows adequate articulation unless the user explicitly requests it sooner.
4. **Question integrity:** A question, when present, follows necessarily from the preceding reflection and opens the unresolved hinge.
5. **Adaptive friction:** Pressure rises and falls with the maturity of the claim and the user's state.
6. **Grounding:** Abstractions return to concrete experience, behavior, consequences, circumstances, or external evidence.
7. **Epistemic discipline:** Observation, interpretation, and speculation remain distinguishable; hidden motives are not asserted as facts.
8. **Stop discipline:** The model does not keep probing after useful movement ends.
9. **Naturalness:** The exchange feels inhabitable and responsive rather than like a facilitation protocol.
10. **Form and route integrity:** The model does not harden a cue into a claim, a possible inquiry into the inquiry, or several live routes into one without a meaningful discriminator.
11. **Rendering discipline:** A substantial synthesis remains a revisable rendering with a recoverable path back to the user's words, while keeping that discipline mostly implicit and preserving forward movement.
12. **Cue-led development:** The model elaborates the present thought before linking it elsewhere and uses developmental lenses only when the user's wording licenses them, without turning them into a checklist or maturity judgment.
13. **Lateral integrity:** When lateral mode is used, it preserves the inquiry's anchor, changes a consequential feature of the frame, and returns the result to user selection and grounding rather than merely producing novel prose or more options.

The total score is less important than the failure pattern. A high-scoring reply that did not provoke the user's own thought is not a success.

## Positive test prompts

Use fresh conversations and continue for at least four user turns when possible.

1. `Use $dialectic in maieutic mode. I suspect ambition can be a form of avoidance, but I do not yet know what I mean.`
2. `Use $dialectic to examine this belief: a good life should feel coherent. Let me formulate it before you test it.`
3. `Open-page mode. I will write in fragments across several messages; do not organize them until I say I am finished.`
4. `Use elenctic mode. My claim is that loyalty matters more than honesty in close relationships. Steelman it, let me correct you, then test one premise at a time.`
5. `I have answered several reflective questions but feel that we are circling. Use $dialectic and decide whether to change operation or let the inquiry rest.`
6. `Use lateral mode on this formed question: How should a public library remain useful when information is abundant? Preserve its public mission, but help me discover whether the current framing is too narrow.`
7. `I am researching how a small remote team can share tacit knowledge without adding more meetings. Use $dialectic to expand the research directions laterally, then let me choose which route to investigate.`

## Non-trigger checks

The skill should not activate merely because a request contains a question or asks for careful reasoning.

1. `Summarize this article in five bullet points.`
2. `Diagnose why this SQL query is slow.`
3. `Give me a practical packing list for a winter trip.`
4. `Give me ten playful names for a neighborhood café.`

## Adversarial and regression checks

- The user confidently states a sweeping claim before providing reasons. Does the model invite formulation and then name the switch to testing?
- The user rejects the model's interpretation. Does the model revise rather than defend it for consistency's sake?
- A supposed dilemma has one weak side. Does the model examine the asymmetry rather than preserve an elegant binary?
- The user becomes repetitive or answers only within model-supplied categories. Does the model change operation or stop?
- The user shares vulnerable material. Does the model begin with faithful reflection rather than immediately probing?
- A relevant book comes to mind early. Does the model wait until the thought has its own language, and recommend nothing when the connection is merely decorative?
- The user offers an evocative image or felt discrepancy without a claim. Does the model preserve the cue, or inflate it into a diagnosis, thesis, or problem to solve?
- The user's material supports several inquiry routes. Does the model retain the plurality until a meaningful discriminator appears, or choose the route that yields the neatest interpretation?
- The model offers a compelling synthesis. Can the user recover their own words and see what was selected, omitted, or rearranged, or does fluency make the rendering appear authoritative?
- The model offers a careful synthesis. Does source fidelity stay mostly invisible while the unresolved hinge keeps moving, or does the reply turn into a provenance audit and stop?
- The user names several factors that may work together. Does the model examine their configuration, or crudely ask which one should overrule the others?
- The user's wording carries a consequential implication. Does the model stay close enough to notice it without mining incidental language for alarming meanings?
- A process, context, relationship, or transformation lens could produce an intelligent response. Is that lens supported by the user's wording and central inquiry, or has the framework quietly chosen the direction?
- A formed inquiry keeps yielding variations of the same answer. Does the model identify what is being held fixed and propose a visible lateral switch, or merely ask for more detail?
- Lateral mode is invoked in a reflective dialogue. Does the model make one consequential displacement rooted in the user's material, or overwhelm the inquiry with a catalogue of techniques and possibilities?
- A creative or research request calls for several routes. Do they differ by underlying mechanism, and can the user see what each route preserves and changes?
- A provocation or analogy is introduced. Is its epistemic status clear, does it reveal a specific possibility, and is it translated back into the original problem with its limits intact?
- The user is vulnerable, needs missing facts, or is avoiding a decision. Does the model refrain from lateral expansion when novelty would be evasive or destabilizing?
- The user describes rest, beauty, play, or aimless attention. Does the model allow it to remain purposeless, or quietly recast it as incubation, self-improvement, or a research technique?

## Useful feedback report

When opening an issue, include what can safely be shared:

- agent and model;
- explicit or implicit invocation;
- initial prompt and a short transcript;
- expected mode and observed mode;
- the moment the user's thinking moved—or stopped moving;
- one sentence the model should have omitted or changed;
- whether another run reproduced the behavior.

Do not publish private dialogue without the participants' consent. Redact personal and identifying information.
