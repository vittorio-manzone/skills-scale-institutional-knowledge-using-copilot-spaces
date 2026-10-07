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

## UX/UI Designer or User Researcher

### Role Summary
This role investigates user needs and turns them into usable, accessible experiences. Depending on the project, the focus may be interaction and visual design, user research, or both.

### Responsibilities
- Plan and conduct appropriate user research, and share findings with the team
- Create user flows, wireframes, prototypes, and design specifications as needed
- Define usability and accessibility considerations with the Product Manager
- Review implemented experiences with Developers and QA/Testing, and identify design gaps

### Decision Ownership and Deliverables
Owns research methods and design recommendations, but not product priority, scope, or delivery commitments. Typical deliverables include research findings, user journeys, prototypes, and design or accessibility guidance.

### Interactions and When Needed
Engages with stakeholders and users to understand needs, partners with the Product Manager to connect findings to product outcomes, and hands off designs and testable behaviors to Developers and QA/Testing. Involve this role when user needs are uncertain, a workflow is complex, or usability and accessibility are significant risks.

---

## Technical Lead or Architect

### Role Summary
Guides the technical approach so the solution is reliable, maintainable, and aligned with system architecture and constraints.

### Responsibilities
- Define or review architecture, technical standards, and integration points
- Work with Developers to break down implementation, estimate effort, and address technical dependencies
- Identify technical risks and propose mitigations for the Project Manager's risk register
- Advise QA/Testing on technical areas that need focused validation

### Decision Ownership and Deliverables
Owns technical design decisions within agreed product scope, architecture standards, and project constraints; escalates material trade-offs or changes in scope, cost, or timeline to the Product Manager and Project Manager. Typical deliverables include design decisions, architecture diagrams, and technical risk or dependency notes.

### Interactions and When Needed
Works directly with Developers on implementation and reviews, explains feasibility and trade-offs to the Product Manager, and shares dependencies and estimates with the Project Manager. Involve this role when work spans systems or teams, introduces substantial technical risk, or needs architectural coordination.

---

## Business Analyst

### Role Summary
Connects business goals and stakeholder needs to clear, actionable requirements and workflows.

### Responsibilities
- Elicit and document business requirements, rules, and current or proposed workflows
- Identify gaps, assumptions, and conflicting stakeholder needs
- Help the Product Manager refine backlog items and acceptance criteria
- Clarify expected behavior and edge cases for Developers and QA/Testing

### Decision Ownership and Deliverables
Owns the clarity and traceability of documented requirements, not product prioritization or stakeholder approval. Typical deliverables include process maps, requirement notes, and refined acceptance criteria.

### Interactions and When Needed
Facilitates input from stakeholders, works with the Product Manager to ensure requirements support desired outcomes, and hands clear requirements and open questions to Developers and QA/Testing. Involve this role when business processes are complex, requirements are ambiguous, or multiple stakeholder groups need alignment.

---

## Release Manager

### Role Summary
Coordinates release readiness and execution so approved changes can be deployed and communicated in a controlled way.

### Responsibilities
- Coordinate the release schedule and readiness checklist with the Project Manager
- Track completion of acceptance criteria, CI and security scans, release notes, smoke tests, and rollback or mitigation plans
- Coordinate deployment handoffs with Developers and QA/Testing, including post-deployment verification
- Prepare release communications for stakeholders and support

### Decision Ownership and Deliverables
Owns release coordination, readiness tracking, and release records; does not independently approve product scope or override technical, quality, or security concerns. Escalates unresolved blockers to the Project Manager and appropriate decision owners. Typical deliverables include a release plan, readiness status, release notes, and rollback coordination.

### Interactions and When Needed
Works with the Project Manager on milestones, Developers and QA/Testing on deployment and verification readiness, and stakeholders on timing and communications. Involve this role when releases have multiple teams or dependencies, a formal release window, or elevated deployment risk.

---

## Security/Privacy Lead

### Role Summary
Helps the team identify and address security, privacy, and applicable compliance requirements throughout delivery.

### Responsibilities
- Identify relevant security and privacy requirements, threats, and data-handling risks
- Advise Developers on appropriate controls and QA/Testing on security and privacy validation
- Review evidence such as security scan results and track identified risks or remediation
- Escalate material risks through the Project Manager and follow the security incident runbook when an incident occurs

### Decision Ownership and Deliverables
Owns security and privacy guidance and review findings, but does not replace designated risk acceptance, compliance approval, or Security on-call responsibilities. Unresolved risks must be escalated to the appropriate authorized owner before release. Typical deliverables include security and privacy requirements, review findings, and tracked mitigation actions.

### Interactions and When Needed
Partners with the Product Manager to surface requirements, Developers to implement controls, QA/Testing to validate them, and the Project Manager to track risks and escalations. Involve this role when handling sensitive data, adding external integrations, changing access or data flows, or when policy or regulation requires review.

---

## Assigning roles
These roles describe responsibilities, not required headcount. Assign a clear owner for each responsibility that applies to the project; on smaller teams, one person may cover multiple roles when qualified and conflicts are managed. Bring in specialist support when the work's complexity, risk, or policy requirements exceed the team's experience.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
