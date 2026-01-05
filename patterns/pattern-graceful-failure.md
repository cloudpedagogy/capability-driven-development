# Pattern: Graceful Failure

_Status: Draft_

---

## Context

All AI-enabled systems will fail at some point.

Failure may occur due to:
- missing or degraded inputs
- model error or misclassification
- infrastructure or dependency outages
- shifts in context beyond design assumptions
- unanticipated edge cases

In many systems, failure is treated as:
- an exceptional technical fault
- something to be hidden or minimised
- a rare condition to optimise away

Capability-Driven Development treats failure as **inevitable** and therefore a **primary design concern**.

---

## Capability Risk Addressed

**Loss of capability, trust, and accountability when systems fail abruptly, silently, or opaquely.**

When failure is poorly handled:
- humans lose situational awareness
- responsibility becomes unclear
- automation drift accelerates
- confidence in systems erodes

Systems that fail badly often do more harm than systems that fail often.

---

## Problem

Many AI-enabled systems:

- fail silently or degrade invisibly
- produce outputs without signalling uncertainty
- block workflows when components fail
- force users to invent workarounds
- obscure whether failure is technical or epistemic

As a result:
- humans are left guessing what the system is doing
- incorrect outputs may be trusted
- responsibility becomes diffused during incidents

Failure becomes chaotic rather than informative.

---

## Pattern (Solution)

**Design systems to fail in ways that are visible, bounded, and recoverable.**

In the Graceful Failure pattern:

- failure states are explicitly recognised
- systems degrade to simpler, safer behaviour
- humans are informed and re-empowered
- core activities can continue without automation

Failure is treated as a **mode of operation**, not an exception.

---

## How the Pattern Preserves Capability

This pattern preserves capability by:

- maintaining human situational awareness
- preventing silent or misleading outputs
- supporting continuity of responsibility
- enabling recovery without panic or blame

It ensures that:
- humans remain in control under stress
- uncertainty is surfaced, not hidden
- trust is preserved through transparency

---

## When to Use This Pattern

Use the Graceful Failure pattern when:

- systems operate in uncertain or changing contexts
- AI components are non-deterministic
- failure could mislead or harm users
- work must continue despite degradation

This pattern is essential for:
- decision support systems
- workflow orchestration
- monitoring and oversight

---

## When *Not* to Use This Pattern

This pattern is **not appropriate** when:

- failure has no meaningful impact
- systems are purely optional or advisory
- outputs are clearly non-authoritative

Even then, designers should consider:
- cumulative effects of repeated failure
- erosion of trust through inconsistency

---

## Relationship to CDD Method Steps

This pattern is most closely associated with:

- **03 — Ethics, Equity, and Risk**  
  Addresses harm from misleading or opaque failure.

- **05 — System Design and Architecture**  
  Requires explicit modelling of failure modes.

- **07 — Iteration and Change**  
  Enables learning from breakdowns.

- **08 — Retirement and Deprecation**  
  Supports safe withdrawal of systems.

---

## Common Misuses or Failure Modes

Common failures include:

- hiding failure to preserve appearance of reliability
- failing closed in ways that block work
- continuing to output low-confidence results
- shifting responsibility during incidents
- treating failure solely as a technical issue

These failures compound harm and undermine trust.

---

## Related Examples

This pattern is demonstrated in:

- **Decision Support System**  
  Where low-confidence analysis triggers human judgement.

- **Workflow Orchestration System**  
  Where cases default to human handling when automation fails.

- **Monitoring and Oversight System**  
  Where absence or degradation of signals does not imply safety.

Across examples, graceful failure enables continuity and accountability.

---

## Summary

The Graceful Failure pattern ensures that AI-enabled systems:

- fail visibly and informatively
- preserve human control under stress
- support recovery and learning
- maintain trust despite breakdowns

In Capability-Driven Development, failure is not the opposite of success —  
it is an opportunity to **demonstrate responsibility**.
