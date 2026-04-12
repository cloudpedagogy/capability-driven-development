# PROJECT_SPEC: capability-driven-development

## 1. Repo Name
`capability-driven-development`

## 2. One-Sentence Purpose
A theoretical and procedural framework for designing AI-enabled software systems that prioritize human and institutional capability.

## 3. Problem the App Solves
Closes the gap between abstract AI ethics/capability frameworks and practical software implementation; prevents "technology-first" design that automates tasks at the expense of human oversight and institutional governance.

## 4. Primary User / Audience
Software designers, developers, learning technologists, and applied researchers.

## 5. Core Role in the CloudPedagogy Ecosystem
Provides the methodology (the "HOW") that translates the AI Capability Framework (the "WHAT") into concrete system design decisions and architectural choices.

## 6. Main Entities / Data Structures
- (Conceptual) **Method Steps**: An 8-stage design sequence.
- (Conceptual) **Design Artifacts**: Templates for documenting intent, boundaries, and risk.
- (Conceptual) **Patterns**: Technology-agnostic implementations of responsibility (e.g., oversight, delegation).

## 7. Main User Workflows
1. **Define Intent**: Establish human and institutional capability goals.
2. **Boundary Design**: Specify human-AI split of duties.
3. **Risk/Governance Mapping**: Identification of harms and design of oversight/traceability.
4. **Architectural Selection**: Choosing implementation patterns that respect capability constraints.
5. **Lifecycle Management**: Planning for evaluation, iteration, and retirement.

## 8. Current Features
- Extensive `/method` guidelines.
- `/foundations` for framework alignment.
- `/design-artifacts` templates.
- `/patterns` library for responsible implementation.
- `/examples` for applied illustrations.
- `/ai-assisted-reflection` prompts for design teams.

## 9. Stubbed / Partial / Incomplete Features
- The method is described as a "living method" with individual documents potentially marked as **Draft**.

## 10. Import / Export and Storage Model
- **N/A**: This is a pure documentation and methodology repository.

## 11. Relationship to Other CloudPedagogy Apps
Acts as the meta-framework that defines the design logic behind all other CloudPedagogy software tools (e.g., it informs the UI and data models of assessment and mapping engines).

## 12. Potential Overlap or Duplication Risks
Might overlap with theoretical research repos; distinguished by its focus on *application* and *software systems design*.

## 13. Distinctive Value of This App
Focuses specifically on the procedural design steps needed to ensure institutional responsibility is "baked in" to software, not added as a training or policy afterthought.

## 14. Recommended Future Enhancements
(Inferred) Creation of a digital "Design Wizard" or IDE plugins that surface CDD patterns during active coding; automated audits of system architecture against CDD patterns.

## 15. Anything Unclear or Inferred from Repo Contents
While the method is procedural, the repository does not contain an executable "engine"—it relies on the user to apply the markdown-based methodology to their own development projects.
