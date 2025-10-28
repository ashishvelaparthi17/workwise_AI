---
title: [J2] OpenSearch Hybrid Upgrade
labels:
  - epic: J
  - type: story
---

## Epic
Epic J — Scale & Extras

## Description
Add OpenSearch for BM25 + k-NN; keep pgvector as source of truth.

## Acceptance Criteria
- [ ] Retriever chooses OpenSearch for keyword-heavy queries.

## Testing / Validation
- Performance regression test; index sync job idempotent.
