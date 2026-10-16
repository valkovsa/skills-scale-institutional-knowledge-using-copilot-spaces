# OctoAcme Project Management Docs (README)

This README provides a short overview of OctoAcme's project management processes and links to the full process documents in this repository's docs folder.

OctoAcme runs projects through a lightweight, iterative lifecycle that moves from initiation to planning, execution, release, and retrospective. Initiation centers on a Project One-pager that captures the problem, goal, success metrics, stakeholders, and a high-level timeline; a go/no‑go decision gate authorizes planning. Planning breaks approved initiatives into shippable increments with a prioritized backlog, acceptance criteria, estimates, and a Definition of Done; dependencies and risks are captured in a Risk Register and surfaced during planning and weekly syncs.

Execution emphasizes predictable delivery and traceability: teams use a project board (Backlog → Ready → In Progress → In Review → QA → Done), timeboxed planning, and a Pull Request workflow that favors small PRs, linked issues and acceptance criteria, CI gating, and required approvals. Releases are categorized (patch, minor, major) and follow pre-release checks (CI/security scans, release notes, rollback plans, and smoke tests) with automated pipelines preferred; an incident playbook and rollback steps protect production stability.

Roles and quality practices are explicit. Project Managers coordinate delivery, schedules, risks, and stakeholder communications; Product Managers define outcomes and prioritize the backlog; Developers implement and test features; QA validates acceptance criteria and runs manual or automated tests as needed. Quality assurance is embedded across the lifecycle with unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and tracking via velocity, burndown, and operational dashboards. Retrospectives capture action items (owner and due date) to drive continuous improvement.

## Links to docs

- [Project management overview](./octoacme-project-management-overview.md)
- [Project initiation](./octoacme-project-initiation.md)
- [Project planning](./octoacme-project-planning.md)
- [Execution and tracking](./octoacme-execution-and-tracking.md)
- [Risks and communication](./octoacme-risks-and-communication.md)
- [Release and deployment](./octoacme-release-and-deployment.md)
- [Retrospective and continuous improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and personas](./octoacme-roles-and-personas.md)

## Notes

This README is intended as a single entry point to help contributors and project managers quickly discover and navigate OctoAcme's process documentation. Feel free to suggest wording edits, add badges, or surface key checklists directly in this file.
