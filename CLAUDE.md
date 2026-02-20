# CLAUDE.md — opencupid-web

## What this is
Single-page marketing website for OpenCupid, hosted on GitHub Pages.

## Build
```bash
npm install
npm run build   # Compiles SCSS → css/style.css
npm run dev     # Watch mode for SCSS
```

## Deploy
Push to `main` — GitHub Actions builds SCSS and deploys to GitHub Pages.

## Structure
```
index.html          # Single page (Bootstrap 5 + custom theme)
scss/
  _variables.scss   # Bootstrap variable overrides
  style.scss        # Main SCSS
css/                # Compiled output (gitignored)
```
