# Credits and disclosures

## AI tools used
| Tool | What it was used for | Where in the project |
|---|---|---|
| Claude Code | Scaffolded this repository before Factory dispatch: wrote the 5 seat mandate files in `mandates/`, this file, and repo layout. Wrote no Pocketful application code. | `mandates/`, `CREDITS.md` only |
| Band Desktop — 5 coding-agent seats (Planner, Implementer, Test author, Reviewer, Integrator), each running Claude Code as its runtime | The Factory itself: plans, implements, tests, and reviews all Pocketful stage code, dispatched one stage at a time by the human entrant | `stage-1/` through `stage-4/` — all application code |

## Compliance notes
- Mandate files (`mandates/*.md`) are generic role descriptions with no track-specific detail — no endpoint paths, field names, or error codes — per the event's disqualifier on mandate specificity.
- All code in `stage-1/` through `stage-4/` comes from the Band Desktop room's agent-seat collaboration. No code in those directories is hand-written or hand-fixed by the human entrant, per the event's disqualifier on that point.
- `room.json` (full room download from Band) is included in this repo as the record of that collaboration.

## Third-party code and libraries
Populated by the Factory itself as stages are built; see each `stage-N/RUN.md`.

## Team and mentors
Solo entrant.
