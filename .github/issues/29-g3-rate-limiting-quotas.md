---
title: [G3] Rate Limiting & Quotas
labels:
  - epic: G
  - type: story
---

## Epic
Epic G — Observability, QA, and Ops

## Description
Per-user and per-org throttles; friendly 429 with retry-after.

## Acceptance Criteria
- [ ] Configurable via env/flags.

## Testing / Validation
- Load test hits limits; logs show bucket state.
