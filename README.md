# UK49s Prediction Engine

A statistical prediction tool for UK49s Lunchtime and Teatime lottery draws. Built as a single-file HTML app — no backend, no dependencies to install, deploys instantly to Vercel.

## Features

- **Daily predictions** for both Lunchtime (12:49 PM) and Teatime (5:49 PM) draws
- **6 backtested strategies** — hot numbers, hot+skip blend, balanced odd/even, pairs, cold numbers, frequency wheel
- **Full statistics panel** — frequency heatmap for all 49 numbers, odd/even + high/low splits, top 12 frequent pairs
- **Strategy backtesting** — each strategy tested against 100 historical draws with 1+, 2+, and 3+ match rates
- **History view** — last 30 results for each draw type

## Tech

Single-file `index.html`. Pure HTML + CSS + vanilla JavaScript. No framework, no build step, no npm.

## Deploy to Vercel

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → New Project → Import your GitHub repo
3. Vercel auto-detects it as a static site — hit Deploy
4. Done. Live in ~30 seconds.

## Disclaimer

UK49s is a certified random draw. No prediction system can guarantee wins. This app applies statistical pattern analysis for entertainment and informed number selection only. Please gamble responsibly.
