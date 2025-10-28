---
title: [A1] Repo & Mono-repo Structure
labels:
  - epic: A
  - type: story
---

## Epic
Epic A — Project Scaffolding & DevX

## Description
Create mono-repo `intra-copilot` with `/backend`, `/frontend`, `/infra`, `/docs`, `/ops`. Python toolchain, pre-commit, black, ruff, mypy, pytest.

## Acceptance Criteria
- [ ] Repo created with README, CONTRIBUTING, CODEOWNERS.
- [ ] Makefile tasks (`make dev`, `make test`, `make fmt`, `make lint`).
- [ ] CI runs lint+tests on PR.

## Testing / Validation
- Push PR with a failing lint and verify CI blocks.
- `make dev` starts local FastAPI server.
