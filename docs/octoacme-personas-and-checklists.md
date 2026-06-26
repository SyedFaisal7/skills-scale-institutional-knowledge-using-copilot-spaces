# Personas & Process Checklists

This file provides practical checklists and templates to accompany the personas in docs/octoacme-roles-and-personas.md. Use these to reduce handoff friction and improve clarity of ownership.

## Role Handoff Checklist (use at major handoffs)
- [ ] Single owner assigned for the handoff
- [ ] Acceptance criteria documented and attached to the issue/PR
- [ ] Stakeholders and affected teams notified
- [ ] Dependencies identified and owners assigned
- [ ] Monitoring and rollback plan attached (if deployable)
- [ ] Post-handoff validation steps defined (who verifies, how)

## Planning Checklist (kickoff → sprint readiness)
- [ ] Project one-pager present and approved
- [ ] Success metrics defined and measurable
- [ ] High-level timeline and milestones created
- [ ] Backlog items prioritized and sized
- [ ] Owners assigned for top-priority work
- [ ] SRE/DevOps consulted for deployability concerns
- [ ] UX Researcher consulted for user-facing features
- [ ] Data Analyst consulted for instrumentation needs

## Release & Deployment Checklist
- Pre-release
  - [ ] All PRs merged with approvals
  - [ ] CI & security scans passing
  - [ ] Release notes drafted
  - [ ] Rollback plan documented
  - [ ] Stakeholders and on-call informed
- Release
  - [ ] Deploy to staging and run smoke tests
  - [ ] Verify key SLOs/health checks
  - [ ] Deploy to production per runbook
- Post-release
  - [ ] Run post-deploy verification
  - [ ] Monitor dashboards for regressions
  - [ ] Communicate release status to stakeholders

## Risk Register template (CSV / table format)
- ID | Description | Impact (H/M/L) | Likelihood (H/M/L) | Owner | Mitigation | Status

## Suggested usage
- Add the Role Handoff Checklist to the issue template when work moves Ready→In Progress.
- Attach Planning Checklist items to kickoff notes.
- Use the Release Checklist as part of the PR checklist for release PRs.

## Notes
- Keep checklists lightweight and actionable — prefer links to actual runbooks and dashboards rather than duplicating content.
