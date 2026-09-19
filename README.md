# Beat Loom

A 16-step browser sequencer for weaving your own drum beat, bassline, and melody into a loop. Pure static HTML/CSS/JS — no build step, no dependencies.

## Run locally

Open `index.html` in a browser, or serve the folder with any static file server:

```bash
npx serve .
```

## Deploy

This repo deploys as-is on Netlify (see `netlify.toml`) — publish directory is the repo root, no build command needed.

## Notes

- The demo login on the gate screen is a hardcoded, client-side check (`demo@beatloom.app` / `loom123`) — a UI gate, not real authentication.
- Saving loops uses the `db`/`user` Claude artifact capabilities when running as a Claude artifact, and falls back to `localStorage` everywhere else (including this static deploy).
