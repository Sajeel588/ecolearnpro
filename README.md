# EcoLearn — Smart Sustainability Learning Platform

A responsive React + TypeScript sustainability learning dashboard built as a hackathon MVP. It runs in the browser without an API key or backend.

## Features
- Student dashboard: eco-points, level, streak, progress, daily challenge, recommended lesson.
- Six interactive learning modules covering climate, waste, renewable energy, water, biodiversity, and responsible consumption.
- Six-question multiple-choice knowledge check with automatic scoring and explanations.
- Eight eco-challenges with point rewards, same-day duplicate reward prevention, and activity history.
- Environmental impact estimates with visible illustrative assumptions; these are not verified measurements.
- SDG explorer for goals 4, 6, 7, 12, 13, 14, and 15.
- College analytics with charts and a fictional leaderboard, explicitly labelled demo data.
- Rule-based lesson recommendations and LocalStorage progress persistence.
- Responsive desktop sidebar and mobile navigation.

## Run locally
Requirements: Node.js 20+ and npm.

```bash
git clone https://github.com/Sajeel588/ecolearnpro.git
cd ecolearnpro
npm install
npm run dev
```
Open the URL Vite prints (usually http://localhost:5173).

Production build:
```bash
npm run build
npm run preview
```

## GitHub Pages
1. In repository **Settings → Pages**, choose **GitHub Actions** as the deployment source.
2. Push to `main`, or manually run the **Deploy to GitHub Pages** workflow in Actions.
3. After the workflow succeeds, the site is typically available at https://sajeel588.github.io/ecolearnpro/.

The Vite configuration uses relative asset paths for project-site hosting.

## Data transparency
Progress is stored in this browser under `ecolearn-state-v1`; there is no login, cloud sync, institutional database, or server-side storage. Clearing browser storage removes demo progress. College analytics and leaderboard profiles are fictional. Environmental metrics use illustrative per-action assumptions and are not verified environmental outcomes. No live AI service is connected; recommendations are rule-based.

## Demo walkthrough
1. Explore the overview.
2. Open My learning, read a lesson, then take the knowledge check.
3. Complete a challenge and check the points and history.
4. View My impact and its assumptions.
5. Explore SDGs and College analytics.

## Stack
React 18, TypeScript, Vite, Tailwind CSS configuration, custom responsive CSS, Lucide React, Recharts, LocalStorage, GitHub Actions.
