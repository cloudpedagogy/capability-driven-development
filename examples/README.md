# Capability-Driven Development — Examples

_Status: Draft_

---

## Purpose of the Examples

The examples in this directory demonstrate how **Capability-Driven Development (CDD)** is applied in practice.

They are **worked design narratives**, not implementation guides.

Each example shows how the CDD method shapes:
- system intent
- human–AI boundaries
- ethical and governance decisions
- architectural structure
- evaluation, change, and retirement considerations

The purpose of these examples is to make the method **concrete, legible, and defensible**.

---

## What These Examples Are

CDD examples are:

- end-to-end design walkthroughs  
- grounded in realistic professional contexts  
- structured explicitly around the CDD method steps  
- focused on **design reasoning and trade-offs**  
- technology-agnostic and implementation-neutral  

They illustrate *how decisions are made*, not *how systems are built*.

---

## What These Examples Are Not

CDD examples are **not**:

- tutorials or how-to guides  
- platform or vendor documentation  
- code repositories or workflow definitions  
- product specifications  
- reference architectures  

Specific tools, platforms, or implementations may be explored elsewhere (e.g. Labs), but are intentionally excluded here.

---

## How to Read the Examples

Each example follows the same underlying logic, aligned to the CDD method:

1. Capability intent  
2. Human–AI boundaries  
3. Ethics, equity, and risk  
4. Governance and oversight  
5. System design and architecture  
6. Evaluation and monitoring  
7. Iteration and change  
8. Retirement and deprecation  

Not every example gives equal weight to every step, but all steps are considered.

Readers are encouraged to:
- read examples alongside the `/method` documents
- focus on *why* decisions were made, not just *what* was chosen
- compare examples to see how CDD adapts across contexts

---

## Current Examples

The current examples are organised by **capability challenge**, not by sector, tool, or technology.

### Decision Support Systems  
`example-decision-support-system.md`

Explores systems where AI supports human judgement by analysing information, surfacing options, or highlighting considerations — without making final decisions.

Typical contexts include:
- advisory tools
- classification support
- sense-making systems

---

### Workflow Orchestration Systems  
`example-workflow-orchestration-system.md`

Explores systems that coordinate tasks, routing, escalation, and hand-offs between humans and AI.

Typical contexts include:
- request or case routing
- triage and escalation workflows
- semi-agentic coordination systems

---

### Monitoring and Oversight Systems  
`example-monitoring-and-oversight-system.md`

Explores systems that monitor activity, risk, or patterns and surface signals for human review.

Typical contexts include:
- risk detection
- compliance monitoring
- anomaly or threshold alerts

---

## Why Examples Are Grouped This Way

Examples are grouped by **system role**, not by application domain.

This allows:
- reuse across education, research, and public-interest contexts  
- comparison of how CDD applies to different system functions  
- extension to new domains without restructuring the repository  

Specific instantiations (e.g. higher education, research administration) may be discussed within examples, but do not define them.

---

## Adding New Examples

New examples should be added when they:

- demonstrate a **distinct capability challenge**
- reveal a **new design tension or trade-off**
- stress-test the CDD method in a meaningful way

Examples should not be added solely to:
- showcase a tool
- document an implementation
- repeat an existing pattern with minor variation

When in doubt, extend an existing example rather than creating a new one.

---

## Relationship to Other Directories

- `/method`  
  Defines the CDD process that examples apply.

- `/patterns`  
  Abstracts recurring design solutions observed across examples.

- `/design-artifacts`  
  Provides templates used to document decisions illustrated in examples.

- `/labs` (if present elsewhere)  
  May contain runnable or technical implementations inspired by examples.

---

## Summary

The examples in this directory show how Capability-Driven Development operates **in practice**, across different types of AI-enabled systems.

They are intended to support:
- learning and sense-making  
- design review and discussion  
- institutional defensibility  
- consistent application of the method  

Examples are where the method becomes real.

