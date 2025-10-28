---
title: [A2] FastAPI App Skeleton
labels:
  - epic: A
  - type: story
---

## Epic
Epic A — Project Scaffolding & DevX

## Description
Bootstrap FastAPI app with health endpoints, versioning (`/api/v1`).

## Acceptance Criteria
- [ ] `/healthz` returns 200, `/version` returns git sha + semver.
- [ ] Pydantic settings via env/.env.

## Testing / Validation
- Curl both endpoints; verify JSON schema & non-regression test.
