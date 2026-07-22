# OctoAcme Project Management – Docs Overview

This folder contains the project management documentation for OctoAcme. The guides here cover the full project lifecycle, team roles, communication practices, and quality standards used across all cross-functional projects.

## Project Lifecycle

OctoAcme projects follow five phases:

1. **Initiation** – Define the problem statement, align stakeholders, identify early risks, and reach a go/no-go decision using a lightweight one-pager.
2. **Planning** – Build a prioritized backlog, estimate scope, map milestones and dependencies, and document a Definition of Done (DoD).
3. **Execution** – Deliver in small, testable increments using a project board (Backlog → Ready → In Progress → In Review → QA → Done). PR practices stay disciplined: small changes, linked issues, CI checks before review, and required approval before merge. Risks are escalated through a tiered path (team triage → PM/Product Lead → sponsor).
4. **Release** – Run release-readiness checks, verify the deployment, communicate the launch, and ensure a rollback plan is in place.
5. **Retrospective & Continuous Improvement** – Convert lessons learned into tracked action items with owners and due dates.

## Roles and Personas

| Role | Core Responsibilities |
|---|---|
| **Project Manager (PM)** | Coordinates delivery, schedules, risks, and cross-team communication |
| **Product Manager (PdM)** | Defines outcomes, owns backlog prioritization, and measures success |
| **Developers** | Implement and test features; surface technical risks early |
| **QA / Testing** | Validates quality and acceptance criteria |
| **Stakeholders** | Provide inputs and approvals at planned checkpoints |

## Communication Practices

- **Standups** (twice-weekly or as agreed) and **weekly PM + PdM syncs** keep the delivery team aligned.
- **Sprint/milestone demos** and **stakeholder updates** (weekly or milestone-based) maintain shared visibility.
- Standardized **status and incident communication templates** provide a single source of truth for project health.

## Quality Assurance

- Unit tests on all new logic; integration and smoke tests where relevant.
- CI pipeline enforces lint, test, and security scans on every PR.
- Manual QA performed where needed for acceptance validation.
- Release readiness checks confirm quality gates are met before deployment.

## Documents in This Folder

| File | Contents |
|---|---|
| [octoacme-project-management-overview.md](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and lifecycle summary |
| [octoacme-project-initiation.md](octoacme-project-initiation.md) | Initiation process and one-pager template |
| [octoacme-project-planning.md](octoacme-project-planning.md) | Backlog, estimation, milestones, and Definition of Done |
| [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) | Project board workflow, PR process, and risk escalation |
| [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) | Release readiness, rollback planning, and launch communication |
| [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format and action-item tracking |
| [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) | Risk management, status templates, and escalation paths |
| [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) | Detailed persona definitions for PM, PdM, Developers, QA, and Stakeholders |
