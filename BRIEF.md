# Portfolio Site Build Brief

## WHAT THIS IS
A personal portfolio for Sean Richardson — freelance web developer and designer.

## BACKGROUND
The site has a live WebGL shader background (braindance fog aesthetic). The shader code is ALREADY in index.html. Keep the shader EXACTLY as-is. It renders at quarter res, 15fps, 2 octaves — ultra-light on GPU.

CRITICAL: The shader background opacity is currently 0.4 — change to 0.7 so it's more visible/vibrant.

## LAYOUT
1. **Top bar**: "Sean Richardson" left, "Contact" link right, category tabs below
2. **Main content**: AUTO-SCROLLING horizontal carousel that takes up ~50-60% of viewport height. Cards are BIG. The carousel MOVES continuously left (CSS animation), pauses on hover. Cards are duplicated for infinite seamless scroll.
3. **Below carousel**: Simple text list of other work without images
4. **Bottom**: Contact email + location

## IMAGES AVAILABLE (in img/ folder) — ONLY USE THESE:
- `prophitz.jpg` — Prophitz × Razed crypto casino leaderboard ($5K prize pool)
- `shopify-coffee.jpg` — Coffee shop Shopify store
- `shopify-streetwear.jpg` — Streetwear Shopify store  
- `shopify-tech.jpg` — Tech accessories Shopify store

Each card shows the FULL image (object-fit: contain on a dark bg, NOT cropped with cover).

## LIVE LINKS for cards:
- Prophitz: https://seanysean12345.github.io/prophitz-leaderboard/
- Coffee: https://seanysean12345.github.io/shopify-demos/coffee.html
- Streetwear: https://seanysean12345.github.io/shopify-demos/streetwear.html
- Tech: https://seanysean12345.github.io/shopify-demos/tech-store.html

## TEXT-ONLY PROJECTS (listed below carousel, no images):
- WooCommerce Performance Fix — Diagnosed 100% CPU, eliminated spikes
- AI Agent System — Multi-platform autonomous agent
- Audio Stem Separation — ML pipeline, any song under 60 sec
- GLSL Shader Backgrounds — This site's background is one

## DESIGN RULES:
- Font: Space Grotesk (already loaded)
- No gray/dark panels behind text — text sits directly on the shader bg
- Clean, minimal — not cluttered
- Mobile responsive (cards become 85vw on mobile)
- Cards have subtle border, slight hover effect
- Carousel scrolls continuously via CSS animation (translateX), duplicated cards for seamless loop

## FILE: index.html (single file, everything inline)
