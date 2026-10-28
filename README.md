# FRYARD — Nashville Hot Chicken (concept website)

Concept website for [@fryardindia](https://www.instagram.com/fryardindia/), the Nashville hot chicken stall at the Night Market.

**Concept website · menu and prices from FRYARD's menu · not the official site**

## What's inside
- **Home** — a scroll story in six scenes: neon FRYARD sign and string lights flicker on, then a walk through the night market (video through a WebGL heat-haze shader) ending in a white-hot flash; "Into the oil" chili-oil dunk with a glaze gauge; "Too hot to handle" tender burst with letters that react to your cursor and melt on scroll; a draggable fryer knob that sets the heat for the whole site; bestsellers as swinging kitchen order tickets on a rail; and a pickle-physics "cool down" section. Optional procedural sizzle sound.
- **Menu** — FRYARD's real menu (tenders, sliders, burritos, loaded bowls, combos, dips, drinks, add-ons) with their own product photos upscaled 4x. Slider-splash video opener; a pinned showcase of one signature per section with protein/kcal badges, size options and quantity; then the full menu with sticky section tabs and add-on lists
- **Our story** — draggable polaroids and a scroll timeline
- **Find us** — animated map, live open/closed status (IST), party-order request that opens an Instagram DM

## Tech
Single `index.html` with GSAP + ScrollTrigger and Lenis (CDN). Video sections are full-quality frame sequences packed into WebP sprite sheets (`seq/<clip>/sNN.webp`, 8 frames each) and loaded progressively so scrolling works immediately.

## Run locally
Serve the folder with any static server, e.g. `npx serve .` or `python3 -m http.server`, then open `http://localhost:3000` (or `:8000`).
