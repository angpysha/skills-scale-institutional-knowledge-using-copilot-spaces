# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) facilitated by the **Scrum Master** — focus on progress, blockers, dependencies
- Weekly delivery sync — PM, PdM, Scrum Master review progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone (all team roles participate)
- Post-release support review — **Support Lead** shares feedback and bug trends with Product Manager

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (Scrum Master facilitates)
- Level 2: PM escalates to Product Lead and dependent teams; DevOps Engineer engaged for infrastructure blockers
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint (DevOps Engineer)
- [ ] Regular demos scheduled (Scrum Master coordinates)
- [ ] Risk register updated weekly (PM and Scrum Master)
- [ ] UX sign-off completed for features with user-facing changes
- [ ] DevOps deployment runbook reviewed before release
- [ ] Support Lead notified of release contents and known issues
