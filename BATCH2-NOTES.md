# Jaguar ROM website — Batch 2

This is an **overlay** on top of Batch 1. Do not delete existing `assets/jaguar-logo.png`, `assets/jaguar-color.png` or `assets/main.js`.

## Included
- `features/index.html` — detailed security features and limitations
- `index.html` — homepage links to feature page
- `assets/style.css` — additional responsive styles
- `robots.txt`, `sitemap.xml` — basic indexing support

## Review before publishing
- Confirm the scope of all security descriptions, especially key eviction and Type-Zero SMS.
- Verify all supported-device instructions and release links before adding downloads.
- Confirm current patch levels and firmware dependencies.
- Add official Telegram links when provided.
- Keep GitHub Pages disabled until review is complete.

## Local test
`python3 -m http.server 8000` then open `http://localhost:8000/` and `http://localhost:8000/features/`.

## Git
Commit to `beta` only; do not merge to `main` until approved.
