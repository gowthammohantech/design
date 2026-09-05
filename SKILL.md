---
name: mercury-design
description: Mercury's dark-canvas business-banking design system. Use whenever building, styling, or reviewing UI in this repo — React components, pages, Tailwind classes, CSS, marketing surfaces, or dashboard screens. Covers colors, Arcadia typography, radius and spacing scales, and 19 component specs. Trigger on any request mentioning styling, theming, a new screen or component, or "make this look right."
---

# Mercury design system

Read `DESIGN.md` at the repo root for the full token set before writing UI code.
Import `mercury-theme.css` for the Tailwind v4 `@theme` layer.

## Non-negotiables

Get these wrong and the output stops reading as Mercury:

1. **Dark canvas is the default.** Marketing surfaces are `#171721` with `#ededf3` text. This is not a dark-mode variant — there is no light default to toggle back to. The light track (`#fbfcfd`) is dashboard-only.
2. **Never `#000000` or `#ffffff`.** Black is `#171721` / `#1e1e2a`. Off-white text is `#ededf3`. Pure white appears only as text on an indigo fill.
3. **One filled indigo CTA per band.** `#5266eb` fills exactly one pill in any given section. A second CTA in the same band uses `button-secondary` (bordered, `#272735` hairline on canvas).
4. **Body UI is weight 420.** Not 400, not 500. Buttons, nav, inputs, labels — all 16px / 420.
5. **Display tracking is positive.** +0.42px to +0.48px on 28–42px headings. Never negative.
6. **Radius scale is 4 / 8 / 12 / 32 / 40.** 12px for cards, 32px for pill CTAs, 4px for chrome. Never 16px or 20px, never 0px on a card.
7. **Periwinkle accents are decoration.** `#9cb4e8` and `#cdddff` never fill a button, link, or interactive surface.
8. **Error is pink-magenta `#d03275`.** Not red.

## Component quick reference

| Need | Use | Geometry |
|---|---|---|
| Primary action | indigo fill `#5266eb`, white text | h40, `0 20px`, r32 |
| Secondary action | canvas fill, `#272735` border | h40, `0 20px`, r32 |
| Input / email pill | `#fbfcfd` fill, dark ink | h46, `0 20px`, r32 |
| Product card | `#1e1e2a` fill, `#272735` border | p32 (p20 compact), r12 |
| Testimonial | `#1e1e2a` fill, 21px/360 body | p40, r12 |
| Soft tag | indigo @ 10% alpha, indigo text | `4px 8px`, r8 |
| Nav | canvas, h72, `0 32px` | links r4, `8px 12px` |

Focus rings use `#5266eb`. Transitions are `0.15s cubic-bezier(0.4, 0, 0.2, 1)`.

## Fonts

Arcadia and Arcadia Display are proprietary and not redistributable. If the licensed files aren't present in the repo, use Inter Variable at the same weights (360 / 400 / 420 / 480) with +0.4px tracking on display sizes. Do not substitute Helvetica, Roboto, or SF Pro.

## Layout rhythm

- Marketing section padding: 72–112px vertical. Dashboard: 32–40px.
- Horizontal gutter: 32px throughout.
- 16-column grid, 1952px max width, 32px gutters.
- Breakpoints 1440 / 1024 / 768; display sizes step 65 → 49 → 42 → 32.

## When something isn't specified

`DESIGN.md` has a Known Gaps section — dashboard semantic colors, card hover states, sub-brand accents, and frosted-glass panels are not defined. Don't invent a token silently; pick the nearest existing one and say which gap you hit.
