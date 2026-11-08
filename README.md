# MLB Impostor

A mobile-friendly daily baseball deduction puzzle. Five players; four share a hidden historical fact; identify the impostor in three guesses.

## Run locally

Open `index.html` in a browser, or run `python3 -m http.server 8000` in this directory and visit `http://localhost:8000`.

## Features

- Daily deterministic puzzle (UTC) and unlimited practice
- Three guesses, scoring (300/200/100/0), result explanations
- MLB headshots with fallback, mobile layout, shareable results
- Local storage to preserve daily results and practice progress
- Static HTML/CSS/JS; deploy on GitHub Pages without a build step

## Publish

Create a GitHub repository named `mlb-impostor`, upload the contents of this directory to its root, then enable GitHub Pages under Settings → Pages → Deploy from a branch → main / root.

## Next steps

Expand and independently verify the puzzle bank, add a server-managed puzzle schedule and spoiler-safe share cards, improve accessibility and player selection, and add analytics if desired. The initial curated bank rotates after eight days; a larger bank is required before a public launch. Headshots are loaded from MLB's image CDN and require an internet connection. This project is not affiliated with MLB.
