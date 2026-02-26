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

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach teams on agile best practices. They serve the team and organization by ensuring processes are followed and continuously improved.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove blockers that impede team progress
- Coach team members on agile principles and practices
- Shield the team from external interruptions during a sprint
- Track and communicate sprint metrics (velocity, burndown)

### Goals
- Enable the team to deliver consistently and predictably
- Foster a culture of continuous improvement
- Help the team become self-organizing and high-performing

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective facilitation and action item follow-up
- Blocker escalation to Project Manager when needed
- Coordination with Product Manager on backlog readiness

### Key Interactions
- **Project Manager**: Coordinates on release timelines, escalates blockers, and aligns on cross-team dependencies
- **Developers**: Coaches on agile practices, removes impediments, facilitates estimation
- **Product Manager**: Ensures backlog is refined and ready for sprint planning

---

## UX Designer

### Role Summary
UX Designers shape the user experience by conducting research, creating wireframes and prototypes, and collaborating with engineering to ensure usability standards are met throughout development.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define and document interaction patterns and design guidelines
- Participate in backlog refinement to clarify UX requirements
- Ensure delivered features meet usability and accessibility standards

### Goals
- Deliver intuitive, user-centered experiences
- Reduce rework by resolving design ambiguity before development
- Advocate for user needs within the product team

### Typical Communication
- Design reviews and prototype walkthroughs
- Collaboration on acceptance criteria with Product Manager
- Feedback sessions and usability test reports
- Async design comments in project boards or design tools

### Key Interactions
- **Product Manager**: Co-defines user stories and acceptance criteria; aligns design with product vision
- **Developers**: Shares design specifications and provides implementation guidance
- **QA/Testing**: Reviews tested features for usability compliance before release

---

## DevOps Engineer

### Role Summary
DevOps Engineers manage CI/CD pipelines, infrastructure, deployment automation, and system reliability. They bridge the gap between development and operations to ensure smooth, repeatable delivery.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Manage cloud infrastructure, environments, and configuration
- Monitor system health, reliability, and performance
- Support incident response and root cause analysis
- Define and enforce security and compliance controls in the pipeline

### Goals
- Enable fast, reliable, and automated delivery
- Minimize downtime and mean time to recovery (MTTR)
- Maintain secure and auditable infrastructure

### Typical Communication
- Release coordination with Project Manager and Developers
- Incident and on-call runbooks
- Infrastructure change proposals and post-incident reviews
- CI/CD status updates in team channels

### Key Interactions
- **Project Manager**: Coordinates release windows and deployment schedules
- **Developers**: Collaborates on pipeline requirements and environment configurations
- **QA/Testing**: Provides stable test environments and automated deployment for QA validation

---

## Business Analyst

### Role Summary
Business Analysts gather and analyze requirements, document workflows, and identify process improvements. They act as a bridge between business stakeholders and the delivery team.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Analyze existing workflows and identify improvement opportunities
- Create process flow diagrams, user stories, and use cases
- Support User Acceptance Testing (UAT) with stakeholders
- Maintain requirements traceability through delivery

### Goals
- Ensure requirements are clear, complete, and actionable
- Reduce ambiguity that leads to rework or misalignment
- Connect business objectives to delivery outcomes

### Typical Communication
- Requirements workshops and stakeholder interviews
- Written user stories, use cases, and BRDs (business requirements documents)
- UAT coordination and sign-off documentation
- Regular syncs with Product Manager and Project Manager

### Key Interactions
- **Product Manager**: Translates business needs into prioritized backlog items; validates feature intent
- **Project Manager**: Aligns requirements scope with project timeline and resources
- **Developers**: Clarifies requirements and resolves ambiguities during development

---

## Support Lead

### Role Summary
Support Leads own post-release customer support, triage incoming bugs and user feedback, and maintain help documentation. They serve as the voice of the customer after a product ships.

### Responsibilities
- Own the customer support queue and ensure timely, quality responses
- Triage and prioritize reported bugs and feedback for the engineering team
- Maintain and update FAQ, help docs, and knowledge base articles
- Identify patterns in support tickets to surface product improvement opportunities
- Coordinate with Developers and QA on incident resolution

### Goals
- Ensure customers receive fast and effective support
- Reduce repeat issues by feeding actionable feedback to the product team
- Maintain a current and accurate knowledge base

### Typical Communication
- Support ticket summaries and trend reports to Product Manager
- Bug escalations and incident updates to Developers and QA
- Help documentation updates coordinated with Product Manager
- Post-release feedback loops in team retrospectives

### Key Interactions
- **Product Manager**: Shares aggregated user feedback and bug trends to inform roadmap priorities
- **Developers**: Escalates critical bugs for resolution; coordinates on hot fixes
- **QA/Testing**: Collaborates on reproducing and validating reported issues

---

## Onboarding Checklist by Role

Use this checklist to guide new team members through their first days in each role. Items should be completed within the first two weeks unless otherwise noted.

### All Roles
- [ ] Review the [Project Management Overview](octoacme-project-management-overview.md)
- [ ] Review this Roles and Personas document
- [ ] Review the [Project Planning](octoacme-project-planning.md) process
- [ ] Review the [Execution and Tracking](octoacme-execution-and-tracking.md) guide
- [ ] Get access to the project board (e.g., GitHub Projects)
- [ ] Attend a team standup and sprint ceremony as an observer
- [ ] Meet with your direct counterparts (see Key Interactions above)

### Developers
- [ ] Set up local development environment
- [ ] Review branching and PR conventions in the repo README
- [ ] Complete at least one code review with a team member
- [ ] Confirm CI/CD pipeline access and understand the build process

### Product Manager
- [ ] Review the current roadmap and backlog
- [ ] Meet with key stakeholders and sponsors
- [ ] Review open and recent user research or feedback

### Project Manager
- [ ] Review the risk register and current project status
- [ ] Attend a cross-team dependency meeting
- [ ] Review the release plan and upcoming milestones

### Scrum Master
- [ ] Review recent retrospective notes and outstanding action items
- [ ] Shadow a sprint planning session before facilitating independently
- [ ] Review team velocity and burndown history
- [ ] Identify current blockers and confirm escalation paths

### UX Designer
- [ ] Review existing design guidelines and component library (if applicable)
- [ ] Access and review current user research findings
- [ ] Meet with Product Manager to understand active feature roadmap
- [ ] Review in-flight prototypes or wireframes for current sprint work

### DevOps Engineer
- [ ] Review CI/CD pipeline configuration and deployment runbooks
- [ ] Gain access to infrastructure environments (dev, staging, production)
- [ ] Review on-call and incident response procedures
- [ ] Meet with Developers to understand current environment pain points

### Business Analyst
- [ ] Review existing requirements documentation and backlog
- [ ] Meet with Product Manager and Project Manager to align on scope
- [ ] Review any open UAT findings or outstanding requirements gaps
- [ ] Identify key business stakeholders and schedule introduction meetings

### Support Lead
- [ ] Get access to the customer support queue and ticketing system
- [ ] Review existing help documentation and FAQs
- [ ] Review recent support ticket trends and top reported issues
- [ ] Meet with Product Manager to establish a feedback cadence

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

