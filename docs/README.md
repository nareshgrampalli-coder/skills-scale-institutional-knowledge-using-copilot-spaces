# OctoAcme Project Management Docs

This folder is the central knowledge base for OctoAcme's project management processes. It provides a shared, structured reference for all cross-functional teams delivering product features, services, and integrations. Use the overview below to quickly understand how our processes fit together, then follow the links to dive into any area in depth.

---

## Process Overview

OctoAcme's project management approach is built around a lightweight but structured lifecycle that moves work through **initiation, planning, execution, release, and retrospective improvement**. Projects begin with a clear business need, stakeholder alignment, success metrics, and a one-pager that defines goals, timelines, risks, and team roles. Once approved, planning turns the initiative into a prioritized backlog with acceptance criteria, estimates, dependencies, a release plan, and a documented Definition of Done. This creates a consistent foundation for delivery while keeping work aligned to measurable outcomes and stakeholder expectations.

The model depends on clear role ownership across cross-functional teams. **Project Managers** coordinate timelines, delivery, risks, communications, and team rituals. **Product Managers** define the problem, prioritize the backlog, and measure customer and business outcomes. **Developers** build and test features while helping with estimation, technical design, and risk identification. **QA** supports validation of quality and acceptance criteria. **Stakeholders** provide input and approvals. These roles are reinforced throughout the documentation, emphasizing clear ownership, iterative delivery, and data-informed decision-making.

Execution is managed through a regular operating rhythm and visible workflows. Teams use a project board with stages such as Backlog, Ready, In Progress, In Review, QA, and Done to track work from idea to completion. Daily or twice-weekly standups surface progress, blockers, and dependencies, while weekly syncs and monthly stakeholder updates maintain alignment. Escalation paths are clearly defined, moving issues from team triage to PM, Product Lead, and sponsor-level attention as business impact increases. Communication is treated as a core discipline, with templates for weekly status reporting, incident updates, and a shared source of truth in project documentation.

Quality assurance is embedded throughout delivery and release rather than treated as a final step. OctoAcme expects unit tests for new logic, integration tests where needed, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance when appropriate. Pull requests should remain small, link to issues and acceptance criteria, and pass automated tests and linting before review, with at least one approval required before merge. Releases are standardized through pre-release checks, staged deployments, rollback planning, post-deploy verification, and stakeholder communication. After sprints, releases, or incidents, retrospectives capture lessons learned and convert them into tracked improvement actions, reinforcing a continuous improvement culture.

---

## Document Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level principles, core roles, key artifacts, and lifecycle summary |
| [Project Initiation](octoacme-project-initiation.md) | How to kick off a project: problem statement, stakeholders, and charter |
| [Project Planning](octoacme-project-planning.md) | Scope, backlog, milestones, dependencies, and Definition of Done |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Sprint workflow, board management, standups, and progress tracking |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, status reporting, and communication cadence |
| [Release and Deployment](octoacme-release-and-deployment.md) | Pre-release checklist, staged rollout, rollback, and post-deploy verification |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format, action items, and improvement tracking |
| [Roles and Personas](octoacme-roles-and-personas.md) | Responsibilities and expectations for PM, PdM, developers, QA, and stakeholders |

---

## How to Use These Docs

- Start with the [Project Management Overview](octoacme-project-management-overview.md) for a quick orientation to OctoAcme's approach.
- Follow the lifecycle in order (Initiation → Planning → Execution → Release → Retrospective) for end-to-end guidance.
- Add or update process docs in this folder and keep links in this README current.
- Add relevant docs to `.copilot/` if you want Copilot Spaces to use them as context for AI assistance.
