# FRYARD — Nashville Hot Chicken (concept website)

Concept website for [@fryardindia](https://www.instagram.com/fryardindia/), the Nashville hot chicken stall at the Night Market.

**Concept website · sample products and prices · not a real store**

## What's inside
- **Home** — a scroll story in six scenes: string lights flicker on, then a walk through the night market (video through a WebGL heat-haze shader) ending in a white-hot flash; "Into the oil" chili-oil dunk with a glaze gauge; "Too hot to handle" tender burst with letters that react to your cursor and melt on scroll; a draggable fryer knob that sets the heat for the whole site; bestsellers as swinging kitchen order tickets on a rail; and a pickle-physics "cool down" section. Optional procedural sizzle sound.
- **Menu** — filterable menu with a heat picker (No heat to Cluck yeah), working order bag with pickup ticket (demo only), slider splash sequence in the header
- **Our story** — draggable polaroids and a scroll timeline
- **Find us** — animated map, live open/closed status (IST), party-order request that opens an Instagram DM

## Tech
Single `index.html` with GSAP + ScrollTrigger and Lenis (CDN). Video sections are full-quality frame sequences packed into WebP sprite sheets (`seq/<clip>/sNN.webp`, 8 frames each) and loaded progressively so scrolling works immediately.

## Run locally
Serve the folder with any static server, e.g. `npx serve .` or `python3 -m http.server`, then open `http://localhost:3000` (or `:8000`).
