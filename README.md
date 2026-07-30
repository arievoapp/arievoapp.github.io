# Arievo — Workout Together, Grow Together

Landing page for **Arievo**, a gym-buddy matching and training platform.

## The idea

- **Buddy matching** — pair identity-verified users by workout style, fitness level, goal, and training times, not just location.
- **Live gym map** — flip "looking for a buddy" on, browse gyms on a map, and raise your hand at one.
- **100% certified trainers** — every trainer is verified before appearing in search; members send a session request and get a tick or a cross back. No exclusive contracts — book a single 1:1 session with any available coach without committing to a full training plan.
- **Streaks** — a 30-day workout streak unlocks a free trainer session; two streak freezes cover a missed day.
- **Groups & leaderboards** — every gym gets an auto-created group (plus custom ones); a transparent engagement score (streak, weekly sessions, volume, consistency, tenure) ranks members with a visible point breakdown.
- **Shared workout logging** — log sets against 300+ curated exercises (with form videos) or custom ones, then push the entry to your training partner's log.
- **Post-workout ratings & progress posts** — on every plan, rate your buddy after a session (feeds back into future matching) and post your progress to celebrate wins.
- **Free vs. Premium** — free members get buddy search/requests, regular logging, limited challenge participation, and no streak freezes. Premium members get early visibility into buddies and trainers, a 24-hour head start on sending requests, buddy accountability scores, city-wide gym challenges, early slot reservations, in-depth training analysis, in-app nudges, and streak-completion rewards. Premium trainers get full client progress logging, in-depth graphical trend analysis, and the ability to post their own updates.
- **Feedback loop** — a feedback form on the landing page (visual only for now, no backend wired up yet — see the `feedbackForm` handler in `index.html`).
- **Planned** — a trainer-facing client dashboard with progress trends and at-risk/consistency alerts.

## Mission

Workout together, grow together — a healthier lifestyle is easier to keep with a buddy.

## Status

This repo is the marketing landing page (`index.html`) for **Arievo**. The product itself is being built as a separate React Native / Expo + Supabase app (currently a UI-only prototype on mock data — matching, map, streaks, trainer requests, groups/leaderboards, and workout logging are all functional in that prototype; a trainer client-management dashboard is not yet built).

## Running locally

It's a single static HTML file — no build step. Open `index.html` directly in a browser, or serve it locally:

```bash
npx serve .
```

## Live demo

Once GitHub Pages is enabled for this repo (Settings → Pages → Deploy from branch → `main` / root), the site will be live at:

`https://<your-github-username>.github.io/<repo-name>/`
