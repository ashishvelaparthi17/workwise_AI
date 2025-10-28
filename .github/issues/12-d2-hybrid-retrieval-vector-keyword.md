---
title: [D2] Hybrid Retrieval (Vector + Keyword)
labels:
  - epic: D
  - type: story
---

## Epic
Epic D — RAG Index & Retrieval

## Description
Implement retriever that merges vector top-k with BM25 and re-ranks.

## Acceptance Criteria
- [ ] API: `search_knowledge(query, sources[], k)` returns ranked chunks with scores.

## Testing / Validation
- Queries with rare acronyms favor keyword; semantic paraphrases still hit.
