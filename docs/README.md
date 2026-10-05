# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management docs. This library describes a customer-first, iterative approach built around clear ownership, evidence-based decisions, and a psychologically safe culture where teams can share feedback and learn.

## Project management process summary

OctoAcme guides work through five lifecycle phases: **Initiation → Planning → Execution → Release → Closeout**. Initiation validates the problem, expected outcomes, success metrics, stakeholders, and resources in a project one-pager before a go/no-go decision. Planning turns approved work into a prioritized backlog of shippable increments, with acceptance criteria, estimates, dependencies, milestones, a release plan, and a Definition of Done.

During execution, teams use a project board to track work from Backlog through Ready, In Progress, In Review, QA, and Done. Product Managers define the outcomes and prioritize the roadmap and backlog; Project Managers coordinate plans, schedules, risks, dependencies, and communication; Developers design, implement, test, and review changes. QA and stakeholders help validate quality and acceptance criteria.

Communication keeps delivery and stakeholders aligned: delivery teams hold 15-minute daily standups focused on progress and blockers, with a weekly delivery sync to review progress and risks. Product and Project Managers align weekly, teams demo at the end of each sprint or milestone, and stakeholders receive regular weekly or milestone-based updates (with monthly updates described in the overview). Teams track risks in a register, review them regularly, and escalate blockers through the team, Project Manager, Product Lead, and sponsor.

Quality is built into planning and delivery through clear acceptance criteria and a Definition of Done, unit and applicable integration tests, critical-flow smoke tests, CI checks and security scans, code review, and manual QA when needed. Before release, teams verify acceptance criteria, CI and security results, release notes, smoke tests, and rollback plans; they then deploy, verify, and communicate the release. After a sprint, release, milestone, or incident, a retrospective turns lessons into a small set of owned, time-bound improvement actions.

## Documentation index

### Lifecycle and delivery

- [Project Management Overview](./octoacme-project-management-overview.md) — principles, lifecycle, roles, and core artifacts.
- [Project Initiation](./octoacme-project-initiation.md) — validate and authorize new work.
- [Project Planning](./octoacme-project-planning.md) — shape the backlog, milestones, and delivery plan.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — team workflow, progress tracking, quality, and escalation.
- [Release & Deployment](./octoacme-release-and-deployment.md) — release readiness, deployment, and rollback.

### Ways of working

- [Risks & Communication](./octoacme-risks-and-communication.md) — risk management, stakeholder updates, and escalation.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — learnings and improvement actions.
- [Roles & Personas](./octoacme-roles-and-personas.md) — responsibilities and communication expectations.

## Quick reference: artifacts and templates

- [Project One-pager template](./octoacme-project-initiation.md#project-one-pager-template) — problem, goal, success metrics, stakeholders, timeline, risks, and team.
- [Backlog Item template](./octoacme-project-planning.md#backlog-item-template) — description, acceptance criteria, priority, estimate, and owner.
- [Risk Register fields](./octoacme-risks-and-communication.md#risk-register) — impact, likelihood, owner, mitigation, and status.
- [Weekly Status template](./octoacme-risks-and-communication.md#communication-templates) — progress, next steps, risks, and decisions needed.
- [Release Notes template](./octoacme-release-and-deployment.md#release-notes-template) — summary, notable changes, migrations, and known issues.
- [Retrospective Action Item template](./octoacme-retrospective-and-continuous-improvement.md#example-action-item-template) — owner, due date, and success criteria.
- Other core artifacts include the roadmap and release plan, sprint/iteration backlog, acceptance criteria and Definition of Done, and retrospective notes.

## How to use these docs

Use the lifecycle guides in order when starting and delivering a project, and return to the supporting guides whenever you need role, risk, or communication guidance. Treat the checklists and templates as practical starting points; adapt them to the project's context while keeping ownership, outcomes, and decisions clear. Keep the project charter and current status in the project repository as the source of truth. Where Copilot Spaces needs process-specific context, add the relevant documents to `.copilot/`.

## Quick Start for new team members

1. Read the [Project Management Overview](./octoacme-project-management-overview.md) to learn the principles, lifecycle, and core artifacts.
2. Review [Roles & Personas](./octoacme-roles-and-personas.md) to understand your responsibilities and team interfaces.
3. For a new initiative, follow [Project Initiation](./octoacme-project-initiation.md); for active work, start with [Project Planning](./octoacme-project-planning.md) or [Execution & Tracking](./octoacme-execution-and-tracking.md).
4. Join the team's standups and weekly syncs, find the project board and current status, and ask the Project Manager where project-specific artifacts are maintained.
