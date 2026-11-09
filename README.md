# Jamie's Italian — Concept Site

A single-page concept website for Jamie's Italian (The Dubai Mall), built to show what
a dedicated site for the restaurant could look like. No build step — `index.html` is a
fully self-contained static page (fonts load from Google Fonts; every photo and the
logo are embedded directly in the file).

## Run locally

Just open `index.html` in a browser — no server or install needed.

## Deploy on Netlify

**Option A — connect this GitHub repo (recommended, auto-deploys on every push):**

1. Push this repo to GitHub (see below).
2. On [netlify.com](https://app.netlify.com), click **Add new site → Import an existing project**.
3. Pick this repository. Build settings are already set via `netlify.toml`
   (publish directory `.`, no build command needed) — just click **Deploy**.

**Option B — drag and drop (fastest, no GitHub needed):**

Go to [app.netlify.com/drop](https://app.netlify.com/drop) and drag `index.html` onto
the page.

## Push this repo to GitHub

```bash
git init
git add .
git commit -m "Jamie's Italian concept site"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

(Create the empty repo on GitHub first at github.com/new — don't initialize it with a
README, since this folder already has one.)

## Notes

- Jamie's Italian is a known international chain (Jamie Oliver) operating under license
  at The Dubai Mall — worth keeping in mind that they likely already have a corporate
  web presence, which may change how an outreach pitch here should be framed compared
  to an independent local business.
- The in-store menu photos captured were only 140px wide and not legible. The menu on
  this page is reconstructed from the category headers that were readable, the real
  dishes visible in your photos, and well-known public Jamie's Italian signature dishes
  (e.g. the Super Food Salad, 6-Hour Slow-Cooked Lamb). Confirm items and pricing
  against the current Dubai Mall menu before sharing this externally.
- Source screenshots used to build the page are kept locally but excluded from git via
  `.gitignore` (already baked into `index.html` as compressed images).
