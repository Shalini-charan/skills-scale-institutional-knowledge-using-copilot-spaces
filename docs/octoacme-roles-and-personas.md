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
- Collaborate with **Product Managers** on acceptance criteria and feature specifications
- Work with **Project Managers** on estimation and timeline planning
- Receive quality guidance from **QA/Testing Leads** on test strategies and acceptance validation
- Follow technical direction from **Technical Leads/Architects** on design and architecture decisions
- Coordinate with **DevOps/Release Engineers** on deployment and CI/CD processes
- Participate in ceremonies facilitated by **Scrum Masters/Agile Coaches**

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
- Define acceptance criteria with **Developers** and **QA/Testing Leads**
- Coordinate with **Project Managers** on release planning and timelines
- Consult **Stakeholders/Sponsors** on business priorities and trade-offs
- Work with **Technical Leads/Architects** on feasibility and technical trade-offs
- Support **Scrum Masters/Agile Coaches** in backlog refinement and prioritization

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
- Align with **Product Managers** on priorities and scope
- Coordinate with **Developers** on estimation and capacity planning
- Work with **QA/Testing Leads** to plan quality assurance timelines and resource allocation
- Escalate technical risks identified by **Technical Leads/Architects**
- Coordinate with **DevOps/Release Engineers** on deployment schedules and rollback procedures
- Facilitate communication with **Stakeholders/Sponsors** on progress and risks
- Support **Scrum Masters/Agile Coaches** in process adherence and meeting facilitation

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality strategy, test planning, and acceptance validation. They ensure features meet quality standards and acceptance criteria before release.

### Responsibilities
- Design test plans and define testing approach (unit, integration, end-to-end)
- Establish quality metrics and acceptance criteria validation
- Coordinate manual and automated testing efforts
- Report quality status and blockers in weekly syncs
- Identify quality risks and propose mitigations
- Review and refine acceptance criteria with developers and product teams
- Define Definition of Done related to quality standards

### Goals
- Ensure high product quality and minimal production incidents
- Accelerate testing cycles and reduce manual QA overhead
- Provide early feedback on feature design and testability
- Maintain consistent quality standards across all releases

### Typical Communication
- Sprint planning and acceptance criteria refinement
- Test plan reviews with developers
- Quality status reports and metrics
- Risk identification and escalation to Project Managers

### Interactions with Other Roles
- Collaborate with **Developers** on test strategies and code testability
- Work with **Product Managers** to validate acceptance criteria alignment with business goals
- Coordinate with **Project Managers** on quality timelines and resource needs
- Consult **Technical Leads/Architects** on test design for complex technical components
- Support **DevOps/Release Engineers** in pre-deployment smoke testing and validation
- Participate in retrospectives facilitated by **Scrum Masters/Agile Coaches** to improve quality processes
- Report quality status to **Stakeholders/Sponsors** during milestone reviews

---

## Technical Lead/Architect

### Role Summary
Technical Leads own the high-level technical design, technology stack decisions, and technical risk mitigation for projects.

### Responsibilities
- Design system architecture and integration points
- Review technical designs and RFC (Request for Comments)
- Identify and escalate technical risks and dependencies
- Mentor developers on technical standards and best practices
- Participate in design reviews and performance optimization
- Make technology stack decisions aligned with project goals
- Define technical standards and coding guidelines

### Goals
- Deliver scalable, maintainable technical solutions
- Reduce technical debt and refactoring overhead
- Ensure consistency with platform standards and patterns
- Mitigate technical risks early in the project lifecycle

### Typical Communication
- Design review meetings and RFC discussions
- Technical deep-dives and spike planning
- Architectural decision logs and ADRs (Architecture Decision Records)
- Technical risk identification and escalation

### Interactions with Other Roles
- Mentor and guide **Developers** on architecture and design best practices
- Advise **Product Managers** on technical feasibility and trade-offs
- Communicate technical risks to **Project Managers** for mitigation planning
- Work with **QA/Testing Leads** on test design for complex architectural components
- Collaborate with **DevOps/Release Engineers** on scalability and deployment considerations
- Participate in ceremonies led by **Scrum Masters/Agile Coaches** to provide technical guidance
- Brief **Stakeholders/Sponsors** on significant technical decisions and their business implications

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate agile ceremonies, remove impediments, and drive continuous process improvement. They enable teams to operate effectively and deliver value iteratively.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove impediments and blockers that impact team productivity
- Coach team members on agile principles and practices
- Maintain project dashboards and burndown charts
- Drive continuous improvement through retrospective action items
- Ensure compliance with team's Definition of Done
- Coach teams on effective communication and collaboration

### Goals
- Enable the team to deliver consistently at high velocity
- Foster a culture of continuous improvement and psychological safety
- Reduce process waste and improve flow
- Build strong, self-organizing team dynamics

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective facilitation and action item tracking
- Coaching conversations with team members
- Process improvement recommendations

### Interactions with Other Roles
- Facilitate ceremonies involving all team members (**Developers**, **Product Managers**, **Project Managers**, **QA/Testing Leads**, **Technical Leads/Architects**, **DevOps/Release Engineers**)
- Coach **Developers** on agile practices and technical collaboration
- Support **Product Managers** in backlog refinement and sprint planning
- Collaborate with **Project Managers** on process consistency and adherence
- Ensure **QA/Testing Leads** have visibility in sprint planning and refinement
- Work with **Technical Leads/Architects** to balance technical work and feature delivery
- Support **DevOps/Release Engineers** in sprint planning for deployment activities
- Brief **Stakeholders/Sponsors** on team velocity trends and process improvements

---

## DevOps/Release Engineer

### Role Summary
DevOps and Release Engineers manage deployment pipelines, infrastructure, and release processes to ensure reliable, efficient deployments to production.

### Responsibilities
- Own CI/CD pipelines and deployment automation
- Manage infrastructure and environment provisioning
- Coordinate release planning and deployment windows
- Maintain deployment documentation and runbooks
- Manage rollback procedures and incident response for deployments
- Monitor system health and performance post-deployment
- Establish standards for infrastructure as code and deployment practices

### Goals
- Enable frequent, low-risk deployments to production
- Reduce deployment-related incidents and rollbacks
- Improve observability and monitoring of deployed systems
- Minimize deployment-related downtime and support overhead

### Typical Communication
- Release planning and deployment coordination
- Infrastructure and pipeline status updates
- Post-incident reviews and deployment retrospectives
- Deployment documentation and runbooks

### Interactions with Other Roles
- Support **Developers** with CI/CD pipeline improvements and deployment feedback
- Coordinate with **Product Managers** on release timelines and feature rollout strategies
- Work with **Project Managers** to schedule deployment windows and manage release risks
- Collaborate with **QA/Testing Leads** on pre-deployment testing and smoke test execution
- Consult **Technical Leads/Architects** on infrastructure design and scalability considerations
- Participate in ceremonies led by **Scrum Masters/Agile Coaches** to align on deployment activities
- Report deployment status and infrastructure issues to **Stakeholders/Sponsors**

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors represent business interests, provide decision-making authority, and ensure projects align with organizational strategy and objectives.

### Responsibilities
- Provide business context and strategic alignment for projects
- Approve scope, timeline, and resource decisions
- Serve as escalation point for business-impacting issues
- Provide input on success metrics and business outcomes
- Communicate project importance and priorities across the organization
- Make trade-off decisions on scope, schedule, and resources

### Goals
- Ensure projects deliver maximum business value
- Maintain alignment with organizational strategy
- Enable timely decision-making and risk escalation
- Maximize return on investment for project initiatives

### Typical Communication
- Milestone reviews and status updates
- Decision approvals and trade-off discussions
- Escalation resolution and issue triage
- Executive briefings and announcements

### Interactions with Other Roles
- Receive project updates from **Project Managers** and provide guidance
- Align priorities with **Product Managers** on business objectives
- Review and approve scope, schedule, and resource decisions coordinated by **Project Managers**
- Receive quality and risk reports from appropriate team leads
- Make strategic decisions based on recommendations from **Technical Leads/Architects**
- Approve release decisions coordinated by **DevOps/Release Engineers** and **Project Managers**
- Participate in milestone reviews and project closure discussions
- Engage with **Scrum Masters/Agile Coaches** for process governance and escalations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference interactions between personas to understand cross-functional dependencies and communication patterns.
