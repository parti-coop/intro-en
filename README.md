# Parti — Intro page for the Tokyo deliberative technologies workshop (July 2026)

A single-page English introduction to Parti Co-op and twenty years of digital democracy in Korea,
built as a static site for GitHub Pages.

## Contents

- `index.html` — the whole page (all CSS inline; only external dependency is Google Fonts)
- `assets/parti-logo.svg` — Parti wordmark (from the official brand assets)

## Deploy on GitHub Pages

1. Repository: `parti-coop/parti-intro`.
2. Push these files to the `main` branch:
   ```bash
   cd parti-intro
   git init && git add . && git commit -m "Parti intro page for Tokyo workshop"
   git branch -M main
   git remote add origin git@github.com:parti-coop/parti-intro.git
   git push -u origin main
   ```
3. In the repo: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / root**.
4. The page will be live at `https://parti-coop.github.io/parti-intro/` within a minute or two.

## Before sharing — small edits to consider

- **Contact**: the page currently links peacecode.net and parti.coop. If you want a direct
  email or LinkedIn on the "Who's here in Tokyo" card, add it in the `#ohyeon` section.
- **Workshop name**: the footer says "workshop on deliberative technologies in Asia · Tokyo,
  July 2026" — adjust if you prefer the official event title.
- All statistics follow the Parti common-numbers canon (10th-anniversary page basis, 2026).
