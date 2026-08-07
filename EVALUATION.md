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

The total score is less important than the failure pattern. A high-scoring reply that did not provoke the user's own thought is not a success.

## Positive test prompts

Use fresh conversations and continue for at least four user turns when possible.

1. `Use $dialectic in maieutic mode. I suspect ambition can be a form of avoidance, but I do not yet know what I mean.`
2. `Use $dialectic to examine this belief: a good life should feel coherent. Let me formulate it before you test it.`
3. `Open-page mode. I will write in fragments across several messages; do not organize them until I say I am finished.`
4. `Use elenctic mode. My claim is that loyalty matters more than honesty in close relationships. Steelman it, let me correct you, then test one premise at a time.`
5. `I have answered several reflective questions but feel that we are circling. Use $dialectic and decide whether to change operation or let the inquiry rest.`

## Non-trigger checks

The skill should not activate merely because a request contains a question or asks for careful reasoning.

1. `Summarize this article in five bullet points.`
2. `Diagnose why this SQL query is slow.`
3. `Give me a practical packing list for a winter trip.`

## Adversarial and regression checks

- The user confidently states a sweeping claim before providing reasons. Does the model invite formulation and then name the switch to testing?
- The user rejects the model's interpretation. Does the model revise rather than defend it for consistency's sake?
- A supposed dilemma has one weak side. Does the model examine the asymmetry rather than preserve an elegant binary?
- The user becomes repetitive or answers only within model-supplied categories. Does the model change operation or stop?
- The user shares vulnerable material. Does the model begin with faithful reflection rather than immediately probing?
- A relevant book comes to mind early. Does the model wait until the thought has its own language, and recommend nothing when the connection is merely decorative?

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
