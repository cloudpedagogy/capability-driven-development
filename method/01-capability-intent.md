# Capability Intent

_Status: Draft_

---

## Purpose of This Step

This step defines **capability intent**: a clear, explicit articulation of the human, organisational, and institutional capabilities that a system is intended to support, protect, or strengthen.

Capability intent is the **first and most critical step** in Capability-Driven Development.

Its purpose is to ensure that:
- system design begins with capability requirements, not tools
- automation does not quietly reshape roles or responsibilities
- later design decisions remain anchored to human and institutional needs
- trade-offs are made consciously rather than implicitly

If capability intent is unclear or implicit, all subsequent steps in the method are compromised.

---

## What Is Capability Intent?

Capability intent describes:

- **what people must remain able to do** as a result of the system  
- **what judgements must remain human**  
- **what responsibilities cannot be delegated to automation**  
- **what institutional values must be preserved**  

It is not a description of:
- system features
- technical functionality
- efficiency gains
- implementation approach

Capability intent answers a different question:

> *What capability must this system exist to serve — and what capability must it not undermine?*

---

## Relationship to the AI Capability Framework

Capability intent should be defined **with explicit reference to the AI Capability Framework**.

The Framework provides:
- the capability domains
- the ethical and governance grounding
- the shared language for judgement

Capability intent translates those domains into **system-specific intent**.

For example:
- Which capability domains are most relevant in this context?
- Where is capability particularly fragile?
- What forms of erosion would be unacceptable?

Capability intent does not restate the Framework.  
It applies it deliberately.

---

## What Capability Intent Is *Not*

To avoid misinterpretation, capability intent is **not**:

- a list of system requirements
- a technical specification
- a product vision statement
- a statement of intended benefits alone

Statements such as:
- “reduce workload”
- “improve efficiency”
- “scale support”
- “automate decisions”

are **insufficient** unless they are explicitly linked to capability preservation and limits.

---

## Core Design Questions

When defining capability intent, designers should be able to answer the following questions clearly and in plain language.

### Capability preservation
- What human capabilities must remain central when this system is in use?
- What forms of expertise, judgement, or discretion must not be displaced?

### Capability strengthening
- Where should the system *support* people to act more effectively, confidently, or consistently?
- What forms of cognitive, administrative, or analytical load are appropriate to reduce?

### Capability limits
- What decisions or actions must not be automated under any circumstances?
- Where must human accountability remain explicit and visible?

### Institutional responsibility
- What responsibilities does the institution retain regardless of system behaviour?
- What failures would be unacceptable even if technically efficient?

---

## Common Failure Modes at This Stage

Capability intent is often undermined by predictable design shortcuts:

- starting with available tools or platforms
- defining success only in terms of efficiency or scale
- assuming “human-in-the-loop” without specifying what that means
- deferring ethical or governance concerns to later stages

These shortcuts result in systems that:
- erode professional judgement
- obscure accountability
- create governance risk
- are difficult to defend after deployment

CDD explicitly treats these as design failures, not implementation issues.

---

## Outputs of This Step

The outcome of this step should be a **documented capability intent**, typically captured using the **System Capability Brief** in `/design-artifacts`.

At minimum, this output should include:

- a concise statement of capability purpose
- explicit capability boundaries
- identification of non-negotiable human roles
- reference to relevant AI Capability Framework domains

This output constrains all subsequent design steps.

---

## Relationship to Subsequent Steps

Capability intent directly informs:

- **Human–AI boundaries**  
  by defining what cannot be delegated

- **Ethics, equity, and risk**  
  by clarifying what harms would constitute capability erosion

- **Governance and oversight**  
  by anchoring accountability to capability, not system output

If capability intent changes, earlier design decisions must be revisited.

---

## Practical Guidance

When defining capability intent:

- write it in language understandable outside technical teams
- make assumptions explicit
- prioritise clarity over completeness
- revisit and refine it collaboratively

Capability intent is not immutable, but it should not drift silently.

---

## Summary

Capability intent establishes **why a system should exist at all** from a capability perspective.

By defining intent before automation, Capability-Driven Development ensures that:

- systems serve human capability rather than reshape it by default
- governance is grounded in purpose
- design decisions remain defensible over time

This step sets the ethical and operational foundation for everything that follows.

---

## Next Step

Continue to:

👉 `02-human-ai-boundaries.md`

That step translates capability intent into explicit design boundaries between human judgement and AI assistance.
