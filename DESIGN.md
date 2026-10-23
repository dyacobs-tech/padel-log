# Padel Log — Design System

Swiss / editorial direction (inspired by Lexington Themes): flat, typography-led,
hairline structure, one accent. No gradients, no soft shadows, no pill shapes.

## Tokens
- Background: `#000` (true black). Panels: `#101012`, raised: `#1b1b1e`.
- Text: `#f5f5f7`; muted: `#8e8e93`.
- Accent (only): lime `#c6f432` — wordmark, active states, primary buttons, key numbers.
- Semantic colors stay: win `#30d158`, loss `#ff453a`, training `#0a84ff`, tie `#ffd60a`.
- Hairlines: `1px solid rgba(255,255,255,.09)` separate everything; shadows are banned.

## Shape
- Radius: 8px on cards/inputs/buttons, 7px segmented buttons, 4px tags & W/L chips.
- Nothing is pill-shaped (999px) except avatars/dots.

## Typography
- Inter / system grotesque. Tabular numerals everywhere (`font-variant-numeric: tabular-nums`).
- Kickers & labels: 11px, 700, uppercase, letter-spacing .12–.14em, muted.
- Display numbers: 34–38px, weight 800, letter-spacing −1px.
- Primary buttons: uppercase, 800, letter-spacing .08em.

## Rules for future changes
- New UI uses the tokens above; never introduce a second accent color.
- Selected segmented control = lime background, black text.
- Keep the layout max-width 640px, left-aligned, grid-disciplined.
