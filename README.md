# Levity

A fully interactive, 3D "floating" landing page for a fictional zero-sugar energy drink brand — built as a single self-contained `index.html` with no build step or framework.

## Highlights

- **Real 3D can** rendered with Three.js — procedurally built from lathe geometry with a canvas-painted label texture (no external 3D models)
- **8 flavors**, each retinting the entire site's accent color and the can's label when selected
- **Depth-layered UI** — pointer-driven parallax on cards, background orbs, and the hero stage; an interactive scrub-able lift-curve chart
- **Full purchase flow** — cart drawer, free-shipping progress, subscription pricing, and a confetti checkout
- **Performance-aware** — respects `prefers-reduced-motion`, falls back to a CSS can if WebGL is unavailable

## Running it

Just open `index.html` in a browser, or serve the folder with any static file server. It loads Three.js and Google Fonts from a CDN, so it needs an internet connection to render fully.

## Tech

Vanilla JS, CSS, and Three.js (r128) loaded via CDN. No build tools, no dependencies to install.
