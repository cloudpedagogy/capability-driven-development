# Capability-Driven Development (CDD)

**A capability-first approach to designing AI-enabled software systems**

---

## Overview

**Capability-Driven Development (CDD)** is a practical, capability-first approach to designing AI-enabled software systems.

It provides a structured method for translating **human, organisational, and institutional capability requirements** into concrete system design decisions — before architectures, automation, or implementation choices are made.

CDD is designed to be used alongside the **CloudPedagogy AI Capability Framework**, helping builders, designers, and institutions ensure that AI-enabled systems remain responsible, governable, and defensible as technologies evolve.

---

## Why Capability-Driven Development Exists

The CloudPedagogy **AI Capability Framework** defines what responsible AI capability looks like across six domains:

- awareness  
- co-agency  
- applied practice  
- ethics and equity  
- governance  
- continuous learning  

However, many organisations struggle with a practical gap:

> **How do we actually design and build software systems that embody those capability requirements?**

In practice, AI-enabled systems are often developed by:

- starting with tools or platforms  
- automating tasks before defining human oversight  
- addressing ethics and governance after deployment  
- treating capability as training rather than design  

**Capability-Driven Development exists to close this gap.**

It ensures that:

- capability requirements are defined *before* automation  
- human judgement is designed into systems, not added later  
- governance and accountability are treated as design constraints  
- systems can evolve without undermining institutional responsibility  

---

## Relationship to the AI Capability Framework

The relationship between the two is intentional and explicit:



**AI Capability Framework**  
→ defines **WHAT** responsible AI capability is


**Capability-Driven Development**
→ defines **HOW** to design and build systems that embody that capability



### Key principles of this relationship

- CDD does **not replace** the AI Capability Framework  
- CDD **assumes and applies** the Framework  
- The Framework can be used **without** CDD  
- CDD should **not** be used without reference to the Framework  

The Framework provides the **normative foundation**;  
CDD provides the **procedural design method**.

---

## What Capability-Driven Development Is (and Is Not)

### CDD *is*:

- a software and systems design approach  
- capability-first, not technology-first  
- explicitly concerned with human–AI boundaries  
- grounded in governance, ethics, and accountability  
- applicable to AI-enabled systems in education, research, and public-interest contexts  

### CDD *is not*:

- a tool or platform  
- a maturity model or compliance checklist  
- a prompt-engineering guide  
- a replacement for institutional policy or professional judgement  

CDD supports responsible design — it does not automate responsibility.

---

## The Capability-Driven Development Method

At its core, CDD follows a deliberate design sequence:

1. **Capability intent**  
   Define the human and institutional capabilities the system must support.

2. **Human–AI boundaries**  
   Specify where AI assists, where humans decide, and where escalation occurs.

3. **Ethics, equity, and risk**  
   Identify foreseeable harms, exclusions, misuse, and unintended consequences.

4. **Governance and oversight**  
   Design accountability, traceability, review, and contestability into the system.

5. **System design and architecture**  
   Select architectures and implementation patterns that respect earlier constraints.

6. **Evaluation and monitoring**  
   Determine how the system will be reviewed, audited, and improved over time.

7. **Iteration and change**  
   Plan for adaptation as technologies, contexts, and expectations evolve.

8. **Retirement and deprecation**  
   Design for graceful shutdown, replacement, or withdrawal where necessary.

This method is described in detail in the `/method` directory.

---

## Repository Structure

This repository is organised to support practical application and long-term evolution.

### `/foundations` — Scope, Purpose, and Framework Alignment

Clarifies the purpose, boundaries, and positioning of Capability-Driven Development, including its explicit relationship to the CloudPedagogy AI Capability Framework.



### `/method` — The Capability-Driven Development Method

The procedural core of Capability-Driven Development, outlining the ordered design steps for translating capability requirements into system design decisions.


### `/design-artifacts` — Capability-Led Design Templates

Reusable templates for documenting capability intent, human–AI boundaries, governance, risk, and evaluation within AI-enabled system design.


### `/patterns` — Capability-Aware Design Patterns

Technology-agnostic design patterns for implementing capability requirements responsibly, including oversight, delegation, fallback, and contestability.



### `/examples` — Applied System-Level Illustrations

Illustrative system-level examples showing how Capability-Driven Development can be applied in real design and development contexts.


### `/ai-assisted-reflection` — Optional AI-Supported Design Reflection

Optional prompts to support human reflection and sense-making during system design.  
These resources are explicitly secondary to the method and do not automate decisions.

## How This Repository Is Intended to Be Used

Capability-Driven Development is most effective when used as part of a broader capability development journey:

- **Assess** current capability using the AI Capability Framework  
- **Design** systems using Capability-Driven Development  
- **Implement** systems via applied Labs or projects  
- **Reflect and adapt** as contexts and technologies change  

CDD supports designers, developers, learning technologists, and applied researchers who are building real systems where AI use must remain responsible, governable, and defensible.

## Status and Evolution

Capability-Driven Development is a **living method**.

- The AI Capability Framework is intentionally stable  
- CDD is expected to evolve through applied use  
- Changes are documented via versioning and changelogs  
- Individual documents may be marked **Draft**, **Stable**, or **Deprecated**  

Stability is treated as a governance concern, not an assumption.


## License

This repository is released under the  
**Creative Commons Attribution–NonCommercial–ShareAlike 4.0 International License (CC BY-NC-SA 4.0).**

You are free to share and adapt the material for non-commercial purposes, provided appropriate credit is given and derivatives are shared under the same licence.

---

## About CloudPedagogy

CloudPedagogy develops open, governance-credible resources for building confident, responsible AI capability across education, research, and public service.

- Website: https://www.cloudpedagogy.com/
- Framework: https://github.com/cloudpedagogy/cloudpedagogy-ai-capability-framework


