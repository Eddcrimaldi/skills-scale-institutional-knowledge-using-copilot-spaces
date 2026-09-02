# OctoAcme Project Management Documentation

## Overview
OctoAcme runs projects with a clear, iterative lifecycle that begins with a lightweight initiation (one-pager, stakeholder alignment, and success metrics) and moves into planning, execution, release, and retrospective. Planning breaks approved work into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done. Teams estimate using T-shirt sizing or story points and map work to releases and milestones to keep scope and timeline aligned.

Execution is managed on a transparent project board (Backlog → Ready → In Progress → In Review → QA → Done) and uses a pull-request driven workflow that encourages small PRs, linked issues and acceptance criteria, CI gating (tests and linting), and reviewer approvals before merging. Team rhythm includes short daily standups, weekly delivery syncs, and demos at the end of sprints or milestones to surface progress, risks, and dependencies.

Risk management and stakeholder communication are formalized with a simple risk register (ID, impact, likelihood, owner, mitigation) and documented escalation paths from team triage up to sponsor-level escalation for business-impacting issues. Releases are standardized — requiring passing CI and security scans, drafted release notes, rollback plans, and pre/post-deploy smoke tests. Quality assurance is embedded across stages with unit, integration, and end-to-end smoke tests, automated security scanning in CI, and manual QA for final acceptance when needed.

Continuous improvement is closed-looped through timeboxed retrospectives that produce 2–3 prioritized action items which are tracked back into the backlog with owners and due dates. These processes are intended to improve discoverability, reduce single-person dependencies, and make project delivery predictable and measurable.

---

## Documents (in this folder)
| Document | Purpose |
|----------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | Concise introduction to OctoAcme's approach, roles, and key artifacts |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate and authorize work with stakeholder alignment |
| [Project Planning](octoacme-project-planning.md) | Guidance for turning initiatives into actionable plans and backlogs |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day execution management and progress tracking |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk identification, assessment, and stakeholder communication |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release types, pre-release requirements, and deployment procedures |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capturing learnings and converting them to improvements |
| [Roles and Personas](octoacme-roles-and-personas.md) | Definitions of core roles and responsibilities |

## Getting started
Start with the [Project Management Overview](octoacme-project-management-overview.md) for a high-level understanding, then open process-specific docs based on your role or the phase of work. Use the Issue template ".github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml" to propose updates to these docs.

## Contributing
- For document updates, open an issue using the process-doc update template or create a pull request with proposed changes.
- Keep items concise, cite any references or decisions, and list acceptance criteria for process changes.
