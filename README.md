# Royal Velora — Landing Page

A single-page static site for Royal Velora, Palm Beach, Staoueli, Algeria.

## Stack
Plain HTML/CSS/JS — no build step, no dependencies.

## Local preview
Just open `index.html` in a browser, or serve it locally:

```bash
npx serve .
```

## Structure
```
index.html      # everything: markup, styles, and scripts
assets/         # real property photos used throughout the site
```

## Deploy to Vercel
1. Push this repo to GitHub (see below).
2. In Vercel, "Add New Project" → import `kiko1313/hotel`.
3. Framework preset: **Other** (static site). No build command, no output directory override needed — Vercel will serve `index.html` from the root automatically.
4. Deploy.

## Push to GitHub
From this folder:

```bash
git init
git add .
git commit -m "Initial commit: Royal Velora landing page"
git branch -M main
git remote add origin https://github.com/kiko1313/hotel.git
git push -u origin main
```
