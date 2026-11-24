# Shivani Photography

A cinematic wedding photography portfolio website for **Shivani Photography**, based in Bhopal, India and available across India and for destination weddings.

## Features

- **Cinematic hero** with a slow Ken Burns zoom and animated entrance
- **Masonry gallery** with category filtering and an accessible fullscreen lightbox
- **Scroll-reveal animations** that fade content in as it enters the viewport
- **About section** with photographer bio and stats
- **Process timeline** showing the workflow from first hello to final gallery
- **Collections (packages)** with three tiers of wedding coverage
- **Testimonials carousel** with auto-rotation and manual controls
- **FAQ accordion** using native HTML `<details>` elements
- **Inquiry form** with inline validation and a mailto fallback
- **Fully responsive** with a mobile navigation drawer
- **Accessible** — skip link, ARIA labels, focus traps, keyboard navigation, and `prefers-reduced-motion` support
- **Dark editorial theme** — Cormorant Garamond serif + Jost sans-serif, gold accents on a warm charcoal palette

## Tech Stack

- Single-file HTML with inline CSS and vanilla JavaScript
- No build step or dependencies required
- Google Fonts loaded via CDN
- Optional Node.js dev server for local preview

## Running Locally

### Option 1 — Node.js (recommended)

```bash
node server.js
```

Then open **http://localhost:8000/** in your browser.

### Option 2 — Any static file server

Serve the `index.html` file with any static server (Python `http.server`, VS Code Live Server, etc.) and open it in your browser.

## Customization

All content is driven by a single `CONFIG` object in the `<script>` section of `index.html`. Edit the gallery images, packages, testimonials, process steps, and business details there — no separate data files needed.

## License

© Shivani Photography. All rights reserved.
