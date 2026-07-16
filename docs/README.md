# OctoAcme Project Management Docs

This README is the central index for OctoAcme's project management process documentation. Use it to quickly orient yourself to how we run projects and navigate to the detailed guidance for each phase.

---

## Process Summary

OctoAcme runs projects through an iterative lifecycle: initiation, planning, execution/tracking, release, and retrospective improvement. Teams start with a lightweight one-pager to define the problem, goals, stakeholders, success metrics, timeline, and major risks before moving forward.

During planning, approved work is translated into a prioritized backlog with estimates, milestones, dependencies, acceptance criteria, and a clear Definition of Done. In execution, teams deliver in small increments, track work on a visible board, and review progress through regular standups, delivery syncs, and milestone demos.

Roles are intentionally cross-functional and explicit: PMs coordinate delivery and risk, PdMs own outcomes and prioritization, Developers implement and surface technical risks, QA validates acceptance criteria, and stakeholders provide direction and approvals. This role clarity keeps ownership visible and improves collaboration across project stages.

Communication and quality are built into delivery. Teams maintain a shared source of truth, provide regular status updates, and use a clear escalation path for blockers and incidents. Quality gates include PR review standards, CI checks (linting/build/security), required testing (unit/integration/smoke where applicable), release readiness checks, and post-release retrospectives with tracked action items.

### Lifecycle at a Glance

- **Initiation:** align on problem, outcomes, scope, and success criteria.
- **Planning:** build prioritized backlog, milestones, and risk/dependency plans.
- **Execution & Tracking:** deliver incrementally with clear workflow visibility.
- **Release:** pass release gates, deploy safely, verify outcomes.
- **Retrospective:** capture learnings and track continuous improvement actions.

### Roles & Personas

| Role | Primary Focus |
|------|--------------|
| Project Manager (PM) | Delivery cadence, risk, dependencies, stakeholder communication |
| Product Manager (PdM) | Outcomes, backlog prioritization, success metrics |
| Developers | Implementation, testing, technical risk identification |
| QA/Testing | Acceptance-criteria validation, test coverage |
| Stakeholders | Direction, approvals, escalation decisions |

### Quality Assurance Practices

- **PR workflow:** small PRs linked to issues, include acceptance criteria, peer-reviewed before merge.
- **CI:** automated linting, build checks, and security scans on every pull request.
- **Testing:** unit and integration tests required; end-to-end smoke tests for critical flows.
- **Security scans:** CI-integrated scans flag vulnerabilities before code reaches main.
- **Manual QA:** feature acceptance validated by QA/Testing against defined criteria before release.

---

## Document Index

| Document | Description |
|----------|-------------|
| [OctoAcme Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and lifecycle overview |
| [Project Initiation Guide](octoacme-project-initiation.md) | How to kick off a project: charter, stakeholder alignment, and go/no-go |
| [Project Planning](octoacme-project-planning.md) | Backlog setup, milestones, estimates, and release planning |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Sprint cadence, project board workflow, PR standards, and metrics |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, lifecycle, escalation model, and status reporting |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release gates, deployment steps, verification, and rollback |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retro format, lessons-learned capture, and improvement tracking |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and communication patterns for each role |
