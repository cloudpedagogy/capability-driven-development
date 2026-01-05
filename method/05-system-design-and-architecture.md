# System Design and Architecture

_Status: Draft_

---

## Purpose of This Step

This step translates **capability intent**, **human–AI boundaries**, **ethical constraints**, and **governance requirements** into concrete system design and architectural decisions.

Its purpose is to ensure that:
- architecture reflects capability requirements rather than convenience
- governance and oversight are structurally supported
- human judgement is preserved through system design, not policy alone
- later implementation choices cannot undermine earlier commitments

In Capability-Driven Development, architecture is not neutral.  
It encodes values, priorities, and responsibility.

---

## Why Architecture Matters for Capability

Architectural decisions shape:

- how work flows through a system
- where decisions are made or constrained
- what is visible, logged, or reviewable
- how easily systems can be adapted or challenged

If architecture is chosen before capability and governance constraints are clear, systems tend to:
- privilege automation over judgement
- obscure responsibility
- resist oversight and contestation
- accumulate hidden risk over time

CDD treats architecture as a **consequence of prior design decisions**, not a starting point.

---

## What This Step Covers

This step addresses:

- system structure and component boundaries
- data and information flows
- decision points and control surfaces
- separation of concerns between humans and AI
- design patterns that reinforce accountability and oversight

It does **not** prescribe specific technologies, platforms, or implementation stacks.

---

## Relationship to Earlier Steps

System design and architecture must be consistent with:

- **Capability intent**  
  What the system must support and must not undermine.

- **Human–AI boundaries**  
  Where authority, delegation, escalation, and override occur.

- **Ethics, equity, and risk**  
  Which harms must be prevented or mitigated structurally.

- **Governance and oversight**  
  What must be observable, reviewable, and contestable.

If architectural choices conflict with any of these, the design must be revisited.

---

## Core Architectural Design Questions

Designers should be able to answer the following questions clearly.

### Structure and separation
- How are system components separated by responsibility?
- Are AI components isolated from decision authority where required?
- Can parts of the system be modified without undermining governance?

### Control and checkpoints
- Where do human checkpoints exist in workflows?
- How are escalation and fallback handled structurally?
- Are there explicit points where automation pauses or defers?

### Visibility and traceability
- What information is visible to users, reviewers, and overseers?
- Can system behaviour be reconstructed and explained?
- Are logs and records aligned with governance needs?

### Failure and resilience
- How does the system behave when AI components fail or degrade?
- Are failure modes safe, visible, and recoverable?
- Does the system degrade gracefully rather than silently?

### Adaptability and change
- How easily can rules, thresholds, or boundaries be adjusted?
- Can the system evolve without eroding accountability?
- Is retirement or replacement architecturally feasible?

---

## Architectural Patterns in Capability-Driven Development

CDD encourages **capability-aware patterns** rather than performance-driven ones.

Examples include:

- **Explicit decision boundaries**  
  Clear separation between recommendation and decision.

- **Human-controlled checkpoints**  
  Mandatory review points for sensitive actions.

- **Fallback-first design**  
  Default behaviours when automation fails or is uncertain.

- **Audit-friendly flows**  
  Structures that support explanation and review by design.

- **Scope-limited components**  
  Preventing systems from expanding beyond intended use.

These patterns are described in detail in `/patterns`.

---

## Common Failure Modes at This Stage

Typical architectural failures include:

- tightly coupling AI outputs to actions without review
- optimising for throughput at the expense of oversight
- centralising control in ways that obscure accountability
- designing for normal operation but not failure
- assuming governance can be added later through process

Once embedded in architecture, these failures are difficult to reverse.

---

## Outputs of This Step

The outcome of this step should be a **documented system design**, typically captured using the **System Architecture & Flow Diagram** in `/design-artifacts`.

At minimum, this output should include:

- a high-level system structure
- identified decision points and control surfaces
- human–AI interaction boundaries
- governance and oversight hooks
- failure and fallback behaviour

This output constrains implementation and future change.

---

## Relationship to Evaluation and Monitoring

Architectural decisions determine:

- what can be observed and measured
- what forms of evaluation are possible
- how issues can be detected early
- whether learning and adaptation are feasible

Poor architecture limits meaningful evaluation, regardless of intent.

---

## Practical Guidance

When designing system architecture:

- prioritise clarity over cleverness
- design for scrutiny, not just success
- assume the system will be questioned
- make responsible behaviour structurally easy

Good architecture makes governance routine rather than exceptional.

---

## Summary

This step ensures that Capability-Driven Development produces systems where:

- architecture reflects capability and responsibility
- oversight is structurally supported
- automation remains bounded and accountable
- systems can evolve without losing legitimacy

System design is where capability intent becomes operational reality.

---

## Next Step

Continue to:

👉 `06-evaluation-and-monitoring.md`

That step defines how system behaviour is assessed, reviewed, and improved over time.
