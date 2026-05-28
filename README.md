# Arunachal Pradesh Family Field Guide

Static GitHub Pages site for planning a 3-11 October 2026 family trip to Arunachal Pradesh.

The site adapts the Markdown-to-webpage renderer pattern from [`kush0511/pct-section-j-field-guide`](https://github.com/kush0511/pct-section-j-field-guide): Markdown content is loaded from `content.md`, rendered client-side with `markdown-it`, sanitized with DOMPurify, and enhanced with responsive tables, callouts, image grids and optional Mermaid diagrams.

## Local preview

Serve the directory with any static server:

```bash
python3 -m http.server 4173
```

Then open `http://localhost:4173`.

## Files

- `content.md`: trip plan, itinerary options, helicopter notes, sources and image galleries
- `index.html`: static shell and CDN dependencies
- `app.js`: Markdown renderer and enhancements
- `styles.css`: responsive expedition-board design
