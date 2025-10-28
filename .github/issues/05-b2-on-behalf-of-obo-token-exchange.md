---
title: [B2] On-Behalf-Of (OBO) Token Exchange
labels:
  - epic: B
  - type: story
---

## Epic
Epic B — Identity, AuthN/Z, and OBO

## Description
For downstream tools, exchange incoming token → OBO tokens per connector.

## Acceptance Criteria
- [ ] Token broker module issues per-resource OBO (Confluence, GitHub, Jira).
- [ ] Failed exchange returns 401 with trace id.

## Testing / Validation
- Simulate downstream call; assert OBO audience and expiry.
