# OctoAcme Project Management Docs

This collection of process documents centralizes how OctoAcme runs projects — from initial validation through planning, execution, release, and continuous improvement. The goal of these docs is to make project practices discoverable, reduce single-person dependencies, and provide consistent guidance for effective, repeatable delivery.

OctoAcme uses a lightweight, stage-gated lifecycle with clear decision gates and artifacts. Initiation creates a one‑pager that captures problem, goals, success metrics, stakeholders, and an initial risk list. Planning breaks approved initiatives into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release/milestone map. Execution emphasizes small, testable increments, a strict PR workflow (small PRs, linked issues, CI checks, approvals), and a maintained risk register. Releases follow a deployment checklist with rollback and incident playbooks, and retrospectives capture action items for continuous improvement.

Roles and responsibilities are explicit so ownership and handoffs are clear: Project Managers coordinate delivery, schedules, risks and communications; Product Managers own outcomes, prioritization, and success metrics; Developers implement features and tests; QA validates acceptance criteria; and stakeholders provide inputs and approvals. Communication is driven by a regular cadence (standups, weekly PM+PdM syncs, demos/reviews, and monthly stakeholder updates) and standardized templates (weekly status, incident messages). Quality assurance combines automated testing (unit, integration, end-to-end smoke tests), CI-based security scanning, manual acceptance QA when needed, and post‑deploy verification — all gated by acceptance criteria and the Definition of Done.

Documentation index
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

How to use this README
- Use this as the single entry point to OctoAcme project process docs.
- Keep the one-pager and release notes linked in each project repo.
- To propose edits to these docs, open an issue or PR and reference the relevant file.

Related issue: #2
