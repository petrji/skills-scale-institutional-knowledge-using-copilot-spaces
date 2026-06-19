# OctoAcme Project Management Docs

## Overview

This folder contains the complete OctoAcme project management process documentation. These guides serve as a central source of truth for how we run projects, from initial conception through retrospective and continuous improvement.

These docs are designed to:
- **Reduce onboarding friction** by providing clear, consistent guidance for all team members
- **Enable consistent execution** across cross-functional projects
- **Capture institutional knowledge** so processes aren't lost to single-person dependencies
- **Support continuous improvement** by maintaining a versioned, collaborative source of truth

## How to Use These Docs

1. **New to OctoAcme?** Start with [Project Management Overview](#project-management-overview) to understand our principles and roles.
2. **Starting a new project?** Follow the lifecycle docs in order: Initiation → Planning → Execution & Tracking → Release & Deployment → Retrospective.
3. **Need guidance on a specific topic?** Use the process index below to jump directly to the relevant document.
4. **Contributing improvements?** Use the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose changes.

---

## OctoAcme Project Lifecycle

### 1. [Project Management Overview](./octoacme-project-management-overview.md)

**Purpose:** Provides a concise introduction to how OctoAcme runs projects.

**Key Topics:**
- Core principles (customer-first, iterative delivery, clear ownership, data-informed, psychological safety)
- Core roles and responsibilities (PM, PdM, Developers, QA, Stakeholders)
- Key artifacts (Project Charter, Roadmap, Sprint Backlog, Risk Register)
- High-level project lifecycle
- Communication cadence

**When to Use:** Start here as your introduction to OctoAcme's approach. Reference this when onboarding new team members or when establishing expectations for a new project.

---

### 2. [Project Initiation Guide](./octoacme-project-initiation.md)

**Purpose:** Define the initial steps to validate and authorize work, align stakeholders, and create a lightweight plan.

**Key Topics:**
- Goals and decision criteria for moving into planning
- Minimum deliverables (Project One-pager, stakeholder list, timeline, risks, resources)
- Project One-pager template
- Initiation checklist
- Decision gate criteria

**When to Use:** When a new project idea or feature proposal is ready to be explored. Use this to create lightweight business justification before investing heavily in planning.

---

### 3. [Project Planning](./octoacme-project-planning.md)

**Purpose:** Turn an approved initiative into an actionable plan and backlog for delivery.

**Key Topics:**
- Planning activities (kickoff, backlog creation, estimation, DoD definition, dependency mapping)
- Backlog item template
- Sprint/iteration planning approach
- Risk & dependency management
- Planning checklist

**When to Use:** After initiation approval, use this to break work into shippable increments, estimate scope, and identify dependencies and risks.

---

### 4. [Execution & Tracking](./octoacme-execution-and-tracking.md)

**Purpose:** Guidance for managing day-to-day execution and tracking progress toward project milestones.

**Key Topics:**
- Team rhythm (standups, delivery syncs, demos)
- Project board workflow and conventions
- Pull Request workflow and quality standards
- Quality & testing expectations
- Reporting & metrics (velocity, burndown, success metrics)
- Blocker escalation levels
- Execution checklist

**When to Use:** During the active delivery phase. Reference this for daily standups, sprint planning, PR standards, and escalation patterns.

---

### 5. [Risk Management & Communication](./octoacme-risks-and-communication.md)

**Purpose:** Explain how to identify, manage, and communicate risks and dependencies throughout the project.

**Key Topics:**
- Risk register structure and lifecycle
- Stakeholder communication planning
- Communication templates (weekly status, incidents)
- Escalation paths (team-level → PM → Product Lead → Sponsor)

**When to Use:** Use throughout the project lifecycle to maintain awareness of risks, keep stakeholders informed, and escalate issues appropriately.

---

### 6. [Release & Deployment Guide](./octoacme-release-and-deployment.md)

**Purpose:** Standardize how OctoAcme releases features to production to reduce risk and improve observability.

**Key Topics:**
- Release types (patch, minor, major)
- Pre-release requirements (acceptance criteria, passing CI, release notes, rollback plan)
- Deployment checklist
- Rollback & incident playbook
- Release notes template

**When to Use:** When preparing for release to production. Use this to ensure all pre-release gates are met and to standardize deployment and communication practices.

---

### 7. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

**Purpose:** Capture learnings and convert them into actionable improvements.

**Key Topics:**
- When to run retrospectives (after sprint, release, milestone, or incident)
- Retrospective structure (what went well, what could improve, action items)
- Running a retrospective (timebox, facilitation, anonymity options)
- Tracking and measuring improvements
- Action item template

**When to Use:** After each sprint, release, or important milestone. Use this to learn from experience and drive continuous process improvement.

---

### 8. [Roles & Personas](./octoacme-roles-and-personas.md)

**Purpose:** Define typical roles and responsibilities used across OctoAcme projects.

**Included Roles:**
- **Developers:** Design, build, test, and deliver software components.
- **Product Managers:** Define what to build to deliver customer and business value.
- **Project Managers:** Coordinate delivery, manage schedules, risks, and communications.

**When to Use:** Reference this when clarifying role boundaries, responsibilities, and typical communication patterns. Use as a basis for defining team structure for new projects.

---

## Quick Links

| Process | Document | Purpose |
|---------|----------|----------|
| Overview | [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) | Principles, roles, artifacts, lifecycle |
| Initiation | [octoacme-project-initiation.md](./octoacme-project-initiation.md) | Validate work, align stakeholders, lightweight planning |
| Planning | [octoacme-project-planning.md](./octoacme-project-planning.md) | Create backlog, estimate, identify dependencies |
| Execution | [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) | Day-to-day workflows, tracking, escalation |
| Risks & Communication | [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) | Risk management, stakeholder updates, escalation |
| Release | [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) | Pre-release checks, deployment, rollback |
| Retrospective | [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings, drive improvement |
| Roles | [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) | Role definitions and responsibilities |

---

## Contributing to Process Documentation

If you identify a gap, have a suggestion, or want to propose an update to these process docs:

1. **Create an issue** using the [Process Doc Update template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
2. **Include:**
   - Which document you want to update (or if it's a new document)
   - Summary of the proposed content or update
   - Why this update is needed
   - Suggested content (optional)
3. **Discuss with stakeholders** if needed before implementing
4. **Submit a PR** with your changes and link the issue

Our goal is to keep these docs living, evolving artifacts that reflect how we actually work.

---

## Document Maintenance

These documents are version-controlled and live in this repository. To keep them current:

- **Review and update** process docs after each major project cycle or significant change
- **Capture learnings** in retrospectives and feed improvements back into the docs
- **Link** to these docs from project boards and charters
- **Reference** these docs in kickoff meetings, planning sessions, and onboarding

---

## Questions or Feedback?

If you have questions about these processes or suggestions for improvement, please:
- Create an issue using the [Process Doc Update template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
- Reach out to your Project Manager or Product Manager
- Discuss in team meetings or retrospectives
