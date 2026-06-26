# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Additional Personas (New)

### Technical Program Manager (TPM)
- Role summary: Coordinates cross-team technical delivery for complex initiatives. Tracks technical dependencies and milestone-level delivery.
- Responsibilities:
  - Maintain cross-team milestone plans and dependency maps
  - Facilitate technical decision and dependency-resolution meetings
  - Surface and track major technical risks and mitigations
- Interactions:
  - Works with PMs and PdMs to align delivery timelines
  - Partners with Engineering Managers and Tech Leads to unblock implementation
  - Escalates cross-team blockers to Project Manager when broader coordination is needed

### UX Researcher / Designer
- Role summary: Owns user research, ensures designs meet user needs, and validates usability.
- Responsibilities:
  - Plan and run research sessions and usability tests
  - Synthesize findings into actionable insights and design recommendations
  - Produce wireframes, prototypes, and acceptance criteria tied to UX outcomes
- Interactions:
  - Collaborates with PdMs on user needs and success metrics
  - Hands off designs to Developers and supports implementation with design notes
  - Participates in acceptance and usability reviews during QA

### Site Reliability Engineer (SRE) / Operations
- Role summary: Ensures systems are reliable, observable, and operable in production.
- Responsibilities:
  - Define and monitor SLOs / SLIs and alerting
  - Own runbooks and incident response procedures
  - Advise on system architecture for reliability and scalability
- Interactions:
  - Works with Developers to design for operability
  - Coordinates with Release Manager for safe deployments and verification
  - Informs PMs and stakeholders about operational risks and mitigation plans

### Data Analyst / Data Engineer
- Role summary: Provides measurement, instrumentation, and analysis to validate success metrics and guide decisions.
- Responsibilities:
  - Define metrics, events, and instrumentation needs
  - Build dashboards and reports for stakeholders
  - Run experiments and analyses to validate feature impact
- Interactions:
  - Partners with PdMs to define success metrics and measurement plans
  - Supports Developers with instrumentation specifications
  - Informs retrospectives and prioritization through data insights

### Release Manager / DevOps Lead
- Role summary: Coordinates releases, staging verification, and rollback plans.
- Responsibilities:
  - Schedule release windows and manage the release runbook
  - Ensure CI/CD pipeline health and pre-release checks
  - Own rollback/mitigation plans and coordinate post-deploy verification
- Interactions:
  - Works closely with SREs and Developers during deployments
  - Notifies stakeholders and support teams about release timelines and impact
  - Coordinates incident handoffs post-deploy when needed

### Security / Compliance Lead
- Role summary: Ensures security and regulatory requirements are met across the project lifecycle.
- Responsibilities:
  - Conduct security reviews and threat modeling
  - Run compliance checks and audit-related tasks
  - Triage vulnerabilities and advise on remediation
- Interactions:
  - Partners with Developers and SREs to remediate issues
  - Advises PdMs on regulatory and compliance constraints that affect scope or timelines

### Support / Customer Success Liaison
- Role summary: Brings customer feedback and support signals into planning and prioritization.
- Responsibilities:
  - Triage customer issues and identify recurring problems
  - Surface high-impact support cases and coordinate hotfix requests
  - Provide input on prioritization from the customer perspective
- Interactions:
  - Works with PMs and Developers on priority bugs and hotfixes
  - Informs acceptance criteria and customer-facing communications

---

## Handoffs and Interaction Examples
- Incident: SRE leads response and runbook execution; Project Manager coordinates communications and stakeholder updates; Developers fix root cause; Support communicates status to customers.
- New feature delivery: PdM defines success metrics; UX Researcher validates design; Developers implement; Data Analyst verifies instrumentation; Release Manager schedules deployment; SRE monitors SLOs.
- Cross-team technical program: TPM maintains milestone plan, coordinates Tech Leads, raises cross-team risks at weekly PM syncs.

---

## Role RACI (example)
- Feature acceptance: Responsible — Developers; Accountable — Product Manager; Consulted — UX Researcher, QA; Informed — Project Manager, Support
- Production incidents: Responsible — SRE; Accountable — SRE / Engineering Manager; Consulted — Developers, Release Manager; Informed — PM, Support

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
