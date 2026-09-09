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

### Interactions with Other Roles
- Collaborate with **QA/Testing Professionals** on acceptance criteria, test cases, and defect resolution
- Work with **Product Managers** to understand requirements and validate solutions
- Coordinate with **Project Managers** on schedule and dependency management
- Receive security guidance from **Security & Compliance Officers** on code review and architectural decisions
- Consult with **Stakeholders/SMEs** for domain expertise and validation

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

### Interactions with Other Roles
- Partner with **Product Leads** for strategic prioritization and approval of major decisions
- Work with **Project Managers** on timeline coordination and milestone planning
- Collaborate with **Developers** and **QA/Testing Professionals** on acceptance criteria and quality standards
- Engage **Stakeholders/SMEs** for requirements validation and user research
- Report outcomes and metrics to **Sponsors/Executive Stakeholders**

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

### Interactions with Other Roles
- Coordinate with **Product Managers** on priorities and scope
- Track progress with **Developers** and **QA/Testing Professionals**
- Escalate risks and blockers to **Product Leads** and **Sponsors**
- Communicate project status to **Stakeholders/SMEs** and other dependent teams
- Work with **Security & Compliance Officers** on security review schedules and incident management

---

## QA/Testing Professional

### Role Summary
QA and testing professionals ensure product quality through test planning, execution, and validation. They collaborate with developers and product teams to define acceptance criteria and verify that features meet quality standards.

### Responsibilities
- Develop and maintain test plans and test cases
- Execute manual and automated testing for acceptance criteria
- Identify and document defects with clear reproduction steps
- Coordinate end-to-end and smoke testing before releases
- Participate in defining Definition of Done with team
- Conduct security and performance testing as needed

### Goals
- Ensure zero critical bugs reach production
- Maintain high test coverage and quality standards
- Reduce cycle time through efficient test automation

### Typical Communication
- Sprint planning and backlog refinement
- Defect reports and test result summaries
- Release coordination and smoke test execution
- QA metrics in weekly status updates

### Interactions with Other Roles
- Partner with **Developers** on test case design and defect resolution
- Align with **Product Managers** on acceptance criteria and feature validation
- Coordinate with **Project Managers** on testing schedules and release readiness
- Support **Security & Compliance Officers** on security and compliance testing
- Validate solutions with **Stakeholders/SMEs** for real-world usability
- Report quality status to **Product Leads** for release approval decisions

---

## Product Lead

### Role Summary
Product Leads provide senior product guidance, approve key decisions, and serve as escalation point for complex product trade-offs. They align cross-functional teams and ensure solutions meet strategic objectives.

### Responsibilities
- Review and approve project one-pagers and success metrics
- Make strategic prioritization decisions and trade-offs
- Serve as escalation path for product/scope questions
- Align stakeholders on product vision and roadmap
- Guide product strategy and long-term planning
- Approve major release decisions

### Goals
- Ensure product strategy is cohesive and customer-focused
- Remove blockers through timely decision-making
- Maintain strategic alignment across the organization

### Typical Communication
- Weekly PM + PdM syncs
- Stakeholder updates and roadmap reviews
- Escalation meetings for major decisions
- Design and strategy reviews

### Interactions with Other Roles
- Mentor and guide **Product Managers** on strategic decisions
- Escalate complex decisions from **Project Managers** and resolve blockers
- Review technical proposals from **Developers** with strategic implications
- Approve quality and release decisions from **QA/Testing Professionals**
- Align **Sponsors/Executive Stakeholders** on product direction
- Incorporate feedback from **Stakeholders/SMEs** into strategic planning

---

## Sponsor/Executive Stakeholder

### Role Summary
Sponsors are senior business stakeholders or executives who provide strategic direction, secure resources, and approve major decisions. They represent business interests and drive project prioritization.

### Responsibilities
- Approve project initiation and resource allocation
- Provide business context and strategic priorities
- Serve as final escalation path for business-impacting issues
- Review milestone completion and release decisions
- Support removal of organizational blockers

### Goals
- Ensure projects deliver business value
- Enable cross-organizational alignment
- Make timely strategic decisions

### Typical Communication
- Monthly stakeholder updates
- Project milestone reviews
- Executive escalations for critical issues
- Approvals on project charter and major decisions

### Interactions with Other Roles
- Receive strategic recommendations from **Product Leads** on major initiatives
- Review project status and outcomes from **Project Managers**
- Get updates on product vision and metrics from **Product Managers**
- Approve resource allocation and major scope changes recommended by **Project Leads**
- Serve as final escalation for critical risks from any team member
- Provide business context and priorities to guide all team decisions

---

## Security & Compliance Officer

### Role Summary
Security and compliance professionals ensure products meet security requirements, pass security scanning, and incidents are handled appropriately. They work with teams to embed security throughout the development lifecycle.

### Responsibilities
- Define security requirements for projects
- Conduct security reviews and architecture assessments
- Configure and monitor security scanning in CI/CD
- Lead security incident response and investigation
- Maintain compliance with organizational and regulatory standards
- Provide security best practices guidance

### Goals
- Prevent security vulnerabilities reaching production
- Maintain compliance and regulatory alignment
- Embed security practices into team culture

### Typical Communication
- Security review gates during planning and release
- CI/CD security scanning results
- Security incident escalations and post-mortems
- Architecture and design reviews

### Interactions with Other Roles
- Partner with **Developers** on secure coding practices and architecture reviews
- Define security acceptance criteria with **Product Managers**
- Coordinate security review gates with **Project Managers**
- Guide **QA/Testing Professionals** on security and compliance testing
- Report security posture and compliance status to **Product Leads** and **Sponsors**
- Provide security requirements to **Stakeholders/SMEs** for their domain

---

## Stakeholder/Subject Matter Expert (SME)

### Role Summary
Stakeholders and SMEs provide domain expertise, requirements input, and feedback throughout the project lifecycle. They represent end-user needs and business context.

### Responsibilities
- Provide requirements and domain expertise
- Validate proposed solutions against real-world scenarios
- Participate in user research and acceptance testing
- Offer feedback on deliverables and usability
- Support communication with their functional areas

### Goals
- Ensure solutions address real business and user needs
- Bridge gap between delivery team and end users
- Improve feature adoption and usability

### Typical Communication
- Project kickoff and requirement gathering sessions
- Design and feature reviews
- User acceptance testing
- Stakeholder updates and feedback sessions

### Interactions with Other Roles
- Provide domain expertise and requirements to **Product Managers** during discovery
- Review and validate solutions with **Developers** and **QA/Testing Professionals**
- Participate in user acceptance testing coordinated by **Project Managers**
- Inform security and compliance requirements with **Security & Compliance Officers**
- Provide feedback to **Product Leads** on strategic fit and market viability
- Advise **Sponsors** on business impact and end-user needs

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The interaction matrix across roles illustrates how OctoAcme projects succeed through cross-functional collaboration and clear communication.
