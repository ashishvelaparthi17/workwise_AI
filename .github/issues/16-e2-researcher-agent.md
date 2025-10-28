---
title: [E2] Researcher Agent
labels:
  - epic: E
  - type: story
---

## Epic
Epic E — Agents & Orchestration (LangGraph)

## Description
Calls Hybrid Search, fuses chunks, resolves near-dupes, produces citations.

## Acceptance Criteria
- [ ] Returns 3–5 sources with titles, anchors, last-updated.

## Testing / Validation
- Hallucination guard: returns "insufficient evidence" if <2 strong sources.
