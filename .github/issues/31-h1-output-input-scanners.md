---
title: [H1] Output & Input Scanners
labels:
  - epic: H
  - type: story
---

## Epic
Epic H — Security & Compliance

## Description
Redact secrets/PII; allow-list domains for tool calls.

## Acceptance Criteria
- [ ] Blocks outbound URLs not in allow-list; masks tokens.

## Testing / Validation
- E2E with injected secret string → redacted.
