---
title: [C4] Chunking & Normalization
labels:
  - epic: C
  - type: story
---

## Epic
Epic C — Ingestion & Content Lake

## Description
Convert HTML/MD → clean text; semantic chunking 300–800 tokens; preserve headings.

## Acceptance Criteria
- [ ] Each chunk has `doc_id, title, section_anchor, url, updated_at, acl_fingerprint`.

## Testing / Validation
- Snapshot test ensures headings & anchors preserved.
