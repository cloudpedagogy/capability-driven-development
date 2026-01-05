# Pattern: Human-in-the-Loop

_Status: Draft_

---

## Context

The term *“human-in-the-loop”* is widely used in AI system design, but often without precision.

In practice, it is frequently invoked to:
- justify automation without changing system structure
- imply oversight without defining responsibility
- suggest ethical safety without enforceable design constraints

As a result, many systems labelled “human-in-the-loop” still:
- displace judgement in practice
- normalise deference to AI outputs
- obscure accountability when decisions are contested

Capability-Driven Development treats **Human-in-the-Loop** not as a label, but as a **design pattern** that must be implemented deliberately.

---

## Capability Risk Addressed

**Erosion of human judgement and accountability through nominal oversight.**

When human involvement is:
- ill-defined
- optional in practice
- positioned after automated decisions

the system gradually shifts authority to automation, even if humans are technically present.

---

## Problem

Many AI-enabled systems claim human oversight while:

- presenting AI outputs as default or authoritative
- requiring humans only to approve or confirm
- making disagreement costly or exceptional
- logging human involvement without enabling judgement

This results in *rubber-stamping*, where humans are present in name but not in practice.

The core problem is not absence of humans —  
it is **absence of meaningful human authority**.

---

## Pattern (Solution)

**Design the system so that human judgement is a required, substantive step in decision-relevant workflows.**

In the Human-in-the-Loop pattern:

- AI outputs are **advisory**, not binding  
- system progress depends on **human interpretation**, not confirmation  
- disagreement with AI is expected and legitimate  
- responsibility is explicitly assigned to human roles  

The loop is not a checkpoint —  
it is a **decision locus**.

---

## How the Pattern Preserves Capability

This pattern preserves capability by:

- keeping evaluative judgement human
- preventing silent delegation of responsibility
- ensuring accountability remains visible and traceable
- supporting defensible decision-making under scrutiny

It ensures that:
- AI assists thinking, not replaces it
- humans remain answerable for outcomes
- systems remain contestable and reviewable

---

## When to Use This Pattern

Use the Human-in-the-Loop pattern when:

- decisions have ethical, educational, or institutional consequences
- outcomes may be challenged or appealed
- professional judgement is central to legitimacy
- errors carry reputational or equity risk

This pattern is especially important in:
- decision support systems
- workflow orchestration with escalation
- monitoring and oversight contexts

---

## When *Not* to Use This Pattern

This pattern is **not appropriate** when:

- tasks are fully reversible and low-risk
- outcomes are purely mechanical or administrative
- automation does not affect responsibility or rights

Even in such cases, designers should verify that:
- human accountability is genuinely unnecessary
- failure modes remain safe and visible

---

## Relationship to CDD Method Steps

This pattern is primarily applied during:

- **02 — Human–AI Boundaries**  
  Defines where authority and judgement reside.

- **04 — Governance and Oversight**  
  Anchors accountability and review mechanisms.

- **05 — System Design and Architecture**  
  Shapes workflow structure and decision points.

However, it is grounded in **01 — Capability Intent**, which determines whether judgement must remain human in the first place.

---

## Common Misuses or Failure Modes

Common failures include:

- treating approval clicks as judgement
- presenting AI outputs as default selections
- penalising deviation from AI recommendations
- requiring justification only when humans disagree
- logging oversight without enabling contestation

These misuses create the appearance of control without its substance.

---

## Related Examples

This pattern is demonstrated in:

- **Decision Support System**  
  Where AI surfaces considerations but humans decide outcomes.

- **Workflow Orchestration System**  
  Where routing suggestions never override human escalation.

- **Monitoring and Oversight System**  
  Where signals prompt review rather than trigger action.

Across these examples, the pattern ensures that *being in the loop* means **having authority**, not merely presence.

---

## Summary

The Human-in-the-Loop pattern ensures that AI-enabled systems:

- preserve meaningful human judgement
- locate responsibility explicitly
- resist automation drift
- remain defensible under challenge

In Capability-Driven Development, humans are not added to the loop to legitimise automation.

The loop exists **because responsibility cannot be automated**.
