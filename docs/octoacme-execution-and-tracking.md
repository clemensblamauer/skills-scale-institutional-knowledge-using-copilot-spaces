# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- **Daily standups** (15 min) — focus on progress, blockers, dependencies
  - _Facilitated by: Scrum Master_
  - _Attendees: Core delivery team (Developers, QA, UX Designer as needed)_
- **Weekly delivery sync** — show progress, updates, and flagged risks
  - _Facilitated by: Project Manager_
  - _Attendees: PM, PdM, Tech Lead, and key stakeholders_
- **Demo/Review** at the end of each sprint or milestone
  - _Facilitated by: Scrum Master or Project Manager_
  - _Attendees: Full team, stakeholders, Customer Success (for customer-facing features)_

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- **UX validation**: UX Designer reviews implementation against designs
- **Documentation updates**: Technical Writer ensures docs reflect new features

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- **Level 1**: Team-level triage in daily standup (Scrum Master facilitates)
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues
- **Customer-impacting issues**: Customer Success notified immediately for communication planning

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled (Scrum Master coordinates)
- [ ] Risk register updated weekly (PM owns, team contributes)
- [ ] UX validation integrated into review process (if UX Designer assigned)
- [ ] Documentation updates tracked alongside feature work (Technical Writer)
- [ ] Customer feedback loop established (Customer Success)
