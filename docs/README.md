# OctoAcme — Project Management Docs

## Summary
OctoAcme uses a lightweight, iterative project management approach focused on clear ownership, iterative delivery, measurable outcomes, and continuous improvement. This collection of documents captures our processes for starting work, planning, executing, releasing, and learning from projects so contributors and stakeholders can find and follow a consistent approach.

## Brief overview of core processes
- Initiation: Validate ideas with a Project One-pager, identify stakeholders, and decide go/no-go before planning.
- Planning: Break approved work into a prioritized backlog with acceptance criteria, estimates, and a release timeline.
- Execution: Deliver in small increments using the project board and standard PR workflow (small PRs, CI, reviews), run tests and QA, and track progress in weekly syncs.
- Release & Deployment: Follow pre-release checks, run staging smoke tests, deploy via automated pipelines when possible, and have rollback/playbook steps ready.
- Retrospectives & Continuous Improvement: Capture learnings after sprints/releases/incidents, convert them into action items, and track improvements in the backlog.
- Risk & Communication: Maintain a Risk Register, provide regular stakeholder updates, and follow escalation paths for blockers and incidents.

## Documents
- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Release & Deployment](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

## How to use
- Read the Overview to understand roles, cadence, and key artifacts.
- Use the Initiation and Planning docs when starting new projects to create one-pagers and prioritized backlogs.
- Follow Execution & Tracking and Release guides during implementation and deployment.
- Capture improvements in Retrospectives and track risks in the Risk Register.
- Use the ISSUE_TEMPLATE "Add Content to Project Management Process Docs" to propose updates or new docs.

## Maintainers & process
- Docs live in the docs/ folder and are updated via pull requests.
- Use the process doc issue template for proposed updates or additions.
- Suggested PR title for changes to these docs: "[Process Doc Update]: <short description>"
