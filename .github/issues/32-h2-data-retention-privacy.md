---
title: [H2] Data Retention & Privacy
labels:
  - epic: H
  - type: story
---

## Epic
Epic H — Security & Compliance

## Description
Configurable chat history TTL; "don’t store this" option.

## Acceptance Criteria
- [ ] `/ask` accepts `ephemeral=true`; history bypasses persistence.

## Testing / Validation
- TTL expiry removes rows; privacy banner shown.
