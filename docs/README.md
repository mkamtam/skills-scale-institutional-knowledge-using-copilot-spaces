# OctoAcme Project Management Documentation

## Welcome

This directory contains comprehensive guides for running projects at OctoAcme. Whether you're starting a new initiative, planning deliverables, executing work, or capturing lessons learned, you'll find process documentation, templates, and checklists here.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named owners for product and delivery
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

OctoAcme projects follow a structured five-phase lifecycle:

1. **[Initiation](octoacme-project-initiation.md)** — Validate business need, align stakeholders, decide go/no-go
2. **[Planning](octoacme-project-planning.md)** — Break work into shippable increments, identify risks and dependencies
3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Build, test, review, and iterate with regular team rhythm
4. **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardize release procedures and reduce production risk
5. **[Retrospective & Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive continuous improvement

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured lifecycle approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The organization applies five core phases to all cross-functional projects: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with defined acceptance criteria), **Execution** (daily delivery with continuous tracking), **Release** (standardized deployment with risk mitigation), and **Close & Retrospective** (capturing learnings for improvement). This lifecycle is guided by central principles including customer-first prioritization, data-informed decision-making, and psychological safety.

At the heart of every project are three primary roles: the **Project Manager** who coordinates delivery, schedules, and risk management; the **Product Manager** who defines outcomes and prioritizes the backlog; and the **Development team** (developers, QA, and stakeholders) who implement and validate features. Weekly syncs between PM and Product Manager, twice-weekly standups for the delivery team, and monthly stakeholder updates ensure consistent alignment across the organization.

Execution and tracking rely on a GitHub Projects-based workflow with clear quality gates and escalation paths. Teams organize work in a project board with columns spanning Backlog → Ready → In Progress → In Review → QA → Done, supported by small pull requests (≤400 lines when possible) that require at least one approval before merging. Quality assurance is embedded throughout: unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI pipelines. Risk and dependency management are continuous activities, captured in a Risk Register and reviewed weekly during syncs, with escalation happening in three levels—team-level triage, PM escalation to Product Lead, and sponsor-level involvement for business-impacting issues.

Communication and transparency are foundational to OctoAcme's success. Teams maintain a single source of truth for project status, using weekly status templates that highlight progress, next steps, risks, and decisions needed. Stakeholder groups receive regular updates (weekly or milestone-based), while incident communication follows a structured playbook including triage summary, actions in progress, expected timeline, and post-incident retrospective. Finally, OctoAcme closes every project cycle with a dedicated retrospective (45–75 minutes) that examines what went well, what could improve, and generates 2–3 prioritized action items with named owners and due dates. These improvements are tracked and reviewed in weekly PM syncs, embedding continuous learning into the organizational rhythm and ensuring that each project informs and strengthens future delivery.

## Key Documents

### Getting Started

- **[OctoAcme Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to our approach, roles, and key artifacts
- **[OctoAcme Roles & Personas](octoacme-roles-and-personas.md)** — Definitions of Developers, Product Managers, Project Managers, and their responsibilities

### Process Guides (by Phase)

- **[Project Initiation](octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, create a lightweight plan
- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardize releases to reduce risk and improve observability
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements

### Cross-Cutting Concerns

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks, dependencies, and status across stakeholders

## Key Roles

| Role | Responsibility | Focus |
|------|---|---|
| **Project Manager** | Coordinate delivery, manage schedules, risks, communications | Timeline, dependencies, status |
| **Product Manager** | Define outcomes, prioritize backlog, measure success | Customer value, impact metrics |
| **Developers** | Implement features, collaborate on design and testability | Quality, maintainability, delivery |
| **QA/Testing** | Validate quality and acceptance criteria | Test coverage, edge cases |

See [OctoAcme Roles & Personas](octoacme-roles-and-personas.md) for detailed descriptions.

## Key Artifacts

- Project Charter / One-pager
- Risk Register
- Project Backlog & Sprint Plans
- Release Notes
- Retrospective Notes
- Status Reports

## Communication Cadence

- Daily standups (delivery team)
- Weekly PM + Product Lead sync
- Weekly stakeholder status updates
- Ad-hoc escalations as needed

## How to Use This Documentation

1. New team members should start with [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
2. For a specific phase or concern, jump to the relevant process guide above
3. Keep the Project Charter updated in your project repository
4. Use these docs as templates and checklists for your project work

---

*For questions or suggestions about these processes, please open an issue or reach out to the Project Management team.*
