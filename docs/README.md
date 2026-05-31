# OctoAcme Project Management Docs

Welcome! This README provides an overview of OctoAcme's project management processes and links to detailed process documentation.

## Process Summary

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership across five distinct phases: Initiation, Planning, Execution, Release, and Closure. The **Initiation** phase begins with a Project One-pager that defines the business problem, success metrics, stakeholders, and initial resource needs—establishing a clear decision gate before moving forward. Once approved, the **Planning** phase breaks work into shippable increments with prioritized backlogs, acceptance criteria, risk registers, and release milestones.

Execution and day-to-day operations are driven by a consistent team rhythm including daily standups (15 minutes), weekly delivery syncs, and sprint-based iterations tracked through GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done). Pull requests are kept small (≤400 lines when possible) with automated CI testing, linting, and security scans before review. Quality is enforced through unit tests, integration tests, end-to-end smoke tests, and manual QA for feature acceptance. The team uses a blocker escalation framework (Level 1: daily triage, Level 2: PM escalation, Level 3: sponsor-level) to unblock work quickly and transparently.

Core roles are clearly defined: **Project Managers** coordinate schedules, risks, and cross-team communication; **Product Managers** define outcomes, prioritize work, and measure success; **Developers** implement features while contributing to design and quality; and **QA/Testing** validates acceptance criteria. Communication is structured through weekly PM-PdM syncs, twice-weekly team standups, and monthly stakeholder updates using standardized templates for status reports and incident responses. Risk management is embedded throughout the lifecycle via a simple Risk Register (ID, description, impact, likelihood, owner, mitigation) that is reviewed and updated weekly.

At project completion, OctoAcme conducts structured retrospectives (45–75 minutes) to capture learnings, prioritize 2–3 actionable improvements, and measure the impact of process changes. This continuous improvement cycle feeds back into the documentation and process refinements, ensuring that team insights are captured and made accessible through Copilot Spaces. The approach balances rigor (checklists, templates, decision gates) with psychological safety (anonymous feedback, blameless retrospectives) to create a sustainable, learning-driven delivery culture.

## Process Documentation

Each document below provides practical guidance for teams delivering projects with OctoAcme:

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, core roles, key artifacts, and lifecycle phases.
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan.
- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan, backlog, and release timeline.
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution, team rhythm, quality, and blocker escalation.
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies.
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize releases to production, manage rollbacks, and reduce deployment risk.
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements.
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Definitions of typical roles (Developers, Product Managers, Project Managers, QA) and their responsibilities.

## How to Use These Docs

- **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction.
- **Starting a new project?** Follow the sequence: Initiation → Planning → Execution & Tracking → Release → Retrospective.
- **Need process guidance for a specific activity?** Use the links above to jump to the relevant document.
- **Contributing updates?** Please use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose changes.

If you add new processes or documentation, please update this README with a summary and link to maintain a single source of truth for process navigation.
