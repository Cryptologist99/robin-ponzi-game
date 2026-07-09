# $Robin Ponzi Game

A ponzi game for $ROBIN on Robinhood Chain. Taxes the rich to feed the poor.

## Play

Open `index.html` in your browser or visit the deployed Vercel site.

Click "Execute Wealth Redistribution" to scan holders, tax the top wallets, and redistribute to the smallest holders.

## Deploy on Vercel

1. Go to [vercel.com](https://vercel.com) and sign in
2. Click "Add New Project" → Import this repo (`Cryptologist99/robin-ponzi-game`)
3. Vercel auto-detects the static site config from `vercel.json`
4. Click "Deploy" — your site goes live in seconds

## Files

- `index.html` — standalone frontend (works on Vercel, uses localStorage)
- `vercel.json` — Vercel deployment config
- `bankr-app/` — original Bankr app source (manifest, server script, runtime version)

## Bankr App (original)

The `bankr-app/` folder contains the original Bankr app version with server-side scripts and appKV storage. Use that version inside the Bankr terminal for full functionality.