# Example: Monitoring and Oversight System

_Status: Draft_

---

## Context and Problem

Organisations increasingly rely on monitoring systems to surface risks, anomalies, or patterns that require attention.

Common contexts include:
- operational risk and quality assurance
- safeguarding and wellbeing signals
- academic integrity or misconduct indicators
- compliance and governance monitoring

AI-enabled monitoring systems are often proposed to:
- scan large volumes of activity
- detect patterns humans might miss
- alert staff to potential issues earlier

However, poorly designed monitoring systems can:
- drift into surveillance
- overwhelm staff with low-value alerts
- shift responsibility from judgement to metrics
- erode trust among those being monitored

This example illustrates how **Capability-Driven Development** guides the responsible design of an AI-assisted **monitoring and oversight system** that supports judgement without normalising surveillance or automation bias.

---

## Capability Intent

The primary capability intent of this system is to **support informed oversight**, not to enforce compliance or automate judgement.

Specifically, the system is intended to:
- surface signals that merit human attention
- support timely, proportionate review
- enable institutional responsibility and care
- strengthen transparency and accountability

Non-negotiable capability constraints include:
- signals must not be treated as conclusions
- human review must precede any action
- monitoring must be proportionate and contextual
- oversight must not become continuous surveillance

The system exists to **support responsibility**, not to police behaviour.

---

## Human–AI Boundaries

Clear boundaries are established between automated signal detection and human judgement.

In this system:
- AI may identify patterns, anomalies, or thresholds
- AI may cluster or summarise signals for review
- AI may prioritise signals based on defined criteria

AI may **not**:
- determine intent, guilt, or wrongdoing
- initiate punitive action
- close cases or dismiss concerns
- override human judgement

Humans retain authority to:
- interpret signals in context
- determine whether review or action is required
- decide appropriate responses
- document rationale for decisions

Silence or absence of signals is not treated as assurance.

---

## Ethics, Equity, and Risk

Monitoring systems introduce significant ethical and equity risks:

- **Surveillance creep**: expansion beyond original scope  
- **False positives**: disproportionate scrutiny of certain groups  
- **Chilling effects**: behaviour change due to perceived monitoring  
- **Opacity**: lack of understanding of what is monitored and why  

Mitigations include:
- clear definition and communication of monitoring purpose
- proportional thresholds and review criteria
- periodic equity impact analysis
- separation between signal detection and action

Unacceptable risks include:
- covert monitoring
- punitive use of weak signals
- monitoring without clear accountability

---

## Governance and Oversight

Governance focuses on **how monitoring is used**, not just what is detected.

Key governance features include:
- explicit ownership of monitoring functions
- documentation of signal interpretation and response
- review of alert thresholds and criteria
- oversight of how monitoring affects practice and culture

Oversight addresses:
- volume and quality of signals
- response timeliness and proportionality
- equity impacts over time
- adherence to stated monitoring scope

Governance mechanisms are designed to prevent normalisation of over-monitoring.

---

## System Design and Architecture

Architectural decisions reinforce restraint and review.

Key structural choices include:
- separation between detection, review, and action components
- dashboards designed for periodic review, not constant attention
- explicit acknowledgement of uncertainty in signals
- no automatic transitions from signal to consequence

Failure modes are designed to be safe:
- system failure does not halt core activities
- absence of signals does not imply safety or compliance
- alerts degrade gracefully rather than catastrophically

The architecture prioritises interpretability and accountability over coverage.

---

## Evaluation and Monitoring

Evaluation focuses on **oversight effectiveness**, not alert volume.

Key evaluation questions include:
- Are signals meaningful and actionable?
- Are reviewers able to exercise judgement effectively?
- Are certain groups over- or under-represented in signals?
- Is monitoring affecting behaviour or trust?

Indicators include:
- review outcomes and follow-up actions
- false positive and false negative patterns
- qualitative feedback from reviewers and those affected
- periodic reassessment of monitoring scope

Evaluation findings inform changes to thresholds, criteria, and governance.

---

## Iteration and Change

Changes to monitoring criteria or scope are tightly governed.

Each proposed change triggers review of:
- capability intent alignment
- ethical and equity implications
- impact on trust and behaviour
- governance adequacy

Iteration prioritises:
- minimal viable monitoring
- reversibility
- explicit documentation of rationale

Expansion of monitoring scope requires explicit justification and approval.

---

## Retirement and Deprecation

Monitoring systems are explicitly designed to be reducible or withdrawn.

Triggers for retirement or scope reduction include:
- sustained lack of meaningful signals
- unacceptable equity or trust impacts
- changes in legal or ethical context
- availability of less intrusive alternatives

Retirement planning includes:
- transparent communication
- preservation of accountability records
- reflection on organisational learning

Ending monitoring is treated as a responsible outcome, not failure.

---

## Key Design Trade-offs

This example illustrates deliberate trade-offs such as:

- proportional oversight over comprehensive surveillance
- interpretability over detection sensitivity
- trust preservation over enforcement efficiency
- human review over automated response

These trade-offs are explicit and revisited over time.

---

## What This Example Demonstrates About CDD

This example shows how Capability-Driven Development:

- treats monitoring as a governance function, not a control mechanism
- embeds ethical restraint into system structure
- preserves human judgement under conditions of uncertainty
- supports oversight without normalising surveillance
- enables systems to end responsibly

Monitoring and oversight systems are most effective when they **support institutional responsibility without eroding trust**.

This example demonstrates how CDD makes that balance explicit and enforceable.
