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

## QA/Testing Lead

### Role Summary
QA/Testing Leads design and execute quality assurance strategies. They ensure features meet acceptance criteria, identify defects early, and validate readiness for release. They collaborate with product and development teams to define testability requirements and success measures.

### Responsibilities
- Define test strategy and test plan for features and releases
- Create and maintain automated test suites (unit, integration, E2E)
- Perform manual testing and acceptance validation against criteria
- Identify and triage defects; coordinate fixes with developers
- Participate in sprint planning to ensure Definition of Done includes testability
- Validate smoke tests and post-deployment verification
- Report quality metrics and testing coverage

### Goals
- Catch defects early and reduce production issues
- Enable fast, confident releases
- Maintain high quality and customer satisfaction

### Typical Communication
- Sprint planning and backlog refinement
- Test case reviews with developers
- Defect discussions and prioritization with development team
- Quality metrics in status reports to Project Manager and Product Manager

### Interaction with Other Roles
- **Works with Developers** to define testability requirements and review test cases
- **Collaborates with Product Managers** to validate acceptance criteria and prioritize defect fixes
- **Supports Project Managers** with quality metrics for release readiness decisions
- **Partners with Technical Leads** on test architecture and performance testing strategies

---

## Technical Lead/Architect

### Role Summary
Technical Leads own the technical direction and design of projects. They guide architectural decisions, conduct design reviews, mentor developers, and identify and mitigate technical risks.

### Responsibilities
- Define system architecture and technology choices
- Conduct technical design reviews for major features
- Mentor developers on best practices and code quality
- Identify technical risks and propose mitigations
- Contribute to estimation and feasibility assessments
- Ensure adherence to coding standards and test coverage
- Support incident response and post-mortems

### Goals
- Deliver scalable, maintainable, secure systems
- Reduce technical debt and rework
- Accelerate development velocity through good design

### Typical Communication
- Technical design discussions and reviews
- Architecture decision records (ADRs)
- Code review feedback and mentoring sessions
- Risk discussions in planning and weekly syncs

### Interaction with Other Roles
- **Guides Developers** on technical design decisions and best practices
- **Advises Project Managers** on technical feasibility and risk mitigation
- **Partners with QA/Testing Leads** on testability and performance requirements
- **Works with DevOps Engineers** on operational and deployment architecture
- **Supports Product Managers** on technical feasibility of feature proposals

---

## Scrum Master/Iteration Facilitator

### Role Summary
Scrum Masters facilitate Agile ceremonies, coach the team on Agile practices, and remove impediments to delivery. They foster a culture of continuous improvement and psychological safety.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove blockers and impediments identified by the team
- Coach team members on Agile principles and practices
- Track sprint progress and manage the sprint board
- Identify process improvements and drive adoption
- Escalate impediments that require leadership attention

### Goals
- Maintain team velocity and predictable delivery
- Foster a psychologically safe, high-performing team
- Continuously improve delivery processes

### Typical Communication
- Sprint ceremonies and daily standups
- One-on-one coaching and mentoring
- Retrospective facilitation and action tracking
- Escalation summaries to Project Manager

### Interaction with Other Roles
- **Supports the Project Manager** in sprint execution and escalation
- **Coaches all team members** (Developers, QA, Technical Leads) on Agile practices
- **Works with Product Manager** to ensure backlog is ready for sprint planning
- **Reports to Project Manager** on team health, velocity, and process improvements

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders provide business context, funding, and strategic direction for projects. Sponsors have authority to make trade-off decisions and remove organizational barriers.

### Responsibilities
- Provide business context and success criteria alignment
- Approve project scope, timeline, and resource allocation
- Make trade-off decisions when priorities conflict
- Remove organizational and cross-team blockers
- Communicate project status to executive leadership
- Validate outcomes and measure business impact

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment between project objectives and business strategy
- Enable team success by removing barriers

### Typical Communication
- Monthly stakeholder updates and business reviews
- Milestone approvals and gate reviews
- Escalation decisions and prioritization discussions
- Post-release retrospectives and impact assessment

### Interaction with Other Roles
- **Partners with Project Manager** for status updates and escalation authority
- **Aligns with Product Manager** on business objectives and success metrics
- **Provides guidance to Development Team** on business priorities and constraints
- **Reviews release impact** with the full project team

---

## DevOps/Infrastructure Engineer

### Role Summary
DevOps Engineers design, implement, and maintain the infrastructure and deployment pipelines that enable reliable, scalable production operations. They bridge development and operations to ensure smooth deployments and system reliability.

### Responsibilities
- Design and maintain infrastructure for development, staging, and production environments
- Build and optimize deployment pipelines and CI/CD workflows
- Monitor system health, performance, and uptime
- Manage secrets, access control, and security configurations
- Coordinate and execute production deployments
- Prepare and execute rollback plans when needed
- Support incident response and post-incident reviews

### Goals
- Enable fast, reliable, and safe deployments
- Maintain high system availability and performance
- Reduce deployment friction and lead time

### Typical Communication
- Release planning and deployment coordination
- Infrastructure design reviews with Technical Leads
- Deployment checklists and post-deploy verification
- Incident response and status updates

### Interaction with Other Roles
- **Collaborates with Technical Leads** on architecture and scalability decisions
- **Coordinates with Developers** on local development environment setup and CI/CD integration
- **Partners with QA/Testing Leads** on environment provisioning for testing
- **Reports to Project Manager** on deployment readiness and operational risks
- **Supports Sponsors** with post-release monitoring and incident escalation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interaction with Other Roles" sections to understand cross-functional dependencies and communication patterns.
