---
version: "1.0.0"
name: IzeyX Design Language
description: High-contrast consulting editorial system. Georgia display, Arial body, deep navy, electric blue accent, 4px grid. Version 1.
colors:
  primary: "#051C2C"
  secondary: "#2251FF"
  tertiary: "#00A9F4"
  neutral: "#FFFFFF"
  ink: "#000000"
  text: "#333333"
  text-muted: "#4D4D4D"
  mid-grey: "#757575"
  light-grey: "#B3B3B3"
  super-light-grey: "#D0D0D0"
  pale-grey: "#E6E6E6"
  very-pale-grey: "#F0F0F0"
  chart-navy: "#034B6F"
  chart-blue: "#027AB1"
  chart-cyan: "#39BDF3"
  chart-sky: "#71D2F1"
  chart-ice: "#AAE6F0"
  chart-periwinkle: "#AFC3FF"
  on-primary: "#FFFFFF"
  on-accent: "#FFFFFF"
typography:
  display-1:
    fontFamily: Georgia, "Times New Roman", Times, serif
    fontSize: 64px
    fontWeight: 400
    lineHeight: 76px
    letterSpacing: -0.02em
  display-2:
    fontFamily: Georgia, "Times New Roman", Times, serif
    fontSize: 60px
    fontWeight: 400
    lineHeight: 72px
    letterSpacing: -0.02em
  display-3:
    fontFamily: Georgia, "Times New Roman", Times, serif
    fontSize: 56px
    fontWeight: 400
    lineHeight: 68px
    letterSpacing: -0.015em
  display-4:
    fontFamily: Georgia, "Times New Roman", Times, serif
    fontSize: 52px
    fontWeight: 400
    lineHeight: 64px
    letterSpacing: -0.015em
  h1:
    fontFamily: Georgia, "Times New Roman", Times, serif
    fontSize: 44px
    fontWeight: 400
    lineHeight: 52px
    letterSpacing: -0.01em
  h2:
    fontFamily: Georgia, "Times New Roman", Times, serif
    fontSize: 40px
    fontWeight: 400
    lineHeight: 48px
    letterSpacing: -0.01em
  h3:
    fontFamily: Georgia, "Times New Roman", Times, serif
    fontSize: 36px
    fontWeight: 400
    lineHeight: 44px
    letterSpacing: -0.01em
  h4:
    fontFamily: Georgia, "Times New Roman", Times, serif
    fontSize: 32px
    fontWeight: 400
    lineHeight: 36px
    letterSpacing: -0.01em
  h5:
    fontFamily: Georgia, "Times New Roman", Times, serif
    fontSize: 28px
    fontWeight: 400
    lineHeight: 32px
    letterSpacing: 0em
  h6:
    fontFamily: Georgia, "Times New Roman", Times, serif
    fontSize: 24px
    fontWeight: 400
    lineHeight: 28px
    letterSpacing: 0em
  article-lead:
    fontFamily: Arial, "Helvetica Neue", Helvetica, sans-serif
    fontSize: 24px
    fontWeight: 400
    lineHeight: 36px
    letterSpacing: 0em
  article-body:
    fontFamily: Arial, "Helvetica Neue", Helvetica, sans-serif
    fontSize: 20px
    fontWeight: 400
    lineHeight: 32px
    letterSpacing: 0em
  body-lg:
    fontFamily: Arial, "Helvetica Neue", Helvetica, sans-serif
    fontSize: 18px
    fontWeight: 400
    lineHeight: 28px
    letterSpacing: 0em
  body:
    fontFamily: Arial, "Helvetica Neue", Helvetica, sans-serif
    fontSize: 16px
    fontWeight: 400
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Arial, "Helvetica Neue", Helvetica, sans-serif
    fontSize: 14px
    fontWeight: 400
    lineHeight: 20px
    letterSpacing: 0.01em
  label-caps:
    fontFamily: Arial, "Helvetica Neue", Helvetica, sans-serif
    fontSize: 12px
    fontWeight: 700
    lineHeight: 16px
    letterSpacing: 0.05em
  chart-label:
    fontFamily: Arial, "Helvetica Neue", Helvetica, sans-serif
    fontSize: 11px
    fontWeight: 400
    lineHeight: 16px
    letterSpacing: 0.01em
  source:
    fontFamily: Arial, "Helvetica Neue", Helvetica, sans-serif
    fontSize: 11px
    fontWeight: 400
    lineHeight: 16px
    letterSpacing: 0.01em
  slide-headline:
    fontFamily: Georgia, "Times New Roman", Times, serif
    fontSize: 28px
    fontWeight: 400
    lineHeight: 36px
    letterSpacing: -0.01em
  slide-section:
    fontFamily: Georgia, "Times New Roman", Times, serif
    fontSize: 32px
    fontWeight: 400
    lineHeight: 40px
    letterSpacing: -0.01em
  slide-body:
    fontFamily: Arial, "Helvetica Neue", Helvetica, sans-serif
    fontSize: 14px
    fontWeight: 400
    lineHeight: 20px
    letterSpacing: 0em
rounded:
  none: 0px
  sm: 4px
spacing:
  4: 4px
  8: 8px
  12: 12px
  16: 16px
  24: 24px
  32: 32px
  48: 48px
  64: 64px
  96: 96px
components:
  button-primary:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.on-accent}"
    rounded: "{rounded.sm}"
    padding: 12px
    typography: "{typography.body}"
  button-primary-hover:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.sm}"
    padding: 12px
  button-secondary:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.primary}"
    rounded: "{rounded.sm}"
    padding: 12px
  button-ghost:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.secondary}"
    rounded: "{rounded.none}"
    padding: 8px
  page:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.text}"
  header-dark:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
  card:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.text}"
    rounded: "{rounded.none}"
    padding: 32px
  insight-label:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.secondary}"
    typography: "{typography.label-caps}"
  divider-light:
    backgroundColor: "{colors.pale-grey}"
    height: 1px
  divider-medium:
    backgroundColor: "{colors.light-grey}"
    height: 1px
  divider-dark:
    backgroundColor: "{colors.ink}"
    height: 1px
  chart-bar-primary:
    backgroundColor: "{colors.secondary}"
  chart-bar-navy:
    backgroundColor: "{colors.chart-navy}"
  chart-bar-muted:
    backgroundColor: "{colors.light-grey}"
---

## Overview

IzeyX Design Language v1 is a high-contrast consulting editorial system. It is built to feel like a McKinsey digital publication or board deck: Georgia for conclusions, Arial for evidence, deep navy for authority, electric blue used sparingly, and a 4px spacing grid that never breaks.

The identity is not decorative. Structure comes from alignment, white space, and a conclusion-first hierarchy. Pages should look roughly 80–90% white or very pale grey, 5–15% deep navy or black, and under 5% electric blue.

The brand mark lives at `assets/izeyx-mark.png`: a white line triangle in a blue circle. Use it small in headers and slides. Do not restyle it, add a wordmark lockup that fights Georgia headlines, or flood pages with it.

Use this system for reports, insight articles, dashboards, landing pages, and 16:9 decks. Do not invent a second palette, a second type family, or a SaaS card language.

**Formula, in one pass:** Georgia + Arial. White + `#051C2C` + `#2251FF`. 4px grid. Large editorial headlines. Body at ~150% line height. Generous white space. Thin 1px dividers. Almost-square corners. Almost no shadows. One accent at a time. Charts in blues and greys. Headings that state the conclusion.

## Colors

The core brand is four values plus black:

| Token | Hex | Use |
| --- | --- | --- |
| primary / Deep Blue | `#051C2C` | Dark bands, headlines, dark slides, shadows |
| secondary / Electric Blue | `#2251FF` | Links, one highlight, primary action, key chart series |
| tertiary / Cyan | `#00A9F4` | Secondary chart series only |
| neutral / White | `#FFFFFF` | Default page background |
| ink | `#000000` | Darkest separators and rare pure-black text |
| text | `#333333` | Body copy |

Supporting blues are for data visualisation, never for decorating the page: `#034B6F`, `#027AB1`, `#39BDF3`, `#71D2F1`, `#AAE6F0`, `#AFC3FF`.

Neutrals, from dark to pale: `#333333`, `#4D4D4D`, `#757575`, `#B3B3B3`, `#D0D0D0`, `#E6E6E6`, `#F0F0F0`. Do not use the full set on one screen. Body is `#333333`. Captions are `#4D4D4D` or `#757575`. Hairlines are `#E6E6E6`.

Links and interactive text use Electric Blue. Do not colour whole paragraphs blue. Do not introduce green, orange, purple, or gradient fills unless the user explicitly asks.

## Typography

Two faces only.

- **Headings / display:** Georgia Regular. Slight negative tracking on large sizes (−0.01em to −0.02em).
- **Body, UI, labels, numbers, charts:** Arial. Helvetica Neue is an acceptable fallback.
- **Emphasis:** Arial Bold, used rarely.
- **Avoid:** semibold everywhere, mixed third fonts, italic as decoration, all-caps headlines.

Desktop type scale (size / line-height):

- Display 1 64/76
- Display 2 60/72
- Display 3 56/68
- Display 4 52/64
- H1 44/52
- H2 40/48
- H3 36/44
- H4 32/36
- H5 28/32
- H6 24/28
- Article lead 24/36
- Article body 20/32
- Large body 18/28
- Normal body 16/24
- Small body 14/20

Normal body is 16px on 24px — 150% line height. Do not tighten that.

Letter-spacing:

- Large Georgia headlines: −0.01em to −0.02em
- Body: 0em
- Small labels: +0.01em
- Uppercase category labels: +0.04em to +0.06em

Category labels look like this: `INSIGHTS` — Arial Bold, 11–12px, uppercase, ~+5% tracking, Electric Blue or Deep Blue. The headline beneath is Georgia Regular, slightly tight, sentence case, and states a conclusion.

**Wrong:** `Market Analysis`  
**Right:** `Digital adoption has doubled since 2022, creating three immediate growth opportunities`

For 16:9 decks: headline Georgia 24–28pt; section title Georgia 30–36pt; body Arial 12–14pt; chart labels 9–11pt; source 8–9pt. Line spacing 1.15–1.3. Paragraph spacing 6–10pt.

## Layout

Everything sits on a **4px grid**. Allowed spacing: 4, 8, 12, 16, 24, 32, 48, 64, 96. Never 17, 27, 53, or other off-grid values.

| Size | Use |
| --- | --- |
| 4px | Tiny internal gap |
| 8px | Icon-to-text |
| 12px | Compact UI padding, button padding |
| 16px | Default internal padding, paragraph gap |
| 24px | Related content |
| 32px | Component padding |
| 48px | Content groups, heading after a section |
| 64px | Major sections |
| 96px | Large page divisions |

Paragraph rules: no first-line indent. Body 16/24. Space after a paragraph 16–24px. Subheading to paragraph 16px. End of section to next heading 48–64px. Do not put huge gaps between every paragraph.

Page white space is part of the brand:

- Web gutters: 48–64px minimum
- Major sections: 64–96px vertical
- Readable text column: much narrower than the viewport (roughly 640–720px for articles; 1120–1280px for dashboards)
- A4 reports: left/right 22–28mm, top 20–28mm, bottom 20–25mm
- 16:9 slides: margins ~0.5–0.7in

Alignment is the structure. Prefer a strict column grid over cards. Prefer a hairline over a box.

## Elevation & Depth

Elevation exists in the token set (0 / 2 / 4 / 8 / 16px) and the shadow colour is Deep Blue `#051C2C` at low opacity. For reports, articles, and decks, use **almost no shadows**.

If a surface must lift (a dropdown, a sticky header on scroll), use a 4px or 8px shadow derived from `#051C2C` at 8–16% opacity. Never use a black glow, never a coloured electric-blue shadow, never a stacked card that looks like a SaaS dashboard tile.

## Shapes

Keep things almost square. Radius is 0px by default, 4px maximum. Buttons may use 4px. Cards, images, charts, tables, and panels should be 0–4px.

No 16–32px rounded rectangles. No pills except a rare status chip, and even then 4px is preferred. No circular metric orbs as a layout system.

Separators:

- Light: 1px `#E6E6E6`
- Medium: 1px `#B3B3B3`
- Dark: 1px `#000000`

No thick outlines. No decorative frames. No huge rounded containers.

## Components

**Page.** White canvas. Deep navy is used as a full-bleed header/footer band or as type, not as a wash behind everything.

**Insight label.** Uppercase Arial Bold 12px, +0.05em, Electric Blue. Sits 16px above a Georgia headline.

**Headline.** Georgia Regular. Conclusion, not a topic. Colour `#051C2C`.

**Lead.** Arial 24/36, `#333333`, max-width of the reading column.

**Body.** Arial 16/24 or article 20/32. Links `#2251FF`, underline on hover only.

**Primary button.** Electric Blue fill, white text, 4px radius, 12px 24px padding, Arial. Hover to Deep Blue.

**Secondary button.** White fill, Deep Blue text, 1px `#E6E6E6` border, 4px radius.

**Text link / ghost.** No fill, Electric Blue text.

**Card.** Optional. If used: no drop shadow, no 24px radius, 1px `#E6E6E6` or none, 32px padding, white. Prefer open sections with a hairline over cards.

**Table.** Hairline rows `#E6E6E6`. Header Arial Bold 12–14px, Deep Blue or `#333333`. Numbers right-aligned, Arial. No zebra unless density demands it; if so, `#F0F0F0`.

**Chart.** One highlight series in `#2251FF` or `#051C2C`. Remaining series from the supporting blues and greys. Axes and gridlines `#E6E6E6`. Labels Arial 11px `#4D4D4D`. Source line under the chart in 11px `#757575`. No 3D. No rainbow palettes. No decorative icons inside bars.

**Divider.** 1px. Full content width or inset 0. Used to separate major blocks instead of cards.

**Deck slide.** White. Georgia action title top-left. Evidence in a 2–3 column grid. Source bottom-left. Page number bottom-right in Arial 11px `#757575`.

## Do's and Don'ts

**Do**

- Write headings as conclusions.
- Keep Georgia for titles and Arial for everything else.
- Use the 4px spacing scale only.
- Leave large margins. Let the page breathe.
- Use one accent colour at a time, almost always Electric Blue.
- Separate sections with 1px hairlines and 48–64px of space.
- Set body line-height at ~150%.
- Track small uppercase labels; slightly tighten large serif headlines.
- Build charts from navy, electric blue, cyan, and grey.
- Default to 0–4px corners and no shadow.

**Don't**

- Don't use Inter, Roboto, Poppins, Montserrat, Playfair, or any third family.
- Don't use 20–30px rounded “SaaS cards”.
- Don't wrap every block in a bordered tile.
- Don't flood the page with Electric Blue or cyan.
- Don't use thick borders, gradients, glassmorphism, or neon glow.
- Don't indent paragraphs.
- Don't bold entire sentences. Emphasis is rare.
- Don't title slides or pages with generic topics.
- Don't pick off-grid spacing.
- Don't introduce a second accent (orange alerts, green success) unless the product already requires semantic status, and even then keep them tiny.
