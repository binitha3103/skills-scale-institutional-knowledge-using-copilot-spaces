# OctoAcme Project Management Docs

This docs/ folder contains OctoAcme’s project management process documentation — the canonical, discoverable source for how we initiate, plan, execute, release, and improve projects. The materials are organized to help new teammates onboard quickly and to give delivery teams a consistent set of artifacts (one‑pagers, release plans, backlog templates, risk registers, and retrospectives) to use across initiatives. Use this README to jump to the specific guidance you need.

OctoAcme follows a lightweight, iterative lifecycle. Work begins with a Project One‑pager to confirm the problem, goals, stakeholders, and success metrics, and then moves into planning where the backlog is prioritized, estimates are produced, and a Definition of Done is agreed. Execution uses a project board with clear columns (Backlog → Ready → In Progress → In Review → QA → Done) and emphasizes small, reviewable pull requests that include acceptance criteria and automated checks. Releases follow a checklist-driven approach with pre-release checks, smoke tests, rollbacks/incident playbooks, and post-deploy verification.

Roles and responsibilities are clearly defined: Product Managers set outcomes and success metrics, Project Managers coordinate delivery and communications, Developers implement and maintain tests and documentation, QA validates acceptance, and Stakeholders provide approvals and prioritization. Communication is structured — daily standups for immediate blockers and coordination, weekly delivery syncs and PM+PdM alignment, demos at the end of sprints, and regular stakeholder updates — with a defined escalation path from team → PM → Product Lead → Sponsor for blockers that need higher-level attention.

Quality assurance is integrated into the flow: unit and integration tests are expected for new logic, end-to-end smoke tests protect critical flows, CI runs automated security scans and linting, and manual QA is used when human verification is required. Retrospectives capture action items that are tracked as backlog issues so the process continuously improves. A Risk Register and communication templates help the team monitor and escalate dependencies and incidents.

## Project management processes (brief summary)
- Initiation: One‑pager to confirm problem, goals, stakeholders, and success metrics.
- Planning: Kickoff, prioritized backlog, scope estimates, Definition of Done.
- Execution & Tracking: Project board (Backlog → Ready → In Progress → In Review → QA → Done), small PRs, CI checks, standups/demos.
- Release & Deployment: Pre-release checks, staging smoke tests, automated pipelines where possible, rollback/incident playbook.
- Retrospective & Continuous Improvement: Retrospectives, action items tracked in backlog.
- Risk & Communication: Risk register, weekly syncs, structured escalation paths.

## Links to process documents
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)
