# AI-Assisted Reflection: Capability Intent

_Status: Optional · Secondary · Human-Led_

---

## Purpose and Limits

This document supports **human reflection on capability intent** during the design of AI-enabled systems.

It exists to help designers:
- clarify what capability a system is meant to support
- surface hidden assumptions early
- test the coherence and defensibility of intent
- resist technology-first or convenience-driven framing

AI may be used here as a **reflective aid**, not as an authority.

This document does **not** replace:
- the System Capability Brief
- human judgement
- institutional responsibility

If reflection becomes delegation, stop using AI.

---

## When This Reflection Is Useful

This reflection is most useful:

- **before** technical design begins  
- when capability intent feels vague or over-broad  
- when a system risks being justified by efficiency alone  
- when stakeholders disagree on purpose or scope  
- when revisiting intent after scope creep or iteration  

It is **not** intended for late-stage justification or approval.

---

## Core Human-Led Reflection

Before involving AI, reflect in your own words.

Consider the questions below slowly and deliberately.

### 1. What capability is this system meant to support?

Not:
- what the system does
- what technology it uses
- what task it automates

But:
- what *humans or institutions* should be better able to do because this system exists

If this system disappeared tomorrow, what capability loss would actually matter?

---

### 2. Which capabilities must remain human?

Identify capabilities that must **not** be transferred to automation.

Examples:
- ethical judgement
- contextual interpretation
- care, discretion, or responsibility
- accountability for outcomes

Ask:
- What would be unacceptable to lose, even if automation worked “well”?
- Where must authority always remain human?

---

### 3. What capability risks are being accepted?

Every system trades off capability in some way.

Reflect on:
- which capabilities may be weakened
- whose capability might be reduced rather than strengthened
- whether convenience is being mistaken for capability improvement

Being explicit about trade-offs is a mark of responsible design.

---

### 4. What assumptions underpin this intent?

Surface assumptions such as:
- who users are
- how much context they have
- how decisions are made in practice
- what “good outcomes” look like

Assumptions left unexamined tend to harden into design constraints.

---

## Optional AI-Assisted Reflection

Once human intent is articulated, AI may be used as a **mirror**, not a guide.

Appropriate uses of AI include asking it to:

- restate your capability intent in different language
- identify ambiguity or vagueness
- surface implicit assumptions
- highlight tensions between stated goals

Example prompts (adapt freely):

- “Restate this capability intent in plain language and identify ambiguities.”
- “What assumptions might be embedded in this description of capability?”
- “Where could this intent drift toward automation of judgement?”

---

## How to Interpret AI Responses

Treat AI outputs as:
- hypotheses
- alternative framings
- provocations for thought

Do **not** treat them as:
- validation
- critique with authority
- decision criteria

If AI suggestions feel:
- generic
- overly confident
- optimisation-driven
- detached from lived context

they should be discarded without hesitation.

---

## Failure Modes and Warnings

Stop using AI-assisted reflection if you notice:

- AI redefining the purpose of the system
- scope expanding without human agreement
- efficiency replacing responsibility as the primary goal
- language becoming abstract or managerial
- reduced confidence in your own judgement

AI is a poor substitute for accountability.

---

## Relationship to Capability-Driven Development

This reflection supports — but does not replace — the following artefacts:

- `design-artifacts/system-capability-brief.md`
- `design-artifacts/human-ai-boundary-map.md`

If AI-assisted reflection conflicts with the Capability Brief,  
the **Capability Brief takes precedence**.

If the Capability Brief itself feels wrong, revise it **explicitly and transparently**.

---

## Summary

This reflection exists to support one foundational question:

> **What human or institutional capability must this system protect — and why does that matter?**

AI can help surface blind spots.  
It cannot tell you what responsibility requires.

If intent becomes unclear, return to human reflection.
