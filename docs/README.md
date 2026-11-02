# OctoAcme Project Management Docs

This folder contains the documentation for how OctoAcme runs projects, from the first idea to the final retrospective.

## Overview of OctoAcme project management processes

OctoAcme runs projects through a five-stage lifecycle: Initiation, Planning, Execution, Release, and Close & Retrospective. Initiation validates the business need and sets success metrics. It produces a one-pager, a stakeholder list, a high-level timeline and an initial risk list. A go/no-go decision gate then confirms priority and team availability. Planning breaks approved work into a prioritized, estimated backlog with acceptance criteria and a Definition of Done. It also sets milestones and a release plan.

Day-to-day execution is tracked on a project board with the columns Backlog, Ready, In Progress, In Review, QA and Done. Work moves through small pull requests (about 400 lines or fewer) that link to an issue and its acceptance criteria. CI must pass and at least one approval is needed before merging. Releases are patch, minor or major. Each one needs release notes, a rollback plan and smoke tests. The deploy goes to staging first, then production, preferably through an automated pipeline, followed by post-deploy verification.

The core roles are the Project Manager, Product Manager, Developers, QA/Testing and Stakeholders. The Project Manager owns schedules, risks and communication. The Product Manager owns outcomes, backlog priority and success metrics. Developers build, test and document features, and QA validates acceptance criteria. Communication runs on a regular rhythm: daily or twice-weekly standups, a weekly PM and Product Manager sync, a weekly delivery sync, and monthly stakeholder updates. Weekly status reports follow a standard template (progress, next steps, risks, decisions needed). Blockers escalate from team triage to the PM, then the Product Lead, then the Sponsor. Security incidents also notify Security on-call.

Quality assurance is built into every stage. It includes unit and integration tests, end-to-end smoke tests for critical flows, CI linting, security scanning and manual QA when needed. A risk register tracks impact, likelihood, owner and mitigation, and is reviewed weekly. After each sprint, release or incident, a retrospective turns lessons into owned action items. Those items are tracked in the backlog and reviewed in the weekly PM sync, which closes the continuous-improvement loop.

## Documents

| Document | Description |
|----------|-------------|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, lifecycle and communication cadence |
| [Project Initiation](octoacme-project-initiation.md) | Validating and authorizing work, one-pager template and decision gate |
| [Project Planning](octoacme-project-planning.md) | Backlog, estimation, Definition of Done, sprint planning and risk management |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Team rhythm, board and PR workflow, quality and testing, escalation |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk register and lifecycle, stakeholder updates, escalation paths |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release types, pre-release requirements, deployment checklist, rollback |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives and tracking improvements |
| [Roles & Personas](octoacme-roles-and-personas.md) | Responsibilities and goals for Developers, Product Managers and Project Managers |
