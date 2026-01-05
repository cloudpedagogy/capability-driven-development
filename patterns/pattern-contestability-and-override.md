# Pattern: Contestability and Override

_Status: Draft_

---

## Context

AI-enabled systems increasingly influence decisions, workflows, and oversight processes in ways that affect people, institutions, and outcomes.

In such systems, disagreement is inevitable:
- AI outputs may be wrong, incomplete, or misaligned with context
- system behaviour may conflict with professional judgement
- affected parties may challenge interpretations or outcomes

However, many systems are designed in ways that make contestation:
- procedurally difficult
- socially discouraged
- technically opaque
- practically ineffective

Capability-Driven Development treats **contestability and override** as essential design features, not post hoc remedies.

---

## Capability Risk Addressed

**Loss of legitimacy and accountability when decisions or system behaviours cannot be meaningfully challenged or reversed.**

Without contestability:
- errors persist uncorrected
- power shifts silently to system logic
- responsibility becomes unclear
- trust erodes over time

Systems that cannot be challenged cannot be governed.

---

## Problem

Many AI-enabled systems:

- provide outputs without explanation or rationale
- allow overrides only through exceptional or informal means
- treat disagreement as error rather than signal
- log decisions without enabling reversal
- place social or procedural cost on challenge

As a result:
- humans defer even when they disagree
- incorrect outcomes propagate
- accountability becomes performative

The system appears authoritative, even when it should not be.

---

## Pattern (Solution)

**Design explicit, accessible mechanisms that allow humans to challenge, override, and reverse system outputs or behaviours.**

In the Contestability and Override pattern:

- disagreement is expected and legitimate
- override pathways are visible and usable
- reversals are structurally supported
- contestation is logged without penalty

Override is not failure —  
it is an expression of responsible authority.

---

## How the Pattern Preserves Capability

This pattern preserves capability by:

- maintaining human authority over system outcomes
- preventing automation bias and deference
- enabling learning from disagreement
- supporting defensible decision-making

It ensures that:
- responsibility remains exercisable
- governance remains active
- systems can be corrected and improved

---

## When to Use This Pattern

Use the Contestability and Override pattern when:

- system outputs influence decisions with real consequences
- outcomes may be disputed or appealed
- professional or institutional judgement is required
- legitimacy depends on transparency and fairness

This pattern is especially important in:
- decision support systems
- monitoring and oversight systems
- workflow orchestration with escalation or triage

---

## When *Not* to Use This Pattern

This pattern is **not appropriate** when:

- systems are purely informational with no downstream impact
- outputs have no decision relevance
- reversal would have no meaningful effect

Even then, designers should consider whether:
- future scope expansion could introduce risk
- apparent neutrality masks hidden authority

---

## Relationship to CDD Method Steps

This pattern is most closely associated with:

- **02 — Human–AI Boundaries**  
  Ensures authority does not silently migrate to automation.

- **04 — Governance and Oversight**  
  Provides mechanisms for challenge and review.

- **05 — System Design and Architecture**  
  Requires reversible, non-terminal system structures.

- **06 — Evaluation and Monitoring**  
  Enables analysis of disagreement and override patterns.

---

## Common Misuses or Failure Modes

Common failures include:

- allowing override only via informal workarounds
- requiring excessive justification for disagreement
- logging overrides without reviewing them
- penalising or discouraging challenge
- making reversals technically irreversible

These failures turn contestability into a theoretical right rather than a practical one.

---

## Related Examples

This pattern is demonstrated in:

- **Decision Support System**  
  Where recommendations can be rejected without penalty.

- **Workflow Orchestration System**  
  Where routing and escalation decisions can be overridden.

- **Monitoring and Oversight System**  
  Where signals do not mandate action and can be challenged.

Across examples, contestation strengthens legitimacy rather than undermining authority.

---

## Summary

The Contestability and Override pattern ensures that AI-enabled systems:

- remain governable and legitimate
- preserve human authority in practice
- support challenge, correction, and learning
- avoid false finality or automation lock-in

In Capability-Driven Development, a system that cannot be challenged  
**cannot be considered responsibly designed**.
