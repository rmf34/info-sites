# info-sites

A small collection of static info pages, served via GitHub Pages at
**https://rmf34.github.io/info-sites/**.

## Pages

- [`index.html`](index.html) — landing page
- [`martial_arts_comparison.html`](martial_arts_comparison.html) — calibrated
  heatmap comparing common martial arts
- [`which-hybrid.html`](which-hybrid.html) — decision helper for picking
  among current gas-electric hybrid SUVs

## Local preview

Each page is fully self-contained (HTML + inline CSS/JS), so just open it
in a browser, or serve the directory:

```sh
python3 -m http.server 8000
```

## Deploy

Pushing to `main` publishes automatically — Pages is configured to deploy
from `main` / root.
