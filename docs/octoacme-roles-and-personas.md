# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

## Technical Lead / Engineering Lead

### Role Summary
Technical Leads guide technical execution across a project. They align architecture and implementation choices with product goals, delivery timelines, and quality expectations.

### Responsibilities
- Define and communicate technical approach and implementation patterns
- Break down complex work with Developers and support realistic estimation
- Surface technical risks, constraints, and dependencies early
- Partner with QA Lead to ensure testability and quality gates are practical
- Support incident triage and technical decision documentation

### Goals
- Maintain a scalable and maintainable technical foundation
- Reduce delivery risk through early technical alignment
- Improve team effectiveness through clear technical direction

### Interactions with Existing Roles
- **Project Managers**: Align technical sequencing with delivery plans and dependency management
- **Product Managers**: Translate product requirements into feasible technical options and trade-offs
- **Developers**: Mentor on design and implementation decisions, and unblock delivery
- **QA/Testing**: Coordinate on test strategy, automation focus, and defect prioritization
- **Stakeholders**: Provide clear updates on technical risks, constraints, and mitigation options

### Decision-Making Responsibilities
- Own day-to-day technical decisions on architecture, implementation patterns, and trade-offs
- Escalate major scope, timeline, or risk impacts to Project and Product Managers for cross-functional decisions

### Typical Communication
- Technical design reviews and implementation planning sessions
- Ongoing developer syncs during execution
- Risk and trade-off updates in project status reviews

---

## QA Lead / Test Lead

### Role Summary
QA Leads define and coordinate the quality strategy for project delivery. They ensure validation activities are planned early and executed consistently before release.

### Responsibilities
- Define test strategy across functional, integration, regression, and release validation
- Coordinate test planning, test data, and environment readiness
- Track quality metrics and defect trends, and drive corrective actions
- Partner with Developers on test automation and acceptance test coverage
- Confirm release readiness from a quality perspective

### Goals
- Improve confidence in releases through consistent validation
- Detect defects early and reduce escaped issues
- Keep quality outcomes visible across project stakeholders

### Interactions with Existing Roles
- **Project Managers**: Align test milestones, defect triage cadence, and readiness checkpoints
- **Product Managers**: Clarify acceptance criteria and expected user outcomes
- **Developers**: Collaborate on testability, defect resolution, and automation priorities
- **QA/Testing**: Guide test execution standards, coverage expectations, and reporting quality
- **Stakeholders**: Share quality status, key risks, and recommended go/no-go input

### Decision-Making Responsibilities
- Recommend go/no-go decisions based on quality thresholds and unresolved risk
- Prioritize testing focus areas when timelines require risk-based trade-offs

### Typical Communication
- Test plan walkthroughs and quality readiness checkpoints
- Defect triage meetings with engineering and product
- Release quality summaries for project and stakeholder updates

---

## Stakeholder Representative / Business Owner

### Role Summary
Stakeholder Representatives provide business context, decision input, and final alignment on expected outcomes. They help ensure project delivery remains tied to organizational priorities.

### Responsibilities
- Represent business goals, constraints, and success criteria for the initiative
- Validate priorities, milestones, and scope changes against expected value
- Provide timely decisions on trade-offs that affect business outcomes
- Confirm that delivered capabilities meet operational and stakeholder needs
- Support adoption planning and post-release feedback loops

### Goals
- Keep delivery aligned with business priorities and outcomes
- Reduce ambiguity in business decisions and trade-off approvals
- Improve stakeholder trust through consistent engagement

### Interactions with Existing Roles
- **Project Managers**: Align on milestone commitments, escalation paths, and governance needs
- **Product Managers**: Validate roadmap priorities and expected value realization
- **Developers**: Provide domain clarifications and contextual feedback when needed
- **QA/Testing**: Review acceptance outcomes and business-critical validation scenarios
- **Stakeholders**: Consolidate input from affected groups and communicate decisions

### Decision-Making Responsibilities
- Approve key business trade-offs on scope, priority, and rollout sequencing
- Confirm whether delivered outcomes satisfy agreed success criteria

### Typical Communication
- Steering or checkpoint reviews for major milestones
- Scope and priority decision discussions with PM and Product
- Post-release feedback and adoption reviews

---

## Release Manager / Deployment Owner

### Role Summary
Release Managers coordinate release readiness and production deployment activities. They ensure cross-functional teams execute deployment safely with clear communication and rollback preparedness.

### Responsibilities
- Own release planning, cutover checklists, and release calendar coordination
- Confirm readiness across engineering, QA, operations, and stakeholder communications
- Coordinate deployment execution, monitoring, and rollback contingency planning
- Track and communicate release risks, blockers, and mitigation actions
- Lead post-release verification and handoff to ongoing support

### Goals
- Deliver releases safely and predictably
- Minimize deployment-related risk and downtime
- Maintain clear accountability during release windows

### Interactions with Existing Roles
- **Project Managers**: Align release milestones with project timeline commitments
- **Product Managers**: Coordinate release scope, timing, and customer-impact communication
- **Developers**: Validate deployment prerequisites, runbooks, and rollback steps
- **QA/Testing**: Confirm test completion, defect status, and production verification coverage
- **Stakeholders**: Communicate release windows, expected impact, and post-release outcomes

### Decision-Making Responsibilities
- Make operational go/no-go recommendations based on readiness signals across teams
- Trigger rollback execution when release risk exceeds agreed thresholds

### Typical Communication
- Release readiness reviews and go/no-go checkpoints
- Deployment command channel updates during release windows
- Post-release summaries including outcomes, incidents, and follow-up actions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
