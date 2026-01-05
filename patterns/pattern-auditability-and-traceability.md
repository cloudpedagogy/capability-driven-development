# Pattern: Auditability and Traceability

_Status: Draft_

---

## Context

AI-enabled systems increasingly shape decisions, workflows, and oversight processes in ways that must remain **explainable, reviewable, and defensible** over time.

In education, research, and public-interest contexts, systems are often subject to:
- internal review and quality assurance
- external scrutiny or audit
- appeals, complaints, or investigations
- long-term accountability obligations

However, many AI-enabled systems are designed with limited attention to:
- how decisions can be reconstructed
- how responsibility can be demonstrated
- how system behaviour can be explained after the fact

Capability-Driven Development treats **auditability and traceability** as foundational design properties, not documentation add-ons.

---

## Capability Risk Addressed

**Inability to explain, justify, or review system behaviour when accountability is required.**

Without auditability and traceability:
- responsibility becomes opaque
- errors cannot be understood or corrected
- governance processes are undermined
- trust erodes during challenge or review

A system that cannot be reconstructed **cannot be governed responsibly**.

---

## Problem

Many AI-enabled systems:

- record outputs without recording reasoning context
- log activity without linking it to accountable roles
- prioritise performance metrics over explanation
- rely on transient or inaccessible records
- separate technical logs from decision records

As a result:
- decisions cannot be meaningfully reviewed
- accountability becomes retrospective guesswork
- explanations are reconstructed informally or defensively

Audit becomes an exercise in justification rather than understanding.

---

## Pattern (Solution)

**Design systems so that relevant actions, inputs, and decisions can be reconstructed and reviewed by appropriate human authorities.**

In the Auditability and Traceability pattern:

- key system events are recorded intentionally
- records link actions to accountable human roles
- AI contributions are distinguishable from human decisions
- system scope, limits, and assumptions are visible

Auditability supports **understanding**, not surveillance.

---

## How the Pattern Preserves Capability

This pattern preserves capability by:

- enabling accountability without blame-shifting
- supporting explanation and learning over time
- reinforcing human responsibility in mixed human–AI systems
- allowing institutions to stand behind their systems

It ensures that:
- responsibility remains demonstrable
- governance processes are credible
- systems remain defensible under scrutiny

---

## When to Use This Pattern

Use the Auditability and Traceability pattern when:

- systems influence decisions with lasting consequences
- outcomes may be appealed, reviewed, or investigated
- institutional accountability is required
- learning from past decisions is important

This pattern is essential in:
- decision support systems
- monitoring and oversight systems
- workflow orchestration affecting people or resources

---

## When *Not* to Use This Pattern

This pattern is **not appropriate** when:

- systems are transient and low-risk
- outputs have no decision relevance
- records would introduce unnecessary intrusion

Even then, designers should consider:
- future scope expansion
- cumulative effects of seemingly low-impact systems

---

## Relationship to CDD Method Steps

This pattern is most closely associated with:

- **04 — Governance and Oversight**  
  Provides the evidentiary basis for accountability.

- **05 — System Design and Architecture**  
  Requires deliberate structuring of records and logs.

- **06 — Evaluation and Monitoring**  
  Enables review of system behaviour over time.

- **08 — Retirement and Deprecation**  
  Supports reflection and learning after system withdrawal.

---

## Common Misuses or Failure Modes

Common failures include:

- logging everything without purpose or clarity
- treating audit logs as technical artefacts only
- separating human decisions from system context
- making records inaccessible to reviewers
- using auditability primarily for surveillance

These failures create volume without insight.

---

## Related Examples

This pattern is demonstrated in:

- **Decision Support System**  
  Where AI inputs and human decisions are recorded separately.

- **Workflow Orchestration System**  
  Where routing, escalation, and override actions are traceable.

- **Monitoring and Oversight System**  
  Where signals, reviews, and responses are reconstructable.

Across examples, traceability supports learning and accountability rather than enforcement.

---

## Summary

The Auditability and Traceability pattern ensures that AI-enabled systems:

- can be explained and reviewed meaningfully
- support institutional accountability
- enable learning from past use
- remain defensible under scrutiny

In Capability-Driven Development, auditability is not about watching people —  
it is about **being able to stand behind decisions**.
