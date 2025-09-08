# Step 01 — VPS & Infrastructure Verification

## Objective
Verify that the VPS (Ubuntu 24.04 LTS, Hostinger, IP: 31.97.54.216) is properly configured to host the SafeHire backend and supporting services (PostgreSQL, Redis, Traefik, Portainer).

## Deliverables
- Confirm Docker, Docker Compose, and Git are installed and working.
- Confirm PostgreSQL 17 and Redis containers are healthy and accessible.
- Confirm Traefik reverse proxy is routing correctly (http/https).
- Confirm repo is cloned and branch `chore/add-step-instructions` is available.
- Update `step_01_results.md` with findings.

## Verification
- Run `docker ps` and capture container statuses.
- Run `psql -U postgres -h localhost -c '\l'` inside VPS to list databases.
- Verify that `traefik` is serving at `https://erp.blinkds.com` (should show 404 or Traefik default page).
- Verify repo directory exists at `/workspaces/safehire` (or correct path).

---
**Note:** After completing, update `step_01_results.md` with timestamp, branch, commands run, outputs, and any issues.
