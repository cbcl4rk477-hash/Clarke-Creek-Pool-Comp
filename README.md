# 🎱 Clarke Creek Pool Competition

A single-page pool (billiards) competition tracker for the Clarke Creek crew — group stage fixtures, standings, knockout bracket, and prize pool display.

## Features

- Group stage round-robin fixtures, auto-generated from rosters
- Live standings with points, wins, losses
- Knockout bracket (semi-finals → final)
- Prize pool tracker
- State persisted in browser `localStorage`

## Tech

Plain HTML + CSS + vanilla JS. No build step, no dependencies.

## Local development

Just open `index.html` in your browser — no server needed.

```bash
# Optional: serve with any static server
npx serve .
# or
python3 -m http.server
```

## Deployment (Vercel)

This repo is configured for zero-config Vercel deployment.

1. Push to GitHub
2. Import the repo in [vercel.com](https://vercel.com)
3. Deploy — Vercel auto-detects static and uses `vercel.json`

Or deploy instantly from the CLI:

```bash
npm i -g vercel
vercel
```

## Resetting state

Open the browser console and run:

```js
localStorage.clear(); location.reload();
```
