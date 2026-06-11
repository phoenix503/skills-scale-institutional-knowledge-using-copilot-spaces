# OctoAcme Project Management Docs

## About These Docs

These documents describe how OctoAcme manages projects from idea to delivery, including our roles, milestones, communication, and improvement practices. The README summarizes these processes and provides quick links to all process artifacts.

## OctoAcme Project Management Process Overview

OctoAcme follows a structured, five-phase project lifecycle that emphasizes iterative delivery, clear ownership, and data-driven decisions. The process begins with **Initiation**, where new ideas are validated through a lightweight Project One-pager that captures the problem statement, success metrics, stakeholders, and initial timeline. Once stakeholders align and the business need is confirmed, projects move into **Planning**, where work is broken into shippable increments, dependencies are identified, and a prioritized backlog with acceptance criteria is established. The team then enters **Execution**, where day-to-day delivery happens through a structured team rhythm of daily standups, weekly syncs, and sprint-based iterations. After features are complete, the **Release** phase standardizes how updates reach production—using pre-release checklists, smoke testing, and documented rollback plans. Finally, **Retrospectives** capture learnings and convert them into actionable improvements tracked through the project backlog.

### Core Roles & Communication

Three primary personas drive project success: **Project Managers** coordinate schedules, risks, and communications to ensure on-time delivery; **Product Managers** define what should be built and own prioritization based on customer value and metrics; and **Developers** implement features, collaborate on design, and identify technical risks. Clear ownership is reinforced through a consistent communication cadence: daily standups (15 minutes) focus on progress and blockers, weekly PM-PdM syncs align planning and execution, and monthly stakeholder updates maintain visibility. Escalation paths are well-defined, moving from team-level triage in standups to PM escalation and ultimately sponsor-level involvement for business-impacting issues.

### Execution & Quality Assurance

Execution is tracked through GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and governed by consistent workflows. Pull requests are kept small (≤400 lines when possible), include issue links and acceptance criteria, and require at least one approval and passing CI/automated tests before merging. Quality is ensured through multiple layers: unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, and security scanning in CI. Manual QA validates feature acceptance when needed, and success metrics identified in the Project One-pager are continuously monitored via dashboards tracking velocity, burndown, errors, and latency. This multi-layered approach reduces risk and ensures deliverables meet stakeholder expectations before and after release.

## Process Documents

- [Project Management Overview](./octoacme-project-management-overview.md) — Concise introduction to how OctoAcme runs projects, roles, key artifacts, and lifecycle
- [Project Initiation Guide](./octoacme-project-initiation.md) — Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan
- [Project Planning](./octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog for delivery
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Guidance for managing day-to-day execution and tracking progress toward milestones
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks and dependencies
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardize how OctoAcme releases features to production to reduce risk and improve observability
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements
- [Roles and Personas](./octoacme-roles-and-personas.md) — Definitions of typical roles and responsibilities used in OctoAcme projects
