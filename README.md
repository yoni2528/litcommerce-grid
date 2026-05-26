# LitCommerce Grid

A static viewer for a LitCommerce product catalog. Single-page, no build step.

## Usage

1. Open the live site (GitHub Pages).
2. On first load, paste the `authorization` + `selftoken` request headers
   from any `api.litcommerce.com` request (DevTools → Network → Headers).
3. The page fetches all in-stock products once, then caches them in
   `localStorage` for 12 hours. Use the `↻` button to force a refresh.

## Features

- RTL Hebrew UI
- Search by name or SKU
- Filter by category
- Sort by updated / name / price / stock
- Selection (per-card checkbox) persists across reloads
- Export selected products as JSON
- Prices in ILS (₪)

## Privacy

The page is served from GitHub Pages but holds no data of its own. All
credentials and product data live only in your browser's `localStorage`.
