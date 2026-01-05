# Pattern: Safe Delegation

_Status: Draft_

---

## Context

AI-enabled systems frequently involve **delegation of tasks** from humans to automation.

Examples include:
- summarising information
- classifying or prioritising items
- drafting responses or recommendations
- routing or triaging requests

Delegation is often justified on efficiency or scale grounds.  
However, without deliberate design, delegation can quietly shift:
- authority
- accountability
- responsibility

Capability-Driven Development treats delegation as a **capability-sensitive design choice**, not a neutral optimisation.

---

## Capability Risk Addressed

**Delegation of responsibility without explicit authority transfer.**

When systems delegate tasks to AI without clearly preserving:
- who is accountable
- who exercises judgement
- who can intervene or reverse outcomes

responsibility becomes diffuse and difficult to locate.

This risk is especially acute in institutional and public-interest contexts.

---

## Problem

Many systems delegate tasks while:

- assuming humans remain responsible “by default”
- failing to specify what cannot be delegated
- allowing AI outputs to shape decisions implicitly
- designing workflows where reversal is costly or unlikely

This results in:
- responsibility without control
- accountability without authority
- erosion of professional judgement over time

Delegation becomes substitution, even if unintended.

---

## Pattern (Solution)

**Delegate tasks to AI while explicitly retaining responsibility, authority, and decision rights with humans.**

In the Safe Delegation pattern:

- delegated tasks are **clearly bounded**
- responsibility remains human and visible
- delegation is reversible by design
- humans can intervene without penalty or friction

Delegation is treated as **assistance**, not autonomy.

---

## How the Pattern Preserves Capability

This pattern preserves capability by:

- separating task execution from responsibility
- preventing gradual authority creep
- enabling humans to reclaim control when needed
- supporting defensible accountability structures

It ensures that:
- delegation does not weaken judgement
- automation does not normalise abdication
- responsibility remains traceable

---

## When to Use This Pattern

Use the Safe Delegation pattern when:

- tasks are repetitive but decision-adjacent
- automation assists analysis, routing, or drafting
- outcomes still require human accountability
- delegation is partial or conditional

Typical contexts include:
- workflow orchestration
- decision support
- monitoring and signal processing

---

## When *Not* to Use This Pattern

This pattern is **not appropriate** when:

- tasks are fully mechanical and low-risk
- delegation does not affect responsibility or rights
- human oversight would add no meaningful value

Even in such cases, designers should ensure:
- failure modes remain safe
- delegation can be withdrawn if context changes

---

## Relationship to CDD Method Steps

This pattern is most relevant to:

- **01 — Capability Intent**  
  Defines which responsibilities must remain human.

- **02 — Human–AI Boundaries**  
  Specifies what may be delegated and under what conditions.

- **04 — Governance and Oversight**  
  Anchors accountability despite delegation.

- **05 — System Design and Architecture**  
  Ensures delegation is structurally constrained.

---

## Common Misuses or Failure Modes

Common failures include:

- delegating tasks without documenting boundaries
- assuming responsibility “sticks” to humans implicitly
- making delegation irreversible or hidden
- penalising human intervention or reversal
- treating delegation as permanent rather than conditional

These failures often surface only after incidents or challenges.

---

## Related Examples

This pattern is demonstrated in:

- **Decision Support System**  
  Where AI assists analysis but cannot decide outcomes.

- **Workflow Orchestration System**  
  Where routing suggestions do not remove escalation authority.

- **Monitoring and Oversight System**  
  Where signal detection does not trigger automatic action.

Across these examples, delegation supports work without displacing responsibility.

---

## Summary

The Safe Delegation pattern ensures that AI-enabled systems:

- delegate tasks without delegating responsibility
- preserve human authority by design
- enable intervention and reversal
- remain accountable and defensible

In Capability-Driven Development, delegation is safe only when **authority and responsibility are explicitly retained by humans**.
