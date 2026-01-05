# Example: Decision Support System

_Status: Draft_

---

## Context and Problem

Organisations frequently face complex decisions that require synthesising large volumes of information, policy guidance, historical precedent, and contextual judgement.

In education, research, and public-interest settings, these decisions are often:
- time-pressured
- high-stakes
- ethically sensitive
- subject to scrutiny or appeal

Decision support systems using AI are increasingly proposed to:
- summarise information
- surface relevant considerations
- highlight risks or inconsistencies

However, poorly designed systems can:
- displace professional judgement
- create over-reliance on recommendations
- obscure accountability
- undermine trust when decisions are challenged

This example illustrates how **Capability-Driven Development** guides the responsible design of an AI-assisted **decision support system**, not an automated decision-making system.

---

## Capability Intent

The primary capability intent of this system is to **support human judgement**, not replace it.

Specifically, the system is intended to:
- help professionals reason more consistently and transparently
- surface relevant information and considerations
- reduce cognitive load without reducing responsibility
- support defensible, explainable decision-making

Non-negotiable capability constraints include:
- final decisions must remain human
- professional discretion must be preserved
- accountability must be explicit and traceable
- the system must not create a single “correct” answer

The system exists to **augment decision quality**, not to optimise speed or throughput alone.

---

## Human–AI Boundaries

Clear boundaries are established between AI assistance and human authority.

In this system:
- AI may analyse inputs, summarise information, and highlight considerations
- AI may suggest *questions* or *factors* to consider
- AI may flag potential risks or inconsistencies

AI may **not**:
- make decisions
- approve or reject cases
- assign outcomes
- close decision pathways

Humans retain authority to:
- interpret system outputs
- weigh competing considerations
- decide outcomes
- justify and document decisions

Escalation and override are implicit: the human decision-maker can disregard or challenge AI outputs without penalty or justification to the system itself.

---

## Ethics, Equity, and Risk

Several ethical and equity risks are identified early:

- **Over-trust risk**: users may defer to AI suggestions due to perceived objectivity  
- **Bias amplification**: historical patterns reflected in data may disadvantage certain groups  
- **Opacity risk**: outputs that cannot be explained may undermine contestability  
- **Defensive use**: decisions may be justified by reference to the system rather than judgement  

Mitigations include:
- framing outputs as considerations, not recommendations
- avoiding confidence scores or rankings that imply correctness
- requiring human rationale to be recorded independently of AI output
- reviewing impacts across different user groups over time

Unacceptable risks include:
- use of the system as a decision proxy
- pressure to align outcomes with AI outputs for consistency metrics

---

## Governance and Oversight

Governance mechanisms are designed into system use rather than imposed externally.

Key governance features include:
- clear accountability for decisions resting with named human roles
- logging of AI inputs and outputs for transparency
- separation between AI analysis records and human decision rationale
- review mechanisms for contested or appealed decisions

Oversight focuses on:
- patterns of use (e.g. reliance trends)
- divergence between AI suggestions and human decisions
- equity impacts across cases
- system scope adherence

Governance review is periodic and contextual, not continuous surveillance.

---

## System Design and Architecture

Architecturally, the system is designed to reinforce its advisory role.

Key structural decisions include:
- explicit separation between AI analysis components and decision records
- user interfaces that foreground human judgement fields
- no automated transitions from AI output to decision states
- clear visibility of uncertainty and limitations

Failure modes are designed to be safe:
- if AI components fail, the decision process continues without them
- no silent degradation into automated decision-making
- fallback behaviour defaults to human-only processes

The system is intentionally modular to support revision and constraint.

---

## Evaluation and Monitoring

Evaluation focuses on **capability outcomes**, not just performance.

Key evaluation questions include:
- Are users still exercising judgement as intended?
- Is AI output being treated as advisory in practice?
- Are certain groups disproportionately affected by decisions?
- Is reliance on AI increasing over time?

Indicators include:
- qualitative feedback from decision-makers
- review of contested decisions
- analysis of divergence patterns
- periodic reflective review sessions

Evaluation findings are documented and feed directly into change decisions.

---

## Iteration and Change

Changes to the system are governed and deliberate.

Any proposed change triggers review of:
- capability intent alignment
- shifts in human–AI boundaries
- new ethical or equity risks
- governance adequacy

Small changes are not exempt from review if they affect:
- decision framing
- visibility of AI outputs
- workflow defaults

Iteration is reversible where possible, and changes are documented with rationale.

---

## Retirement and Deprecation

From the outset, conditions for retirement are defined.

Triggers include:
- sustained misalignment with capability intent
- inability to govern or oversee use effectively
- emergence of unacceptable risk or inequity
- availability of more appropriate non-technical alternatives

Retirement planning includes:
- preserving decision records for accountability
- supporting users through transition
- documenting lessons learned

Ending system use is treated as a responsible outcome, not failure.

---

## Key Design Trade-offs

This example illustrates several deliberate trade-offs:

- slower decisions in exchange for defensibility
- reduced automation in exchange for accountability
- flexibility in outcomes over consistency metrics
- interpretability over predictive optimisation

These trade-offs are explicit and intentional.

---

## What This Example Demonstrates About CDD

This example shows how Capability-Driven Development:

- keeps judgement human by design, not policy
- embeds ethics and governance into system structure
- treats architecture as a carrier of responsibility
- supports learning across the system lifecycle
- enables systems to end responsibly

Decision support systems are most effective when they **strengthen capability rather than substitute for it**.

This example demonstrates how CDD makes that distinction operational.
