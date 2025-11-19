# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted (Technical Writer with input from PM/PdM)
- Rollback / mitigation plan documented (Release Manager)
- Smoke tests prepared (QA Lead)
- Documentation updated and published (Technical Writer)
- Customer communication plan ready (Customer Success for customer-facing releases)

## Deployment Checklist
_Release Manager coordinates; PM and Tech Lead support_
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests (QA Lead signs off)
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications (Release Manager confirms)
- [ ] Announce release to stakeholders and support (PM communicates internally)
- [ ] Customer communication sent (Customer Success for customer-facing changes)
- [ ] Documentation live and accessible (Technical Writer confirms)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (Release Manager coordinates)
  - Notify Customer Success immediately for customer-impacting issues
  - Rollback to last known-good release if necessary (Release Manager executes)
  - Triage root cause and capture action items (PM facilitates, Scrum Master tracks follow-ups)
  - Update customers on status and resolution (Customer Success communicates)

## Release Notes Template
_Owner: Technical Writer (with input from PM and PdM)_
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
- Documentation links:
