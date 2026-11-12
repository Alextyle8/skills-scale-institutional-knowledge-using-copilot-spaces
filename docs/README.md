# OctoAcme Project Management Docs

This folder contains OctoAcme's shared guidance for managing cross-functional projects, from validating an idea through delivery and learning. The process is iterative and customer-first: teams define measurable outcomes, deliver small increments, keep ownership clear, use evidence to guide decisions, and create space for feedback.

## Process overview

Projects begin with initiation, where the team confirms the business need, success measures, stakeholders, risks, and rough resource needs before deciding whether to proceed. In planning, the approved initiative becomes a prioritized backlog with acceptance criteria, estimates, dependencies, a Definition of Done, and a milestone or release plan. During execution and tracking, the team works through a shared project board, reviews progress and blockers regularly, and demonstrates completed work at sprint or milestone ends.

The Project Manager coordinates delivery, schedules, risks, and communications; the Product Manager/Product Lead sets outcomes, priorities, and success measures; developers build and test; QA validates acceptance and quality; and stakeholders provide input and approvals. Communication keeps these roles aligned through team standups, weekly delivery and PM-product syncs, regular stakeholder updates, and timely escalation of blockers—from the team to the PM, Product Lead, and sponsor when needed. Project documentation and boards serve as the shared source of truth.

Quality is built into the workflow: work should have clear acceptance criteria and meet the Definition of Done; teams use unit tests for new logic, integration tests where applicable, automated CI tests and linting, security scanning, and manual QA when needed. Before release, acceptance criteria and CI checks must pass, release notes and rollback plans are prepared, and staging smoke tests are run. After deployment, teams verify the release and communicate it to stakeholders. A retrospective after each sprint, release, or significant milestone captures lessons and a small set of owned, trackable improvements.

## Process documents

- [Project Management Overview](octoacme-project-management-overview.md) — principles, lifecycle, roles, artifacts, and communication cadence.
- [Project Initiation Guide](octoacme-project-initiation.md) — validate and authorize new work and prepare the one-pager.
- [Project Planning](octoacme-project-planning.md) — shape the backlog, estimates, Definition of Done, milestones, risks, and dependencies.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — team rhythm, project-board workflow, quality practices, reporting, and blocker escalation.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — risk lifecycle, stakeholder updates, templates, and escalation paths.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — release readiness, deployment checks, rollback, incident response, and release notes.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — capture learning and track improvement actions.
- [Roles and Personas](octoacme-roles-and-personas.md) — responsibilities, goals, and typical communication for key roles.
