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

## QA Lead

### Role Summary
QA Leads oversee the quality assurance and testing strategy for the project. They verify that deliverables meet quality standards, collaborate with developers and product owners to establish quality gates, and communicate test results to stakeholders.

### Responsibilities
- Define and maintain testing strategy and quality standards
- Oversee execution of test plans and quality assurance activities
- Collaborate with Developers to establish quality gates and acceptance criteria
- Identify defects, track resolution, and validate fixes
- Report quality metrics and test coverage to Project Manager and Product Manager
- Participate in release planning to ensure quality readiness

### Goals
- Ensure product meets quality standards before release
- Reduce defect escape rate and post-release issues
- Maintain test coverage and traceability
- Enable fast, confident releases

### Typical Communication
- Test status reports and quality metrics dashboards
- Collaboration with Developers during development and code reviews
- Quality gates review with Product Manager and Project Manager
- Release readiness assessments

### How QA Lead interacts with other roles
- **With Developers:** Partners to establish quality gates, reviews code quality, and validates fixes
- **With Product Manager:** Collaborates on acceptance criteria and quality requirements
- **With Project Manager:** Reports quality risks and readiness for release milestones

---

## Change Manager

### Role Summary
Change Managers manage the impact assessment and communication of major process, organizational, or technical changes. They coordinate between teams to ensure smooth transitions, reduce resistance, and document the rationale for changes.

### Responsibilities
- Assess impact of proposed changes on teams, processes, and systems
- Develop change communication and rollout plans
- Coordinate with Project Manager and Business Owner to prioritize and sequence changes
- Facilitate stakeholder alignment and address concerns
- Document change rationale, decisions, and lessons learned
- Monitor change adoption and effectiveness post-implementation
- Identify and mitigate risks related to change

### Goals
- Ensure smooth transition during major changes
- Minimize disruption and resistance to change
- Maintain stakeholder alignment and transparency
- Capture and apply lessons learned for future changes

### Typical Communication
- Change impact assessments and risk analyses
- Stakeholder communication plans and training materials
- Change logs and decision documentation
- Post-implementation reviews

### How Change Manager interacts with other roles
- **With Project Manager:** Works closely to schedule changes and manage dependencies
- **With Business Owner:** Collaborates to assess business impact and obtain approvals
- **With Product Manager:** Coordinates impact on product roadmap and user experience
- **With all teams:** Facilitates communication and training for change adoption

---

## Business Owner

### Role Summary
Business Owners represent the business perspective and define strategic goals for the project. They authorize funding and priority decisions, make final determinations on business-related questions, and ensure alignment between project outcomes and business objectives.

### Responsibilities
- Define business goals and success criteria for the project
- Authorize project funding, staffing, and resource allocation
- Make final decisions on business-related trade-offs and priorities
- Ensure alignment between project delivery and business strategy
- Approve major changes and scope adjustments
- Communicate project outcomes to executive leadership
- Monitor ROI and business impact of project deliverables

### Goals
- Maximize business value and return on investment
- Ensure project aligns with organizational strategy
- Maintain stakeholder confidence and executive visibility
- Drive successful adoption and business impact

### Typical Communication
- Executive status reports and business case reviews
- Approval decisions on scope and budget changes
- Strategic alignment meetings with leadership
- Business impact assessments

### How Business Owner interacts with other roles
- **With Project Manager:** Reviews project status and approves changes affecting scope/budget
- **With Change Manager:** Assesses business impact of major changes and provides approvals
- **With Product Manager:** Aligns on business goals and success metrics
- **With Customer Success Manager:** Reviews customer impact and business outcomes

---

## Customer Success Manager

### Role Summary
Customer Success Managers serve as the voice of the customer. They interface with customers to collect feedback, communicate customer requirements to the team, monitor customer satisfaction, and ensure that project outcomes deliver value to end users.

### Responsibilities
- Collect and synthesize customer feedback and requirements
- Communicate customer needs and pain points to Product Manager and Development Team
- Monitor customer satisfaction and adoption metrics
- Facilitate communication between customers and internal teams
- Coordinate customer testing, pilots, and early access programs
- Report on customer impact and success metrics post-release
- Identify opportunities for product improvements based on customer feedback

### Goals
- Ensure customer needs are understood and prioritized
- Maximize customer adoption and satisfaction
- Drive product improvements based on real customer usage
- Build strong customer relationships and loyalty

### Typical Communication
- Customer feedback summaries and requirements documentation
- Customer success metrics and adoption reports
- Feedback loops with Product Manager and Developers
- Customer communication and training materials

### How Customer Success Manager interacts with other roles
- **With Product Manager:** Communicates customer feedback to inform prioritization and roadmap decisions
- **With Business Owner:** Reports on customer impact and business outcomes
- **With Project Manager:** Coordinates customer testing and feedback collection during project phases
- **With Developers:** Communicates customer use cases and requirements

---

## Interactions and Dependencies

The following diagram illustrates how these personas interact and depend on each other:

- **Product Manager** ↔ **Project Manager:** Align on scope, priorities, and trade-offs
- **Product Manager** ↔ **Developers:** Collaborate on requirements, acceptance criteria, and design
- **Product Manager** ↔ **QA Lead:** Define quality standards and acceptance criteria
- **Project Manager** ↔ **QA Lead:** Track quality readiness and release milestones
- **Project Manager** ↔ **Change Manager:** Schedule changes and manage dependencies
- **Business Owner** ↔ **Project Manager:** Approve scope, budget, and major decisions
- **Business Owner** ↔ **Change Manager:** Assess and approve impact of major changes
- **Customer Success Manager** ↔ **Product Manager:** Feedback loop for product improvements
- **Customer Success Manager** ↔ **Business Owner:** Report customer impact and ROI

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
