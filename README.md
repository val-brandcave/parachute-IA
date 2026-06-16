# Parachute v2 — Information Architecture

Interactive IA map for **Parachute v2** (Realwired's AI appraisal-review tool), prepared by Brandcave.

## Views

- **`/` (index.html)** — zoomable canvas board. Scroll/pinch to zoom, drag to pan, click a card to focus, click empty space to fit. Minimap (bottom-right) for orientation.
- **`/classic.html`** — the same architecture as a stacked card-board.

Cards are color-coded: **Built · Locked in plans · Not decided · Temporary**. In-page tabs (`⊞`) and sub-views (`▸`) are application state, not routes.

> Static site — no build step. Deploys on Vercel as-is (zero-config static).
