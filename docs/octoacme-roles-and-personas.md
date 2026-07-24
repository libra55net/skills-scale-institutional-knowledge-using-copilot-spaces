# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.
Use it to clarify who owns decisions, who carries work across handoffs, and how cross-functional partners stay aligned.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Test Engineers

### Role Summary
QA / Test Engineers turn acceptance criteria into a practical validation approach.
They help the team confirm that work is releasable, testable, and understood before it reaches customers.

### Responsibilities
- Define the test approach for each increment
- Review acceptance criteria for clarity and testability
- Execute or coordinate functional, regression, and smoke testing
- Triage defects and confirm exit criteria before release
- Highlight quality risks, coverage gaps, and release-readiness concerns

### Goals
- Reduce escaped defects and rework
- Make quality expectations explicit before development starts
- Keep release decisions grounded in evidence

### Typical Communication
- Test plans, defect triage notes, and release-readiness updates
- Daily coordination on bug status and quality risks
- Feedback on acceptance criteria during planning and review

### Interactions with Core Roles
- **Developers:** Align on testability, reproduce defects quickly, and confirm fixes before work is marked done.
- **Product Managers:** Refine acceptance criteria, edge cases, and customer-facing quality expectations.
- **Project Managers:** Surface quality gates, testing dependencies, and timeline risks tied to unresolved defects.

---

## UX / UI Designers

### Role Summary
UX / UI Designers define the user flows, interface patterns, and accessibility expectations that shape delivery.
They help the team reduce ambiguity between product intent and implementation details.

### Responsibilities
- Create user flows, wireframes, and design specifications
- Define interaction patterns and accessibility requirements
- Clarify edge cases in user journeys before implementation
- Support design reviews and implementation sign-off
- Keep design decisions documented and discoverable

### Goals
- Deliver usable and consistent customer experiences
- Reduce design rework during implementation
- Ensure accessibility and interaction quality are planned early

### Typical Communication
- Design reviews, annotated mockups, and handoff notes
- Working sessions on scope trade-offs and user flows
- Async clarifications on implementation details and edge cases

### Interactions with Core Roles
- **Developers:** Provide implementation-ready specs, answer interaction questions, and review builds for fidelity.
- **Product Managers:** Translate product goals into user journeys, prioritize experience trade-offs, and validate proposed solutions.
- **Project Managers:** Flag design dependencies, review milestones, and handoff dates that affect the schedule.

---

## DevOps / Platform Engineers

### Role Summary
DevOps / Platform Engineers enable reliable delivery through environments, automation, observability, and deployment safeguards.
They reduce operational risk during integration, release, and post-release support.

### Responsibilities
- Maintain CI/CD pipelines and deployment workflows
- Manage environment readiness and access needs
- Define monitoring, alerting, and rollback expectations
- Support release coordination and production verification
- Escalate operational constraints that affect delivery plans

### Goals
- Improve delivery reliability and release confidence
- Shorten recovery time when issues occur
- Make operational readiness visible before launch

### Typical Communication
- Deployment checklists, environment updates, and incident notes
- Release readiness reviews and rollback planning
- Async updates on pipeline health and operational blockers

### Interactions with Core Roles
- **Developers:** Partner on build reliability, environment issues, observability, and deployment troubleshooting.
- **Product Managers:** Clarify release constraints, launch sequencing, and operational guardrails that may affect customer rollout.
- **Project Managers:** Coordinate release windows, environment dependencies, and escalation paths for operational risks.

---

## Security / Compliance Leads

### Role Summary
Security / Compliance Leads ensure delivery plans account for security expectations, control requirements, and risk acceptance decisions.
They help teams address security concerns before they become release blockers.

### Responsibilities
- Review planned changes for security and compliance impact
- Define required controls, evidence, and review checkpoints
- Advise on threat, privacy, and access-related risks
- Triage security findings and drive mitigation expectations
- Clarify when risk acceptance or leadership escalation is required

### Goals
- Reduce preventable security and compliance issues
- Make security ownership explicit during planning and release
- Prevent late-stage surprises that delay launch

### Typical Communication
- Security review notes, risk decisions, and exception tracking
- Threat discussions during planning or architecture review
- Escalations for unresolved findings or policy gaps

### Interactions with Core Roles
- **Developers:** Advise on secure implementation choices, remediation priorities, and evidence needed to close findings.
- **Product Managers:** Align on customer trust requirements, policy constraints, and acceptable trade-offs.
- **Project Managers:** Add security checkpoints, owners, and escalation timing into the delivery plan and risk register.

---

## Customer Support / Success Liaisons

### Role Summary
Customer Support / Success Liaisons bring field context into planning and prepare the organization for customer-facing change.
They help delivery teams close the loop between release intent and real customer impact.

### Responsibilities
- Share recurring customer pain points and readiness concerns
- Prepare support messaging, enablement, and escalation guidance
- Validate that known customer-impacting changes are documented
- Collect early post-release feedback and route trends back to the team
- Highlight adoption or support risks before launch

### Goals
- Reduce customer confusion during rollout
- Shorten feedback loops after release
- Improve readiness across support and success teams

### Typical Communication
- Support readiness notes, FAQ updates, and launch briefings
- Escalations for customer-impacting incidents or adoption issues
- Post-release summaries of top feedback themes

### Interactions with Core Roles
- **Developers:** Share reproducible customer issues and clarify the operational impact of defects.
- **Product Managers:** Bring customer feedback into prioritization, rollout planning, and success measurement.
- **Project Managers:** Coordinate launch communications, support handoffs, and ownership for customer follow-up items.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Pair these role definitions with the [OctoAcme Handoffs & Ownership Checklist](octoacme-handoffs-and-ownership-checklist.md) when a project needs clearer decision ownership or handoff readiness.
