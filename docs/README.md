# OctoAcme — Project Management Docs

## Overview

OctoAcme uses a lightweight, iterative project management approach focused on **clear ownership**, **iterative delivery**, **measured outcomes**, and **continuous improvement**. The framework guides projects through five core phases—Initiation, Planning, Execution, Release, and Retrospective—with emphasis on transparency, stakeholder alignment, and data-driven decisions.

### Key Principles
- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments to gather feedback early
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning from all team members

### Core Roles
- **Project Manager**: Coordinates delivery, schedules, risk, and communications
- **Product Manager**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

### Project Lifecycle
1. **Initiation**: Problem statement, stakeholders, high-level timeline, success metrics
2. **Planning**: Scope, resources, milestones, dependencies, backlog prioritization
3. **Execution**: Build, test, review, iterate with daily standups and weekly syncs
4. **Release**: Deploy to production with smoke tests and rollback plan
5. **Close & Retrospective**: Capture learnings and feed improvements back into processes

### Communication Cadence
- **Daily**: Team standups (15 min) for progress and blockers
- **Weekly**: PM-PdM alignment and delivery team syncs
- **Monthly**: Stakeholder updates and progress reports
- **As-needed**: Escalations following three-level path (Team → PM → Product Lead → Sponsor)

### Quality & Risk Management
- Unit tests and integration tests for new features
- CI automation for tests, linting, and security scanning
- Pull request reviews with at least one approval required
- Manual QA for feature acceptance when needed
- Active Risk Register maintained and reviewed weekly
- Documented rollback plans for rapid recovery

---

## Documents

Navigate to the process document that best fits your current phase or need:

### Starting a New Project
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to roles, artifacts, and project lifecycle
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Validate business need, align stakeholders, create one-pagers

### Planning & Scoping
- **[Project Planning](octoacme-project-planning.md)** — Break work into increments, estimate scope, identify dependencies, define Definition of Done

### Building & Tracking Progress
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Daily standups, PR workflow, project board usage, quality gates, blocker escalation

### Managing Risks & Stakeholders
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk register, lifecycle, stakeholder communication templates, escalation paths

### Releasing to Production
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Pre-release checklist, deployment process, rollback playbook, release notes

### Learning & Improving
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Run retrospectives, track action items, build a culture of continuous improvement

### Understanding Roles
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed responsibilities and communication patterns for Developers, Product Managers, and Project Managers

---

## How to Use These Docs

**For Project Leads & PMs:**
1. Start with the **Overview** to understand the full lifecycle
2. Use **Initiation** and **Planning** docs to launch new projects
3. Reference **Execution & Tracking** during implementation
4. Follow **Release & Deployment** when shipping to production
5. Capture improvements in **Retrospectives**

**For Developers:**
1. Review **Execution & Tracking** for PR workflow, testing requirements, and escalation paths
2. Reference **Release & Deployment** to understand pre-release quality gates
3. Participate in **Retrospectives** to contribute to process improvements

**For Stakeholders & Sponsors:**
1. Read the **Overview** for context on roles and cadence
2. Reference **Risk Management & Communication** for status updates and escalation processes
3. Review **Release & Deployment** for go-live readiness

---

## Contributing to These Docs

Found a gap or want to improve a process document? Use the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose changes. All improvements are tracked as issues to maintain transparency and alignment.

---

## Quick Reference

| Phase | Key Activity | Owner | Artifact |
|-------|--------------|-------|----------|
| Initiation | Validate need, align stakeholders | PM + PdM | One-pager, Risk list |
| Planning | Scope work, estimate, plan release | PM + Dev Team | Backlog, Release plan |
| Execution | Build, test, review incrementally | Dev Team + QA | PRs, Project board |
| Release | Deploy and verify in production | PM + Ops | Release notes, Rollback plan |
| Retrospective | Capture learnings and improvements | PM + Team | Action items, Metrics |
