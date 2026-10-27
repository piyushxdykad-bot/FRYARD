# FRYARD — Nashville Hot Chicken (concept website)

Concept website for [@fryardindia](https://www.instagram.com/fryardindia/), the Nashville hot chicken stall at the Night Market.

**Concept website · sample products and prices · not a real store**

## What's inside
- **Home** — scroll-scrubbed hero video (192 frames, 1280×720), "Too hot to handle" headline that warps as you scroll, horizontal bestsellers reel, "Golden to glazed" chili-oil dunk sequence, site-wide heat dial, process steps, night-market dolly sequence
- **Menu** — filterable menu, working order bag with pickup ticket (demo only), slider splash sequence in the header
- **Heat scale** — five heat levels from No heat to Cluck yeah; your pick re-tints the whole site
- **Our story** — draggable polaroids and a scroll timeline
- **Find us** — animated map, live open/closed status (IST), party-order request that opens an Instagram DM

## Tech
Single `index.html` with GSAP + ScrollTrigger and Lenis (CDN). Video sections are full-quality frame sequences packed into WebP sprite sheets (`seq/<clip>/sNN.webp`, 8 frames each) and loaded progressively so scrolling works immediately.

## Run locally
Serve the folder with any static server, e.g. `npx serve .` or `python3 -m http.server`, then open `http://localhost:3000` (or `:8000`).
