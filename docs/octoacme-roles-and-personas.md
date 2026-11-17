# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. A person may take on more than one role, especially on smaller teams; assign ownership explicitly so responsibilities and handoffs remain clear.

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

## Engineering Lead / Technical Lead

### Role Summary
The Engineering Lead guides the technical approach and coordinates engineering work so that the solution is feasible, secure, reliable, and maintainable. This role may be held by a senior Developer.

### Responsibilities
- Facilitate technical design and document significant architecture decisions
- Surface technical risks, estimates, and dependencies
- Coordinate implementation across Developers and review technical work
- Advise on technical trade-offs without owning product priority

### Collaboration and Handoffs
- Partners with the Product Manager to assess feasibility and clarify technical implications of scope choices
- Works with the Project Manager to communicate estimates, dependencies, risks, and delivery status
- Guides Developers through design discussions and code reviews; coordinates with QA/Testing on testability and technical readiness
- Consults Operations / SRE or the Release Owner on reliability and deployment concerns

## UX/UI Designer or Researcher

### Role Summary
The UX/UI Designer or Researcher helps the team understand user needs and shape an accessible, usable experience through research, interaction design, and validation.

### Responsibilities
- Plan or conduct user research and synthesize findings
- Create or maintain user flows, prototypes, and design guidance
- Identify usability and accessibility considerations
- Validate designs with users or other appropriate evidence

### Collaboration and Handoffs
- Partners with the Product Manager to connect user needs to product goals, scope, and acceptance criteria
- Shares designs and research insights with Developers early enough to inform estimation and implementation
- Works with Developers and QA/Testing to clarify intended behavior and validate the implemented experience
- Keeps the Project Manager informed of research or design dependencies that may affect milestones

## Business Analyst

### Role Summary
The Business Analyst clarifies business processes, requirements, and stakeholder needs, translating them into documented and testable requirements.

### Responsibilities
- Elicit and document business needs, workflows, assumptions, and constraints
- Identify gaps, ambiguities, and dependencies in requirements
- Support traceability from business needs to backlog items and acceptance criteria
- Record requirement-related decisions and changes

### Collaboration and Handoffs
- Works with the Product Manager to refine requirements, scope, priorities, and acceptance criteria; the Product Manager retains product prioritization ownership
- Coordinates with the Project Manager to record decisions and surface requirement changes or dependencies that could affect delivery
- Clarifies requirements for Developers and QA/Testing, and incorporates stakeholder input through the agreed review process

## Operations / SRE or Release Owner

### Role Summary
The Operations / SRE or Release Owner advises on production readiness and coordinates operational, reliability, and deployment needs. The specific release responsibilities should be assigned explicitly for each project.

### Responsibilities
- Define or advise on operational readiness, monitoring, reliability, and support requirements
- Review deployment risks, rollback or mitigation plans, and release dependencies
- Coordinate deployment verification and operational handoff
- Surface incidents or readiness gaps through the established escalation path

### Collaboration and Handoffs
- Partners with Developers and the Engineering Lead on operational design, observability, and reliability risks
- Coordinates with QA/Testing on verification plans and with the Project Manager on release timing, dependencies, and readiness status
- Works with the Product Manager on customer or business impact and release trade-offs
- Hands off operational guidance and known issues to Customer Support / Enablement Representative and relevant on-call teams

## Customer Support / Enablement Representative

### Role Summary
The Customer Support / Enablement Representative prepares customer-facing support and internal enablement for changes, helping ensure users and support teams can understand and adopt releases.

### Responsibilities
- Identify support impacts, common customer questions, and training needs
- Draft or coordinate FAQs, help content, and enablement materials
- Share customer feedback and recurring issues with the product team
- Confirm support readiness and communicate known issues through agreed channels

### Collaboration and Handoffs
- Works with the Product Manager to understand customer impact, intended outcomes, and product messaging
- Coordinates with the Project Manager and Operations / SRE or Release Owner on release communications, timing, readiness, and known issues
- Consults Developers and QA/Testing when technical or behavioral details need clarification
- Provides support materials and handoff information to customer-facing teams before launch

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Adapt role assignments to the project; one person may cover multiple roles, but each responsibility and decision should have a clear owner.
