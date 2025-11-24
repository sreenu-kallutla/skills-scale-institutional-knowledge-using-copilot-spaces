# OctoAcme Project Management Docs

OctoAcme follows a structured, iterative project management lifecycle that moves projects from initiation through planning, execution, release, and continuous improvement. Each project typically begins with a concise Project One‑pager capturing the problem statement, measurable objectives, stakeholders, timeline, and initial risks. Planning turns approved initiatives into a prioritized backlog with clear acceptance criteria and a documented Definition of Done. Core artifacts — Project One‑pagers, roadmaps/release plans, sprint backlogs, risk registers, and acceptance criteria — are stored alongside code so the project’s single source of truth lives in the repository.

Execution is organized around a predictable team rhythm and explicit workflows. The delivery team uses daily standups for coordination, weekly delivery syncs for progress and risk discussion, and milestone demos or sprint reviews to show completed work. Day‑to‑day work is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and the pull request process enforces small, reviewable changes with linked issues/acceptance criteria, required CI checks (tests, linting, security scans), and peer approval before merging. Cross‑team dependencies and blockers are surfaced on the board and escalated through a defined path when needed.

Roles and responsibilities are documented to enable clear ownership and handoffs. Product Managers define the problem, prioritize the backlog, and measure success; Project Managers coordinate schedules, risks, and communications; Developers implement, test, and review changes; QA verifies acceptance criteria and test plans. Templates and process issue forms (see .github/ISSUE_TEMPLATE/) standardize submissions and reduce single‑person dependency, which helps onboarding and consistent execution.

Quality assurance and release practices emphasize automation, review, and measured rollouts. Teams are expected to provide unit, integration, and end‑to‑end smoke tests for critical flows, run security scans as part of CI, and perform manual QA where necessary. Releases follow a checklist (pre‑release verification, release notes, rollback/mitigation plan, staging smoke tests, and post‑deploy verification) and include an incident playbook for rollbacks and root‑cause capture. Retrospectives after sprints, releases, or incidents convert learnings into prioritized backlog items to close the loop on continuous improvement.

## Document index (in this folder)

- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md

---

For templates and process issue forms see .github/ISSUE_TEMPLATE/.
