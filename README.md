# MST Projects — Landing Page

A single-page marketing website for **MST Projects**, a South African engineering, mining and power-solutions company.

**Live site:** https://raafinco-art.github.io/mst-projects-website/

## About

Built to the MST Projects brand system:

- **Colours:** Midnight Engineering Blue `#0B2A5B`, Industrial Orange `#F47A14`, with steel/graphite/concrete supporting tones (65 / 20 / 10 / 5 ratio).
- **Type:** Montserrat (headings), Inter (body), IBM Plex Mono (technical labels) — via Google Fonts.
- **Sections:** Hero · About · Services · Why Choose Us · Industries · Engineering Process · Call to Action · Contact · Footer.
- **Motion:** scroll reveals, hero parallax, staggered service cards, animated counters — all respecting `prefers-reduced-motion`.

## Tech

Vanilla HTML, CSS and JavaScript — no build step. Open `index.html` directly, or serve the folder with any static server:

```bash
python -m http.server 8123
```

## Structure

```
index.html
assets/
  images/     cinematic industrial photography (per section)
  logo/       brand logos (transparent)
  favicon/    SVG favicon + apple-touch-icon
```

The contact form opens the visitor's email client (`mailto:`) — no backend required.
