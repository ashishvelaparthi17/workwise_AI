---
title: [F1] `/api/v1/ask`
labels:
  - epic: F
  - type: story
---

## Epic
Epic F — Backend API Surface (FastAPI)

## Description
Primary chat endpoint → runs LangGraph with user context & ACL.

## Acceptance Criteria
- [ ] Request: `query`, optional `tools_allowed`, `max_tokens`.
- [ ] Response: `answer`, `citations[]`, `plan`, `trace_id`.

## Testing / Validation
- Contract tests; large queries truncated with 413.
