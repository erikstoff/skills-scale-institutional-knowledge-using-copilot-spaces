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

### How this role interacts with other roles
- **Product Managers:** clarifies requirements and acceptance criteria
- **Project Managers:** provides estimates, progress updates, and technical risks
- **Technical Lead / Architect:** participates in design reviews and follows technical direction
- **QA / Test Engineers:** collaborates on testability and defect investigation

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

### How this role interacts with other roles
- **Project Managers:** aligns priorities, scope, and delivery plans
- **Developers:** clarifies requirements and discusses implementation trade-offs
- **Design / UX:** defines customer problems and validates proposed experiences
- **Executive Sponsor:** communicates product priorities and business outcomes
- **Support / Customer Success:** reviews customer feedback themes for backlog priorities
- **Technical Lead / Architect:** balances product needs with technical trade-offs

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

### How this role interacts with other roles
- **Product Managers:** coordinates scope, priorities, and delivery expectations
- **Executive Sponsor:** escalates decisions and communicates project status
- **Developers and Technical Lead / Architect:** tracks progress, dependencies, and technical risks
- **QA / Test Engineers:** reviews quality risks and release readiness
- **Release / DevOps Engineers:** coordinates deployment windows and release plans
- **Support / Customer Success:** coordinates release communications and incident updates

---

## QA / Test Engineers

### Role Summary
QA / Test Engineers validate that delivered work meets acceptance criteria and quality standards, including the smoke tests required before release.

### Responsibilities
- Create and maintain test plans for project work
- Validate acceptance criteria and report defects with clear reproduction steps
- Run and maintain smoke tests for critical flows
- Report quality risks and release readiness

### Goals
- Find defects before they reach production
- Maintain confidence in release quality gates
- Keep test coverage aligned with product risk

### Typical Communication
- Test plans and defect reports
- Acceptance validation with product and engineering
- Smoke test results during release readiness

### How this role interacts with other roles
- **Developers:** collaborates on testability and defect investigation
- **Product Managers:** clarifies acceptance criteria and expected behavior
- **Project Managers:** reports release readiness and quality risks
- **Release / DevOps Engineers:** coordinates staging smoke tests and quality gates

---

## Release / DevOps Engineers

### Role Summary
Release / DevOps Engineers maintain the deployment process and safely promote changes through staging and production.

### Responsibilities
- Own deployment pipelines and environment promotion
- Execute rollbacks when a release needs to be reversed
- Maintain CI security scanning and communicate scan results
- Coordinate deployment readiness and operational checks

### Goals
- Make releases repeatable and reliable
- Minimize deployment risk and recovery time
- Keep build and deployment pipelines healthy

### Typical Communication
- Build and deployment status
- Release plans, deployment windows, and rollback updates
- CI security scan findings

### How this role interacts with other roles
- **Developers:** resolves build issues and supports reliable delivery
- **Project Managers:** coordinates deployment windows and release plans
- **QA / Test Engineers:** aligns staging smoke test gates with promotion steps
- **Security / Compliance Reviewers:** reviews scan findings and remediation status

---

## Executive Sponsor

### Role Summary
The Executive Sponsor approves project funding and priority and makes the go/no-go decision at initiation.

### Responsibilities
- Approve funding, priority, and project initiation
- Provide the initiation go/no-go decision
- Resolve escalations that cannot be addressed by the team, Project Manager, or Product Lead
- Confirm alignment with business goals

### Goals
- Invest in work that delivers meaningful business value
- Ensure projects have clear sponsorship and direction
- Resolve high-level blockers promptly

### Typical Communication
- Initiation and funding decisions
- Project status and escalation briefings
- Priority and outcome reviews

### How this role interacts with other roles
- **Project Managers:** reviews status, risks, and escalations
- **Product Managers:** aligns funding and priority with product outcomes

---

## Design / UX

### Role Summary
Design / UX leads user research, experience flows, and usability validation to inform product decisions and success metrics.

### Responsibilities
- Conduct user research and synthesize findings
- Create and validate user flows and designs
- Evaluate usability and share findings with the team
- Contribute user-centered measures of success

### Goals
- Deliver usable experiences that address customer needs
- Reduce uncertainty through research and validation
- Align design decisions with measurable outcomes

### Typical Communication
- Research findings and usability feedback
- User flows, prototypes, and design reviews
- Collaboration during discovery and feature refinement

### How this role interacts with other roles
- **Product Managers:** defines customer problems and informs success measures
- **Developers:** clarifies designs and validates implementation fidelity

---

## Support / Customer Success

### Role Summary
Support / Customer Success communicates product changes to customers and brings customer-reported issues and themes back to the project team.

### Responsibilities
- Receive release announcements and share relevant updates with customers
- Surface customer-reported issues and recurring themes
- Feed customer themes into the backlog and retrospectives
- Share customer impact during releases and incidents

### Goals
- Keep customers informed and supported
- Help the team identify recurring customer needs and issues
- Improve future work using customer feedback

### Typical Communication
- Release announcements and customer updates
- Customer issue summaries and feedback themes
- Backlog and retrospective discussions

### How this role interacts with other roles
- **Project Managers:** coordinates release communications and incident updates
- **Product Managers:** shares customer feedback themes to inform backlog priorities

---

## Security / Compliance Reviewer

### Role Summary
Security / Compliance Reviewers assess security and compliance risks, review scan findings before release, and own the security incident runbook.

### Responsibilities
- Maintain the security incident runbook
- Review security scan findings and required mitigations before release
- Advise on security and compliance risks
- Coordinate security incident response guidance

### Goals
- Identify and address security risks before release
- Support compliance with applicable requirements
- Enable a clear and consistent security incident response

### Typical Communication
- Security scan findings and remediation reviews
- Release security assessments
- Security incident runbook and response coordination

### How this role interacts with other roles
- **Developers:** reviews risks and helps clarify remediation requirements
- **Release / DevOps Engineers:** reviews CI scan findings and release security gates

---

## Technical Lead / Architect

### Role Summary
The Technical Lead / Architect sets technical direction, reviews designs, and identifies technical risks during planning.

### Responsibilities
- Set and communicate technical direction
- Lead design reviews and guide architectural decisions
- Identify technical risks and dependencies during planning
- Advise on technical trade-offs

### Goals
- Keep solutions reliable, maintainable, and aligned with technical direction
- Identify technical risks early
- Enable developers to make consistent design decisions

### Typical Communication
- Technical designs and architecture reviews
- Planning discussions on risks and dependencies
- Technical trade-off discussions with product and engineering

### How this role interacts with other roles
- **Developers:** guides implementation and reviews technical designs
- **Product Managers:** discusses technical trade-offs against product needs

---

## Lifecycle RACI Summary

| Role | Initiation | Planning | Execution | Release | Retrospective |
|---|---|---|---|---|---|
| Project Manager | A | A | A | A | A |
| Product Manager | A | A | C | C | C |
| Technical Lead | C | A | A | C | C |
| Developers | I | C | R | R | R |
| QA / Test | I | C | R | A | R |
| Release / DevOps | I | C | C | R | C |
| Security / Compliance | I | C | C | A | I |
| Design / UX | C | C | R | I | R |
| Support / CS | I | I | I | C | C |
| Executive Sponsor | A | I | I | I | I |

R = Responsible; A = Accountable; C = Consulted; I = Informed.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
