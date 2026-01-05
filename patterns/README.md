# Capability-Driven Development — Design Patterns

_Status: Draft_

---

## Purpose of Patterns

The patterns in this directory capture **recurring, capability-preserving design solutions** observed across Capability-Driven Development (CDD) examples.

Their purpose is to:
- make common human–AI design tensions explicit
- provide reusable ways of addressing those tensions responsibly
- support consistent application of the CDD method across systems and contexts
- reduce the risk of repeating known design failures

Patterns sit between **method** and **implementation**:
- they are more concrete than the method
- but more abstract than tools, platforms, or architectures

---

## What a Pattern Is

In Capability-Driven Development, a pattern is:

- a **named response to a recurring capability risk**
- grounded in human judgement, governance, and accountability
- technology-agnostic and context-sensitive
- derived from practice, not theory alone

Each pattern describes:
- the **capability risk** it addresses
- the **design problem** that recurs across systems
- a **structural solution** that helps preserve responsibility
- the conditions under which it is appropriate

Patterns do not prescribe a single implementation.
They describe *design intent and structure*.

---

## What a Pattern Is Not

CDD patterns are **not**:

- technical recipes or code templates
- platform- or vendor-specific guidance
- best-practice checklists
- compliance requirements
- guarantees of ethical outcomes

Using a pattern does not remove the need for judgement.
Patterns support judgement — they do not automate it.

---

## How Patterns Are Used

Patterns are intended to be used:

- during **system design**, to address known risks early
- during **design review**, to test whether responsibilities are preserved
- during **iteration and change**, to detect erosion of capability
- alongside **examples**, to abstract transferable lessons

Patterns may be:
- combined
- adapted
- constrained by context

They should not be applied mechanically.

---

## Relationship to the CDD Method

Patterns do not replace the Capability-Driven Development method.

Instead:
- the **method** defines the design sequence and questions
- **patterns** offer reusable responses to common issues encountered during that sequence

Most patterns relate to multiple method steps, but typically emerge when addressing:
- human–AI boundaries
- ethics, equity, and risk
- governance and oversight
- system design and architecture

Patterns should always be applied **after** capability intent is defined.

---

## Relationship to Examples

Patterns are abstracted from the worked examples in `/examples`.

Each pattern:
- references examples where it is demonstrated
- highlights how similar risks appear across different system types
- supports comparison and learning across contexts

Examples show patterns *in action*;  
patterns make examples *transferable*.

---

## Current Pattern Set

The current patterns address common capability risks in AI-enabled systems:

- **Human-in-the-Loop**  
  Preventing displacement of judgement through explicit boundary design.

- **Safe Delegation**  
  Delegating tasks to AI without delegating responsibility.

- **Fallback and Escalation**  
  Ensuring systems behave safely when automation fails or uncertainty arises.

- **Contestability and Override**  
  Making disagreement, challenge, and reversal practical and legitimate.

- **Auditability and Traceability**  
  Supporting explanation, review, and accountability over time.

- **Graceful Failure**  
  Designing systems that fail visibly and safely rather than silently.

This set is expected to evolve through use.

---

## Adding New Patterns

New patterns should be added only when they:

- address a **distinct and recurring capability risk**
- are observed across multiple examples or contexts
- offer a reusable structural solution
- cannot be adequately covered by an existing pattern

Patterns should not be added to:
- document a single implementation
- showcase a tool or technology
- duplicate existing patterns with minor variation

When in doubt, refine or extend an existing pattern.

---

## Pattern Structure

All patterns follow a consistent structure:

- Context  
- Capability risk addressed  
- Problem  
- Pattern (solution)  
- How the pattern preserves capability  
- When to use  
- When not to use  
- Relationship to CDD method steps  
- Common misuses or failure modes  
- Related examples  

This structure ensures patterns remain usable, defensible, and comparable.

---

## Summary

Patterns are where Capability-Driven Development becomes **reusable without becoming rigid**.

They capture hard-won design lessons while preserving:
- human judgement
- institutional accountability
- ethical restraint
- contextual flexibility

Patterns help ensure that responsible design choices are not rediscovered the hard way.

