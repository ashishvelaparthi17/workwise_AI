---
title: [E7] Workflow Agent (Draft Jira)
labels:
  - epic: E
  - type: story
---

## Epic
Epic E — Agents & Orchestration (LangGraph)

## Description
Prefill Jira ticket templates (access requests, onboarding tasks) but don’t auto-submit.

## Acceptance Criteria
- [ ] `POST /api/v1/actions/jira/draft` returns URL with prefilled fields.

## Testing / Validation
- Required fields enforce; invalid project returns 400.
