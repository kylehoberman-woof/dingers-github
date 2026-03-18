# ⚾ Dingers Only Pool — 2026

A fantasy baseball home run tracker for 4 players: Kyle, Jonah, Greg, and Adam.

## Rules
- **1 point per home run**
- **Double points** during the final month of the regular season (September + any October regular season games)
- **Grand slams** are the tiebreaker if scores are tied at season end

## Features
- 📅 Daily summary — auto-syncs from MLB Stats API on page load
- 🏆 Live leaderboard with standings
- 📊 HR projections (Steamer / ZiPS / THE BAT X consensus)
- 👥 Individual team rosters
- 📋 League rules
- 🎯 Draft recap

## How to Use
Just open `index.html` in any browser. It will automatically pull live 2026 HR data from the MLB Stats API on load.

Hit **🔄 SYNC LIVE HRs** at any time to refresh mid-day.

## Tech
- Pure HTML/CSS/JS — no dependencies, no build step
- Live data via [MLB Stats API](https://statsapi.mlb.com) through [corsproxy.io](https://corsproxy.io)
- No server required

## Hosting
Optionally host for free on GitHub Pages:
1. Push this repo to GitHub
2. Go to Settings → Pages → Source: main branch → / (root)
3. Share `https://yourusername.github.io/dingers-pool` with your league
