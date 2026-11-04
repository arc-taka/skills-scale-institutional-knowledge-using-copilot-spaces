# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles describe capabilities and accountabilities; they do not require a separate person for each role. Assign the needed capabilities explicitly for each project, and allow one person to cover multiple roles when appropriate.

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

## UX/UI Designers and Researchers

### Role Summary
UX/UI Designers and Researchers help ensure that solutions address user needs and provide a clear, accessible, usable experience. Depending on project needs, one person may cover design, research, or both.

### Responsibilities
- Plan and synthesize user research, and share findings with the team
- Create and maintain user flows, prototypes, and design guidance
- Identify usability and accessibility considerations for requirements and acceptance criteria
- Validate designs with users or other appropriate feedback methods

### Interactions with Existing Roles
- Partner with the Product Manager to understand user needs, shape scope, and validate product decisions
- Work with Developers and the Technical Lead to assess feasibility and resolve design questions during implementation
- Coordinate with QA/Testing to include usability and accessibility considerations in acceptance and validation
- Share research findings and design decisions with the Project Manager so dependencies and review needs are reflected in the plan

### Typical Artifacts and Decision Boundaries
- Research findings, user flows, prototypes, design specifications, and usability guidance
- Recommend experience and design decisions; product scope and priority remain with the Product Manager, while implementation choices are made with engineering

---

## Technical Leads and Architects

### Role Summary
Technical Leads and Architects guide technical design and integration so the solution is maintainable, testable, and consistent with relevant architecture. The scope may be held by a project technical lead, an architect, or both.

### Responsibilities
- Guide technical design, architecture, and integration decisions
- Identify technical constraints, interfaces, and dependencies
- Surface technical risks and coordinate mitigation with the team
- Promote maintainability, testability, and appropriate engineering practices

### Interactions with Existing Roles
- Coordinate with the Project Manager to identify technical dependencies, risks, and sequencing needs
- Work with the Product Manager to explain technical trade-offs and their impact on product outcomes and scope
- Guide and support Developers during design and implementation without replacing their ownership of delivered code
- Partner with QA/Testing to ensure designs are testable and technical coverage is appropriate
- Consult stakeholders when technical choices affect commitments, integrations, or operational expectations

### Typical Artifacts and Decision Boundaries
- Design proposals, architecture or integration diagrams, technical decision records, and technical risk notes
- Own or facilitate technical recommendations within agreed engineering standards; product priority and project commitments remain with the Product Manager and Project Manager respectively

---

## Security and Privacy Leads

### Role Summary
Security and Privacy Leads help teams identify and address security, privacy, and data-protection requirements and risks throughout delivery.

### Responsibilities
- Advise on applicable security and privacy requirements and controls
- Help assess risks and identify mitigations or required reviews
- Make security and privacy needs visible in planning, acceptance, and release readiness
- Guide escalation through the appropriate security process when an incident or significant risk arises

### Interactions with Existing Roles
- Work with the Product Manager to understand data use and include relevant security and privacy needs in product requirements
- Coordinate with the Project Manager to track reviews, risks, dependencies, and escalations
- Advise Developers on implementing controls and QA/Testing on validating them
- Inform relevant stakeholders of material risks and decisions through agreed communication channels

### Typical Artifacts and Decision Boundaries
- Security/privacy requirements, risk assessments, review findings, and mitigation recommendations
- Provide specialist guidance and identify required escalation; risk acceptance and release decisions follow the organization's designated authority and process

---

## Data and Analytics Leads

### Role Summary
Data and Analytics Leads help the team collect trustworthy evidence about product behavior and whether intended outcomes are being achieved.

### Responsibilities
- Translate success metrics into measurement and instrumentation needs
- Advise on data quality, event definitions, and reporting
- Help interpret results and communicate limitations or findings after release

### Interactions with Existing Roles
- Partner with the Product Manager to connect success metrics to measurable outcomes and interpret results
- Work with Developers to plan and implement instrumentation
- Coordinate with QA/Testing to verify measurement behavior and data quality where applicable
- Share measurement dependencies and reporting needs with the Project Manager for inclusion in plans and status updates

### Typical Artifacts and Decision Boundaries
- Metric definitions, event or instrumentation specifications, dashboards, and analysis
- Recommend measurement approaches and explain evidence; product direction and priority remain with the Product Manager

---

## Operations/SRE and Support Representatives

### Role Summary
Operations/SRE and Support Representatives help ensure that delivered services can be operated, monitored, and supported effectively. The relevant capability may be provided by an operations engineer, SRE, support representative, or a combination.

### Responsibilities
- Define operational readiness needs, including monitoring, alerting, runbooks, and support handoffs
- Identify reliability and support risks and recommend mitigations
- Contribute to release readiness and post-deployment verification planning
- Share operational or customer-support feedback to inform improvements

### Interactions with Existing Roles
- Partner with Developers and the Technical Lead on reliability, operability, and operational design
- Coordinate with QA/Testing on deployment and operational validation
- Work with the Project Manager to track readiness requirements, risks, and release dependencies
- Collaborate with the Product Manager and stakeholders on support impacts and customer communications
- Participate in incident response and follow-up through the established incident process

### Typical Artifacts and Decision Boundaries
- Readiness checklists, monitoring and alerting requirements, runbooks, support guidance, and operational feedback
- Advise on readiness and operational risk; deployment and incident decisions follow the team's established ownership and escalation process

---

## Role Collaboration Across the Project Lifecycle

- **Planning:** The Product Manager owns product outcomes and priority. The Project Manager coordinates the plan, milestones, risks, and dependencies. Relevant design, technical, security/privacy, analytics, and operations/support roles identify their requirements and dependencies early.
- **Execution:** Developers implement the agreed work, with design and technical specialists collaborating on experience and engineering decisions. Security/privacy requirements and measurement needs are built and validated with the relevant specialists and QA/Testing.
- **Release:** The Project Manager coordinates readiness and communication. Developers, QA/Testing, and Operations/SRE or Support verify the agreed technical, quality, and operational requirements; the Product Manager confirms product acceptance and stakeholder needs.
- **Retrospective:** The team reviews outcomes, incidents, feedback, and delivery learnings. Each role contributes relevant evidence and helps define follow-up actions with clear owners.

These roles are intended to clarify capabilities, handoffs, and consultation—not to add mandatory approval layers. Each project should identify who is accountable for a needed capability and how decisions or escalations are made.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
