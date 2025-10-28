---
title: [D1] Embeddings Store (pgvector)
labels:
  - epic: D
  - type: story
---

## Epic
Epic D — RAG Index & Retrieval

## Description
Provision Postgres+pgvector; table `chunks` with text + vector + metadata.

## Acceptance Criteria
- [ ] Upsert by content hash; GIN for BM25 fallback (pg_trgm or OpenSearch later).

## Testing / Validation
- Insert/search e2e; ensure dedupe by hash.
