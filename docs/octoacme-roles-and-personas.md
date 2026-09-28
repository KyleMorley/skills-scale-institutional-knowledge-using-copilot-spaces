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

## Technical Lead

### Role Summary
Technical Leads provide technical direction for delivery teams. They align architecture and implementation decisions with product goals, quality expectations, and delivery constraints.

### Responsibilities
- Define and evolve technical approach for features and systems
- Guide implementation standards, code quality, and design consistency
- Identify technical risks, dependencies, and mitigation plans
- Support estimation, sequencing, and technical decision-making

### Interaction with existing roles
- **Project Managers:** align technical dependencies and risk mitigation with delivery plans.
- **Product Managers:** translate product requirements into feasible technical options and trade-offs.
- **Developers:** mentor on implementation details, reviews, and technical quality.
- **QA/Testing:** align on test strategy, quality gates, and non-functional requirements.
- **Stakeholders:** explain technical constraints, risks, and decision impacts.

---

## Delivery Manager

### Role Summary
Delivery Managers oversee end-to-end execution across teams. They focus on flow, coordination, and predictable outcomes from planning through release readiness.

### Responsibilities
- Monitor delivery health, throughput, and dependency resolution
- Drive cross-team coordination and unblock execution issues
- Ensure handoffs between planning, build, testing, and release stages are clear
- Escalate risks that threaten scope, timeline, or quality commitments

### Interaction with existing roles
- **Project Managers:** partner on schedules, milestones, and escalation paths.
- **Product Managers:** ensure prioritized work is sequenced for predictable delivery.
- **Developers:** remove process blockers and clarify cross-team dependencies.
- **QA/Testing:** track testing readiness and defect closure as part of delivery status.
- **Stakeholders:** provide transparent updates on progress, risks, and mitigation actions.

---

## Release Manager

### Role Summary
Release Managers own release planning and execution. They coordinate readiness activities so releases are predictable, controlled, and well-communicated.

### Responsibilities
- Define release calendars, scope cutoffs, and go/no-go criteria
- Coordinate release checklists across engineering, QA, and operations
- Manage release communications, approvals, and rollback plans
- Lead release retrospectives and improve release process reliability

### Interaction with existing roles
- **Project Managers:** align release milestones with project schedules and commitments.
- **Product Managers:** confirm release scope, timing, and customer impact messaging.
- **Developers:** coordinate code freeze windows, deployment steps, and hotfix plans.
- **QA/Testing:** validate test completion, defect risk, and release sign-off status.
- **Stakeholders:** communicate release readiness, outcomes, and incident escalations.

---

## UX Designer

### Role Summary
UX Designers ensure solutions are usable, accessible, and aligned with user needs. They connect discovery insights to implementation-ready design guidance.

### Responsibilities
- Conduct or synthesize user research and workflow insights
- Produce wireframes, interaction flows, and design specifications
- Validate usability and accessibility requirements before and after implementation
- Partner with teams to iterate based on user feedback and product metrics

### Interaction with existing roles
- **Project Managers:** align design activities with planning milestones and delivery timelines.
- **Product Managers:** refine problem statements, acceptance criteria, and user outcomes.
- **Developers:** provide implementation guidance and review UX fidelity during build.
- **QA/Testing:** define UX and accessibility acceptance checks for validation.
- **Stakeholders:** present design rationale and gather feedback on user impact.

---

## Support and Operations

### Role Summary
Support and Operations teams represent production reality and customer impact. They ensure services are reliable, supportable, and operationally ready.

### Responsibilities
- Define operational readiness requirements (monitoring, runbooks, alerting)
- Surface recurring production issues and customer pain points
- Support incident response, root-cause analysis, and follow-up improvements
- Advise on deployment risk and post-release stabilization needs

### Interaction with existing roles
- **Project Managers:** feed operational dependencies and readiness tasks into plans.
- **Product Managers:** share customer-facing issues and support trends for prioritization.
- **Developers:** collaborate on observability, maintainability, and production fixes.
- **QA/Testing:** validate production-like test coverage and recovery scenarios.
- **Stakeholders:** report service health, incident trends, and operational risk posture.

---

## Security and Compliance Stakeholder

### Role Summary
Security and Compliance stakeholders ensure delivery aligns with security controls, regulatory requirements, and organizational policies.

### Responsibilities
- Define security and compliance requirements for features and releases
- Review architecture, data handling, and access control decisions
- Coordinate risk assessments, control evidence, and remediation tracking
- Approve or conditionally gate releases based on compliance posture

### Interaction with existing roles
- **Project Managers:** plan security/compliance activities and governance checkpoints.
- **Product Managers:** incorporate regulatory and trust requirements into scope decisions.
- **Developers:** guide secure implementation patterns and remediation priorities.
- **QA/Testing:** align on security testing scope and evidence collection for sign-off.
- **Stakeholders:** communicate residual risk, obligations, and compliance status.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
