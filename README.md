# Ledger

A quiet ledger for tutoring: schedule, students, payments and notes in one place.

Static site, no build step, no backend — all data is stored locally in the browser
via `localStorage`, scoped to whichever device/browser you open it on.

## Run locally
Just open `index.html` in a browser, or serve the folder with any static server:

```
python3 -m http.server 8000
```

## Deploy
Push this repo to GitHub, then import it on [vercel.com/new](https://vercel.com/new).
No framework preset or build command needed — Vercel serves it as a static site.
