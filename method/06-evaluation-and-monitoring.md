# Evaluation and Monitoring

_Status: Draft_

---

## Purpose of This Step

This step defines how an AI-enabled system is **evaluated and monitored over time** to ensure it continues to support the intended human, organisational, and institutional capabilities.

Its purpose is to ensure that:
- system behaviour remains aligned with capability intent
- ethical, equity, and governance commitments hold in practice
- drift, misuse, or over-reliance are detected early
- learning and improvement are intentional rather than reactive

In Capability-Driven Development, evaluation is not an end-stage activity.  
It is an ongoing responsibility.

---

## Why Evaluation Must Be Capability-Led

Many systems are evaluated primarily through:
- accuracy or performance metrics
- uptime and throughput indicators
- usage volume or efficiency gains

While useful, these measures are **insufficient** on their own.

A system can be:
- performant but harmful
- efficient but exclusionary
- widely used but poorly governed

CDD therefore treats evaluation as a **capability question**, not just a technical one.

---

## What Evaluation and Monitoring Cover

Evaluation and monitoring address:

- whether human judgement is still exercised where intended
- whether AI outputs are being over-trusted or misused
- whether governance and oversight mechanisms are functioning
- whether equity impacts are emerging or worsening
- whether system use remains within its defined scope

The focus is on **system behaviour in context**, not isolated metrics.

---

## Relationship to Earlier Steps

Evaluation and monitoring are anchored in:

- **Capability intent**  
  What capabilities the system exists to support and protect.

- **Human–AI boundaries**  
  Whether boundaries are respected or eroded in practice.

- **Ethics, equity, and risk**  
  Whether anticipated risks are materialising and new ones emerging.

- **Governance and oversight**  
  Whether review, contestation, and accountability mechanisms are used effectively.

If evaluation reveals misalignment, earlier design decisions must be revisited.

---

## Core Evaluation Questions

Designers and operators should be able to answer the following questions regularly.

### Capability alignment
- Are users still exercising judgement as intended?
- Has reliance on automation increased beyond design expectations?
- Are any capabilities being weakened or displaced?

### Behaviour and use
- How is the system actually being used under real conditions?
- Are users bypassing safeguards or workarounds becoming normalised?
- Are defaults shaping behaviour in unintended ways?

### Oversight effectiveness
- Are review and oversight processes actively used?
- Are alerts, escalations, or overrides meaningful or ignored?
- Is contestation practical for those affected?

### Equity and impact
- Are particular groups disproportionately affected?
- Are access, burden, or outcomes unevenly distributed?
- Are impacts changing over time?

### Drift and change
- Has the system’s scope expanded informally?
- Have updates altered behaviour without corresponding review?
- Is the system still appropriate for its context?

---

## Common Failure Modes at This Stage

Typical evaluation failures include:

- monitoring only technical performance
- treating evaluation as periodic compliance
- ignoring qualitative feedback or lived experience
- failing to act on known issues
- allowing “temporary” workarounds to become permanent

These failures often lead to gradual erosion of capability and trust.

---

## Outputs of This Step

The outcome of this step should be a **documented evaluation and monitoring plan**, typically captured using the **Capability Evaluation Log** in `/design-artifacts`.

At minimum, this output should include:

- evaluation questions linked to capability intent
- qualitative and quantitative indicators
- review cadence and responsible roles
- escalation triggers and response pathways
- mechanisms for capturing user and stakeholder feedback

Evaluation findings should be recorded, reviewed, and acted upon.

---

## Relationship to Iteration and Change

Evaluation and monitoring directly inform:

- whether boundaries or governance need adjustment
- whether design assumptions remain valid
- whether the system should be expanded, constrained, or withdrawn

Without structured evaluation, iteration becomes guesswork.

---

## Practical Guidance

When evaluating AI-enabled systems:

- prioritise interpretability over volume of metrics
- combine data with human judgement
- treat disagreement and discomfort as signals
- assume that impacts change over time

Effective evaluation supports learning without normalising harm.

---

## Summary

This step ensures that Capability-Driven Development produces systems that:

- remain aligned with their original capability purpose
- are responsive to emerging risks and inequities
- support accountability throughout their lifecycle

Evaluation is where responsibility is sustained, not concluded.

---

## Next Step

Continue to:

👉 `07-iteration-and-change.md`

That step defines how systems are deliberately adapted in response to evaluation findings and changing contexts.
