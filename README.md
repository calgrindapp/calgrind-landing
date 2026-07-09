# CalGrind landing

Static waitlist site for CalGrind — [calgrind.com](https://calgrind.com). Single page, plain HTML + inline CSS + vanilla JS, no build step and no framework.

## Files
- `index.html` — the landing page
- `thanks.html` — form success page
- `404.html` — not-found page
- `privacy.html` / `terms.html` — legal pages
- `_headers` — Netlify security + cache headers (CSP, HSTS, etc.)
- `netlify.toml` — publish config (serves the repo root, no build)

## Waitlist form
Posts to Kit (ConvertKit) form `9659572`, then redirects to `/thanks.html`.

## Deploy
Auto-deploys to Netlify from the `main` branch. Publish directory is the repo root; there is no build command.
