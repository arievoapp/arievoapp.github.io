# Rack — Never Skip Alone

Landing page for **Rack**, a gym-buddy matching and training platform.

## The idea

- **Buddy matching** — pair users by workout style, fitness level, goal, and training times, not just location.
- **Live gym map** — flip "looking for a buddy" on, browse gyms on a map, and raise your hand at one.
- **Trainers on-platform** — certified trainers list specialty, rate, and availability; members send a session request and get a tick or a cross back.
- **Streaks** — a 30-day workout streak unlocks a free trainer session; two streak freezes cover a missed day.
- **Groups & leaderboards** — every gym gets an auto-created group (plus custom ones); a transparent engagement score (streak, weekly sessions, volume, consistency, tenure) ranks members with a visible point breakdown.
- **Shared workout logging** — log sets against 300+ curated exercises (with form videos) or custom ones, then push the entry to your training partner's log.
- **Planned** — a trainer-facing client dashboard with progress trends and at-risk/consistency alerts, and expanded premium visibility into other users and trainers nearby.

## Status

This repo is the marketing landing page (`index.html`) for **Rack**. The product itself is being built as a separate React Native / Expo + Supabase app (currently a UI-only prototype on mock data — matching, map, streaks, trainer requests, groups/leaderboards, and workout logging are all functional in that prototype; a trainer client-management dashboard is not yet built).

## Running locally

It's a single static HTML file — no build step. Open `index.html` directly in a browser, or serve it locally:

```bash
npx serve .
```

## Live demo

Once GitHub Pages is enabled for this repo (Settings → Pages → Deploy from branch → `main` / root), the site will be live at:

`https://<your-github-username>.github.io/<repo-name>/`
