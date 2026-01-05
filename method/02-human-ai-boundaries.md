# Human–AI Boundaries

_Status: Draft_

---

## Purpose of This Step

This step defines **human–AI boundaries**: the explicit division of roles, responsibilities, and authority between humans and AI systems within a designed system.

The purpose of this step is to ensure that:
- human judgement is not quietly displaced by automation
- responsibility and accountability remain clearly located
- assistance, delegation, and escalation are intentionally designed
- system behaviour remains defensible under scrutiny

Where capability intent defines *why* a system exists, human–AI boundaries define **who does what, when, and under what conditions**.

---

## Why Human–AI Boundaries Must Be Explicit

In many AI-enabled systems, boundaries between human and AI roles are left implicit.

This leads to:
- unclear responsibility when systems fail
- over-reliance on automated outputs
- “rubber-stamping” of AI recommendations
- difficulty contesting or overriding system behaviour

Capability-Driven Development treats **implicit boundaries as a design failure**.

Human–AI boundaries must be specified deliberately, documented clearly, and revisited over time.

---

## What Human–AI Boundaries Describe

Human–AI boundaries describe:

- where AI may **assist**, **recommend**, or **summarise**
- where humans must **decide**, **approve**, or **intervene**
- where automation is **prohibited**
- how escalation and fallback operate
- how override and contestability are exercised

They are not limited to interaction design.  
They shape system logic, workflow, and governance.

---

## Common Boundary Types

While boundaries will vary by context, most systems involve a combination of the following roles.

### AI as assistant
- AI supports analysis, drafting, or sense-making
- humans retain decision authority
- outputs are advisory, not binding

### AI as recommender
- AI proposes options or classifications
- humans review, interpret, and decide
- disagreement and override are expected

### AI as triage or routing mechanism
- AI prioritises or routes cases
- humans handle final resolution
- escalation paths are explicit

### AI as monitor or signal detector
- AI surfaces anomalies, risks, or patterns
- humans assess significance and act
- thresholds and alerts are transparent

CDD discourages treating AI as an autonomous decision-maker in contexts involving ethical, educational, or institutional responsibility.

---

## Core Design Questions

When defining human–AI boundaries, designers should be able to answer the following questions unambiguously.

### Authority and decision rights
- Who has final decision authority in this system?
- What decisions, if any, can AI make independently?
- Where must human approval always be required?

### Delegation and limits
- What tasks are appropriate to delegate to AI?
- What tasks must remain human regardless of efficiency gains?
- Where is partial automation acceptable but full automation is not?

### Escalation and fallback
- Under what conditions must cases be escalated to humans?
- What happens when AI outputs are uncertain, conflicting, or missing?
- How does the system behave when automation fails?

### Override and contestability
- How can humans override AI outputs?
- How are disagreements recorded or surfaced?
- Can affected parties challenge system behaviour?

---

## Relationship to Capability Intent

Human–AI boundaries must be **directly derived from capability intent**.

If capability intent specifies that:
- professional judgement must remain central
- certain decisions are ethically sensitive
- institutional accountability cannot be delegated

then boundaries must enforce those constraints.

If boundaries contradict stated capability intent, the design is inconsistent and must be revised.

---

## Common Failure Modes at This Stage

Typical boundary-related failures include:

- assuming “human-in-the-loop” without defining the loop
- allowing AI outputs to become de facto decisions
- designing escalation paths that are technically present but practically unused
- failing to log overrides or disagreements
- conflating assistance with delegation

These failures often only surface after deployment, when correcting them is costly.

---

## Outputs of This Step

The outcome of this step should be a **documented human–AI boundary model**, typically captured using the **Human–AI Boundary Map** in `/design-artifacts`.

At minimum, this output should specify:

- decision points and responsible actors
- AI roles and limits
- escalation triggers
- override mechanisms
- accountability ownership

This output constrains system architecture and workflow design.

---

## Relationship to Subsequent Steps

Human–AI boundaries directly inform:

- **Ethics, equity, and risk**  
  by identifying where harm, bias, or misuse may arise

- **Governance and oversight**  
  by locating responsibility and review points

- **System design and architecture**  
  by shaping workflows, permissions, and controls

Boundaries should not be treated as static.  
They must be revisited as systems evolve.

---

## Practical Guidance

When defining human–AI boundaries:

- avoid vague language such as “reviewed by a human”
- specify conditions, not intentions
- design for disagreement, not compliance
- assume that defaults will be followed unless actively challenged

Well-designed boundaries make responsible behaviour the *path of least resistance*.

---

## Summary

Human–AI boundaries determine how responsibility is enacted in practice.

By making these boundaries explicit, Capability-Driven Development ensures that:

- assistance does not become substitution
- efficiency does not override accountability
- systems remain contestable and governable

This step turns abstract capability intent into enforceable system behaviour.

---

## Next Step

Continue to:

👉 `03-ethics-equity-risk.md`

That step examines how boundary decisions introduce ethical, equity, and risk considerations that must be addressed deliberately.
