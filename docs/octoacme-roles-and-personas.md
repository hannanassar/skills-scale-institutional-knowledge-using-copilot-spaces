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

## Product Owner

### Role Summary
Product Owners bridge the gap between business stakeholders and the development team. They define detailed product requirements, maintain the prioritized backlog, and make day-to-day trade-off decisions to maximize business value.

### Responsibilities
- Define and refine user stories and acceptance criteria
- Prioritize the product backlog based on business value and dependencies
- Accept completed work and validate it meets requirements
- Communicate with stakeholders and gather feedback
- Make trade-off decisions regarding scope, timeline, and resources
- Participate in sprint planning, reviews, and retrospectives

### Goals
- Deliver features that maximize business value and customer satisfaction
- Maintain a clear, prioritized backlog that enables team efficiency
- Ensure transparency between business and engineering teams
- Enable faster feedback loops and course corrections

### Interactions with Other Roles
- **With Project Manager**: Collaborates on scheduling, capacity planning, and stakeholder communication
- **With Developers**: Provides requirements clarity, feedback on implementation, and acceptance decisions
- **With Technical Lead**: Discusses technical feasibility and trade-offs during planning
- **With QA Lead**: Defines acceptance criteria and validates quality standards

### Typical Communication
- Backlog grooming sessions and sprint planning meetings
- Daily standups and sprint reviews
- Stakeholder updates and feedback sessions
- Written user stories and acceptance criteria in tracking tools

---

## Technical Lead/Architect

### Role Summary
Technical Leads establish technical direction, make architecture decisions, and ensure the system is designed for scalability, maintainability, and performance. They mentor developers and guide technical strategy.

### Responsibilities
- Define technical architecture and design patterns
- Conduct technical design reviews and provide guidance
- Make strategic technology decisions and evaluate trade-offs
- Identify and mitigate technical risks
- Mentor developers and promote best practices
- Ensure code quality, performance, and system reliability
- Participate in capacity planning and estimation

### Goals
- Build scalable, maintainable systems that support business growth
- Reduce technical debt and improve system quality
- Enable the team to deliver with high velocity and confidence
- Foster a culture of technical excellence

### Interactions with Other Roles
- **With Project Manager**: Provides technical feasibility assessments and risk identification
- **With Developers**: Reviews designs, mentors on best practices, and unblocks technical issues
- **With Product Owner**: Discusses technical trade-offs and feasibility of requirements
- **With QA Lead**: Ensures testability and quality standards are built into design

### Typical Communication
- Technical design documents and architecture decision records (ADRs)
- Code reviews and design review meetings
- Technical discussions during sprint planning
- Risk registers and mitigation plans

---

## Quality Assurance Lead

### Role Summary
Quality Assurance Leads establish quality standards, define testing strategies, and ensure delivered software meets functional and non-functional requirements. They work throughout the project lifecycle to prevent defects and validate quality.

### Responsibilities
- Define QA strategy and test plans for projects
- Establish quality metrics and acceptance standards
- Design and execute test cases and test automation
- Manage defect triage, prioritization, and tracking
- Collaborate on acceptance criteria definition
- Perform risk-based testing and identify coverage gaps
- Report on quality status and metrics

### Goals
- Deliver high-quality software that meets all requirements
- Detect issues early to reduce cost of fixes
- Build confidence in release readiness
- Continuously improve testing efficiency and coverage

### Interactions with Other Roles
- **With Developers**: Provides test requirements, reports defects, and collaborates on testability
- **With Product Owner**: Validates acceptance criteria and confirms feature readiness
- **With Release Manager**: Certifies quality readiness for production deployment
- **With Technical Lead**: Ensures testing strategy aligns with technical architecture

### Typical Communication
- Test plans and test case documentation
- Defect reports and quality metrics dashboards
- Sprint reviews and QA status updates
- Release readiness reviews and sign-offs

---

## Release Manager

### Role Summary
Release Managers coordinate and execute software releases to production. They manage release planning, deployment sequences, environment management, and ensure smooth, low-risk transitions from development to production.

### Responsibilities
- Create and maintain release plans and deployment schedules
- Manage release candidates, versioning, and release notes
- Coordinate deployment activities across environments
- Manage configuration, rollback procedures, and contingency plans
- Ensure proper testing and validation before production deployment
- Communicate release status to stakeholders and customers
- Monitor and validate post-deployment health

### Goals
- Execute releases with minimal risk and disruption
- Reduce time-to-market while maintaining system stability
- Maintain clear communication and transparency around releases
- Enable rapid issue resolution if problems occur

### Interactions with Other Roles
- **With Developers**: Coordinates code merge and deployment activities
- **With QA Lead**: Validates quality certification before release approval
- **With Project Manager**: Ensures release timeline and stakeholder communication
- **With Operations/Infrastructure**: Coordinates environment setup and deployment execution

### Typical Communication
- Release plans and deployment schedules
- Release notes and change logs
- Deployment coordination meetings
- Post-deployment validation and monitoring reports

---

## Stakeholder Representative

### Role Summary
Stakeholder Representatives serve as the voice of the business, customers, and other interested parties in the project. They gather requirements, provide feedback, and ensure project outcomes align with business objectives.

### Responsibilities
- Gather and articulate business requirements and priorities
- Provide feedback on prototypes, designs, and delivered features
- Ensure project outcomes align with business strategy and goals
- Communicate project status and results to business leadership
- Facilitate decision-making on scope, schedule, and budget trade-offs
- Validate that solutions address the original business problem
- Support change management and stakeholder engagement

### Goals
- Ensure delivered solutions provide business value and ROI
- Maintain stakeholder alignment and engagement throughout the project
- Enable informed decision-making on project trade-offs
- Support successful adoption and realization of project benefits

### Interactions with Other Roles
- **With Project Manager**: Partners on scheduling, status reporting, and stakeholder management
- **With Product Owner**: Provides business context and validates product decisions
- **With Developers**: Reviews progress and provides domain expertise feedback
- **With QA Lead**: Participates in user acceptance testing (UAT) and validation

### Typical Communication
- Requirements workshops and business analysis sessions
- Project status reviews and stakeholder briefings
- User acceptance testing (UAT) sessions
- Executive summaries and business impact reports

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction patterns to understand how different roles collaborate throughout the project lifecycle.
