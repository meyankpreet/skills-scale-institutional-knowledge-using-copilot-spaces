# OctoAcme Project Management Docs

## Overview

This README serves as the main entry point for OctoAcme's project management processes and provides quick access to all process documentation. Whether you're onboarding to a new project, establishing team practices, or scaling institutional knowledge, these docs are your guide.

## Project Management Processes — Summary

OctoAcme follows a structured, customer-first approach to project delivery that spans five key phases: **initiation, planning, execution, release, and continuous improvement**. This methodology prioritizes iterative development, clear ownership, and data-informed decision-making across all cross-functional projects.

### The OctoAcme Lifecycle

- **Initiation**: Teams validate business needs and create a lightweight Project One-pager that establishes the problem statement, success metrics, key stakeholders, and initial timeline. A decision gate ensures full alignment before moving into planning.
- **Planning**: Work is broken into shippable increments with documented acceptance criteria. Dependencies are mapped, a prioritized backlog is created with clear ownership for each item, and a Definition of Done is established.
- **Execution & Tracking**: Teams work in sprints using a project board (Backlog → Ready → In Progress → In Review → QA → Done). Daily standups focus on progress and blockers, while quality is maintained through automated testing, code reviews, and security scanning in CI.
- **Release & Deployment**: Pre-release activities include comprehensive smoke tests, documented rollback plans, and stakeholder communication. Production deployments are verified, and incident playbooks protect stability.
- **Retrospective & Continuous Improvement**: Post-sprint retrospectives capture learnings and generate prioritized action items. A Risk Register is maintained throughout to track issues early and ensure proactive mitigation.

### Core Roles and Accountability

OctoAcme defines clear roles to maintain accountability and streamline decision-making:

- **Project Managers** coordinate delivery schedules, manage risks, track progress against milestones, and ensure transparent stakeholder communication.
- **Product Managers** define customer and business value, prioritize the roadmap, and measure outcomes through success metrics.
- **Developers** implement features, write and maintain tests, participate in design and code reviews, and help identify technical risks.
- **QA/Testing** teams validate quality against acceptance criteria and ensure readiness for release.
- **Stakeholders** provide inputs, approvals, and context on business priorities and constraints.

### Communication and Decision-Making

OctoAcme maintains a structured communication cadence:

- **Daily**: 15-minute standups focused on progress, blockers, and dependencies.
- **Weekly**: PM and product leadership syncs for alignment; twice-weekly delivery team standups; status updates to stakeholders.
- **Monthly**: Stakeholder briefings and roadmap reviews.
- **Ad-hoc**: Escalations following a three-tier path (team-level → PM → Product Lead → Sponsor) to surface and resolve blockers quickly.

### Quality Assurance and Risk Management

Quality is built into every stage:

- Small PRs (≤400 lines when possible) with automated testing before review and at least one approval required.
- Unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows.
- Security scanning in CI and manual QA for feature acceptance when needed.
- A **Risk Register** maintained throughout execution to track issues, impact, likelihood, and mitigation plans.
- Post-sprint retrospectives (45–75 minutes) to capture learnings and generate actionable improvements.

---

## Process Docs Index

Choose the document that matches your current phase or need:

| Phase | Document |
|-------|----------|
| **Introduction** | [Project Management Overview](octoacme-project-management-overview.md) — Start here for core principles, roles, and high-level lifecycle. |
| **Initiation** | [Project Initiation Guide](octoacme-project-initiation.md) — Validate business need, align stakeholders, create a Project One-pager, and decide go/no-go. |
| **Planning** | [Project Planning](octoacme-project-planning.md) — Break work into shippable increments, estimate scope, define Definition of Done, and map dependencies. |
| **Execution** | [Execution & Tracking](octoacme-execution-and-tracking.md) — Manage day-to-day delivery, track progress, run standups, and escalate blockers. |
| **Risk & Communication** | [Risk Management & Communication](octoacme-risks-and-communication.md) — Maintain a Risk Register, manage dependencies, and keep stakeholders informed. |
| **Release** | [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardize release types, pre-release requirements, deployment checklists, and rollback playbooks. |
| **Learning** | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Run effective retrospectives, track action items, and build a culture of continuous improvement. |
| **Reference** | [Roles and Personas](octoacme-roles-and-personas.md) — Detailed descriptions of Developer, Product Manager, and Project Manager responsibilities and goals. |

---

## Getting Started

1. **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md).
2. **Starting a new project?** Follow the [Initiation Guide](octoacme-project-initiation.md) → [Planning Guide](octoacme-project-planning.md).
3. **Already executing?** Use [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md) as your daily references.
4. **Preparing a release?** Consult the [Release & Deployment Guide](octoacme-release-and-deployment.md).
5. **Wrapping up a project?** Schedule a [Retrospective](octoacme-retrospective-and-continuous-improvement.md) and capture learnings.

---

## Key Principles

- **Customer-first**: Prioritize customer value and usability in every decision.
- **Iterative delivery**: Deliver small, testable increments rather than waiting for big-bang releases.
- **Clear ownership**: Every project has named Project Manager and Product Manager; every backlog item has an owner.
- **Data-informed**: Measure impact and iterate based on evidence.
- **Psychological safety**: Encourage feedback, questions, and learning. Blameless retrospectives foster continuous improvement.

---

## Contributing to These Docs

Have a suggestion to improve or extend these process docs? [Open an issue](../../issues/new?template=add-update-content-to-process-docs.yml) using the "Add Content to Project Management Process Docs" template. We're committed to evolving these practices as our team and projects grow.
