# OctoAcme Project Management Documentation

## Overview
OctoAcme's project management approach emphasizes customer-first delivery, iterative development, clear ownership, data-informed decisions, and psychological safety. These principles guide how we plan, execute, and improve our work. This directory centralizes the process docs you need to start, run, and close projects consistently across teams.

OctoAcme runs projects with a clear, iterative lifecycle that begins with a lightweight initiation (one-pager, stakeholder alignment, success metrics) and moves into planning, execution, release, and retrospective. Planning breaks approved work into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done; teams estimate using T-shirt sizing or story points and map work to releases and milestones. Execution is managed on a visible project board with columns (Backlog, Ready, In Progress, In Review, QA, Done) and a pull-request driven workflow that encourages small PRs, linked issues and acceptance criteria, CI gating (tests and linting), and at least one reviewer approval before merging.

Roles and responsibilities are explicit: Product Managers define outcomes and success metrics, Project Managers coordinate delivery, schedules, risks, and communications, developers implement and test, and QA validates acceptance and runs manual checks where needed. These personas are used both to assign clear ownership for artifacts (one-pagers, risk registers, release notes) and to drive exercise scenarios and role-specific guidance within the project. Risk management is formalized with a simple register (ID, impact, likelihood, owner, mitigation) and escalation paths from team triage up to sponsor level for business-impacting issues.

Communication is cadence-driven and centralized: short daily standups for blockers and progress, weekly delivery syncs to surface progress and risks, regular PM+PdM alignment, and monthly stakeholder updates. QA is integrated across the lifecycle with unit, integration, and smoke tests, automated security scanning in CI, and manual QA for acceptance when needed. Releases require passing CI and security checks, release notes and rollback plans, and post-deploy verification. Retrospectives capture learnings and convert them into tracked action items for continuous improvement.

## Table of Contents
- Overview
- Core Project Management Processes
  - Initiation
  - Planning
  - Execution & Tracking
  - Risk Management & Communication
  - Release & Deployment
  - Retrospective & Continuous Improvement
- Process Documentation (links)
- Getting Started

## Core Project Management Processes (brief)
- Initiation: Validate and authorize work by confirming business need, aligning stakeholders, defining success criteria, and creating a lightweight plan (project one-pager).
- Planning: Turn approved initiatives into actionable plans by breaking work into shippable increments, identifying dependencies and risks, estimating, and creating a release timeline.
- Execution & Tracking: Manage day-to-day execution with team rhythms (standups, weekly syncs, demos), track progress on a project board, follow PR and CI practices, and escalate blockers via documented paths.
- Risk Management & Communication: Maintain a risk register, assess and mitigate risks, and keep stakeholders informed via regular status updates and escalation procedures.
- Release & Deployment: Standardize releases with pre-release checks, deployment checklists, rollback plans, and post-deploy verifications and announcements.
- Retrospective & Continuous Improvement: Run timeboxed retrospectives after sprints/releases/incidents, capture 2–3 prioritized action items, and track them in the backlog.

## Process Documentation
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

## Getting Started
New team members should begin with the [Project Management Overview](octoacme-project-management-overview.md) for a high-level understanding, then reference the process documents relevant to their role or the current project phase.
