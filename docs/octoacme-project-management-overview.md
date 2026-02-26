# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- Project Manager (PM): coordinates delivery, schedules, risk, communications.
- Product Manager (PdM): defines outcomes, prioritizes backlog, and measures success.
- Scrum Master: facilitates agile ceremonies, removes blockers, coaches the team.
- Developers: implement features, collaborate on design and testability.
- UX Designer: shapes user experience, creates wireframes and prototypes.
- DevOps Engineer: manages CI/CD pipelines, infrastructure, and deployment automation.
- Business Analyst: gathers and documents requirements, bridges business and delivery teams.
- QA/Testing: validate quality and acceptance criteria.
- Support Lead: owns post-release customer support and feeds user feedback to the product team.
- Stakeholders: provide inputs and approvals.

## Cross-Role Collaboration
Effective project delivery requires clear ownership and regular touchpoints between roles:
- The **Product Manager** and **Business Analyst** collaborate to ensure requirements are clearly defined and traceable to business goals before development begins.
- The **Scrum Master** and **Project Manager** align on sprint cadence, release timelines, and cross-team dependency escalation.
- The **UX Designer** works with the **Product Manager** to define acceptance criteria that include usability standards, and with **Developers** to review implementation before QA.
- The **DevOps Engineer** coordinates with the **Project Manager** on release windows and with **Developers** on environment and pipeline requirements.
- The **Support Lead** surfaces aggregated feedback and bug trends to the **Product Manager** after each release, informing future backlog priorities.
- **QA/Testing** collaborates with the **UX Designer**, **DevOps Engineer**, and **Support Lead** to ensure issues found post-release are reproducible and resolved efficiently.

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
