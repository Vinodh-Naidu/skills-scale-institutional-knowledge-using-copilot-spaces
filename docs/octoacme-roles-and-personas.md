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

### Interactions
- **Product Managers**: Receive acceptance criteria and prioritization guidance
- **Project Managers**: Coordinate schedules and dependency management
- **QA Lead**: Collaborate on test strategy and acceptance validation
- **Technical Program Manager**: Align on technical sequencing and risk mitigation

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Define acceptance criteria and feature specifications

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs
- Data analysis and metrics reviews

### Interactions
- **Project Managers**: Align on roadmap, priorities, and stakeholder communication
- **UX Researcher/Designer**: Incorporate user research into prioritization
- **Data Analyst**: Review success metrics and feature impact
- **Customer Success Liaison**: Incorporate customer feedback into backlog

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

### Interactions
- **Product Managers**: Align on roadmap, priorities, and stakeholder updates
- **Release Manager**: Coordinate release planning and deployment windows
- **Technical Program Manager**: Manage cross-team dependencies
- **All delivery teams**: Facilitate coordination and remove impediments

---

## Release Manager

### Role Summary
Release Managers coordinate all aspects of preparing software for production, including planning, testing, deployment scheduling, and post-release verification. They ensure releases are executed smoothly and include rollback preparedness.

### Responsibilities
- Create and maintain release runbooks and deployment playbooks
- Coordinate release planning, including deployment windows and go/no-go decisions
- Prepare and communicate release notes
- Coordinate smoke testing and post-deployment verification
- Document and execute rollback procedures in case of issues
- Track release metrics and status across environments

### Goals
- Ensure predictable, low-risk deployments to production
- Minimize deployment-related incidents and rework
- Enable rapid rollback if critical issues are discovered
- Maintain clear communication with all stakeholders during releases

### Typical Communication
- Release planning meetings and deployment window coordination
- Pre-release checklists and sign-offs
- Post-deployment verification reports
- Incident communication (if rollback is needed)

### Interactions
- **Project Manager**: Coordinate release scheduling and timeline
- **DevOps / Platform Engineer**: Execute deployments and monitor infrastructure
- **QA Lead**: Coordinate smoke testing and release validation
- **Product Managers**: Review release impact and customer communication
- **Customer Success Liaison**: Coordinate customer notifications and support runbooks

---

## Technical Program Manager (TPM)

### Role Summary
Technical Program Managers manage the coordination and sequencing of large, complex initiatives that span multiple teams, systems, or technical domains. They identify technical dependencies, manage risk, and keep cross-team programs on track.

### Responsibilities
- Map cross-team technical dependencies and sequencing
- Identify and escalate technical risks and blockers
- Facilitate architecture and design discussions across teams
- Create and maintain release interdependency tracking
- Monitor program health and track key milestones
- Communicate technical program status to stakeholders

### Goals
- Ensure technical initiatives deliver on schedule and within scope
- Minimize delays caused by dependencies or technical risks
- Keep all teams aligned on priorities and technical direction
- Enable efficient resource allocation across programs

### Typical Communication
- Weekly cross-team syncs and dependency reviews
- Technical risk registers and escalation communications
- Program health dashboards and milestone tracking
- Architecture and design collaboration sessions

### Interactions
- **Project Managers**: Align on program timelines and milestone tracking
- **Developers & Tech Leads**: Understand technical constraints and dependencies
- **DevOps / Platform Engineers**: Coordinate infrastructure and deployment requirements
- **Security Liaison**: Incorporate security and compliance requirements early

---

## Delivery Lead

### Role Summary
Delivery Leads coordinate day-to-day work within a delivery squad or team, removing impediments and ensuring work meets the Definition of Done. They serve as the operational hub for their team's execution.

### Responsibilities
- Plan and schedule sprint/iteration work
- Remove day-to-day blockers and impediments
- Ensure work items meet Definition of Done before completion
- Facilitate daily standups and iteration planning/review
- Track work progress and identify at-risk items early
- Escalate risks and dependencies to Project Manager

### Goals
- Keep the team focused and productive
- Deliver predictable velocity and quality
- Minimize context-switching and unplanned work
- Foster team collaboration and psychological safety

### Typical Communication
- Daily standups
- Sprint planning and retrospectives
- Blocker resolution and escalation
- Status updates to Project Manager

### Interactions
- **Project Manager**: Escalate risks, dependencies, and resource needs
- **Developers**: Remove blockers and facilitate collaboration
- **QA Lead**: Coordinate testing and acceptance criteria validation
- **Product Manager**: Clarify priorities and acceptance criteria

---

## QA Lead / Test Engineer

### Role Summary
QA Leads define and execute testing strategies to validate software quality and ensure features meet acceptance criteria. They collaborate with developers, product managers, and release managers throughout the software lifecycle.

### Responsibilities
- Define test strategy and approach for initiatives
- Coordinate automated and manual testing efforts
- Create and maintain test plans and test cases
- Sign off on acceptance criteria validation
- Identify and triage quality issues and regressions
- Coordinate testing in staging and production environments
- Provide quality metrics and trend reporting

### Goals
- Ensure software meets quality and acceptance standards before release
- Reduce production defects and rework
- Enable rapid, confidence-building releases
- Continuously improve testing efficiency and coverage

### Typical Communication
- Test planning and strategy discussions
- Quality metrics and defect reports
- Release validation and sign-off communications
- Regression and issue triage meetings

### Interactions
- **Developers**: Collaborate on test coverage and testability
- **Product Managers**: Validate acceptance criteria and feature behavior
- **Release Manager**: Coordinate smoke testing and release validation
- **QA team members**: Coordinate test execution and result analysis

---

## Security Liaison

### Role Summary
Security Liaisons serve as the point of contact for security reviews, threat modeling, and vulnerability remediation. They integrate security practices into the development lifecycle and coordinate with security teams.

### Responsibilities
- Conduct or coordinate security reviews for new features
- Participate in threat modeling and design discussions
- Identify and prioritize security vulnerabilities
- Coordinate vulnerability remediation and patching
- Ensure security scanning is integrated into CI/CD
- Communicate security requirements and constraints to teams
- Track security compliance and policy adherence

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure regulatory and compliance requirements are met
- Foster security awareness across all teams
- Enable rapid remediation when issues are discovered

### Typical Communication
- Security design reviews and threat modeling sessions
- Vulnerability reports and remediation tracking
- Security scanning and compliance results
- Incident communication (if security issues are discovered)

### Interactions
- **Technical Program Manager**: Integrate security requirements into program planning
- **Developers**: Review code and architecture for security best practices
- **Release Manager**: Validate security scanning before production release
- **DevOps / Platform Engineer**: Ensure secure infrastructure and deployment practices

---

## DevOps / Platform Engineer

### Role Summary
DevOps and Platform Engineers build and maintain the infrastructure, CI/CD pipelines, monitoring, and automation that enable reliable software delivery. They ensure production systems are observable, secure, and scalable.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Provision and manage production infrastructure
- Implement monitoring, alerting, and observability tools
- Create and maintain deployment runbooks and automation
- Troubleshoot production incidents and performance issues
- Document infrastructure architecture and operational procedures
- Ensure infrastructure security and compliance

### Goals
- Enable fast, reliable deployments with minimal manual work
- Maintain high production system availability and performance
- Provide visibility into system health and metrics
- Reduce incident response time and impact

### Typical Communication
- Infrastructure and deployment planning meetings
- Monitoring and observability reviews
- Incident response and post-mortems
- Capacity planning and performance optimization discussions

### Interactions
- **Release Manager**: Execute deployments and coordinate release windows
- **Developers**: Support local development environment setup and CI/CD integration
- **Technical Program Manager**: Coordinate infrastructure requirements for complex programs
- **Security Liaison**: Implement secure infrastructure and compliance controls

---

## Data Analyst / Instrumentation Owner

### Role Summary
Data Analysts and Instrumentation Owners define, implement, and maintain the metrics and instrumentation that track product health, user behavior, and business impact. They enable data-driven decision-making across the organization.

### Responsibilities
- Define success metrics and KPIs for initiatives
- Implement instrumentation and event tracking in code
- Validate data quality and pipeline integrity
- Create dashboards and reports for stakeholders
- Analyze trends and provide actionable insights
- Maintain data documentation and metric definitions
- Support incident analysis and post-mortems with data

### Goals
- Enable data-driven product and business decisions
- Provide real-time visibility into product health and user behavior
- Reduce time to insight from data collection to analysis
- Ensure data quality and reliability

### Typical Communication
- Metrics definition and requirements gathering
- Dashboard and report creation for stakeholders
- Data quality and pipeline health reviews
- Post-release impact analysis and trend discussions

### Interactions
- **Product Managers**: Define metrics and review impact analysis
- **Developers**: Implement instrumentation and track data quality
- **Release Manager**: Validate metrics availability before and after releases
- **Technical Program Manager**: Aggregate metrics across complex programs

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers conduct user research, define user experience requirements, and validate the usability and accessibility of features. They ensure products are designed with customer needs and best practices in mind.

### Responsibilities
- Conduct user research to understand customer needs and behaviors
- Create wireframes, prototypes, and design specifications
- Define UX acceptance criteria and usability standards
- Validate feature usability through user testing
- Ensure accessibility and inclusive design standards are met
- Review designs and implementations for UX best practices
- Provide design guidance and recommendations to teams

### Goals
- Deliver intuitive, usable products that delight customers
- Reduce support burden through better design
- Ensure accessibility for all users
- Continuously improve user experience through research and feedback

### Typical Communication
- User research findings and insights
- Design specifications and wireframes
- Usability testing and validation feedback
- Design review and feedback discussions

### Interactions
- **Product Managers**: Incorporate research and design into prioritization
- **Developers**: Provide design specifications and implementation guidance
- **QA Lead**: Validate UX acceptance criteria
- **Customer Success Liaison**: Gather customer feedback and pain points

---

## Customer Success / Support Liaison

### Role Summary
Customer Success and Support Liaisons serve as the voice of the customer within the development process. They bring customer feedback into product decisions, prepare support teams for new features, and coordinate customer communications.

### Responsibilities
- Gather and communicate customer feedback and requests
- Identify customer pain points and support burdens
- Prepare support runbooks and troubleshooting guides for new features
- Coordinate customer communications and announcements
- Provide early access and training to support teams
- Track and report on customer-related metrics and satisfaction
- Triage and escalate critical customer issues

### Goals
- Ensure customer needs are heard and incorporated into product decisions
- Reduce customer support burden and improve satisfaction
- Enable support teams to quickly assist customers
- Build strong relationships and loyalty with customers

### Typical Communication
- Customer feedback and pain point discussions
- Support runbook preparation and training
- Customer announcement and communication coordination
- Customer satisfaction and issue escalation reporting

### Interactions
- **Product Managers**: Provide customer feedback for prioritization
- **Release Manager**: Coordinate customer announcements and support preparation
- **Developers**: Provide early access to features for support team training
- **UX Researcher**: Gather customer pain points and usability feedback

---

## Business Analyst

### Role Summary
Business Analysts translate business requirements and customer needs into clear, actionable user stories and acceptance criteria. They bridge the gap between business stakeholders and delivery teams.

### Responsibilities
- Gather and analyze business requirements from stakeholders
- Translate requirements into user stories with clear acceptance criteria
- Clarify ambiguities and edge cases before development begins
- Validate that delivered solutions meet business requirements
- Create process flows and business logic documentation
- Support requirement refinement and scope discussions
- Participate in testing and acceptance validation

### Goals
- Deliver solutions that meet business requirements and customer needs
- Reduce rework caused by unclear or misunderstood requirements
- Enable teams to build the right thing first time
- Maintain clear traceability between business needs and delivery

### Typical Communication
- Requirements gathering and refinement meetings
- User story creation and acceptance criteria definition
- Process flow and documentation review
- Acceptance testing and requirement validation

### Interactions
- **Product Managers**: Understand business strategy and priorities
- **Developers**: Clarify technical feasibility and implementation approach
- **Project Manager**: Coordinate requirements and scope management
- **QA Lead**: Define acceptance criteria validation and testing approach

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the **Interactions** section to understand how roles collaborate and depend on each other.
- Use the RACI mapping below for common OctoAcme activities.

---

## RACI Mapping for Common Activities

| Activity | PM | PdM | Dev | QA | Delivery | TPM | Release | DevOps | Security | Data | UX | Support | BA |
|----------|----|----|-----|----|---------|----|---------|--------|----------|------|----|---------|----|----------|
| Project Planning | A | C | I | C | C | R | I | I | I | I | I | I | C |
| Design & Architecture | C | C | R | I | I | C | I | C | C | I | C | I | I |
| Acceptance Criteria | I | R | C | C | C | I | I | I | I | I | C | I | R |
| Estimation & Scheduling | R | I | C | I | C | C | I | I | I | I | I | I | C |
| Development | I | I | R | I | C | I | I | C | I | I | I | I | I |
| Testing & QA | I | I | C | R | C | I | I | I | I | I | C | I | C |
| Security Review | I | I | C | I | I | C | I | C | R | I | I | I | I |
| Release Planning | C | C | I | I | I | C | R | C | C | I | I | I | I |
| Deployment | I | I | I | I | I | I | R | R | C | I | I | I | I |
| Post-Release Validation | I | C | I | C | I | I | R | C | I | R | I | I | I |
| Incident Response | I | I | C | I | I | I | C | R | C | I | I | R | I |
| Retrospective | R | C | C | I | C | I | I | I | I | I | I | I | I |

**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (ultimate authority/decision maker)
- **C** = Consulted (provides input)
- **I** = Informed (kept in the loop)