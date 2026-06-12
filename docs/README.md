# OctoAcme Project Management Process Docs

This repository's `docs/` folder contains OctoAcme's program and project management process documents. This README provides links to each document and a short summary to help teammates find the guidance they need.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — concise introduction to OctoAcme roles, principles, lifecycle, and key artifacts.
- [Project Initiation Guide](octoacme-project-initiation.md) — steps to validate and authorize new projects; includes a Project One-pager template.
- [Project Planning](octoacme-project-planning.md) — turning approved initiatives into a plan and backlog; includes backlog item and planning checklists.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — team rhythm, workflows, QA, reporting, and escalation paths for day-to-day delivery.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — release types, pre-release requirements, deployment checklist, and rollback playbook.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — risk register guidance, communication templates, and escalation paths.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — running retrospectives and tracking action items.
- [Roles & Personas](octoacme-roles-and-personas.md) — role summaries and responsibilities used across the docs.

## Summary of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management grounded in customer-first principles and iterative delivery. The methodology encompasses five core phases: **Initiation**, where new ideas are validated through a One-pager and stakeholder alignment; **Planning**, where approved work is decomposed into prioritized backlog items with clear acceptance criteria and release milestones; **Execution**, managed through daily standups and a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done); **Release**, which follows standardized pre-deployment checklists and rollback procedures; and **Close & Retrospective**, where learnings are captured and converted into continuous improvements. This lifecycle ensures that projects move through clear decision gates, with success metrics defined upfront and regularly monitored.

The organization operates with clearly defined roles that balance product vision with delivery execution. **Product Managers** own the problem statement, success metrics, and backlog prioritization; **Project Managers** coordinate schedules, manage risks and dependencies, and facilitate cross-team communication; and **Developers** collaborate on implementation, estimation, and quality. This separation of concerns enables both strategic alignment and operational agility, with weekly syncs between PM and PdM ensuring tight coordination between delivery and product strategy. Communication cadence is intentional—twice-weekly standups for delivery teams, weekly PM/PdM alignment, monthly stakeholder updates, and ad-hoc escalation paths that move from team-level triage through PM, Product Lead, and ultimately Sponsor when business impact is at risk.

Quality and risk management are woven throughout execution rather than treated as afterthoughts. The team maintains a living **Risk Register** that tracks identified issues, their impact and likelihood, mitigation plans, and status—reviewed at weekly syncs to catch emerging dependencies or blockers early. Quality gates include unit and integration testing in CI, security scanning before merge, and manual QA for critical flows. Pull requests are kept small (≤400 lines), require at least one approval, and include issue links and acceptance criteria. The **Blocker Escalation** framework provides three levels of triage—team-level in standups, PM escalation to Product Lead and dependent teams, and finally Sponsor-level involvement for business-impacting issues.

This holistic approach is documented, versioned, and made accessible through a Copilot Space connected to the repository. Process documents stored in `docs/` serve as the single source of truth, with issue templates in `.github/ISSUE_TEMPLATE/` enabling the team to propose updates to processes collaboratively. By centralizing scattered project management knowledge and treating processes as living artifacts, OctoAcme reduces onboarding friction, minimizes single-person dependency risk, and enables consistent, repeatable execution across cross-functional teams.

## How to Use This README

- Refer to this README when you need to find process guidance relevant to your work.
- Use the links above to navigate directly to the process document you need.
- When new process docs are added or existing docs are renamed, update this README to maintain discoverability.
- For questions or suggestions about these processes, refer to the issue template [Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
