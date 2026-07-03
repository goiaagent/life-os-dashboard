# Life OS Dashboard

Phone-first progress view for the Life OS daily loop (see vault2 `life-os/`).

- `index.html` — frozen viewer (four cards: Today, Momentum, State, Direction). Vanilla JS + inline SVG, no build step.
- `data.js` — the only file that changes. Overwritten by the `/evening` skill each night, then committed and pushed here.

Served via GitHub Pages. Contains scores, streaks, mood/energy numbers, and task titles only — no journal text.
