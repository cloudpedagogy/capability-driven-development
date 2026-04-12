# Applied Example: AI-Assisted Syllabus Audit

This example demonstrates the Capability-Driven Development (CDD) workflow applied to an AI-assisted syllabus refinement project using CloudPedagogy tools.

## Step 01: Capability Intent
**Goal**: Use AI to identify gaps in AI Literacy coverage across a curriculum.
**Intent**: Professionals (Curriculum Designers) must remain the authoritative source of course content. The AI should strengthen their ability to map large datasets without replacing their subject-matter expertise.

### Manifest Snippet (`course.yml`)
```yaml
scoping:
  ai_intent: "Identify mapping gaps"
  governance:
    capability_preservation: "Subject matter expertise retained by humans"
    permitted_uses: ["Gap analysis", "Cross-referencing"]
```

## Step 02: Human-AI Boundaries
**Logic**: AI suggests capability mappings; Humans must approve or override every suggestion before it enters the final syllabus.

### Decision Record Snippet (`decision-summary.json`)
```json
{
  "step": "mapping_validation",
  "ai_suggestion": "Module 1 aligns with Ethics domain",
  "human_decision": "Override",
  "rationale": "Module 1 covers transparency, which fits 'Governance' better than 'Ethics' in our framework."
}
```

## Step 03: Risk & Ethics
**Scenario**: The AI may hallucinate alignment where none exists, leading to a "false positive" for literacy coverage.
**Mitigation**: The governance dashboard flags any module with a 100% AI-only mapping score as "High Risk" until a human review occurs.

## Step 04: Governance & Oversight
**Audit Trail**: The final output is published to a Research Object, linking the original `course.yml` to the `decision-summary.json`.

---

## Tool Mapping for this Example
1. **Course Engine**: Authorised the initial intent.
2. **Capability Studio**: Orchestrated the human-AI decision loop.
3. **Integration SDK**: Consolidated the audit trails.
4. **Programme Dashboard**: Visualised the maturity score.
