# Step 02 — Database Schema & Prisma Migration

## Objective
Set up Prisma with PostgreSQL 17 to create all required SafeHire database tables (Users, Drivers, IncidentReports, FileUploads, RefreshTokens, AnalyticsCache).

## Deliverables
- Confirm `.env` file has correct `DATABASE_URL` for Postgres 17.
- Run `npx prisma generate` and `npx prisma migrate dev --name init`.
- Verify all tables are created in database.
- Seed database with sample users, drivers, and reports (`npx prisma db seed`).
- Update `step_02_results.md`.

## Verification
- Run `psql -U postgres -d safehire -c '\dt'` and confirm tables exist.
- Confirm at least 1 admin user and 1 driver record are seeded.
- Add output of `npx prisma studio` screenshot/notes if possible.

---
**Note:** Update `step_02_results.md` with migration logs, schema confirmation, and issues if any.
