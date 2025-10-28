---
title: [C1] Confluence Connector (Read-only)
labels:
  - epic: C
  - type: story
---

## Epic
Epic C — Ingestion & Content Lake

## Description
Incremental pull of spaces/pages via API; store raw HTML + metadata.

## Acceptance Criteria
- [ ] Delta by `updated_at`/hash; backoff on rate limits.
- [ ] S3/Blob: `raw/confluence/{space}/{pageId}.html`.

## Testing / Validation
- Seed with 50+ pages; rerun job updates only changed pages.
