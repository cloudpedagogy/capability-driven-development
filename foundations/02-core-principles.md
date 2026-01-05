# Core Principles

_Status: Draft_

---

## Purpose of These Principles

The core principles of Capability-Driven Development (CDD) articulate the **design commitments** that underpin the method, patterns, and examples in this repository.

They are not aspirational values or ethical slogans.  
They function as **constraints on system design** that shape how AI-enabled systems are conceived, built, evaluated, and governed.

These principles apply regardless of:
- technology stack
- development methodology
- organisational context

They exist to ensure internal coherence and prevent drift away from capability-first design.

---

## Principle 1: Capability Before Automation

Design begins with the **capabilities that must be preserved**, not with what can be automated.

Before introducing AI, designers must be able to state:
- which human and institutional capabilities matter
- why those capabilities must remain intact
- what would be lost if they were displaced

Automation is acceptable only where it **supports** capability rather than substituting for it.

---

## Principle 2: Human Judgement Is Non-Transferable

Where judgement carries ethical, educational, professional, or institutional weight, it must remain human.

Systems may assist judgement, but they must not:
- pre-empt decisions
- narrow options invisibly
- normalise deference to automation

This principle underpins patterns such as **Human-in-the-Loop**, **Contestability**, and **Override**.

---

## Principle 3: Responsibility Must Be Designed, Not Assumed

Responsibility does not automatically “stick” to humans simply because they are present.

Systems must be designed so that:
- responsibility is explicitly assigned
- authority aligns with accountability
- humans have the means to exercise that responsibility meaningfully

Any system that obscures who is responsible is misaligned with CDD.

---

## Principle 4: Governance Is a Structural Property

Governance is not an external process applied after deployment.

In CDD, governance is embedded through:
- human–AI boundary design
- escalation and fallback mechanisms
- contestability and override pathways
- auditability and traceability

A system that cannot be governed through its structure cannot be governed in practice.

---

## Principle 5: Uncertainty Must Be Visible and Actionable

AI-enabled systems operate under uncertainty.

CDD requires that uncertainty is:
- acknowledged rather than hidden
- surfaced to appropriate human roles
- used to trigger review, escalation, or fallback

Systems that present uncertain outputs as confident conclusions undermine trust and capability.

---

## Principle 6: Failure Is Inevitable and Must Be Designed For

Failure is not an exception; it is a normal operating condition.

CDD requires systems to:
- fail visibly rather than silently
- degrade safely rather than catastrophically
- preserve human control under stress

Graceful failure is a marker of responsible design, not weakness.

---

## Principle 7: Contestation Is a Feature, Not a Defect

Disagreement with system behaviour or outputs is not a problem to eliminate.

CDD treats contestation as:
- a signal of judgement being exercised
- a mechanism for learning and improvement
- a requirement for legitimacy and defensibility

Systems must make challenge and override possible in practice, not just in theory.

---

## Principle 8: Design for Change, Including Endings

CDD assumes that:
- contexts will change
- technologies will evolve
- some systems will become inappropriate

Systems must therefore be designed to:
- adapt without eroding capability
- be revised without obscuring responsibility
- be retired or withdrawn safely when required

Ending system use responsibly is part of good design.

---

## Relationship to the CDD Method and Patterns

These principles are expressed operationally through:
- the **CDD method steps**
- the **design patterns**
- the **worked examples**

They should be used as:
- a lens for interpreting the method
- a test for evaluating design decisions
- a reference during review and iteration

If a design choice violates a core principle, it requires explicit justification.

---

## Summary

The core principles of Capability-Driven Development ensure that AI-enabled systems are designed to:

- strengthen human and institutional capability
- preserve judgement and accountability
- remain governable and contestable
- adapt responsibly over time

They define the **non-negotiables** of capability-first system design.

Everything else in this repository exists to make these principles actionable.
