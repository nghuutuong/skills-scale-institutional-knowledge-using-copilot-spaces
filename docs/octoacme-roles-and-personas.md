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

## QA / Testing Lead

### Role Summary
QA/Testing Leads own the quality strategy and acceptance criteria validation for projects. They design test plans, ensure comprehensive coverage, and validate that solutions meet acceptance criteria before release.

### Responsibilities
- Design and execute test strategies aligned with project scope and risk profile
- Define and validate acceptance criteria with Product Managers and Developers
- Identify and document quality gaps and defects
- Plan and coordinate QA activities across sprints
- Conduct smoke tests, regression testing, and UAT coordination before release

### Goals
- Ensure releases meet quality expectations and business needs
- Reduce the risk of escaped defects and regressions
- Improve visibility into product readiness and quality trends

### Typical Communication
- Collaborate with Developers on test coverage and automation
- Review acceptance criteria during sprint planning
- Report test progress and quality metrics in weekly delivery syncs
- Escalate quality risks and blockers to the Project Manager

### Interaction with Existing Roles
- Works with Product Managers to verify that acceptance criteria reflect customer value and business intent
- Partners with Developers to design testable features and automate verification
- Reports quality and release readiness to Project Managers so delivery risks can be managed proactively

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide technical direction, design solutions, and identify technical risks and dependencies. They mentor developers and ensure solutions align with architectural principles and scalability goals.

### Responsibilities
- Define the technical approach and architecture for significant features
- Identify technical risks, dependencies, and integration points
- Mentor Developers on design patterns and best practices
- Review technical designs and complex pull requests
- Propose mitigations for technical risks identified during planning

### Goals
- Deliver solutions that are maintainable, scalable, and technically sound
- Reduce avoidable engineering rework and technical debt
- Align delivery decisions with system constraints and long-term strategy

### Typical Communication
- Participate in project planning to identify technical complexity
- Conduct technical design reviews before development
- Flag architectural risks in weekly syncs
- Collaborate with Product Managers on technical trade-offs and feasibility

### Interaction with Existing Roles
- Guides Developers on implementation decisions and architecture standards
- Partners with Product Managers to assess whether roadmap goals are feasible within technical constraints
- Coordinates with Project Managers on dependencies, sequencing, and risk planning

---

## Scrum Master / Iteration Coordinator

### Role Summary
Scrum Masters (or Iteration Coordinators) facilitate team ceremonies, coach the team on process adherence, and help remove blockers that impede progress. They ensure the team follows the Definition of Done and continuous improvement practices.

### Responsibilities
- Facilitate daily standups, sprint planning, and retrospectives
- Identify and help resolve process blockers
- Coach the team on OctoAcme practices and iterative delivery
- Track sprint metrics and team velocity
- Ensure the Definition of Done is applied consistently

### Goals
- Improve team efficiency and predictability
- Remove friction that slows delivery
- Strengthen a healthy, repeatable operating rhythm

### Typical Communication
- Lead team ceremonies and track action items
- Report process health and impediments to the Project Manager
- Facilitate retrospectives and drive action-item follow-up
- Escalate systemic blockers preventing team productivity

### Interaction with Existing Roles
- Supports Developers and Product Managers by keeping ceremonies focused and actionable
- Works with Project Managers to identify process gaps, team bottlenecks, and cross-team dependencies
- Helps stakeholders understand how delivery health and team velocity are being managed over time

---

## Stakeholder / Sponsor

### Role Summary
Sponsors and key stakeholders provide business context, approve scope and resources, and remove organizational blockers. They represent the business interests and ensure alignment with strategic priorities.

### Responsibilities
- Provide business context and prioritize conflicting demands
- Approve project scope, budget, and timeline
- Remove organizational blockers and dependencies
- Participate in project reviews and decision gates
- Provide feedback on deliverables and validate business value

### Goals
- Ensure strategic alignment and stakeholder confidence
- Support successful delivery of business value
- Reduce delays caused by unclear priorities or organizational friction

### Typical Communication
- Attend project kickoff and key decision gates
- Review monthly stakeholder updates
- Provide feedback during demos and release reviews
- Escalate business-impacting risks and decisions

### Interaction with Existing Roles
- Provides direction to Product Managers and clarifies business priorities
- Receives status updates from Project Managers and uses them to support decisions or unblock dependencies
- Supports cross-functional alignment when trade-offs affect scope, staffing, or timeline

---

## UX / Design Lead

### Role Summary
UX/Design Leads define the user experience, create design specifications, and ensure solutions are usable and align with product vision. They collaborate with Product Managers and Developers to deliver user-centric features.

### Responsibilities
- Define user experience and design specifications
- Conduct user research and validate design assumptions
- Create wireframes, prototypes, and design documentation
- Review implementation for usability and design consistency
- Identify usability risks and propose improvements

### Goals
- Deliver products that are intuitive, accessible, and valuable to users
- Close the gap between customer needs and technical implementation
- Ensure design quality is visible throughout delivery

### Typical Communication
- Participate in backlog refinement to define design requirements
- Review user stories and acceptance criteria with Product Managers
- Conduct design reviews before development
- Report usability feedback and design risks in weekly syncs

### Interaction with Existing Roles
- Works closely with Product Managers to translate customer need into product direction
- Collaborates with Developers to ensure designs are feasible and implemented accurately
- Shares usability decisions and risks with Project Managers so they can be considered in planning and release readiness

---

## Release / DevOps Engineer

### Role Summary
Release and DevOps Engineers own the deployment infrastructure, manage release pipelines, and ensure reliable, safe deployments to production. They work closely with the team to automate and standardize release processes.

### Responsibilities
- Design and maintain deployment pipelines and infrastructure
- Automate testing, security scanning, and deployment processes
- Plan and execute production deployments
- Document rollback procedures and incident response
- Monitor deployment health and troubleshoot production issues

### Goals
- Reduce deployment risk and improve release predictability
- Increase operational confidence and automation maturity
- Protect service reliability during change and incident response

### Typical Communication
- Participate in release planning to assess deployment readiness
- Coordinate deployment schedules and maintenance windows
- Report infrastructure risks and deployment blockers
- Conduct post-deployment verification and incident response

### Interaction with Existing Roles
- Works with Developers to ensure the system is ready for reliable deployment
- Coordinates with QA/Testing Leads on smoke testing, validation, and release gates
- Supports Project Managers in scheduling and communicating production changes safely

---

## How These Roles Interact

These personas work together in a complementary manner:

- Product Managers work with UX/Design Leads to define user experience and with Developers to plan feasibility
- Project Managers coordinate across Technical Leads, QA/Testing Leads, and Developers to ensure milestones are met
- QA/Testing Leads work with Developers to define acceptance criteria and with Release/DevOps Engineers to plan pre-release validation
- Technical Leads mentor Developers and coordinate with Release/DevOps Engineers on deployment strategy
- Scrum Masters facilitate ceremonies across all roles and track impediments across the team
- Stakeholders/Sponsors provide direction to Product Managers and receive updates from Project Managers
- Release/DevOps Engineers work with QA/Testing Leads on smoke testing and with Developers on deployment readiness

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
