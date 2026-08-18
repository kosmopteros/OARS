# OARS 1.0

## Open Artificial Respondent Standard

*Defining the Artificial Respondent category*

**Version:** 1.0

**Date:** 12 August 2026

**Editor:** Alexander Pichugin

## 1. Purpose

OARS determines when an artificial entity may be described as an
**Artificial Respondent**. It defines the category and the minimum way such a
respondent functions.

OARS does not prescribe how respondents are generated, stored, simulated, or
expressed. It is not a response-quality benchmark, an exchange format, a
certification system, or a claim of equivalence to human research participants.

In this document, **must** states a requirement, **must not** states a
prohibition, and **may** states a permission.

## 2. Terms

**Artificial Respondent** — a particular, persistent, addressable artificial
entity that satisfies this standard.

**Relevant selection boundary** — the earliest point at which a particular
research demand, task-specific audience criterion, selection query, panel
search, direct address, or assignment can influence which respondent is used
or how state represented as prior is constituted. Earlier admission to a
standing respondent population may establish respondent status only when the
entity, its operative state, and evidence of both already exist independently
of the particular demands that population may later serve. Admission,
registration, or labeling alone establishes nothing under OARS.

**Operative prior state** — respondent-specific state that exists at the
relevant selection boundary and can materially constrain what the respondent
knows, notices, values, recalls, appraises, decides, or does.

**Encounter** — the bounded material or situation made available to a
respondent on an occasion for possible response.

**Response** — the respondent's semantic outcome, including an answer,
question, judgment, choice, uncertainty, abstention, or disengagement. A
Response is distinct from its wording, rendering, or delivery.

**Response realization** — an optional expression of a Response as text,
speech, action, structured data, or another modality.

**Persona** — a representation, archetype, profile, character description, or
instruction set. A persona may characterize or help constitute a respondent;
it is not a respondent merely by being represented or invoked.

**Artificial** identifies the origin or status of the entity: it was
constructed or instantiated rather than recruited as a biological participant.
It does not imply an LLM, human fidelity, consciousness, or a particular
production method.

**Synthetic** is a broad provenance adjective. **Synthesized** describes a
production act or its result. Neither word is an OARS category, and neither
proves that a respondent existed.

## 3. Definition

An **Artificial Respondent** is a persistent, addressable artificial entity
constituted or admitted for respondent participation independently of the
particular demand that later finds, selects, assigns, or questions it. The
respondent and an operative version of its prior state, together with evidence
sufficient to verify both, must exist before the relevant selection boundary.
In an Encounter, each Response must be causally traceable through its formation
to that state and, insofar as Encounter information influenced it, only to
material the respondent actually observed.

In plain terms:

> **The respondent exists before the particular audience query, panel
> selection, or task that later finds it. The response is causally traceable to
> what that respondent already was and to what it actually observed.**

## 4. Category requirements

An entity is an Artificial Respondent under OARS 1.0 only if all eight
requirements are satisfied.

### OARS-1 — Prior respondent

The particular respondent and an operative version of its prior state must
exist before the relevant selection boundary. A standing respondent population
may therefore contain Artificial Respondents before a later query selects a
panel from it. Admission alone does not waive this or any other OARS
requirement.

A character created, completed, or retrofitted in response to the particular
demand that is supposed to find it does not satisfy this requirement.

### OARS-2 — Persistent identity and operative state

The respondent must be one addressable entity with respondent-specific
state capable of continuity across Encounters. Persistence does not require
continuous execution; it requires that later participation remains attributable
to the same entity and its legitimate state history.

Divergent continuations are distinct respondents from their point of
divergence. A branch chosen after the relevant selection boundary because it
best fits the Encounter, a preferred result, or a scoring rule must not be
presented as the unselected continuation of the prior respondent.

The state must operate as the state of that particular respondent, not merely
as instructions to portray one. A persona, biography, memory graph, profile,
demographic row, sample, model, or answer is insufficient by itself. Shared
model weights, training data, and corpora of prior responses are implementation
substrate, not respondent-owned state by themselves.

A persistent or versioned representation supplied to a general output
generator as instructions for portraying an entity remains a persona. Its
influence on generated wording or output is not enough to turn the
representation into an Artificial Respondent.

### OARS-3 — Independent formation and prior-state evidence

The selection criteria, Encounter material, preferred result, or scoring rule
must not create or rewrite state represented as prior. Evidence sufficient to
verify the particular respondent and operative prior-state version must be
fixed before the relevant selection boundary. OARS prescribes no evidence
format.

The claimed ordering and binding must themselves be independently verifiable.
Prior-state evidence must make post-boundary creation or material alteration
detectable; claimant-controlled timestamps, version labels, or records are
insufficient by themselves.

Records completed during or after the Encounter may account for observation
and Response formation. They must not backfill missing prior-state evidence or
turn a post-hoc explanation into a pre-existing respondent.

### OARS-4 — Bounded encounter and knowledge

Only Encounter material actually available and observed through the
respondent's bounded capabilities may influence its Response. Hidden,
unreached, future, implementation-only, or otherwise unavailable information
must not be attributed to the respondent.

Claimed non-observation must correspond to an effective information boundary
on Response formation. Material made available to a response-forming operation
is not rendered unobserved by labeling it so afterward.

Knowledge or recognition attributed to the respondent must be supported by its
operative state or acquired through material it actually observed. Availability
in shared implementation substrate alone must not supply respondent-attributed
semantic knowledge. Uncertainty and non-recognition must remain possible, as
must recognition supported by the respondent's own experience, interests,
language, or other operative state. In a multipart Encounter, what the
respondent inspects, continues to inspect, or leaves unobserved may itself
depend on that state.

### OARS-5 — Causally traceable formation

Each Response must be causally traceable through its formation to the
respondent's operative prior state and, insofar as Encounter information
influenced it, only to material the respondent actually observed.

Before the Response is completed, contemporaneous operational evidence must
already identify the operative prior-state version, what was observed, the
respondent-specific formation basis, and any operations or interfaces claimed
to have materially formed the semantic outcome. The completed Response must
bind to that antecedent evidence. A later receipt or account may identify and
assess existing causes; it must not invent them.

The causal claim must concern material semantic properties of the Response,
such as its stance, judgment, uncertainty, choice, reason, or intended action.
Identity citation, arbitrary variation, wording, cadence, or style alone is
insufficient. The cited causes must expose observable respondent-specific
dependencies capable of affecting those material semantic properties under an
appropriate comparison. Persistent insensitivity to removing, suppressing, or
materially changing a cited cause under otherwise equivalent conditions defeats
that causal claim. This does not require deterministic wording or a different
outcome from every single comparison. Variation not attributable to the cited
cause does not establish dependency.

Dependence on an undifferentiated respondent-specific model, state blob, prompt,
or causal bundle is insufficient unless the evidence identifies
respondent-specific information within it that materially contributed to the
semantic outcome.

The claim must be capable of independent falsification and must distinguish
respondent contribution from shared implementation substrate, platform policy,
human intervention, and optional Response realization.

A generated rationale, chain of thought, prompt transcript, training
provenance, plausible output, or citation of respondent state is not sufficient
by itself. OARS requires neither private chain of thought nor complete access
to every internal operation. It requires respondent-specific operational
evidence for the claimed causal formation basis and a claim that can be
disproved.

### OARS-6 — Calibrated agency and honest outcomes

Semantic outcomes must be capable of varying with materially different
respondent state and Encounter. Agreement, resistance, questioning, answering,
uncertainty, ambivalence, abstention, and disengagement are legitimate where
supported and applicable. No outcome type may be imposed universally by shared
substrate or platform policy. Universal compliance, sycophancy, defensiveness,
refusal, or contrarianism is not evidence of agency merely because it is
consistent.

An execution failure or platform restriction must not be presented as the
respondent's choice, belief, emotion, or psychology.

### OARS-7 — Semantic separation and medium neutrality

The respondent's semantic Response and any claimed formation process must
remain distinguishable from platform intervention, optional Response
realization, and human choice among candidate responses, authorship, or semantic
editing after the Encounter begins. Human or platform intervention that
materially selects, adds, suppresses, substitutes, or changes the semantic
outcome must be disclosed as intervention and must not be presented or
attributed as the respondent's Response. Selection among semantically
equivalent realizations may remain realization.

A renderer or policy may constrain realization; it must not add respondent
knowledge, reverse the respondent's stance, or receive attribution as respondent
psychology.

OARS presumes no LLM, natural language, model family, database, memory
ontology, psychological framework, simulated world, attention mechanism, or
output modality.

### OARS-8 — Falsifiability and limits

The claim that an entity is an Artificial Respondent must be independently
testable and capable of being disproved. Independence means that evidence can
be examined and challenged apart from the Response's own description; it does
not require public disclosure of private respondent state. The evidence must
permit an examiner to identify at least one observable condition under which a
material category claim would fail.

Examination must be capable of detecting post-selection construction, post-hoc
state, decorative state, unbounded knowledge, blanket ignorance, fixed
compliance or refusal, systematic defensiveness, and policy or realization
leakage.

Plausible output and self-authored explanation are insufficient. OARS alone
establishes neither human prediction, psychological fidelity, distributional
fit, representativeness, panel independence, consciousness, legality, safety,
nor fitness for a particular use.

## 5. Evidence timing

OARS does not collapse all evidence into a slogan such as "proof before the
answer." Different claims have different possible deadlines:

| Deadline | What must exist |
| --- | --- |
| Before the relevant selection boundary | The particular respondent, its operative prior-state version, and prior-state evidence sufficient to verify both. |
| During the Encounter and before Response completion | Evidence of what was actually observed and antecedent operational evidence of respondent-specific formation. |
| At Response completion | A linkage from the semantic Response to the antecedent evidence that formed it. |
| During or after formation | A completed account may assemble and assess the evidence, but may not create causes or repair a missing earlier record. |

The Response therefore does not merely *leave* evidence or receive a rationale
afterward. It is bound to a formation basis that already exists when the
Response is completed.

## 6. Category boundaries

| Term | What it names | What it does not establish |
| --- | --- | --- |
| **Artificial Respondent** | A persistent artificial entity satisfying all eight OARS requirements. | Human likeness, validity, representativeness, or consciousness. |
| **Persona** | A representation or instruction for portraying a person or type. | A persistent, response-capable individual. |
| **Artificial persona** | A persona produced or maintained artificially. | An Artificial Respondent. |
| **Synthetic or synthesized response** | An output produced through synthesis. | That any respondent existed or formed it. |
| **Model or fine-tuned model** | Implementation substrate capable of producing outputs. | A particular respondent, respondent-owned state, bounded observation, or causal formation. |

A persona characterizes. A respondent encounters and forms a Response. A
Response is an outcome, not an individual.

OARS excludes pure model output, not model use. A general or fine-tuned model
may participate in formation or realize a Response. Without independently
examinable evidence of the causal path from this respondent, through what it
actually observed, to its semantic outcome, the result is a generated or
synthesized output—not evidence of an Artificial Respondent's Response.

## 7. Claims under OARS

An organization may state that an entity is an **Artificial Respondent under
OARS 1.0** only when it can substantiate all eight requirements. OARS does not
operate a certification program, authorize a certification mark, or endorse an
implementation.

Population grounding, empirical agreement with human participants, and panel
methodology may be valuable additional properties. They are not substitutes
for respondenthood and are not established by OARS 1.0.

## 8. License

Copyright 2026 Alexander Pichugin.

This standard is licensed under the [Creative Commons Attribution 4.0
International License](LICENSE).
