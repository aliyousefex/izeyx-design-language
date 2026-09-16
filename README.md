# IzeyX Design Language v1

High-contrast consulting editorial system for IzeyX products, reports, and decks.

Built for **Claude Code** and Claude’s “link code from GitHub” flow. Attach this repository and the agent should follow `DESIGN.md` instead of inventing a look.

## Use with Claude

Paste this repo URL into **Link code from GitHub**:

```
https://github.com/aliyousefex/izeyx-design-language
```

What Claude should read, in order:

1. `CLAUDE.md` — hard rules
2. `DESIGN.md` — tokens + rationale (DESIGN.md format)
3. `tokens/tokens.css` — CSS variables and primitives
4. `assets/triangle-circle-no-words.png` — official logo (triangle in a circle, no words)
5. `preview/index.html` — live specimen (article, deck, charts, type, colour)

In a Claude Code project, add:

```
Follow @DESIGN.md strictly for all UI.
Use Georgia for headings and Arial for body.
Use assets/triangle-circle-no-words.png as the logo. Do not generate a new mark.
Do not invent colours, fonts, or spacing outside the v1 system.
```

## Logo

| File | Role |
| --- | --- |
| `assets/triangle-circle-no-words.png` | Official PNG logo — triangle in a circle, **no words** |
| `assets/izeyx-mark.png` | Identical copy of the same file |

Use this PNG for favicons, headers, slides, and app icons. Never redraw it. If a name is needed, set “IzeyX” in Arial beside the mark, not inside it.

## The system, short

| Layer | Rule |
| --- | --- |
| Display type | Georgia Regular |
| Body type | Arial Regular (Arial Bold for rare emphasis) |
| Canvas | `#FFFFFF` |
| Authority | `#051C2C` Deep Blue |
| Accent | `#2251FF` Electric Blue |
| Body text | `#333333` |
| Grid | 4 → 8 → 12 → 16 → 24 → 32 → 48 → 64 → 96 px |
| Corners | 0–4 px |
| Borders | 1 px `#E6E6E6` / `#B3B3B3` / `#000000` |
| Shadows | Almost none |
| Headings | State the conclusion, not the topic |

Page mix: ~80–90% white/pale, 5–15% navy/black, &lt;5% electric blue.

## Local preview

Open `preview/index.html` in a browser. No build step. Fonts are system Georgia and Arial.

## Version

v1.0.0 — first lock of type, colour, spacing, and component rules.

This is an IzeyX system inspired by a high-contrast consulting editorial aesthetic. It uses portable substitutes (Georgia, Arial) rather than proprietary typefaces.
