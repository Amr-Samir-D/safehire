# Step 08 — Final Deploy & Smoke Test on `erp.blinkds.com`


**Objective:** Deploy backend via Docker Compose on VPS (or Portainer) with Traefik labels and perform final smoke tests from public domain.


**Tasks:**
- Deploy backend stack using provided `docker-compose.backend.yml` or Portainer compose.
- Ensure Traefik routes `erp.blinkds.com` to the backend and TLS is available.
- Run public-facing smoke tests (from remote machine) to authenticate and fetch main dashboard metrics.


**Deliverable:** `step_08_results.md` including curl output, HTTPS verification, and any traefik logs.
