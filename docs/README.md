# OctoAcme Project Management Docs

This folder is the home for OctoAcme's project management process documentation. Start here to understand how we run projects, then follow the links below for details on each stage of the lifecycle.

## Project Management Processes Overview

OctoAcme runs projects through a lightweight, five-stage lifecycle: **Initiation → Planning → Execution → Release → Close & Retrospective**. Initiation validates the business need through a Project One-pager (problem statement, SMART goal, success metrics, stakeholders, rough timeline, and initial risks), and work only advances past the decision gate when metrics are clear, stakeholders agree on priority, and team availability is confirmed. Planning then converts the approved initiative into action: a kickoff meeting, a prioritized backlog with acceptance criteria, T-shirt or story-point estimates, a documented Definition of Done, dependency mapping, and a release/milestone plan. The guiding principles throughout are customer-first prioritization, iterative delivery of small testable increments, clear named ownership, data-informed decisions, and psychological safety.

Execution is organized around a predictable team rhythm and a shared project board (Backlog → Ready → In Progress → In Review → QA → Done). Daily 15-minute standups surface progress, blockers, and dependencies; weekly delivery syncs cover progress and flagged risks; and each sprint or milestone ends with a demo/review. Code moves through a disciplined pull request workflow — PRs kept to roughly 400 lines or fewer, linked to an issue with acceptance criteria stated, passing CI tests and linting before review, and at least one approval before merge. Progress is tracked with velocity and burndown, alongside the success metrics defined in the One-pager and dashboards for errors, latency, and usage.

Roles are explicit and complementary. **Project Managers** own plans, timelines, risks, dependencies, meeting facilitation, and status reporting; **Product Managers** define problem statements and success metrics, prioritize the roadmap and backlog, and validate outcomes with research and data; **Developers** implement features to acceptance criteria, write tests and docs, review code, and flag technical risks; **QA/Testing** validates quality and acceptance; and **Stakeholders/Sponsors** supply inputs and approvals. Communication follows a defined cadence — weekly PM/PdM sync, team standups, monthly stakeholder updates, and a single source of truth (project README or release doc) for status — using a standard weekly template covering progress, next steps, risks/blockers, and decisions needed. Risks live in a register (ID, description, impact, likelihood, owner, mitigation, status) reviewed weekly, and escalation follows a clear path: team-level triage → PM → Product Lead → Sponsor, with security incidents routed through the security runbook.

Quality assurance and continuous improvement close the loop. Testing spans unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, security scanning in CI, and manual QA for feature acceptance. Releases are classified as patch, minor, or major, and are gated on merged PRs meeting acceptance criteria, passing CI and security scans, drafted release notes, a documented rollback plan, and prepared smoke tests — with staging verification before an automated production deploy, post-deploy checks, and stakeholder announcement. Failures trigger incident response, rollback to the last known-good release, and root-cause triage. After each sprint, release, milestone, or incident, a timeboxed 45–75 minute retrospective captures what went well and what could improve, with the top 2–3 action items assigned owners, due dates, and success criteria, tracked in the backlog and reviewed in the weekly PM sync.

## Documentation Index

| Document | Description |
| --- | --- |
| [Project Management Overview](./octoacme-project-management-overview.md) | Principles, core roles, key artifacts, lifecycle, and communication cadence. |
| [Project Initiation](./octoacme-project-initiation.md) | One-pager template, minimum deliverables, initiation checklist, and decision gate. |
| [Project Planning](./octoacme-project-planning.md) | Backlog creation, estimation, Definition of Done, risk/dependency management. |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Team rhythm, board workflow, PR conventions, metrics, and blocker escalation. |
| [Risks & Communication](./octoacme-risks-and-communication.md) | Risk register, risk lifecycle, stakeholder comms templates, escalation paths. |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Release types, pre-release requirements, deployment checklist, rollback playbook. |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Retro structure, facilitation guidance, and tracking improvements. |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Responsibilities, goals, and communication patterns for each persona. |
