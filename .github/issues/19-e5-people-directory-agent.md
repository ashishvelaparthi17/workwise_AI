---
title: [E5] People/Directory Agent
labels:
  - epic: E
  - type: story
---

## Epic
Epic E — Agents & Orchestration (LangGraph)

## Description
Lookup owners (LDAP/Okta), on-call (PagerDuty), Slack channels.

## Acceptance Criteria
- [ ] Given service name → returns team, Slack channel, PD schedule.

## Testing / Validation
- Missing data handled with graceful fallback message.
