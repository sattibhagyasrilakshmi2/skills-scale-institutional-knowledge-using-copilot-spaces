# OctoAcme Project Management Docs

This folder contains OctoAcme's program-level project management documentation. The guides here describe how we initiate, plan, execute, release, and continuously improve projects. They are intentionally lightweight and action-oriented so teams can adopt and adapt them quickly.

Our process emphasizes iterative delivery, clear ownership, measurable outcomes, and a focus on quality. Start with a short Project One-pager to align stakeholders on problem, objective, success metrics, and timeline; then plan by breaking work into prioritized backlog items with clear acceptance criteria and a Definition of Done. During execution, keep work small, use CI and automated tests, and manage progress on a project board that shows Backlog → Ready → In Progress → In Review → QA → Done.

Roles and responsibilities are explicit: Product Managers define outcomes and prioritize work; Project Managers coordinate delivery, schedules, risks, and communications; Developers implement and test changes; QA validates quality and acceptance criteria; Stakeholders and Sponsors provide inputs and approvals and support escalations. Use the personas document (octoacme-roles-and-personas.md) as the canonical reference for role descriptions and interaction patterns.

Quality gates and release controls reduce risk: require passing CI and security scans before merge, prefer small PRs with linked issues and acceptance criteria, and run staged smoke tests before production. Maintain a Risk Register that captures impact, likelihood, owner, and mitigation; escalate issues using the Level 1–3 escalation path in the risks document. Capture retrospective action items as issues with owners and due dates and measure their impact over time.

Quick links

- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md

Quick checklist (what to do when starting a new initiative)

- Create a Project One-pager (Problem, Goal, Success metrics) and share with stakeholders
- Hold a kickoff to align scope, roles, and timeline
- Add a prioritized backlog with acceptance criteria and estimates
- Set Definition of Done and test plans for each backlog item
- Use the project board to track work and surface dependencies
- Require CI, tests, and security scans to pass before merging PRs
- Prepare release notes, rollback plan, and smoke tests before deploy
- Run a retrospective after the release and convert action items into tracked issues

Using Copilot Spaces with these docs

These docs are ready to be used as a knowledge source in GitHub Copilot Spaces. Add the repository (or the docs/ and .github/ISSUE_TEMPLATE folders) to a Copilot Space to enable search, summarization, and collaborative improvement. Follow the exercise steps in .github/steps/ to practice creating issues, drafting a README summary, and using the Copilot Cloud Agent to generate PRs that update process docs.

If you'd like, I can also:
- Add links from the repository root README to this docs/README.md
- Open a PR that clarifies one or more process documents (for example: expand personas, add a release checklist template, or add examples to the Risk Register)

