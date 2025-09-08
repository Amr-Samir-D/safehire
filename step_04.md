# Step 04 — Authentication & Google Login

## Objective
Implement secure JWT authentication and Google OAuth login.

## Deliverables
- Ensure `/api/auth/login`, `/api/auth/register`, `/api/auth/me` work with JWT.
- Add Google OAuth login with `passport-google-oauth20`.
- Configure Google Client ID/Secret in `.env`.
- Verify login via Google returns JWT and user record.
- Update `step_04_results.md`.

## Verification
- Login with email/password returns JWT.
- Hitting `/api/auth/me` with JWT returns user profile.
- Login with Google successfully creates/returns user.
- Screenshots or logs for verification.

---
**Note:** Results must be logged in `step_04_results.md`.
