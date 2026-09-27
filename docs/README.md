# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This directory contains comprehensive guides for running projects following the OctoAcme approach—a customer-first, iterative, and data-driven methodology that emphasizes clear ownership, incremental delivery, and continuous improvement.

## Quick Start

New to OctoAcme? Start here:
- **[Project Management Overview](octoacme-project-management-overview.md)** — Understand our principles, core roles, and project lifecycle at a glance.

## Process Guides

Select the guide that matches your current phase:

### 1. **Initiation** — Validate and authorize new work
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Define business need, stakeholders, success criteria, and make the go/no-go decision.

### 2. **Planning** — Turn an idea into an actionable plan
- **[Project Planning](octoacme-project-planning.md)** — Break work into increments, identify risks and dependencies, align timelines and responsibilities.

### 3. **Execution** — Build, test, and deliver incrementally
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day workflows, team rhythm, quality practices, and blocker escalation.

### 4. **Release** — Deploy features to production
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize releases, manage rollbacks, and communicate changes.

### 5. **Close & Learn** — Capture insights and improve
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Run effective retrospectives and convert learnings into action items.

## Cross-Cutting Concerns

These guides apply throughout the project lifecycle:

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, assess, and mitigate risks; communicate status and escalations.
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Understand key roles (Developer, Product Manager, Project Manager) and their responsibilities.

## OctoAcme Project Management Overview

OctoAcme uses a structured, iterative project management lifecycle that moves initiatives through initiation, planning, execution, release, and retrospective improvement. Projects begin with a one-pager defining the problem, SMART goal, success metrics, stakeholders, timeline, risks, and proposed team. Once stakeholders agree on priority, success criteria, and team availability, the initiative moves into planning. Planning includes creating and prioritizing a backlog, defining acceptance criteria and the Definition of Done, estimating work, identifying dependencies, and establishing release milestones.

During execution, teams manage work through a project board with stages such as Backlog, Ready, In Progress, In Review, QA, and Done. Delivery is organized around small, shippable increments, supported by sprint or iteration planning, daily standups, weekly delivery syncs, and regular demos or milestone reviews. Project Managers coordinate schedules, risks, dependencies, and communications; Product Managers define outcomes, prioritize work, and measure product impact; Developers implement and test solutions; QA validates quality and acceptance criteria; and stakeholders provide input, approvals, and escalation support.

Communication is designed to maintain transparency and enable timely decisions. Teams use daily standups to surface progress, blockers, and dependencies, while weekly status or delivery updates cover accomplishments, next steps, risks, blockers, and decisions needed. Stakeholder communication is tailored to groups such as engineering, sales, and support, with a project README or release document serving as the single source of truth. Risks are recorded in a risk register, reviewed regularly, and escalated from the team to the Project Manager, Product Lead, and Sponsor when they have broader business impact. Security incidents follow a dedicated security runbook and involve the Security on-call team.

Quality assurance is integrated throughout delivery and release rather than left to the end. Pull requests should remain small where possible, include issue links and acceptance criteria, and pass automated tests, linting, and security scans before review. New logic requires unit tests, with integration tests and end-to-end smoke tests added when appropriate; manual QA is used for feature acceptance when needed. Before production deployment, acceptance criteria must be met, CI and security checks must pass, release notes and rollback plans must be prepared, and staging smoke tests must be completed. After each sprint, release, milestone, or incident, retrospectives capture what went well, identify improvements, and assign a small number of owned, time-bound action items for continuous improvement.

## Using These Docs in Copilot Spaces

Add process-specific docs to `.copilot/` so GitHub Copilot Spaces can reference them as context when assisting your team. This helps ensure guidance is tailored to OctoAcme practices and keeps processes discoverable and accessible to all team members.

## Contributing Updates

To add, update, or improve these documentation files, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template. This ensures changes are reviewed, documented, and aligned with the team's project management framework.
