# Iteration and Change

_Status: Draft_

---

## Purpose of This Step

This step defines how AI-enabled systems are **iterated, adapted, and changed over time** in a controlled, capability-aligned manner.

Its purpose is to ensure that:
- changes are intentional rather than reactive
- capability intent remains explicit as systems evolve
- governance and accountability are preserved through modification
- learning from evaluation leads to responsible adaptation

In Capability-Driven Development, iteration is not a technical optimisation cycle.  
It is a **capability governance process**.

---

## Why Iteration Requires Deliberate Design

All AI-enabled systems change over time due to:
- updates to models, rules, or data
- shifts in organisational priorities
- changes in user behaviour or expectations
- regulatory, ethical, or contextual developments

Without structured iteration, systems tend to:
- drift beyond their original purpose
- accumulate unmanaged risk
- erode human judgement and oversight
- become difficult to defend or retire

CDD treats unmanaged change as a **capability risk**.

---

## What This Step Covers

Iteration and change address:

- how design assumptions are revisited
- how evaluation findings inform modification
- how changes are reviewed, approved, and documented
- how scope and boundaries are preserved or revised
- how responsibility is maintained through system evolution

It applies to **all changes**, not just major redesigns.

---

## Relationship to Earlier Steps

Iteration and change are grounded in:

- **Capability intent**  
  What the system exists to support must remain visible.

- **Human–AI boundaries**  
  Changes must not quietly shift authority or delegation.

- **Ethics, equity, and risk**  
  New or altered risks must be reassessed.

- **Governance and oversight**  
  Changes must remain reviewable and accountable.

- **Evaluation and monitoring**  
  Iteration should respond to observed behaviour, not assumptions.

Any change that invalidates earlier decisions requires those steps to be revisited.

---

## Core Design Questions

Designers and operators should be able to answer the following questions for any proposed change.

### Trigger and rationale
- What prompted this change?
- What evidence or evaluation supports it?
- What problem is the change intended to address?

### Capability impact
- Does this change strengthen or weaken intended capabilities?
- Does it alter who exercises judgement or authority?
- Are any capabilities at risk of erosion?

### Boundary and governance impact
- Does this change shift human–AI boundaries?
- Does it affect escalation, override, or contestability?
- Are new governance mechanisms required?

### Risk and equity impact
- Does the change introduce new risks or inequities?
- Does it alter who benefits or who bears burden?
- Are mitigation strategies still adequate?

### Reversibility
- Can this change be rolled back if needed?
- Is there a clear way to assess its impact post-change?

---

## Common Failure Modes at This Stage

Typical iteration failures include:

- implementing changes without revisiting capability intent
- treating “minor” changes as exempt from review
- allowing cumulative changes to shift system purpose
- failing to document decision rationales
- prioritising speed over accountability

These failures often lead to systems that no longer resemble their original design commitments.

---

## Outputs of This Step

The outcome of this step should be a **documented change and iteration record**, typically captured using the **Change Impact Note** in `/design-artifacts`.

At minimum, this output should include:

- description of the change
- rationale and triggering evidence
- assessment of capability impact
- review and approval record
- plan for post-change evaluation

Change records support transparency and institutional memory.

---

## Relationship to System Lifecycle

Iteration and change form the bridge between:
- initial system design
- long-term operation
- eventual retirement or replacement

Well-governed iteration makes later deprecation deliberate rather than urgent.

---

## Practical Guidance

When managing iteration and change:

- assume change will accumulate over time
- design review processes that scale
- make capability impact explicit in every change
- prefer reversible changes where possible

Responsible systems evolve consciously, not accidentally.

---

## Summary

This step ensures that Capability-Driven Development produces systems that:

- adapt without drifting
- learn without eroding accountability
- change without obscuring responsibility

Iteration is where capability commitments are either honoured or lost.

---

## Next Step

Continue to:

👉 `08-retirement-and-deprecation.md`

That final step defines how systems are responsibly withdrawn, replaced, or shut down without undermining capability, trust, or accountability.
