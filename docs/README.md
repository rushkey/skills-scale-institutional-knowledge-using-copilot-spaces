# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation! This README provides an overview of how we run projects at OctoAcme and links to each core process doc.

## Core Principles

- **Customer-first:** We prioritize delivering measurable value to customers.
- **Iterative delivery:** Projects move forward through small, testable increments.
- **Ownership & roles:** Each project has a Project Manager and Product Lead with clear responsibilities.
- **Data-informed:** We use metrics and evidence to guide decisions and improvements.
- **Quality focus:** Definition of Done, robust testing, and post-release reviews ensure reliability.

## Project Management Process Overview

OctoAcme follows a structured five-phase project lifecycle designed to deliver customer value consistently and predictably.

### Lifecycle & Core Workflows

Projects progress through **Initiation, Planning, Execution, Release, and Close & Retrospective** phases. During **Initiation**, teams validate business need, align stakeholders, and create a lightweight Project One-pager defining the problem, goals, and success metrics. In the **Planning** phase, work is broken into shippable increments with prioritized backlogs, clear acceptance criteria, and identified dependencies. The **Execution** phase emphasizes iterative delivery through daily standups, weekly syncs, and small pull requests (≤400 lines) with mandatory code reviews. Teams maintain a project board with columns spanning Backlog, Ready, In Progress, In Review, QA, and Done to provide visibility. **Release** involves comprehensive pre-release checks—passing CI/security scans, completed acceptance criteria, and documented rollback plans—followed by staged deployment to production. Finally, **Retrospectives** held after each sprint or release capture learnings and convert them into actionable improvements tracked in the project backlog.

### Roles, Responsibilities & Communication

OctoAcme defines clear ownership through four primary personas: **Project Managers** coordinate delivery activities, manage schedules, risks, and stakeholder communications; **Product Managers** define what to build, prioritize the backlog, and measure outcomes; **Developers** implement features, write tests, and collaborate on design and code reviews; and **QA/Testing** validates quality and acceptance criteria. Communication follows a consistent cadence: daily 15-minute standups focused on progress and blockers, weekly PM and Product Manager syncs, twice-weekly delivery standups, and monthly stakeholder updates. Risk escalation follows a three-level path: team-level triage in daily standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues. A centralized Risk Register tracks all identified risks with impact, likelihood, owner, and mitigation plans, reviewed at every weekly sync.

### Quality Assurance & Delivery Standards

Quality is embedded throughout OctoAcme's execution model through multiple checkpoints. Teams implement **unit tests** for new logic, **integration tests** where applicable, and **end-to-end smoke tests** for critical flows before release. **Security scanning** runs in CI, and **manual QA** validates feature acceptance when needed. The Definition of Done, documented during planning, ensures consistent quality standards across all work items. Before any production deployment, teams verify passing CI and security scans, complete acceptance criteria, prepared smoke tests, and documented rollback/mitigation plans. Post-deployment verification and stakeholder announcement complete the release process. Teams also measure impact through **velocity tracking, burndown charts, and dashboards** for key signals like errors, latency, and usage to inform data-driven iteration.

### Continuous Improvement & Documentation

OctoAcme institutionalizes learning through blameless retrospectives held after sprints, releases, or significant milestones. Retrospectives timebox to 45–75 minutes and focus on what went well, areas for improvement, and prioritized action items (limited to 2–3 to avoid overload). Action items are tracked in the project backlog with clear owners and timelines, reviewed in weekly PM syncs, and measured for impact. All process knowledge is centralized in versioned documentation stored in the repository, giving all team members equal access to processes, decisions, and rationale. This documentation-first approach accelerates onboarding, reduces single-person dependency risk, and enables consistent, repeatable project execution across teams.

## Key Documentation

- [Project Management Overview](octoacme-project-management-overview.md) — Introduction to OctoAcme roles, principles, and high-level lifecycle
- [Project Initiation Guide](octoacme-project-initiation.md) — Steps to validate, authorize, and align on new work
- [Project Planning Guide](octoacme-project-planning.md) — Converting initiatives into actionable backlogs and release plans
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day workflows, team rhythm, and quality standards
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk registers, escalation paths, and stakeholder communication
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklist, and rollback procedures
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Running retrospectives and converting learnings into action items
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed descriptions of Project Managers, Product Managers, Developers, and QA roles

## Getting Started

1. **New team member?** Start with [Project Management Overview](octoacme-project-management-overview.md) to understand our approach and key roles.
2. **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning Guide](octoacme-project-planning.md).
3. **In execution?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day workflows and quality standards.
4. **Managing risks or communicating status?** Use [Risk Management & Communication](octoacme-risks-and-communication.md).
5. **Preparing for release?** Review [Release & Deployment Guide](octoacme-release-and-deployment.md).
6. **Holding a retrospective?** See [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).

## Contributing to Process Docs

Have feedback or want to propose updates to these process documents? [Create an issue](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) using the "Add Content to Project Management Process Docs" template.
