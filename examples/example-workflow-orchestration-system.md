# Example: Workflow Orchestration System

_Status: Draft_

---

## Context and Problem

Many organisations rely on complex workflows to handle requests, cases, or tasks that require coordination across multiple roles, teams, or functions.

Examples include:
- routing support or service requests
- triaging cases for review or escalation
- coordinating responses across departments
- managing queues, priorities, and hand-offs

AI-enabled workflow orchestration systems are increasingly proposed to:
- classify and route requests
- prioritise workloads
- reduce delays and manual coordination
- scale service provision

However, poorly designed orchestration systems can:
- obscure responsibility for outcomes
- shift judgement implicitly to automation
- create rigid processes that resist exception
- normalise escalation avoidance or deferral

This example illustrates how **Capability-Driven Development** guides the responsible design of an AI-assisted **workflow orchestration system** that coordinates work without displacing human responsibility.

---

## Capability Intent

The primary capability intent of this system is to **support coordinated human action**, not to optimise workflow efficiency at the expense of judgement or care.

Specifically, the system is intended to:
- reduce coordination overhead and friction
- make work visible and traceable
- support timely and appropriate escalation
- preserve professional discretion in handling cases

Non-negotiable capability constraints include:
- responsibility for outcomes remains human
- judgement at hand-off points must be preserved
- escalation pathways must remain accessible and usable
- the system must not silently resolve or close cases

The system exists to **enable coordination**, not to enforce compliance or eliminate discretion.

---

## Human–AI Boundaries

Clear boundaries are established between AI-supported orchestration and human authority.

In this system:
- AI may assist with classification, prioritisation, and routing suggestions
- AI may surface indicators of urgency, risk, or backlog
- AI may recommend escalation pathways based on defined criteria

AI may **not**:
- close cases autonomously
- override human routing decisions
- suppress escalation or re-routing
- determine final responsibility for resolution

Humans retain authority to:
- accept, modify, or reject routing suggestions
- escalate cases regardless of AI classification
- reassign work based on contextual knowledge
- determine resolution and closure

Human intervention is treated as a normal and expected part of system operation.

---

## Ethics, Equity, and Risk

Key ethical and equity risks are identified early:

- **Deflection risk**: requests may be repeatedly routed without resolution  
- **Visibility risk**: some cases may become less visible due to classification bias  
- **Burden shifting**: certain roles may absorb disproportionate workload  
- **Access inequity**: some users may be less able to navigate escalation pathways  

Mitigations include:
- visibility of routing history and delays
- time-based and risk-based escalation triggers
- regular review of workload distribution
- multiple, accessible escalation routes

Unacceptable risks include:
- use of the system to avoid responsibility
- normalisation of delayed or deflected responses
- suppression of complex or ambiguous cases

---

## Governance and Oversight

Governance mechanisms focus on **workflow behaviour**, not individual performance.

Key governance features include:
- clear ownership of workflow stages
- traceability of routing and reassignment decisions
- auditability of escalation and override actions
- review of systemic patterns rather than isolated cases

Oversight addresses:
- bottlenecks and deflection patterns
- escalation frequency and effectiveness
- workload equity across roles
- adherence to defined scope and purpose

Governance review is periodic and contextual, avoiding real-time surveillance.

---

## System Design and Architecture

Architectural choices reinforce coordination rather than control.

Key structural decisions include:
- explicit separation between routing logic and case resolution
- visibility of workflow state and history to relevant actors
- manual override available at all routing points
- no irreversible automated transitions

Failure modes are designed to be safe:
- if AI classification fails, cases default to human triage
- escalation remains available under all conditions
- system degradation does not block work progression

The architecture supports flexibility, transparency, and review.

---

## Evaluation and Monitoring

Evaluation focuses on **coordination quality**, not just throughput.

Key evaluation questions include:
- Are cases reaching appropriate handlers in a timely way?
- Are escalation pathways used and effective?
- Is workload distribution becoming uneven?
- Are users experiencing friction or confusion?

Indicators include:
- time-to-resolution patterns
- escalation and re-routing rates
- qualitative feedback from staff and users
- review of stalled or repeatedly routed cases

Evaluation findings inform both workflow design and governance review.

---

## Iteration and Change

Changes to routing logic, thresholds, or workflow structure are governed.

Each proposed change triggers review of:
- capability intent alignment
- impacts on human–AI boundaries
- equity and burden distribution
- escalation accessibility

Iteration prioritises:
- reversibility
- documentation of rationale
- post-change review

Small changes are treated as potentially significant if they affect coordination dynamics.

---

## Retirement and Deprecation

Conditions for retirement or scope reduction are defined early.

Triggers include:
- persistent coordination failure or inequity
- inability to govern workflow behaviour effectively
- changes in organisational structure or responsibility
- replacement by simpler or more human-centred processes

Retirement planning includes:
- preserving workflow records for accountability
- supporting transition to alternative processes
- capturing lessons about coordination and escalation

Ending or simplifying orchestration is treated as a responsible design outcome.

---

## Key Design Trade-offs

This example illustrates deliberate trade-offs such as:

- flexibility over rigid efficiency
- visibility over silent optimisation
- escalation access over throughput metrics
- coordination support over automated resolution

These trade-offs are explicit and revisited over time.

---

## What This Example Demonstrates About CDD

This example shows how Capability-Driven Development:

- supports human coordination without enforcing compliance
- makes escalation and override normal rather than exceptional
- embeds governance into workflow structure
- treats orchestration as a shared responsibility, not a control system

Workflow orchestration systems are most effective when they **enable people to act together responsibly**, rather than attempting to manage work on their behalf.

This example demonstrates how CDD keeps coordination humane, governable, and adaptable.
