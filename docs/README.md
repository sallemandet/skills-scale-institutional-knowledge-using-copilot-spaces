# OctoAcme Project Management Docs

This directory centralizes OctoAcme’s project management processes and guidance. It turns tacit team knowledge into versioned, discoverable artifacts so teams can onboard faster, run projects more consistently, and iterate on process improvements.

Overview of OctoAcme Project Management Processes

OctoAcme follows a lightweight, iterative lifecycle: Initiation → Planning → Execution → Release → Retrospective. Each initiative begins with a one‑pager that defines the problem, objective, and measurable success metrics. Planning breaks the approved scope into shippable backlog items with clear acceptance criteria, estimates, and owners, and maps milestones and dependencies. Execution is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done) with small, well-documented PRs, CI checks, and at least one approval required before merge. Releases follow a checklisted path (staging → smoke tests → production) with rollback plans and post‑deploy verification.

Roles & Workflows

Roles are explicit so ownership and handoffs are predictable: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate delivery, schedules, risks, and communications; Developers implement, test, and review; QA validates acceptance criteria; Stakeholders provide input and approvals. Teams run daily standups for immediate blockers and weekly delivery syncs for status and risk review. Risks and cross‑team dependencies are logged in a risk register with named owners and mitigations, and escalating follows a documented path (team → PM → Product Lead → Sponsor).

Communication & Quality Assurance

Communication is structured via templates and a steady cadence: weekly status updates, milestone demos, and incident summaries (with blameless retrospectives when appropriate). Quality is layered and automated where possible—unit and integration tests, end‑to‑end smoke tests, security scanning in CI, and manual QA for final acceptance. Releases require passing CI/security scans, meeting acceptance criteria, release notes, and a rollback plan. After releases or incidents, retrospectives produce prioritized action items tracked back into the backlog to drive measurable continuous improvement.

Document Links

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](docs/octoacme-roles-and-personas.md)

How to propose changes
- Use the `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` template to propose updates.
- Track action items from retros in the backlog and link them to the originating retrospective or release notes.
