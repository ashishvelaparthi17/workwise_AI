---
title: [E8] Parallelization & Retry Policy
labels:
  - epic: E
  - type: story
---

## Epic
Epic E — Agents & Orchestration (LangGraph)

## Description
Enable parallel subgraphs (e.g., Researcher + People) and idempotent retries.

## Acceptance Criteria
- [ ] p95 latency improves vs serial; retries don’t duplicate side effects.

## Testing / Validation
- Chaos tests: transient failure recovers; dedupe key works.
