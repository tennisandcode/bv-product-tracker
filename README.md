# Black Voyage — Product Tracker

Live dashboard for BV product launches: 7 gated stages, 10 department lanes, the master flow chart (Workflow v2) with cross-department routing, timelines, burn-up charts, EN/中文, light/dark.

## Open it
- **Hosted (Render):** the homepage `/` is the **SuperPM fork** (`index.html` = `superpm.html`).
- **Main dashboard:** `dashboard.html` (reachable at `/dashboard.html`).
- **Locally:** download and double-click `index.html` (SuperPM) or `dashboard.html` (tracker) — no build needed (single files).
- `superpm.html` — the SuperPM fork source (autopilot, SLA timers, health score); identical to `index.html`.

## Edit it
The main tracker dashboard lives in one file, `dashboard.html`. Inside it:
- `TEAM` — departments, roles, heads/members
- `GATES` — stage exit criteria (the gate map)
- `FLOW` — master flow chart lanes/nodes
- `XROUTES` — cross-department hand-off routes
- `LAUNCHES` — the live cards (tasks, statuses, check-ins)
- `ZH` — Chinese translations (correct freely)
- `PLAN` — planned days per stage

Edit on GitHub (pencil icon on `dashboard.html`) → commit → Render redeploys in ~1 min.

## Reference
- `docs/build-plan-v0.3.md` — full build plan
- `data/` — Task Playbook + Flow Master Sheet (fill these in, team)
- `skill/` — the Claude skill for operating the tracker
