---
title: [D3] Re-ranker Service
labels:
  - epic: D
  - type: story
---

## Epic
Epic D — RAG Index & Retrieval

## Description
Host cross-encoder (e.g., bge-reranker-base) behind internal HTTP.

## Acceptance Criteria
- [ ] Re-rank API SLA p95 < 200ms on N=50.

## Testing / Validation
- A/B shows MRR/NDCG uplift vs no re-rank.
