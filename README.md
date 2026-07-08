# Parachute v2 — Information Architecture

Interactive IA map for **Parachute v2** (Realwired's AI appraisal-review tool), prepared by Brandcave.

## Views

- **`/` (index.html)** — zoomable canvas board. Scroll/pinch to zoom, drag to pan, click a card to focus, click empty space to fit. Minimap (bottom-right) for orientation.
- **`/classic.html`** — the same architecture as a stacked card-board.
- **`/wireframes.html`** — inline workbook editing wireframes (Jul 7 direction): the workbook as the workspace — findings merged in with inline decisions, section-specific edit tools, read-only Source view, Customize behind one button. Four annotated static screens.

Cards are color-coded: **Built · Locked in plans · Not decided · Temporary**. In-page tabs (`⊞`) and sub-views (`▸`) are application state, not routes.

> Static site — no build step. Deploys on Vercel as-is (zero-config static).
