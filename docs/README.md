# OctoAcme Project Management Documentation

## Purpose
Central hub for OctoAcme's project management processes, tools, and best practices. Use this guide to navigate documentation based on your role or project stage.

## OctoAcme Project Management Overview

OctoAcme follows a structured, lifecycle-based approach to project management centered around five core phases: **Initiation, Planning, Execution, Release, and Retrospective**. The framework emphasizes customer-first delivery, iterative development, and clear ownership. During initiation, teams validate business need and align stakeholders around a lightweight Project One-pager that defines the problem statement, measurable success metrics, and key milestones. Once approved by the Product Lead and sponsor, the project moves into planning, where the backlog is prioritized, work is estimated using T-shirt sizing or story points, and a Definition of Done is established. This structured handoff ensures all stakeholders understand scope, dependencies, and timeline before execution begins.

Execution and delivery are coordinated through a daily standup rhythm and a project board (typically GitHub Projects) with columns for Backlog, Ready, In Progress, In Review, QA, and Done. The organization maintains a pull request workflow with small, reviewable changes (≤400 lines), automated testing and linting in CI, and a requirement for at least one approval before merging. Quality assurance is embedded throughout—unit tests, integration tests, end-to-end smoke tests, and security scanning run automatically, with manual QA performed for feature acceptance when needed. Weekly delivery syncs track velocity and burndown while a three-level escalation path (team triage → PM → Product Lead → Sponsor) ensures blockers and risks surface quickly.

Core roles are clearly defined: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define what to build and prioritize the backlog; **Developers** implement features and own code quality; and **QA/Testing** validates acceptance criteria. This separation of concerns is reinforced by a communication cadence that includes twice-weekly standups for the delivery team, weekly syncs between PM and Product Manager, monthly stakeholder updates, and a Risk Register that captures identified threats, their impact and likelihood, mitigation plans, and owner accountability. Release follows a standardized process with pre-release checklists (CI passing, security scans cleared, release notes drafted, rollback plan documented), deployment verification, and post-release announcement. Finally, retrospectives held after each sprint or milestone capture learnings, identify 2–3 prioritized action items with clear owners and due dates, and feed continuous improvements back into the process—creating a culture of psychological safety and data-informed iteration.

## Lifecycle Stages

1. **Initiation** — Validate the business need, align stakeholders, and create a lightweight one-pager
2. **Planning** — Break work into shippable increments, estimate, and identify dependencies
3. **Execution** — Build, test, review, and iterate with daily standups and weekly syncs
4. **Release** — Deploy to production with pre-release checklists and rollback plans
5. **Close & Retrospective** — Capture learnings and drive continuous improvement

## Core Principles

- **Customer-first** — Prioritize customer value and usability
- **Iterative delivery** — Ship small, testable increments
- **Clear ownership** — Named PM and Product Lead for each project
- **Data-informed** — Measure impact and iterate on evidence
- **Psychological safety** — Encourage feedback and learning

## Documentation Index

### For Project Managers & Product Leads
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, and artifacts
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate ideas, align stakeholders, and decide go/no-go
- **[Project Planning](octoacme-project-planning.md)** — How to break work into backlog items, estimate, and create release plans
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk registers, escalation paths, and stakeholder updates

### For Delivery Teams
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day workflows, standups, project board setup, and quality standards
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Pre-release checklists, deployment procedures, and rollback playbooks

### For Continuous Learning
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — How to run retros and convert learnings into action items
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Definitions of PM, Product Manager, Developers, and QA responsibilities

## Quick Reference

### By Role
- **Project Manager** → Start with [Project Management Overview](octoacme-project-management-overview.md) and [Project Initiation Guide](octoacme-project-initiation.md)
- **Product Manager** → See [Project Planning](octoacme-project-planning.md) and [Execution & Tracking](octoacme-execution-and-tracking.md)
- **Developer** → Review [Execution & Tracking](octoacme-execution-and-tracking.md) and [Release & Deployment Guide](octoacme-release-and-deployment.md)
- **QA/Tester** → See [Execution & Tracking](octoacme-execution-and-tracking.md) for quality and testing standards

### By Project Stage
- **Just Starting?** → [Project Initiation Guide](octoacme-project-initiation.md)
- **Planning Phase** → [Project Planning](octoacme-project-planning.md)
- **In Delivery** → [Execution & Tracking](octoacme-execution-and-tracking.md)
- **Ready to Release** → [Release & Deployment Guide](octoacme-release-and-deployment.md)
- **Post-Release** → [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## How to Use This Documentation

- Keep these docs in version control alongside your project charter and roadmap
- Link to relevant process docs in your project README or onboarding guide
- Treat these as living documents — update based on team feedback and continuous improvement action items
- Use Copilot Spaces to index these docs for quick reference during standups and planning sessions
- Propose updates to process docs using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template
