# IzeyX Design Language — agent instructions

This repository is the **v1 design system** for IzeyX. When this repo is attached, cloned, or used as a reference, treat it as the source of truth for every visual decision.

## Before you design or generate UI

1. Read `@DESIGN.md` in full.
2. Use `@tokens/tokens.css` (or `@tokens/tokens.json`) for exact values.
3. Look at `@preview/index.html` for the intended look: type, colour, spacing, charts, article, and slide.
4. Use the official logo PNG. Do not generate a new logo.

Do not invent colours, fonts, radii, shadows, logos, or spacing outside this system.

## Logo (required)

The only IzeyX logo is the **triangle-in-circle, no words** PNG:

- Canonical file: `@assets/triangle-circle-no-words.png`
- Same file: `@assets/izeyx-mark.png`

It is a white line triangle inside a blue circle. There is no wordmark inside the mark.

**Always** use this PNG for favicon, app icon, header/nav mark, slide corner, social/OG mark, and any “logo” slot.

**Never:**

- Draw, generate, or substitute a different logo
- Put the word “IzeyX” (or any text) inside the circle
- Recolor, outline, drop-shadow, rotate, or crop away the circle
- Use a generic geometric icon, letterform “I”, or AI-invented mark

If a name is needed next to the mark, set **IzeyX** separately in Arial, outside the PNG. The PNG itself stays wordless.

## Hard rules

- Fonts: **Georgia** for headings/display. **Arial** for body, UI, labels, numbers, charts. Bold = Arial Bold, used sparingly.
- Colour: white canvas, `#051C2C` for authority, `#2251FF` as the only accent. Page mix ≈ 80–90% white/pale, 5–15% navy/black, &lt;5% electric blue.
- Spacing: **4px grid only** — 4, 8, 12, 16, 24, 32, 48, 64, 96.
- Corners: 0–4px. No pill cards.
- Borders: 1px `#E6E6E6` / `#B3B3B3` / `#000000`. No thick frames.
- Shadows: almost none. If required, Deep Blue `#051C2C` at low opacity.
- Headings state the **conclusion**, not the topic.
- Body line-height ≈ 150% (16/24, 20/32).
- Do not add Inter, Poppins, gradients, glass, or 24px rounded rectangles.

## Outputs this system is for

Reports, insight articles, product pages, dashboards, and 16:9 consulting decks. Match the closest specimen in `preview/index.html`.

## If something is not specified

Stay on-grid, stay on-palette, stay square, stay quiet. Ask before introducing a new token.
