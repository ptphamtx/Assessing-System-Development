# Assessing System Development

## What I Know

### • Mapping System Workflows
I translate requirements into clear system workflows. I create use-case diagrams to define goals and system boundaries, then extend them with activity or process flows to surface decision points, exceptions, and alternate paths. This “from intent to interaction” mapping reduces ambiguity and accelerates story writing and test planning.  
For example, in a “Browse Catalog → Enroll” journey, I mapped the happy path and three alternates (prerequisite missing, section full, payment pending), which directly informed acceptance criteria and prevented late surprises.

### • User Stories and Acceptance Criteria That Are Testable
I’ve learned to take workflows and turn them into user stories using simple Given/When/Then acceptance criteria. This approach makes requirements clear and easier to test in demos. I practice breaking them down into smaller slices that still deliver end-to-end value, focusing first on core behaviors and verifying whether outcomes match what’s shown in the diagrams. This helps connect what was designed with what gets built.

### • ER Modeling to Align Domain and Persistence
I can draw ER diagrams to understand main entities and how they relate (one-to-many, many-to-many). This supports writing better stories and sequence diagrams because I know what objects exist and how they connect.

---

## Where I Am Weak

### • Writing Detailed Documentation and Maintaining Technical Documents
My documentation becomes inconsistent mid-sprint. READMEs and decision notes don’t always stay updated with code changes. I know this causes friction for new collaborators and for my future self when revisiting the project.

### • Web Styling and CSS Design
I’m slow with styling. Layout systems, spacing scales, and responsive polish take longer than they should. I also don’t have a strong design system yet (tokens, themes, components), which affects how “finished” features feel in demos even when the backend and logic are solid.

---

## What I Wish I Knew

### • Docs That Grow With the Code
Keep documentation (diagrams, design notes, decisions) updated at the same pace as code. This might mean a PR checklist or small gates that remind me to adjust docs when code changes.

### • Front-End Design Basics
Learn how to use a design system or utility-first framework so spacing, layout, and accessibility are handled smoothly. This ensures UI polishing doesn’t slow down delivery.

### • Clear Testing Layers
Understand the difference between unit, integration, and end-to-end testing, and when to use each. For some projects, this includes using “contract tests” to ensure the front end and back end agree on communication.

---

## Supporting Work / Knowledge

- **System Development Course 1:** [GitHub Repository](https://github.com/ptphamtx/Data-Mining-2/tree/main)  
- **System Development Course 2:** [GitHub Repository](https://github.com/ptphamtx/Data-Mining-1/tree/main)  
- **DataCamp Courses:** [Certificate PDF](https://drive.google.com/file/d/1YLFjpZ7GvVE2THXq3MXS5_z66bnemJBY/view?usp=sharing)

---

## Summary
I translate requirements into clear, testable flows—from use-case diagrams to activity maps—so edge cases surface early and stories with Given/When/Then stay aligned with what’s built. ER modeling grounds the work by clarifying entities and relationships, improving story slicing and sequence diagrams, and linking naturally to Data Management.  
Current gaps include maintaining documentation mid-sprint and delivering polished, accessible UI styling. I’m addressing these with lightweight docs-as-code checklists, adopting a design system or utility-first approach, and formalizing layered testing practices.
