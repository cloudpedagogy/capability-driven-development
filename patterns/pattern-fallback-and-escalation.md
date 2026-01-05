# Pattern: Fallback and Escalation

_Status: Draft_

---

## Context

AI-enabled systems inevitably encounter situations where:
- inputs are ambiguous or incomplete
- confidence is low or miscalibrated
- system components fail or degrade
- cases fall outside design assumptions

In many systems, these situations are handled implicitly or not at all.

Fallback and escalation are often treated as:
- error-handling afterthoughts
- operational exceptions
- rare failure cases

Capability-Driven Development treats fallback and escalation as **first-class design features**, essential to preserving responsibility and trust.

---

## Capability Risk Addressed

**Silent failure, deflection, or inappropriate automation under uncertainty.**

Without explicit fallback and escalation:
- systems may continue operating when they should not
- uncertain cases may be forced into inappropriate categories
- responsibility may be deferred rather than exercised
- failures may remain invisible until harm occurs

This risk grows as systems scale or become more autonomous.

---

## Problem

Many AI-enabled systems:

- assume high-confidence inputs by default
- lack clear thresholds for uncertainty
- route edge cases through the same logic as normal cases
- make escalation difficult, slow, or stigmatised

As a result:
- uncertainty is hidden
- exceptions are suppressed
- humans intervene too late or not at all

The system appears stable while capability quietly erodes.

---

## Pattern (Solution)

**Design explicit fallback and escalation pathways that activate under uncertainty, failure, or ambiguity.**

In the Fallback and Escalation pattern:

- uncertainty is detected and acknowledged
- automated processing pauses or degrades safely
- cases are routed to appropriate human review
- escalation is normalised and accessible

Fallback is not a failure state —  
it is a **responsible response to uncertainty**.

---

## How the Pattern Preserves Capability

This pattern preserves capability by:

- preventing silent automation drift
- ensuring humans remain involved when judgement is required
- making system limits visible and actionable
- supporting accountability during edge cases

It ensures that:
- uncertainty triggers care, not concealment
- escalation is part of normal operation
- responsibility is exercised, not deferred

---

## When to Use This Pattern

Use the Fallback and Escalation pattern when:

- inputs or contexts vary widely
- classification or prediction confidence fluctuates
- errors have ethical or institutional consequences
- cases may exceed system competence

Typical contexts include:
- workflow orchestration
- monitoring and oversight
- decision support under uncertainty

---

## When *Not* to Use This Pattern

This pattern is **not appropriate** when:

- systems are fully deterministic and low-risk
- failure modes are trivial and reversible
- human intervention would add no value

Even then, designers should verify that:
- uncertainty truly does not matter
- failure cannot propagate harm

---

## Relationship to CDD Method Steps

This pattern is most closely associated with:

- **02 — Human–AI Boundaries**  
  Defines when control returns to humans.

- **03 — Ethics, Equity, and Risk**  
  Identifies harms associated with misclassification or silence.

- **04 — Governance and Oversight**  
  Establishes accountability for escalation decisions.

- **05 — System Design and Architecture**  
  Ensures fallback pathways are structurally supported.

---

## Common Misuses or Failure Modes

Common failures include:

- treating fallback as an error condition to minimise
- hiding uncertainty behind forced classifications
- making escalation bureaucratic or punitive
- routing escalations to inappropriate roles
- failing to log or review fallback events

These failures create systems that appear efficient but are fragile and unsafe.

---

## Related Examples

This pattern is demonstrated in:

- **Decision Support System**  
  Where low-confidence outputs trigger human analysis rather than recommendations.

- **Workflow Orchestration System**  
  Where ambiguous cases are escalated rather than silently routed.

- **Monitoring and Oversight System**  
  Where uncertain signals prompt review instead of action.

Across examples, escalation is treated as care, not failure.

---

## Summary

The Fallback and Escalation pattern ensures that AI-enabled systems:

- respond responsibly to uncertainty
- surface limits rather than hide them
- support timely human intervention
- remain trustworthy under stress

In Capability-Driven Development, a system that cannot escalate safely **cannot be trusted at scale**.
