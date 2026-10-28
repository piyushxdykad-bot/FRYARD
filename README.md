# FRYARD — Nashville Hot Chicken (concept website)

Concept website for [@fryardindia](https://www.instagram.com/fryardindia/), the Nashville hot chicken stall at the Night Market.

**Concept website · menu and prices from FRYARD's menu · not the official site**

## What's inside
- **Home** — an ordering-app dashboard: greeting, live order card with your pickup number, promo slides that loop the Google Flow videos (full-quality frames), category tiles, signature and combo cards, Order again, and cards for the stall and the story. Desktop keeps your bag open as a side panel; phones get a bottom tab bar.
- **Menu** — FRYARD's real menu (tenders, sliders, burritos, loaded bowls, combos, dips, drinks, add-ons) with their own product photos upscaled 4x. Slider-splash video opener; a pinned showcase of one signature per section with protein/kcal badges, size options and quantity; then the full menu with sticky section tabs and add-on lists
- **Our story** — clean, premium editorial layout: split hero with live open status; the 1930s hot chicken legend read word by word; "One night at FRYARD", a pinned sideways strip from 6 PM to 11 PM with a live clock and timeline; rolling numbers on a cream section; full-bleed closing call to action
- **Find us** — animated map, live open/closed status (IST), party-order request that opens an Instagram DM

## Tech
Single `index.html` with GSAP + ScrollTrigger and Lenis (CDN). Video sections are full-quality frame sequences packed into WebP sprite sheets (`seq/<clip>/sNN.webp`, 8 frames each) and loaded progressively so scrolling works immediately.

## Run locally
Serve the folder with any static server, e.g. `npx serve .` or `python3 -m http.server`, then open `http://localhost:3000` (or `:8000`).
