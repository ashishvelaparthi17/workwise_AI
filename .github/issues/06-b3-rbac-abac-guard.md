---
title: [B3] RBAC & ABAC Guard
labels:
  - epic: B
  - type: story
---

## Epic
Epic B — Identity, AuthN/Z, and OBO

## Description
Implement org roles (admin, maintainer, user) + attribute-based checks (team, space).

## Acceptance Criteria
- [ ] Policy middleware enforces route access; audit log on deny.

## Testing / Validation
- Matrix tests for roles × routes; denial paths logged.
