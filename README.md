# Rack — Never Skip Alone

Landing page for **Rack**, a gym-buddy matching and training platform.

## The idea

- **Buddy matching** — pair users by schedule, split, and lift level, not just location.
- **Trainers on-platform** — book a session, message, and sync progress notes without a third-party app.
- **Trainer dashboard** (planned) — trainers log client workouts, trend metrics over time, get an app-generated consistency score, and are prompted when a client is at risk of dropping off.
- **Streaks** — a 30-day workout streak unlocks a free trainer session.
- **Response guarantee** — every buddy or trainer request gets an answer; if no one responds in time, Rack auto-offers an alternate match.
- **Premium** — periodized training phases (loading / maintenance / peak), a buddy accountability score across multiple parameters, shared workout logging, and expanded visibility into other users and trainers nearby.

## Status

This repo currently contains the marketing landing page only (`index.html`). The matching engine, trainer dashboard, and scoring system are not yet built.

## Running locally

It's a single static HTML file — no build step. Open `index.html` directly in a browser, or serve it locally:

```bash
npx serve .
```

## Live demo

Once GitHub Pages is enabled for this repo (Settings → Pages → Deploy from branch → `main` / root), the site will be live at:

`https://<your-github-username>.github.io/<repo-name>/`
