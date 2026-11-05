# AI — notes for Claude

Home for Peyton's AI agents and automations. **This repo is PUBLIC** — never commit secrets, tokens, personal data, or private account details.

## Contents
- `cyber-news/` — weekday cyber news briefings written by a scheduled Claude Code cloud routine ("Weekday Cyber News Briefing (10 AM AZ)", runs 17:00 UTC Mon–Fri).
  - `reports/YYYY/MM/YYYY-MM-DD.md` — one report per day
  - `reports/LATEST.md` — copy of the newest report
  - `INDEX.md` — list of all reports, newest first
  - Manage the routine: https://claude.ai/code/routines (routine ID kept in the private claude-notes repo)

## Rules
- The routine pushes directly to `main` and only touches `cyber-news/`. Pull before editing locally to avoid conflicts.
- New agents/automations get their own top-level folder with a README, and a row in the root `README.md` table.

## Status (2026-11-04)
- Routine works end to end, but the cloud environment's network allowlist blocks most news/government sites, so reports are thin until that's fixed (claude.ai/code → Environments → Default → network access).
