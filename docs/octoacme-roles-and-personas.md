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

## QA Lead / Quality Assurance Manager

### Role Summary
QA Leads own the quality strategy, testing approach, and acceptance validation for projects. They collaborate with Product and Project Managers to define quality standards and ensure features meet acceptance criteria before release.

### Responsibilities
- Define test plans and quality assurance approach for each project phase
- Establish acceptance criteria frameworks and quality gates
- Coordinate manual testing, automation strategy, and regression testing
- Validate features against acceptance criteria before PR merge and release
- Identify quality risks and blockers early
- Collaborate on Definition of Done to ensure testability requirements
- Participate in retrospectives to improve testing efficiency

### Goals
- Ensure features are released with high quality and minimal post-release defects
- Reduce cycle time by catching issues early through effective testing
- Build confidence in release readiness through comprehensive validation

### Typical Interactions
- **With Product Managers**: Refine acceptance criteria and prioritize test coverage
- **With Developers**: Review code for testability, participate in code reviews, collaborate on test automation
- **With Project Managers**: Report quality metrics, flag quality risks, coordinate testing schedules
- **With Technical Architects**: Ensure testing strategy aligns with architectural decisions
- **With Security Officers**: Define security testing requirements and validate security acceptance criteria

---

## Technical Architect

### Role Summary
Technical Architects provide technical guidance, evaluate design trade-offs, and identify architectural risks that impact project feasibility, timeline, and quality. They help teams make informed decisions about technology choices and system design.

### Responsibilities
- Assess technical feasibility and identify architectural risks during planning
- Review technical designs for scalability, maintainability, and security
- Provide guidance on technology choices and design patterns
- Identify technical dependencies and integration points
- Collaborate on Definition of Done to ensure architectural standards
- Mentor developers on best practices and technical standards
- Participate in code reviews for architecture-level decisions

### Goals
- Enable sustainable, scalable system design
- Reduce technical debt and rework through early risk identification
- Transfer knowledge and build team technical capability

### Typical Interactions
- **With Product Managers**: Advise on technical feasibility of feature requests
- **With Developers**: Provide design guidance, code review, mentorship
- **With Project Managers**: Communicate technical risks and dependencies that affect timeline
- **With QA Leads**: Ensure architectural decisions support testability and quality
- **With Security Officers**: Embed security considerations into system architecture

---

## Scrum Master / Iteration Lead

### Role Summary
Scrum Masters or Iteration Leads facilitate team ceremonies, remove blockers, and protect team capacity. They enable the team to work efficiently within the defined sprint/iteration rhythm and escalate impediments that require management intervention.

### Responsibilities
- Facilitate daily standups, sprint planning, sprint reviews, and retrospectives
- Track sprint progress and maintain the burndown chart
- Identify and help remove blockers and impediments
- Protect the team from scope creep and external interruptions
- Track team velocity and capacity
- Escalate risks and blockers to the Project Manager when appropriate
- Support the team in adhering to the Definition of Done and team agreements

### Goals
- Maintain steady, predictable team velocity
- Minimize time spent in blockers and unplanned work
- Foster team self-organization and continuous improvement

### Typical Interactions
- **With Developers**: Facilitate ceremonies, remove blockers, protect capacity
- **With Project Managers**: Escalate impediments, report team status, coordinate external dependencies
- **With Product Managers**: Facilitate backlog refinement and acceptance discussions
- **With QA Leads**: Coordinate testing schedules and quality metrics reporting

---

## Security Officer / Security Champion

### Role Summary
Security Officers or Security Champions embed security considerations into project execution. They ensure security requirements are captured in acceptance criteria, security risks are tracked in the risk register, and incident response procedures are followed.

### Responsibilities
- Identify security requirements and acceptance criteria for features
- Review designs and code for security risks and vulnerabilities
- Conduct security threat assessment during planning
- Ensure security testing is part of the Definition of Done
- Track security-related risks in the Risk Register
- Coordinate incident response and post-incident security reviews
- Provide security guidance to developers and testers

### Goals
- Ensure features are delivered securely without compromising user data or system integrity
- Reduce security-related incidents and vulnerabilities in production
- Build security awareness across the team

### Typical Interactions
- **With Developers**: Code review for security, provide security guidance
- **With QA Leads**: Define security testing strategy and acceptance criteria
- **With Project Managers**: Flag security risks, coordinate incident response
- **With Product Managers**: Ensure security requirements are included in feature definitions
- **With Technical Architects**: Review architectural decisions for security implications

---

## Sponsor / Stakeholder

### Role Summary
Sponsors and Stakeholders provide business context, strategic direction, and approval authority. They prioritize initiatives, allocate resources, and serve as the escalation point for business-impacting decisions.

### Responsibilities
- Define business objectives and success metrics for projects
- Prioritize project roadmap and resource allocation
- Approve project charter and major scope changes
- Serve as escalation point for business-level risks and decisions
- Provide stakeholder alignment and communication
- Review project status at regular intervals
- Make go/no-go decisions for releases and major milestones

### Goals
- Ensure projects deliver business value and align with strategy
- Make informed trade-off decisions between competing priorities
- Maintain transparency and stakeholder alignment

### Typical Interactions
- **With Project Managers**: Monthly status updates, risk escalation, resource decisions
- **With Product Managers**: Strategic direction, backlog prioritization, success metrics
- **With Delivery Teams**: Milestone reviews and release approvals
- **With Technical Architects**: Understand technical trade-offs and feasibility implications

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When working on projects, identify which personas are needed for your team and define interactions through the communication and responsibility patterns outlined above.
