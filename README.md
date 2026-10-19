# Safa's Letter Trainer

A single-page practice game for the Arabic letters أ ب ت ث: letter names, shapes in each position, where a letter sits in a word, and 24 vocabulary words. Missed questions come back until they stick, and right answers build an ice cream reward.

Live: https://safa-letter-trainer.stockywhacky.workers.dev

## Run locally

Open `index.html` in a browser. There is no build step. Progress is saved in the browser's localStorage.

## Deploy

```
npx wrangler deploy --assets . --name safa-letter-trainer --compatibility-date 2026-10-01
```

`.assetsignore` keeps Wrangler's cache out of the upload.
