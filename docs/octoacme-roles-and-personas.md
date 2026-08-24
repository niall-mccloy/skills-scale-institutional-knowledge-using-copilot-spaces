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

### Interaction with Other Roles
- Collaborate with **QA/Testing Leads** on test automation and acceptance criteria clarification
- Work with **Technical Leads** on design reviews and technical feasibility
- Coordinate with **DevOps Engineers** on deployment and infrastructure needs
- Receive prioritization and feature context from **Product Managers**
- Follow delivery schedules set by **Project Managers**

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

### Interaction with Other Roles
- Partner with **Project Managers** on timeline feasibility and risk management
- Engage **Stakeholders/Sponsors** for business priorities and trade-off decisions
- Define acceptance criteria in consultation with **QA/Testing Leads**
- Review technical feasibility with **Technical Leads**
- Measure feature success with input from **DevOps Engineers** (observability and metrics)

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

### Interaction with Other Roles
- Work with **Product Managers** to translate business goals into executable plans
- Escalate blockers to **Stakeholders/Sponsors** for resolution
- Coordinate with **Scrum Masters** on sprint ceremonies and team impediments
- Track **QA/Testing** status and release readiness
- Monitor technical risks with **Technical Leads**
- Plan deployments with **DevOps Engineers**

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality assurance strategy and ensure all deliverables meet acceptance criteria before release. They collaborate with developers and product managers to define testability requirements and execute comprehensive test plans.

### Responsibilities
- Define and maintain test plans aligned with acceptance criteria
- Coordinate unit, integration, and end-to-end testing efforts
- Validate features meet Definition of Done before release
- Identify and document quality gaps and blockers
- Participate in pre-release smoke testing and deployment verification
- Collaborate with developers on testability and test automation

### Goals
- Ensure zero critical bugs reach production
- Reduce time from feature completion to release readiness
- Increase test coverage and automation

### Typical Communication
- Sprint planning and retrospectives
- Daily standups (quality status updates)
- Test result summaries and bug reports
- Pre-release readiness sign-offs

### Interaction with Other Roles
- Partner with **Developers** on test automation and code testability
- Align acceptance criteria with **Product Managers**
- Report quality status and release readiness to **Project Managers**
- Collaborate with **Technical Leads** on test strategy for complex components
- Support **DevOps Engineers** with smoke test execution during deployment
- Brief **Stakeholders** on quality risks and release readiness

---

## Technical Lead/Architect

### Role Summary
Technical Leads make architectural decisions, ensure code quality, and mitigate technical risks. They mentor developers, guide design reviews, and maintain technical standards across the project.

### Responsibilities
- Own technical design and architecture decisions
- Conduct technical design reviews and code reviews
- Identify and mitigate technical risks and scalability concerns
- Mentor developers and establish coding standards
- Define deployment and integration strategies
- Advise Product and Project Managers on technical feasibility and trade-offs

### Goals
- Deliver maintainable, scalable solutions
- Reduce technical debt and rework
- Enable team autonomy through clear technical direction

### Typical Communication
- Technical design documents and architecture reviews
- Code review feedback and guidance
- Risk register updates for technical risks
- Technical feasibility assessments during planning

### Interaction with Other Roles
- Mentor and guide **Developers** on technical standards and design decisions
- Assess technical feasibility for **Product Managers** and **Project Managers**
- Collaborate with **QA/Testing Leads** on test strategy for complex systems
- Advise **DevOps Engineers** on deployment architecture and scalability needs
- Escalate technical risks to **Stakeholders** when business-critical

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders provide business context, secure resources, and make critical business decisions. They champion the project and ensure alignment with organizational strategy.

### Responsibilities
- Define business goals and success metrics
- Secure budget and resource commitments
- Provide executive-level approvals and escalation authority
- Communicate business context and market drivers to the team
- Review progress and make go/no-go decisions at gates
- Escalate cross-organizational blockers

### Goals
- Deliver business value aligned with organizational strategy
- Secure resources and resolve top-level blockers
- Maintain stakeholder confidence and alignment

### Typical Communication
- Monthly stakeholder updates and steering committee meetings
- Project initiation and gate approvals
- Escalated risk and blocker resolution
- Release announcements and success celebrations

### Interaction with Other Roles
- Partner with **Product Managers** on business priorities and trade-off decisions
- Escalate blockers raised by **Project Managers**
- Approve timelines and resource allocation with **Project Managers**
- Receive quality and readiness updates from **QA/Testing Leads**
- Make go/no-go decisions based on technical risk assessments from **Technical Leads**
- Celebrate release success with **DevOps Engineers** and the full team

---

## Scrum Master/Team Facilitator

### Role Summary
Scrum Masters remove team impediments, coach the team on process adherence, and facilitate ceremonies. They foster a culture of continuous improvement and psychological safety.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Remove team impediments and blockers
- Coach team on Agile practices and process adherence
- Track team health and psychological safety
- Escalate systemic issues to leadership
- Maintain sprint board and process discipline

### Goals
- Maximize team velocity and predictability
- Foster continuous improvement and learning
- Build a psychologically safe team environment

### Typical Communication
- Facilitation of all sprint ceremonies
- One-on-ones with team members
- Retrospective action item tracking
- Escalations to Product Lead and Project Manager

### Interaction with Other Roles
- Facilitate ceremonies with **Developers**, **QA/Testing Leads**, **Technical Leads**, and all team members
- Escalate team impediments to **Project Managers** for resolution
- Protect team capacity and psychological safety in partnership with **Product Managers**
- Track and resolve process blockers, escalating to **Project Managers** or **Stakeholders** when needed
- Celebrate team accomplishments and improvements

---

## DevOps/Infrastructure Engineer

### Role Summary
DevOps Engineers own deployment pipelines, infrastructure, and operational readiness. They enable reliable, fast delivery and maintain system observability.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage production and staging infrastructure
- Define and implement security scanning and compliance checks
- Create runbooks for deployment and incident response
- Monitor system health and performance
- Support release activities and rollback procedures
- Advise developers on deployment best practices

### Goals
- Enable fast, reliable deployments to production
- Maintain system availability and performance
- Reduce deployment risk and cycle time

### Typical Communication
- Pre-release readiness reviews
- Deployment planning and execution
- Incident response and post-mortems
- Infrastructure and monitoring updates

### Interaction with Other Roles
- Advise **Developers** on deployment best practices and infrastructure requirements
- Coordinate with **QA/Testing Leads** on smoke test execution and deployment verification
- Work with **Technical Leads** on deployment architecture and scalability
- Support **Project Managers** with release planning and deployment timelines
- Execute deployments and report status to **Stakeholders** and **Project Managers**
- Participate in **Scrum Master** ceremonies to surface infrastructure blockers

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the **Interaction with Other Roles** sections to understand cross-functional workflows and communication patterns.
