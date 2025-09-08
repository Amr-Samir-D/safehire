# Step 03 — Basic API Smoke Test

## Objective
Confirm Express backend starts correctly and APIs respond as expected.

## Deliverables
- Start backend: `npm run dev` or `docker-compose up`.
- Verify `/api/health` endpoint responds with `{"status":"ok"}`.
- Test `/api/auth/register` with sample user.
- Test `/api/auth/login` and receive JWT.
- Update `step_03_results.md`.

## Verification
- Output from `curl http://localhost:3000/api/health`.
- JSON response from register/login API.
- Confirm Prisma logs show queries executing.

---
**Note:** Record test commands and results in `step_03_results.md`.
