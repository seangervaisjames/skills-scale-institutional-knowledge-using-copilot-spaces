# OctoAcme Project Management Docs

This README is the central index for OctoAcme's project management process documentation. Use it to quickly orient yourself to how we run projects and navigate to the detailed guidance for each phase.

---

## Process Summary

OctoAcme uses a lightweight, iterative project management approach built on customer-first principles, clear ownership, and continuous improvement.

**Initiation** — Confirm the business need, define measurable outcomes, align stakeholders on scope and success criteria, and make a go/no-go decision. Key output: a project charter or one-pager.

**Planning** — Convert the approved initiative into a prioritized backlog with acceptance criteria, estimates, and a milestone-based release plan. Dependencies and risks are identified early and tracked throughout.

**Execution & Tracking** — Deliver in small, testable increments. The team stays aligned through daily standups and weekly delivery syncs. Work moves through a structured project board (Backlog → In Progress → In Review → Done), and pull requests must be small, linked to issues, and pass CI checks before review.

**Risk Management & Communication** — Risks are documented in a risk register and managed through a defined lifecycle (Identified → Assessed → Mitigated → Monitored → Closed). Weekly status updates and a tiered escalation model keep stakeholders informed and blockers resolved at the right level.

**Release & Deployment** — Releases follow standardized pre-release gates (acceptance criteria met, CI passing, release notes written, rollback plan in place), coordinated deployment steps, post-deployment verification, and a stakeholder announcement.

**Retrospective & Continuous Improvement** — After every sprint, release, or significant incident, the team captures what went well, what didn't, and root causes. Actionable improvements are added to the backlog and tracked.

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
