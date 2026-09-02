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
- Partner with **Technical Leads** on complex architectural decisions
- Collaborate with **QA Lead** on test strategy and acceptance criteria
- Report blockers and risks to **Project Managers**
- Implement requirements defined by **Product Managers**

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
- Align with **Stakeholders/Sponsors** on strategic priorities
- Work with **Project Managers** on delivery timelines
- Define acceptance criteria with **QA Lead** and **Developers**
- Coordinate with **Technical Lead** on feasibility and trade-offs

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
- Report status and risks to **Stakeholders/Sponsors**
- Coordinate with **Technical Lead** on dependency management
- Work with **QA Lead** on test schedules and quality gates
- Facilitate communication across all team members

---

## QA / Quality Assurance Lead

### Role Summary
Owns quality strategy, test planning, and validation for delivered features. Ensures features meet acceptance criteria and quality standards before production release.

### Responsibilities
- Define acceptance criteria and test strategy with product and development teams
- Create and maintain comprehensive test plans (unit, integration, end-to-end, security)
- Coordinate manual QA when needed
- Validate release readiness and provide quality sign-off on deployments
- Track quality metrics and defects
- Identify and escalate quality risks

### Goals
- Ensure features meet acceptance criteria and quality standards before production
- Minimize defects reaching production
- Maintain consistent quality standards across all releases
- Enable rapid, confident deployments

### Typical Communication
- Sprint planning sessions and backlog refinement
- PR reviews for testability and test coverage
- Quality metrics reporting and dashboard updates
- QA sign-offs during release preparation
- Post-deployment verification and incident response

### Interaction with Other Roles
- Partner with **Developers** on test strategy and code coverage
- Work with **Product Managers** to define acceptance criteria
- Collaborate with **Technical Lead** on testing architecture and automation
- Provide quality gates and sign-offs to **Project Managers**
- Support **Operations Lead** with smoke test procedures and monitoring setup

---

## Technical Lead / Architecture Lead

### Role Summary
Senior developer or architect who provides technical guidance, design review, and escalation for complex technical decisions. Ensures systems are scalable, maintainable, and aligned with best practices.

### Responsibilities
- Review technical designs and architectural trade-offs
- Identify technical risks and propose mitigations
- Guide code quality standards and establish review practices
- Support estimation and capacity planning
- Mentor developers on complex technical problems
- Lead design reviews and architecture discussions
- Advocate for technical excellence and debt reduction

### Goals
- Maintain high code quality and reduce technical debt
- Ensure system scalability and performance
- Support team growth and capability development
- Enable sustainable, rapid delivery

### Typical Communication
- Design reviews and architectural decision documentation
- Technical escalations and guidance for complex problems
- Code review expectations and quality standards
- Mentoring and skill development discussions
- Architecture decisions and technology choices

### Interaction with Other Roles
- Guide **Developers** on technical best practices and design
- Collaborate with **Product Managers** on feasibility and technical trade-offs
- Support **QA Lead** on test automation and testing architecture
- Advise **Project Managers** on technical risks and mitigation
- Work with **Operations Lead** on deployability and operational concerns

---

## Security / Compliance Lead

### Role Summary
Ensures projects meet security, compliance, and data governance requirements. Protects customer data and maintains regulatory compliance posture throughout the project lifecycle.

### Responsibilities
- Review security scanning and vulnerability findings in CI/CD pipelines
- Advise on data protection and compliance requirements
- Participate in threat modeling for sensitive features
- Provide security sign-off on releases and deployments
- Respond to security incidents following incident runbooks
- Establish and enforce security best practices
- Conduct security reviews during design and planning phases

### Goals
- Protect customer data and system integrity
- Maintain compliance with regulatory requirements
- Enable secure feature delivery without slowing innovation
- Build security awareness and best practices across the team

### Typical Communication
- Design reviews for security-sensitive features
- CI/CD scan results and vulnerability reporting
- Pre-release security approvals and sign-offs
- Security incident response and post-incident reviews
- Security training and awareness updates
- Compliance audit preparation and documentation

### Interaction with Other Roles
- Review designs with **Technical Lead** and **Developers**
- Advise **Product Managers** on security implications of features
- Provide security gates and sign-offs to **Project Managers**
- Coordinate with **Operations Lead** on security monitoring and incident response
- Report security status to **Stakeholders/Sponsors**

---

## Operations / DevOps Lead

### Role Summary
Manages deployment infrastructure, monitoring, and operational readiness. Ensures reliable, observable deployments and enables rapid incident response and recovery.

### Responsibilities
- Oversee CI/CD pipeline configuration, reliability, and security
- Plan and execute deployments to production
- Set up monitoring, alerting, and dashboards for new features
- Prepare rollback and mitigation procedures
- Support incident response and post-incident learning
- Maintain operational runbooks and playbooks
- Plan capacity and infrastructure needs

### Goals
- Ensure reliable, observable deployments to production
- Enable rapid incident detection and response
- Minimize deployment risk and downtime
- Support team visibility into system health and performance

### Typical Communication
- Release planning and deployment window coordination
- Post-deploy verification and monitoring setup
- Incident response and escalation
- Operational metrics and SLO reporting
- Infrastructure capacity and scaling discussions
- Runbook and playbook reviews

### Interaction with Other Roles
- Coordinate deployment timelines with **Project Managers**
- Work with **Technical Lead** on deployability and operational concerns
- Collaborate with **QA Lead** on smoke tests and deployment verification
- Coordinate with **Security Lead** on security monitoring and incident response
- Support **Developers** with deployment tooling and diagnostics
- Report operational status to **Stakeholders/Sponsors**

---

## Stakeholder / Sponsor

### Role Summary
Executive or business stakeholder who provides funding, strategic direction, and approval authority for projects. Represents business interests and ensures project alignment with organizational goals.

### Responsibilities
- Approve go/no-go decisions at project initiation and major gates
- Provide strategic context and business constraints
- Ensure project alignment with business objectives and ROI
- Escalate blockers at the sponsor level
- Attend and provide input on key milestone reviews and gate decisions
- Support and remove organizational barriers
- Approve budget and resource allocation

### Goals
- Ensure project delivers business value and meets ROI targets
- Maintain alignment between project and business strategy
- Enable team success through resource and organizational support
- Make timely, informed decisions on project direction

### Typical Communication
- Monthly stakeholder updates and status reviews
- Project initiation approval and gate reviews
- Escalation for blockers and business decisions
- Strategic alignment discussions
- Budget and resource approval
- Release announcements and success celebrations

### Interaction with Other Roles
- Provide approval and strategic direction to **Project Managers**
- Align on success metrics and priorities with **Product Managers**
- Receive escalations and risk reports from **Project Managers**
- Review progress and results from delivery teams
- Support organizational enablement for **Developers** and cross-functional team

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference these personas when creating project documentation, communication plans, and escalation paths.
- Use the "Interaction with Other Roles" sections to understand cross-functional dependencies and communication flows.
