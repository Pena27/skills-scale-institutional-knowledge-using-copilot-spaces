# OctoAcme Project Management Documentation

Welcome to OctoAcme's project management processes and best practices. This guide centralizes all program management knowledge to help teams execute projects consistently and effectively.

## Overview

OctoAcme follows a structured, iterative approach to project delivery. Our methodology emphasizes:
- **Customer-first thinking** — prioritize customer value and usability
- **Iterative delivery** — ship small, testable increments
- **Clear ownership** — each project has named owners and accountable roles
- **Data-informed decisions** — measure impact and iterate based on evidence
- **Psychological safety** — encourage feedback, learning, and continuous improvement

## About OctoAcme's Project Management Processes

OctoAcme's project management framework is designed to centralize scattered knowledge and convert tacit team insights into searchable, versioned artifacts. This approach enables:

- **Equal access to processes** — all team members have the same access to processes, decisions, and rationale
- **Structured knowledge** — connect repositories as structured knowledge sources to extract, refine, and standardize workflows
- **Collaborative improvement** — feed validated improvements back into living documentation
- **Faster onboarding** — accelerate team member onboarding and reduce single-person dependency risk
- **Consistent execution** — enable consistent, repeatable project execution across teams

The OctoAcme framework defines clear roles, responsibilities, and communication patterns. It emphasizes continuous improvement through retrospectives and encourages a blameless, learning-focused culture.

## Project Lifecycle

OctoAcme projects follow a five-stage lifecycle:

1. **[Initiation](./octoacme-project-initiation.md)** — Validate the problem, align stakeholders, define success metrics, decide go/no-go
2. **[Planning](./octoacme-project-planning.md)** — Break work into shippable increments, estimate scope, identify dependencies, create release plan
3. **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Build, test, review, iterate; track progress through daily standups and project boards
4. **[Release & Deployment](./octoacme-release-and-deployment.md)** — Deploy to production, verify functionality, communicate changes, prepare rollback plans
5. **[Retrospective & Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings, identify improvements, track action items, refine processes

## Core Roles & Responsibilities

Each project has clearly defined roles and owners. See [OctoAcme Personas](./octoacme-roles-and-personas.md) for detailed role definitions:

- **Project Manager (PM)** — Coordinates delivery, manages schedules, owns risk communication and escalation
- **Product Manager (PdM)** — Defines outcomes, prioritizes backlog, measures success and impact
- **Developers** — Implement features, write tests, collaborate on design and testability
- **QA/Testing** — Validate quality, verify acceptance criteria, conduct smoke tests
- **Stakeholders** — Provide inputs, approvals, and business context

## Key Artifacts

Every OctoAcme project maintains:

- **Project Charter / One-pager** — Problem, goal, success metrics, stakeholders, timeline
- **Roadmap and Release Plan** — High-level milestones and delivery schedule
- **Sprint/Iteration Backlog** — Prioritized items with acceptance criteria and estimates
- **Definition of Done (DoD)** — Shared quality standards for work completion
- **Risk Register** — Identified risks with impact, likelihood, owner, and mitigation plans
- **Decision Log** — Key decisions and rationale for traceability
- **Retrospective notes** — Learnings and action items for continuous improvement

## Communication & Risk Management

OctoAcme emphasizes transparent, frequent communication:

- **Daily standups** (15 min) — progress, blockers, dependencies
- **Weekly PM + PdM sync** — alignment on priorities and risks
- **Weekly stakeholder updates** — status, risks, decisions needed
- **Ad-hoc escalations** — risk escalation path: Team → PM → Product Lead → Sponsor

Learn more in [Risk Management & Communication](./octoacme-risks-and-communication.md).

## Quality & Testing Standards

All OctoAcme projects follow consistent quality practices:

- **Unit tests** for new logic
- **Integration tests** where applicable
- **End-to-end smoke tests** for critical flows before release
- **Security scanning** in CI pipeline
- **Manual QA** for feature acceptance when needed
- **Small PRs** (≤ 400 lines when possible) with clear acceptance criteria
- **Require approval** before merging (team-defined policy)

## All Documentation

- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to roles, artifacts, and lifecycle
- [Project Initiation Guide](./octoacme-project-initiation.md) — Steps to validate, authorize, and kickoff new work
- [Project Planning](./octoacme-project-planning.md) — Breaking down work, estimating, identifying dependencies
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day delivery management and progress tracking
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Risk identification, escalation, and stakeholder communication
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Release types, pre-flight checklists, rollback procedures
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and refining processes
- [OctoAcme Personas](./octoacme-roles-and-personas.md) — Detailed role definitions and responsibilities

## Getting Started

**Choosing your entry point:**

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a concise introduction
- **Starting a new project?** Follow the [Initiation](./octoacme-project-initiation.md) → [Planning](./octoacme-project-planning.md) flow
- **Managing an active project?** See [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management](./octoacme-risks-and-communication.md)
- **Preparing a release?** Consult the [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **Running retrospectives?** Follow the [Retrospective Guide](./octoacme-retrospective-and-continuous-improvement.md)
- **Understanding roles?** Review [OctoAcme Personas](./octoacme-roles-and-personas.md)

## Contributing to These Docs

To suggest updates or add new process content, use the issue template: **[Add Content to Project Management Process Docs](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)**

This ensures:
- Clear rationale for changes
- Alignment with existing processes
- Proper review and discussion before updates
- Tracking of improvements over time
