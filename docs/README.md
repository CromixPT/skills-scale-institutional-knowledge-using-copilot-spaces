# OctoAcme Project Management Docs

Welcome! This README provides an overview of OctoAcme's project management processes and links to detailed process documentation.

## Process Summary

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear accountability. The framework spans five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Closure & Retrospective**. During initiation, teams validate business need and stakeholder alignment through a lightweight Project One-pager that captures the problem statement, measurable success metrics, and resource requirements. Once approved, planning converts the initiative into an actionable backlog with prioritized, estimated work items organized by milestones. This structured approach ensures that teams move forward only when success criteria are clearly defined and stakeholders agree on priority.

Execution and delivery are coordinated through regular team rhythms—daily standups (15 minutes), weekly delivery syncs, and sprint-based planning with a Definition of Done. Work is tracked on a project board with standard columns (Backlog, Ready, In Progress, In Review, QA, Done), and pull requests follow conventions of being small (≤400 lines), linked to issues, and requiring at least one approval before merge. Quality is embedded throughout the process: unit and integration tests are required for new logic, end-to-end smoke tests validate critical flows before release, and security scanning runs in CI. Risk management is continuous, with a Risk Register maintained and escalated through defined levels (team triage → PM → Product Lead → Sponsor) as needed.

OctoAcme's role structure balances product strategy with execution and coordination. **Product Managers** define outcomes, prioritize the backlog, and measure success through data and user research. **Project Managers** own delivery coordination, timelines, risk management, and stakeholder communication. **Developers** implement features, write tests, and contribute to design and estimation. This separation of concerns is reinforced by a weekly PM-PdM sync, twice-weekly standups for delivery teams, and monthly stakeholder updates. Communication is standardized through templates (weekly status, incident reports) and a single source of truth kept in the project repository.

Release and post-delivery are equally structured: pre-release checklists ensure all acceptance criteria are met, CI passes, and rollback plans exist before deployment to production. After each sprint, release, or milestone, the team conducts a blameless retrospective to capture learnings and convert them into 2–3 prioritized action items. This continuous improvement cycle—measuring impact, celebrating wins, and making iterative changes—embeds learning and adaptation into the organizational culture, reducing single-person dependency and ensuring repeatable, consistent execution across teams.

## Process Documentation

Each document below provides practical guidance for teams delivering projects with OctoAcme:

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's principles, roles, and key artifacts.
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan.
- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan, backlog, and release timeline.
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution, team rhythm, quality, and blocker escalation.
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies.
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize releases to production, manage rollbacks, and reduce deployment risk.
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements.
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Definitions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities.

## How to Use These Docs

- **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction.
- **Starting a new project?** Follow the sequence: [Initiation](octoacme-project-initiation.md) → [Planning](octoacme-project-planning.md) → [Execution & Tracking](octoacme-execution-and-tracking.md) → [Release](octoacme-release-and-deployment.md) → [Retrospective](octoacme-retrospective-and-continuous-improvement.md).
- **Managing risks or communicating status?** See [Risk Management & Communication](octoacme-risks-and-communication.md).
- **Preparing to release?** Use the [Release & Deployment Guide](octoacme-release-and-deployment.md).
- **Running a retrospective?** See [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).

## Contributing to These Docs

If you identify gaps, improvements, or new processes that should be documented, please create an issue using the ["Add Content to Project Management Process Docs"](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template. This helps us keep our processes living, versioned, and continuously refined.
