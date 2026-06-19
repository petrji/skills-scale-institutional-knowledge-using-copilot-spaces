# OctoAcme Project Management Docs

## Purpose

This folder contains the complete set of OctoAcme project management processes, designed to help teams understand how we run projects collaboratively, deliver value iteratively, and maintain transparency across stakeholders. These documents serve as a central source of truth for project governance, workflow standards, and best practices.

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](#project-management-overview) for a high-level introduction.
- **Starting a new project?** Follow the progression: Initiation → Planning → Execution & Tracking → Release & Deployment → Retrospectives.
- **Looking for guidance on a specific topic?** Use the index below to find the relevant process document.
- **Contributing to these docs?** Use the issue template [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose updates or new content.

---

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured, five-phase project lifecycle designed to ensure customer-first delivery with clear ownership and data-informed decisions. The lifecycle begins with **Initiation**, where new ideas are validated through a lightweight Project One-pager that confirms business need, identifies stakeholders, and establishes success metrics. Once approved, projects move into **Planning**, where work is broken into shippable increments with prioritized backlogs, detailed acceptance criteria, and a Definition of Done. The core **Execution & Tracking** phase manages day-to-day delivery through daily standups, weekly delivery syncs, and a GitHub Projects board with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done). Small pull requests (≤400 lines) with automated testing, linting, and at least one approval ensure quality throughout. Finally, projects reach **Release & Deployment**, where pre-release requirements (passing CI, security scans, smoke tests) and a documented rollback plan mitigate production risk, followed by **Retrospectives** to capture learnings and drive continuous improvement.

The organizational structure relies on three core personas with distinct responsibilities: **Developers** implement features, maintain tests, and identify technical risks while collaborating on design reviews; **Product Managers** define what to build, prioritize backlogs, and measure outcomes through data-driven decisions; and **Project Managers** coordinate delivery schedules, manage risks and dependencies, and ensure transparent stakeholder communication. This clear role separation prevents ambiguity and enables efficient decision-making across cross-functional teams.

Risk and communication management are embedded throughout the process. OctoAcme maintains a Risk Register (tracking ID, description, impact, likelihood, owner, and mitigation) that is reviewed weekly during syncs, with escalation paths flowing from team level → PM → Product Lead → Sponsor. Stakeholder communication follows a consistent cadence—weekly syncs between PM and Product Manager, twice-weekly standups for delivery teams, and monthly stakeholder updates—using standardized templates for status reports and incident communications to ensure transparency and alignment.

Quality assurance is a shared responsibility integrated at every stage: unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, and security scanning in CI pipelines. Manual QA validates feature acceptance when needed, while velocity and burndown metrics track progress. Together, these practices—rigorous workflows, clear roles, structured communication, and quality gates—enable OctoAcme teams to deliver reliable increments while maintaining stakeholder confidence and organizational learning.

---

## Process Documents Index

### [Project Management Overview](./octoacme-project-management-overview.md)
A concise introduction to OctoAcme's approach, core roles (PM, Product Manager, Developers, QA, Stakeholders), key artifacts, and the high-level project lifecycle. Use this as your entry point to understand OctoAcme's foundational principles: customer-first delivery, iterative development, clear ownership, data-informed decisions, and psychological safety.

### [Project Initiation Guide](./octoacme-project-initiation.md)
Lightweight steps to validate and authorize new work before moving into detailed planning. Covers the Project One-pager template, stakeholder identification, success metrics, and the decision gate for moving into planning. Start here when exploring a new project idea or feature proposal.

### [Project Planning](./octoacme-project-planning.md)
Turning an approved initiative into an actionable plan and backlog for delivery. Includes activities like kickoff meetings, backlog prioritization, estimation, Definition of Done, dependency mapping, and release planning. Use this when your project has been greenlit and you're ready to break work into shippable increments.

### [Execution & Tracking](./octoacme-execution-and-tracking.md)
Day-to-day execution workflows, team rhythm (standups, syncs, demos), pull request standards, quality and testing practices, reporting metrics, and blocker escalation. Reference this during sprint planning and throughout delivery to ensure alignment on workflows and quality expectations.

### [Risk Management & Communication](./octoacme-risks-and-communication.md)
How to identify, assess, and monitor risks using a Risk Register, maintain stakeholder communication, and escalate issues. Covers communication templates (weekly status, incident communication) and escalation paths. Use this to manage project health and keep stakeholders informed.

### [Release & Deployment Guide](./octoacme-release-and-deployment.md)
Standardize how OctoAcme releases features to production. Covers release types (patch, minor, major), pre-release requirements, deployment checklist, rollback and incident playbook, and release notes template. Reference this when preparing a release or responding to a production incident.

### [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
How to run effective retrospectives after sprints, releases, or milestones to capture learnings and convert them into actionable improvements. Includes structure, facilitation tips, action item tracking, and a continuous improvement culture mindset. Use this after significant milestones to drive team learning.

### [Roles & Personas](./octoacme-roles-and-personas.md)
Detailed definitions of typical roles used in OctoAcme projects: Developers, Product Managers, and Project Managers. Clarifies responsibilities, goals, and typical communication for each persona. Reference this when onboarding new team members or clarifying role expectations.

---

## Quick Links

- **[OctoAcme Project Management Overview](./octoacme-project-management-overview.md)** — Start here for a high-level understanding
- **[Project One-pager Template](./octoacme-project-initiation.md#project-one-pager-template)** — Lightweight project validation
- **[Risk Register](./octoacme-risks-and-communication.md#risk-register)** — Track and manage risks
- **[Backlog Item Template](./octoacme-project-planning.md#backlog-item-template)** — Standard work item format
- **[Definition of Done](./octoacme-project-planning.md#sprint--iteration-planning)** — Quality and acceptance criteria

---

## Contributing

To propose updates, additions, or clarifications to these process documents, please open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template. This ensures your proposal is reviewed for alignment with existing processes and team needs.
