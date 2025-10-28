---
title: [G1] Tracing & Metrics
labels:
  - epic: G
  - type: story
---

## Epic
Epic G — Observability, QA, and Ops

## Description
OpenTelemetry + Langfuse for traces, prompts, token usage, errors.

## Acceptance Criteria
- [ ] Each `/ask` has trace_id; spans for nodes & tools.

## Testing / Validation
- Force error → see spans with exception details.
