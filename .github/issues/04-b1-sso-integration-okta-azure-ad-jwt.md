---
title: [B1] SSO Integration (Okta/Azure AD) + JWT
labels:
  - epic: B
  - type: story
---

## Epic
Epic B — Identity, AuthN/Z, and OBO

## Description
Implement OAuth2 Authorization Code flow; issue signed service JWT; map claims to user.

## Acceptance Criteria
- [ ] `/auth/login` redirects to IdP, `/auth/callback` completes sign-in.
- [ ] Access token stored server-side; frontend gets HttpOnly session cookie.

## Testing / Validation
- Happy path login; token expiry refresh; logout clears session.
