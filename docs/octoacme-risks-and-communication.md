# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- **Customer Success** maintains customer-specific communication channels
- **Technical Writer** ensures documentation accurately reflects current state
- **Release Manager** coordinates deployment-related communications

## Communication Templates
### Weekly Status Template
_Owner: Project Manager_
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

### Incident Communication
_Owner: Release Manager (technical) + Customer Success (customer-facing)_
- Triage summary
- Actions being taken
- Expected timeline
- Impact assessment
- Customer communication (if external impact)
- Post-incident blameless retrospective scheduled

### Customer Impact Communication
_Owner: Customer Success with input from PM_
- Issue description in customer-friendly terms
- Affected customers/features
- Workaround (if available)
- Timeline for resolution
- Follow-up plan

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
