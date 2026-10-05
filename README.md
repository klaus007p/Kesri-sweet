# Kesari — Mithai & Memories

A complete visual-only, heritage-inspired sweet-shop website. No cart, backend, forms, tracking or data handling. Category tabs and order/enquiry buttons are decorative; navigation and the mobile menu work.

## Open the standalone website

Open `index.html` in your browser. There is no install or build step. Files are organised as:

- `index.html` — all shop content and sections
- `css/styles.css` — commented mobile-first styles and design tokens
- `js/main.js` — menu, scroll header and gentle reveals
- `assets/` — 24 local sweet illustrations, mandala, gift box and decorative map

Google Fonts is the only external resource. Serif and sans-serif fallbacks work offline.

## Change colours and fonts

Edit the `:root` variables at the top of `css/styles.css`. Palette: `--maroon`, `--saffron`, `--cream`, `--pistachio`, `--gold`. Supporting surface and text roles are next to them. Change `--font-heading` and `--font-body` and update the Google Fonts link in `index.html` if needed. Spacing uses an 8px scale.

## Personalise the shop

Search `index.html` for Kesari/kesari to replace the sample wordmark, page title, story and copyright. Replace the sample tagline, `[YEAR]`, `[ADDRESS]`, `[PHONE]`, `[HOURS]` and `@[HANDLE]` with your real details. No founding date or contact details have been invented. The story, testimonial names/quotes, product prices and gift contents are sample showcase copy, not verified business facts. Update those before publication. Replace or remove the showcase notes once your real details are entered.

## Replace illustrations with photographs

Put your photo in `assets/` and replace the corresponding image's `src` in `index.html` (for example `assets/sweet-01.svg` with `assets/kaju-katli.jpg`). Update its alt text to match. Each card has one image source; the arched shape and cropping remain in CSS. A sweet also appears in the hero/favourites/social sections, so change those image sources too, or overwrite its SVG asset with another SVG to update all instances at once. Square images around 800px work well; the story can use a portrait image. Replace `assets/gift.svg` independently for each gift box. The map is decorative and does not represent a real location.

## Accessibility and sizing

Semantic sections, Hindi language labels, focus outlines, keyboard-trapped mobile navigation, Escape-to-close and reduced-motion support are included. Layout starts with two sweet columns and enhances at 768px, 1024px and 1280px. Horizontal carousels scroll within their own rows.
