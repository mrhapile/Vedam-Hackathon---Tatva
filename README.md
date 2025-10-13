# TATVA’25 — The Cosmic Yagna (HTML + CSS Only)

A single‑page, immersive landing built with only HTML and CSS. It evokes "Vedic Futurism" with a lotus preloader, layered nebula background, glass navigation, shimmering gold hero title, decorative countdown rings, tarot‑style event cards with hover previews, a CSS‑only unfolding registration form, and an animated star‑river footer.

## Quick Start

1. Open `index.html` directly in your browser (no build tools required).
2. For best fonts, keep internet on (Google Fonts are linked). Everything else is local CSS.

## Files

- `index.html` — structure and minimal accessibility hooks
- `styles.css` — all visuals, animations, and responsive layout
- `assets/` — optional posters or GIFs for event cards (`poster-*.webp`, `preview-*.gif`)

## Notes & Constraints

- This version intentionally uses no JavaScript for logic; countdown rings are decorative.
- The registration form unfolds via the CSS checkbox technique and submits with default browser behavior.
- Heavy motion respects `prefers-reduced-motion`.
- Replace placeholder asset URLs in inline `style="--poster:...; --preview:...;"` with your images/GIFs to see hover previews.

## Customize

- Edit colors and easing in `:root` tokens inside `styles.css`.
- Change section copy in `index.html` and add/remove event cards by duplicating an `.card`.

## Credits

Design and implementation scaffold for Vedam Hackathon — TATVA’25.
