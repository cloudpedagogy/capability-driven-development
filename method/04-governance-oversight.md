# Governance and Oversight

_Status: Draft_

---

## Purpose of This Step

This step defines how **governance and oversight** are designed into an AI-enabled system.

Its purpose is to ensure that:
- responsibility for system behaviour is clearly located
- oversight is practical, timely, and meaningful
- accountability is demonstrable, not assumed
- ethical and risk considerations are enforceable in operation

In Capability-Driven Development, governance is not an external control layer.  
It is a **core system property**.

---

## Why Governance Must Be Designed In

In many systems, governance is addressed through:
- policy statements detached from system behaviour
- reliance on professional norms without technical support
- post-hoc audits that occur too late to prevent harm

This results in systems that are:
- difficult to scrutinise
- resistant to challenge
- fragile under regulatory or public review

CDD treats governance as a **design problem**, not an administrative afterthought.

---

## What Governance and Oversight Cover

Governance and oversight design addresses:

- **accountability** — who is responsible for what, and when  
- **traceability** — what decisions were made, by whom, and on what basis  
- **review** — how system behaviour is examined over time  
- **contestability** — how decisions can be challenged or overridden  
- **scope control** — how appropriate use is maintained as contexts change  

These elements must be supported by system behaviour, not just documentation.

---

## Relationship to Earlier Steps

Governance and oversight are shaped by:

- **Capability intent**  
  What responsibilities must remain human and institutional.

- **Human–AI boundaries**  
  Where authority, escalation, and override are located.

- **Ethics, equity, and risk**  
  Which harms or inequities require active oversight.

If governance mechanisms cannot support these requirements, earlier design decisions must be revisited.

---

## Core Design Questions

Designers should be able to answer the following questions clearly.

### Accountability
- Who is accountable for system outcomes at each decision point?
- Where does responsibility sit when AI outputs contribute to decisions?
- How is accountability communicated to users and stakeholders?

### Traceability
- What information must be recorded to explain system behaviour?
- Can decisions be reconstructed and justified after the fact?
- How are changes to models, rules, or workflows documented?

### Review and monitoring
- How often is system behaviour reviewed?
- Who conducts reviews, and with what authority?
- What triggers deeper investigation or intervention?

### Contestability and override
- How can decisions be challenged by users or affected parties?
- How are overrides implemented and recorded?
- Are contestation processes practical in real workflows?

### Scope and use control
- How is appropriate use defined and enforced?
- What prevents gradual expansion into unsuitable contexts?
- How are boundary breaches detected and addressed?

---

## Common Failure Modes at This Stage

Typical governance failures include:

- assuming audit logs alone constitute oversight
- designing review processes that are too slow or burdensome to use
- obscuring accountability through distributed responsibility
- providing theoretical contestation without practical access
- allowing systems to drift beyond their original scope

These failures often become visible only during incidents or external scrutiny.

---

## Outputs of This Step

The outcome of this step should be a **documented governance and oversight design**, typically captured using the **Governance and Oversight Plan** in `/design-artifacts`.

At minimum, this output should specify:

- accountability roles and responsibilities
- logging and traceability requirements
- review cadence and authority
- contestation and override mechanisms
- scope boundaries and enforcement approaches

This output constrains system architecture, data handling, and operational processes.

---

## Relationship to System Design

Governance and oversight requirements directly shape:

- permissions and access controls
- workflow structure and checkpoints
- data retention and logging design
- user interfaces for review and override

Treating governance as separate from system design creates brittle and ineffective controls.

---

## Practical Guidance

When designing governance and oversight:

- prioritise mechanisms that work under real conditions
- ensure oversight does not rely on exceptional effort
- design for disagreement and challenge
- assume systems will be used under pressure

Effective governance makes responsible behaviour the default, not the exception.

---

## Summary

This step ensures that Capability-Driven Development produces systems that are:

- accountable in practice, not just in principle
- transparent and contestable
- robust under institutional, regulatory, and public scrutiny

By designing governance and oversight into systems from the outset, CDD supports long-term trust and defensibility.

---

## Next Step

Continue to:

👉 `05-system-design-and-architecture.md`

That step translates capability, boundary, ethical, and governance constraints into concrete system structures and design patterns.
