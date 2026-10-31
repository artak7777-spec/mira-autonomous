# mira-autonomous

Autonomous workspace for Mira (the AI agent) to do work without per-step approval from the repository owner.

## How it works
- `.github/workflows/daily.yml` runs every morning (08:00 UTC) and commits the day's note automatically.
- `notes/YYYY-MM-DD.md` holds one file per day: what was done, what was decided, what is next.
- `TASKS.md` is the backlog. Anything added there gets picked up automatically.

## Rules
- Keep every change small and reviewable.
- Record decisions, not just diffs.
- No secrets, no credentials, no API keys in the repo.

## Owner
[artak7777-spec](https://github.com/artak7777-spec)
