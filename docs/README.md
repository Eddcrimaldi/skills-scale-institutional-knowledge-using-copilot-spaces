# OctoAcme Project Management Documentation

## Overview
OctoAcme runs projects with a customer-first, iterative approach that emphasizes clear ownership, measurable outcomes, and psychological safety. Projects begin with a lightweight initiation to validate the problem and success metrics, then move through planning, execution, release, and continuous improvement. These docs centralize the processes, templates, and checklists teams use to plan work, manage risks, deliver reliably, and learn from each iteration.

OctoAcme's delivery workflow centers on short, visible feedback loops: prioritized backlogs, timeboxed planning, small pull requests, and regular demos. Work progresses on a project board (Backlog → Ready → In Progress → In Review → QA → Done), and pull requests should include linked issues, acceptance criteria, and pass automated CI (tests, linting, security scans) before review and merge. Releases follow a clear checklist with pre-release verification and rollback plans to reduce production risk.

Roles and responsibilities are explicit. Product Managers define outcomes and success metrics, Project Managers coordinate delivery and communication, developers implement features and tests, and QA validates acceptance criteria through automated and manual checks. A simple risk register, escalation paths, and stakeholder communication templates ensure transparency and rapid resolution of blockers.

Quality assurance is embedded across the lifecycle: unit and integration tests for code quality, end-to-end smoke tests for critical flows, CI-based security scanning, and manual QA for acceptance where needed. Post-release, OctoAcme runs timeboxed retrospectives to capture learnings and converts action items into backlog tasks to be tracked and measured.

## Core Project Management Processes

### Initiation
Validate and authorize work: confirm business need, align stakeholders, define measurable success criteria, and create a lightweight plan (one‑pager).

### Planning
Turn approved initiatives into shippable increments: build a prioritized backlog with acceptance criteria, estimate scope, define Definition of Done, and map releases and milestones.

### Execution & Tracking
Manage day-to-day delivery with regular rhythms (daily standups, weekly delivery syncs, demos). Track work on the project board, use small PRs with CI gating, and escalate blockers through documented paths.

### Risk Management & Communication
Maintain a risk register (ID, impact, likelihood, owner, mitigation). Use weekly status templates and a single source of truth (project README or release doc) to keep stakeholders informed. Escalation flows from team → PM → Product Lead → Sponsor.

### Release & Deployment
Follow pre-release requirements (passing CI/security checks, release notes, rollback plans). Deploy through automated pipelines when possible, run staging/production smoke tests, and follow the incident playbook for failures.

### Retrospective & Continuous Improvement
Timeboxed retrospectives after sprints/releases to capture what went well, what to improve, and 2–3 prioritized action items. Track improvements in the backlog and measure their impact.

## Process Documentation (files in this folder)

| Document | Purpose |
|----------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | Concise intro to OctoAcme's approach, roles, and key artifacts |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate and authorize work with stakeholder alignment |
| [Project Planning](octoacme-project-planning.md) | Guidance for turning initiatives into actionable plans and backlogs |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day execution management and progress tracking |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk identification, assessment, and stakeholder communication |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release types, pre-release requirements, and deployment procedures |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capturing learnings and converting them to improvements |
| [Roles and Personas](octoacme-roles-and-personas.md) | Definitions of core roles and their responsibilities |

## Getting started
1. Start with the [Project Management Overview](octoacme-project-management-overview.md) for a high-level orientation.
2. Use the Initiation and Planning guides when starting a new project or feature.
3. Follow Execution & Tracking for day-to-day workflows and the Release guide for production deployments.
4. Capture improvements in retrospectives and add action items to the backlog.

## Acceptance criteria (for this README)
- Content aligns with the existing process documents.
- Improves discoverability and provides a clear entry point to the docs folder.
- Links to all process files in docs/ are present.
