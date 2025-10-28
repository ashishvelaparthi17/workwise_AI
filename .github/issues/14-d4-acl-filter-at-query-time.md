---
title: [D4] ACL Filter at Query-time
labels:
  - epic: D
  - type: story
---

## Epic
Epic D — RAG Index & Retrieval

## Description
Apply ABAC filter in SQL to exclude chunks outside user ACL.

## Acceptance Criteria
- [ ] No chunk leaves service without ACL check; audits record filter card.

## Testing / Validation
- User with reduced ACL sees fewer results; snapshots differ.
