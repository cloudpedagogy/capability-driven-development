# CDD Practitioner's Guide

This guide provides operational guidance for teams adopting the Capability-Driven Development (CDD) methodology within the CloudPedagogy ecosystem.

## Roles & Responsibilities

| Role | CDD Focus | Key Deliverable |
|:---|:---|:---|
| **Curriculum Designer** | Step 01 (Intent) | Syllabus Capability Brief (manifest.json) |
| **Governance Lead** | Step 03-04 (Ethics & Oversight) | Risk Register / Maturity Report |
| **System Architect** | Step 05 (Implementation) | Integrated Adapter Config |
| **Domain Lead** | Step 06 (Evaluation) | Skills-Gap Evidence |

## Entry & Exit Criteria

### Phase 1: Conceptualisation (Steps 01-02)
- **Start when**: A new educational program or AI-assisted feature is proposed.
- **Finish when**: A `System Capability Brief` is documented and the `Human Decision Zone` is mapped.

### Phase 2: Design & Governance (Steps 03-04)
- **Start when**: Boundaries are confirmed.
- **Finish when**: Foreseeable risks are mitigated and a Governance Plan is activated in the Dashboard.

### Phase 3: Deployment & Iteration (Steps 05-08)
- **Start when**: Architecture is validated against capability intent.
- **Finish when**: Evaluation logs confirm capability strengthening and any retirement criteria are met.

## How to use the Tooling

1. **Start with YAML**: Define your intent in Course Engine (`course.yml`).
2. **Exercise Decisions**: Run a role-play exercise in AI Capability Studio to stress-test your human-AI boundaries.
3. **Consolidate Evidence**: Use the Integration SDK to pipe all metadata into a **Research Object** for final publication.

---

## Tips for Success
- **Intent over Features**: Do not describe what the AI *does*, describe what the human *remains able to do*.
- **Plan for Override**: If you cannot easily override the AI's output, your boundaries (Step 02) are failing.
- **Lifecycle is a Service**: Deprecation (Step 08) is a core part of governance, not an end-of-life problem.
