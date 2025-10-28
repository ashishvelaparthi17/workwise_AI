---
title: [F4] `/api/v1/admin/reindex`
labels:
  - epic: F
  - type: story
---

## Epic
Epic F — Backend API Surface (FastAPI)

## Description
Admin-only trigger for connector & embeddings jobs.

## Acceptance Criteria
- [ ] Kicks SQS/EventBridge; returns job id.

## Testing / Validation
- Unauthorized returns 403; job shows in ops dashboard.
