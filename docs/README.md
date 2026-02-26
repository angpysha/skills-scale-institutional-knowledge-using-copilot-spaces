# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This `docs/` folder contains the OctoAcme program and project management process documents, used to scale institutional knowledge via [Copilot Spaces](https://docs.github.com/en/copilot/using-github-copilot/copilot-spaces/about-copilot-spaces). Whether you are onboarding to the team or looking to understand a specific workflow, these documents serve as the single source of truth for how OctoAcme runs its projects.

## OctoAcme Project Management Process Overview

OctoAcme delivers business value through collaborative, iterative project management. Every project follows a defined lifecycle: **Initiation** (define the problem statement, identify stakeholders, and establish high-level timelines), **Planning** (scope, resources, milestones, risks, and dependencies), **Execution** (day-to-day build-test-review cycles tracked on a project board), **Release** (deployment, verification, and rollback readiness), and **Retrospective** (structured reflection and action item tracking for continuous improvement). This lifecycle ensures consistent delivery practices across all cross-functional projects.

Delivery is driven by clearly defined roles. The **Project Manager (PM)** coordinates schedules, risks, and communications; the **Product Manager (PdM)** owns the product vision and backlog prioritization; **Developers** implement features and maintain quality through design and code reviews; **QA/Testing** validates acceptance criteria; and **Stakeholders** provide inputs and approvals. A regular communication cadence—twice-weekly standups, weekly PM/PdM syncs, and monthly stakeholder updates—keeps everyone aligned and minimizes surprises.

Execution is tracked on a project board with columns: **Backlog → Ready → In Progress → In Review → QA → Done**. Pull request workflow guidance and a three-level escalation path ensure issues surface quickly. Risk is managed through a living risk register, and project health is communicated via a weekly status report template, keeping the project board and documentation as the single source of truth for all stakeholders.

Release readiness is governed by a pre-release requirements checklist and a deployment checklist, with a documented rollback and incident playbook ready if needed. After each release, a timeboxed retrospective captures what went well, what didn't, and concrete action items—closing the loop and feeding learnings back into future planning cycles.

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Purpose, principles, core roles, key artifacts, and lifecycle at a glance |
| [Project Initiation](octoacme-project-initiation.md) | Kickoff checklist, project charter, stakeholder identification |
| [Project Planning](octoacme-project-planning.md) | Scope, milestones, resource planning, dependency mapping |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Project board workflow, PR guidance, standup format, escalation levels |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, weekly status template, escalation paths |
| [Release & Deployment](octoacme-release-and-deployment.md) | Pre-release requirements, deployment checklist, rollback/incident playbook |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, timeboxing, action item tracking |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and goals for each project role |

## Proposing Updates

To propose an update to any of these process documents—or to add a new one—open a GitHub issue using the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** issue template. The template will guide you through selecting the relevant document, summarizing the proposed change, explaining the rationale, and optionally providing draft content. Once submitted, the team will review the proposal and open a pull request to incorporate approved changes.
