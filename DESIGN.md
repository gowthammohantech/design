---
name: Mercury
version: alpha
website: https://mercury.com
description: >-
  Mercury's business-banking design language — a dark-canvas fintech built on
  inverted ink (#ededf3 on #171721), an electric indigo CTA (#5266eb), and a
  pale-periwinkle decorative accent (#9cb4e8). Type runs arcadia and
  arcadiaDisplay at non-conventional weights (360, 420, 480) with positive
  0.42px tracking on display sizes. Buttons are 32px pill radii on a 4px base
  radius scale.

colors:
  primary: "#5266eb"
  primary-hover: "#4354c8"
  primary-active: "#3442a6"
  primary-soft: "#5266eb"        # applied at 10% alpha
  accent-periwinkle: "#9cb4e8"   # decoration only
  accent-mist: "#cdddff"         # decoration only
  canvas: "#171721"
  canvas-elevated: "#1e1e2a"
  canvas-light: "#fbfcfd"
  surface-default: "#ededf3"
  surface-secondary: "#f4f5f9"
  surface-hover: "#dddde5"
  ink-default: "#ededf3"
  ink-emphasized: "#1e1e2a"
  ink-subdued: "#c3c3cc"
  ink-disabled: "#70707d"
  hairline: "#272735"
  hairline-subdued: "#c3c3cc"
  error: "#d03275"
  on-primary: "#ffffff"

typography:
  display-xxl:
    fontFamily: "arcadiaDisplay, 'Inter Variable', system-ui, sans-serif"
    fontSize: 65px
    fontWeight: 480
    lineHeight: 1.1
    letterSpacing: "0"
  display-xl:
    fontFamily: "arcadiaDisplay, 'Inter Variable', system-ui, sans-serif"
    fontSize: 49px
    fontWeight: 480
    lineHeight: 1.1
    letterSpacing: "0"
  display-lg:
    fontFamily: "arcadiaDisplay, 'Inter Variable', system-ui, sans-serif"
    fontSize: 42px
    fontWeight: 480
    lineHeight: 1.15
    letterSpacing: "0.42px"
  display-md:
    fontFamily: "arcadiaDisplay, 'Inter Variable', system-ui, sans-serif"
    fontSize: 32px
    fontWeight: 480
    lineHeight: 1.15
    letterSpacing: "0.48px"
  display-sm:
    fontFamily: "arcadiaDisplay, 'Inter Variable', system-ui, sans-serif"
    fontSize: 28px
    fontWeight: 480
    lineHeight: 1.2
    letterSpacing: "0.42px"
  display-sm-light:
    fontFamily: "arcadiaDisplay, 'Inter Variable', system-ui, sans-serif"
    fontSize: 28px
    fontWeight: 360
    lineHeight: 1.2
    letterSpacing: "0.42px"
  heading-md:
    fontFamily: "arcadiaDisplay, 'Inter Variable', system-ui, sans-serif"
    fontSize: 24px
    fontWeight: 480
    lineHeight: 1.2
    letterSpacing: "0.48px"
  body-lg:
    fontFamily: "arcadia, 'Inter Variable', system-ui, sans-serif"
    fontSize: 21px
    fontWeight: 360
    lineHeight: 1.35
    letterSpacing: "0"
  body-lg-emphasized:
    fontFamily: "arcadia, 'Inter Variable', system-ui, sans-serif"
    fontSize: 21px
    fontWeight: 480
    lineHeight: 1.2
    letterSpacing: "0"
  body-md:
    fontFamily: "arcadia, 'Inter Variable', system-ui, sans-serif"
    fontSize: 18px
    fontWeight: 360
    lineHeight: 1.35
    letterSpacing: "0"
  body-md-emphasized:
    fontFamily: "arcadia, 'Inter Variable', system-ui, sans-serif"
    fontSize: 18px
    fontWeight: 480
    lineHeight: 1.35
    letterSpacing: "0"
  body-default:
    fontFamily: "arcadia, 'Inter Variable', system-ui, sans-serif"
    fontSize: 16px
    fontWeight: 420
    lineHeight: 1.0
    letterSpacing: "0"
  body-relaxed:
    fontFamily: "arcadia, 'Inter Variable', system-ui, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: "0"
  caption:
    fontFamily: "arcadia, 'Inter Variable', system-ui, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: "0.24px"

rounded:
  xs: "4px"
  sm: "8px"
  md: "12px"
  lg: "32px"
  xl: "40px"
  pill: "9999px"

spacing:
  xxs: "2px"
  xs: "4px"
  sm: "8px"
  md: "12px"
  base: "20px"
  lg: "32px"
  xl: "40px"
  2xl: "72px"
  3xl: "112px"

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.body-default}"
    rounded: "{rounded.lg}"
    padding: "0px 20px"
    height: "40px"
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "{colors.on-primary}"
    typography: "{typography.body-default}"
    rounded: "{rounded.lg}"
    padding: "0px 20px"
    height: "40px"
  button-primary-pressed:
    backgroundColor: "{colors.primary-active}"
    textColor: "{colors.on-primary}"
    typography: "{typography.body-default}"
    rounded: "{rounded.lg}"
    padding: "0px 20px"
    height: "40px"
  button-secondary:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink-default}"
    typography: "{typography.body-default}"
    rounded: "{rounded.lg}"
    padding: "0px 20px"
    height: "40px"
    border: "1px solid {colors.hairline}"
  email-capture-pill:
    backgroundColor: "{colors.canvas-light}"
    textColor: "{colors.ink-emphasized}"
    typography: "{typography.body-default}"
    rounded: "{rounded.lg}"
    padding: "0px 0px 0px 20px"
    height: "46px"
  text-input:
    backgroundColor: "{colors.canvas-light}"
    textColor: "{colors.ink-emphasized}"
    typography: "{typography.body-default}"
    rounded: "{rounded.lg}"
    padding: "0px 20px"
    height: "46px"
    border: "1px solid {colors.hairline-subdued}"
  text-input-focused:
    backgroundColor: "{colors.canvas-light}"
    textColor: "{colors.ink-emphasized}"
    typography: "{typography.body-default}"
    rounded: "{rounded.lg}"
    padding: "0px 20px"
    height: "46px"
    border: "1px solid {colors.primary}"
  top-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink-default}"
    typography: "{typography.body-default}"
    rounded: "{rounded.xs}"
    padding: "0px 32px"
    height: "72px"
  nav-link:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink-default}"
    typography: "{typography.body-relaxed}"
    rounded: "{rounded.xs}"
    padding: "8px 12px"
    height: "32px"
  card-scene:
    backgroundColor: "{colors.canvas-elevated}"
    textColor: "{colors.ink-default}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: "32px"
  card-product-mockup:
    backgroundColor: "{colors.canvas-elevated}"
    textColor: "{colors.ink-default}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: "20px"
  card-feature-light:
    backgroundColor: "{colors.surface-default}"
    textColor: "{colors.ink-emphasized}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: "32px"
  card-testimonial:
    backgroundColor: "{colors.canvas-elevated}"
    textColor: "{colors.ink-default}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.md}"
    padding: "40px"
  pill-tag-soft:
    backgroundColor: "{colors.primary-soft}"
    textColor: "{colors.primary}"
    typography: "{typography.caption}"
    rounded: "{rounded.sm}"
    padding: "4px 8px"
  hero-disclaimer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink-subdued}"
    typography: "{typography.caption}"
    rounded: "{rounded.xs}"
    padding: "0px 32px"
    height: "41px"
  logo-strip-cell:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink-subdued}"
    typography: "{typography.body-default}"
    rounded: "{rounded.xs}"
    padding: "20px"
  footer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink-subdued}"
    typography: "{typography.caption}"
    rounded: "{rounded.xs}"
    padding: "112px 32px"
  link-inline:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.primary}"
    typography: "{typography.body-relaxed}"
    rounded: "{rounded.xs}"
    padding: "0"
---

## Overview

Mercury's marketing surface opens on a deep indigo-black `#171721` — a near-black tinted with violet, never pure `#000000` — overlaid with atmospheric photography that bleeds into the hero. Inverted text `#ededf3` carries the entire reading surface, with `#c3c3cc` as the secondary register and `#272735` doing the hairline work. The single brand voltage, indigo `#5266eb`, appears exactly once per band as the primary pill CTA, and as the inline-link color. Two pale-periwinkle accents, `#9cb4e8` and `#cdddff`, appear in gradient washes and product-mockup highlights but are kept off interactive elements. The light track exists — `#fbfcfd` — but the authenticated dashboard product is where it runs, not the marketing top of funnel.

**Inverted canvas as signature.** Where most business-banking sites default to a white marketing surface with indigo accents, Mercury runs the inverse and trusts photography to do the warmth. The dark canvas is not a dark-mode toggle; it is the default state of the brand.

**Weight 420 as quiet signal.** The body register sits at the non-standard weight 420 — between regular (400) and medium-equivalent (480).

**Positive-tracked display.** Display sizes 28–65px carry +0.42px to +0.48px letter-spacing, the inverse of the negative-tracked convention that dominates fintech.

**Key characteristics:**

- Dark canvas as default — every marketing surface lives on `#171721`, with light `#fbfcfd` reserved for the authenticated dashboard.
- Single voltage CTA — indigo `#5266eb` fills one pill per band, never two.
- Arcadia at weight 420 for all UI body.
- Positive 0.42–0.48px letter-spacing on display tiers.
- 32px pill radius for CTAs on a 4px base; the scale collapses to 4 / 8 / 12 / 32 / 40.
- Photography, not CSS gradients, is the hero depth medium.
- Scene cards — product mockups composite as `#1e1e2a` elevated panels with 12px corners.

## Colors

### Brand & accent

| Token | Hex | Role |
|---|---|---|
| `primary` | `#5266eb` | Filled CTA, inline links, focus rings. The load-bearing voltage. |
| `primary-hover` | `#4354c8` | CTA hover |
| `primary-active` | `#3442a6` | CTA pressed |
| `primary-soft` | `#5266eb` @ 10% alpha | Soft tag pills, inline emphasis chips |
| `accent-periwinkle` | `#9cb4e8` | Decoration only — mockup highlights, atmospheric washes |
| `accent-mist` | `#cdddff` | Decoration only — lighter gradient washes |

### Surface

| Token | Hex | Role |
|---|---|---|
| `canvas` | `#171721` | Marketing default. Violet-tinted near-black. |
| `canvas-elevated` | `#1e1e2a` | Scene cards, testimonial blocks, mockup chrome |
| `canvas-light` | `#fbfcfd` | Dashboard default; inputs and the email-capture pill |
| `surface-default` | `#ededf3` | Inverted-light panel fill for light interludes |
| `surface-secondary` | `#f4f5f9` | Cooler off-white sub-fill on stacked light cards |
| `surface-hover` | `#dddde5` | Press lift on light surface cards |

### Text

| Token | Hex | Role |
|---|---|---|
| `ink-default` | `#ededf3` | All reading text on the dark canvas. Cool off-white, never pure white. |
| `ink-emphasized` | `#1e1e2a` | Dark text when inverting onto a light surface |
| `ink-subdued` | `#c3c3cc` | Helper text, captions, footer copy, table labels |
| `ink-disabled` | `#70707d` | Unavailable controls only |

### Hairlines & semantic

| Token | Hex | Role |
|---|---|---|
| `hairline` | `#272735` | 1px border on scene cards against the dark canvas |
| `hairline-subdued` | `#c3c3cc` | Lighter hairline on inverted-light cards |
| `error` | `#d03275` | Error text, icon, border. Pink-magenta, never red. |
| `on-primary` | `#ffffff` | The only place pure white is allowed — text on indigo fills |

## Typography

### Families

Two proprietary families: **arcadia** for body, UI, and captions; **arcadiaDisplay** for headings and hero. Both are variable fonts with non-standard weights — 360 (light display), 400 (regular), 420 (UI default), 480 (display medium).

When Arcadia is unavailable, fall back to **Inter Variable** at weight 420 with positive 0.4px tracking on display sizes. Avoid Helvetica, Roboto, and SF Pro — all three are too geometric for Arcadia's slightly humanist silhouette.

### Hierarchy

| Token | Size | Weight | Line height | Tracking | Use |
|---|---|---|---|---|---|
| `display-xxl` | 65px | 480 | 1.1 | 0 | Hero headline, wide breakpoints |
| `display-xl` | 49px | 480 | 1.1 | 0 | Primary section headline |
| `display-lg` | 42px | 480 | 1.15 | +0.42px | Section opener |
| `display-md` | 32px | 480 | 1.15 | +0.48px | Mid-section heading |
| `display-sm` | 28px | 480 | 1.2 | +0.42px | Card title |
| `display-sm-light` | 28px | 360 | 1.2 | +0.42px | Editorial sub-heading |
| `heading-md` | 24px | 480 | 1.2 | +0.48px | Sub-section label |
| `body-lg` | 21px | 360 | 1.35 | 0 | Testimonial lead, hero supporting copy |
| `body-lg-emphasized` | 21px | 480 | 1.2 | 0 | Pull-quote in scene card |
| `body-md` | 18px | 360 | 1.35 | 0 | Marketing paragraph body |
| `body-md-emphasized` | 18px | 480 | 1.35 | 0 | Inline emphasis inside body |
| `body-default` | 16px | 420 | 1.0 | 0 | UI body — buttons, nav, inputs. The workhorse. |
| `body-relaxed` | 16px | 400 | 1.4 | 0 | Footer body, helper paragraph |
| `caption` | 12px | 400 | 1.4 | +0.24px | Disclaimers, table labels, fine print |

### Principles

- **Weight 420 carries UI.** Buttons, nav, inputs, and the email-capture pill all render at 16px / 420. Bumping to 500 reads as institutional; dropping to 400 reads as generic.
- **Positive tracking on display.** Tiers at 28–42px carry +0.42px to +0.48px. The hero at 49px and 65px reverts to 0.
- **Two-family economy.** Arcadia for every UI surface; arcadiaDisplay for every heading 24px and up. Never mix across the boundary.

## Layout

### Spacing

Base unit 4px, with 12 / 20 / 32px doing most of the mid-range work.

`xxs` 2px · `xs` 4px · `sm` 8px · `md` 12px · `base` 20px · `lg` 32px · `xl` 40px · `2xl` 72px · `3xl` 112px

- **Section padding:** 72–112px vertical on marketing; 32–40px on dashboard surfaces.
- **Card padding:** 32px on scene and feature cards; 20px on compact mockup cards; 40px on testimonials.
- **Nav padding:** `0 32px` horizontal — 32px is the repeating horizontal rhythm.

### Grid & container

- `--grid-max-width: 1952px`, `--grid-total-columns: 16`, `--grid-gutters: 32px`. A 16-column grid, wider than the 12-column default.
- `--navbar-height: 72px`, `--navbar-banner-height: 49px`, `--subnav-height: 48px`.
- Pricing collapses 4-up → 2-up → 1-up at 1024 / 768.

### Whitespace

Vertical air runs generously — hero padding 72px, major section gaps 112px, tightening to 32px inside cards. The dark canvas does the heavy lifting; whitespace holds photography and scene cards apart, not borders.

## Elevation & depth

| Level | Treatment | Use |
|---|---|---|
| 0 | Flat dark canvas `#171721` | Default surface |
| 1 | Elevated panel `#1e1e2a` | Scene cards, testimonials, mockup chrome |
| 2 | `box-shadow` with `#70707d` at low alpha | Floating panels above an elevated panel |
| 3 | Atmospheric photography | Hero depth — image-based, not literal shadow |

Photography *is* the hero depth system: the image bleeds into `#171721` with no harsh edge, creating a horizon that reads as depth without a gradient. Below the fold, switch to surface-ladder elevation. Drop shadows stay rare and subtle.

## Shapes

| Token | Value | Use |
|---|---|---|
| `xs` | 4px | Nav cells, hairline tags, table chrome (dominant, ~91 uses) |
| `sm` | 8px | Form inputs, small product cells |
| `md` | 12px | Scene cards, feature cards, dashboard mockup chrome |
| `lg` | 32px | Pill buttons, email-capture pill, text inputs |
| `xl` | 40px | Soft-corner hero cards |
| `pill` | 9999px | Status pills, indicator dots |

Photography runs full-bleed with no rounded corners. Product UI scenes sit inside 12px containers. Customer logo strips render as plain wordmarks with no card chrome.

## Components

### Buttons

**`button-primary`** — the system-wide CTA, exactly one filled pill per band.
Background `primary` `#5266eb`, text `#ffffff`, `body-default` (16px / 420), padding `0 20px`, height 40px, radius 32px. Hover → `#4354c8`; pressed → `#3442a6`.

**`button-secondary`** — outline alternative on the dark canvas.
Background `canvas`, text `ink-default`, 1px `hairline` border, same pill geometry as primary.

### Inputs & forms

**`email-capture-pill`** — hero email capture with an embedded CTA.
Background `canvas-light` `#fbfcfd`, text `ink-emphasized`, `body-default`, padding `0 0 0 20px`, height 46px, radius 32px. The filled `button-primary` sits flush-right inside the pill — the signature double-component.

**`text-input`** — standard field.
Background `canvas-light`, text `ink-emphasized`, 1px `hairline-subdued` border, padding `0 20px`, height 46px, radius 32px. Focus swaps the border to `primary`.

### Navigation

**`top-nav`** — full-width, floating over hero photography.
Background `canvas` (or transparent on first paint), text `ink-default`, padding `0 32px`, height 72px. Wordmark left, primary nav center, log-in plus `button-primary` right.

**`nav-link`** — `body-relaxed` (16px / 400), padding `8px 12px`, height 32px, radius 4px. Hover lifts to a 10%-opacity indigo background.

### Cards & containers

**`card-scene`** — product mockup scene on the dark canvas. Background `canvas-elevated`, padding 32px, radius 12px, 1px `hairline` border. Contains nested mini-mockups.

**`card-product-mockup`** — compact product-feature card. Background `canvas-elevated`, padding 20px, radius 12px. One screenshot above a 2-line label and 3-line description.

**`card-feature-light`** — inverted-light track. Background `surface-default` `#ededf3`, text `ink-emphasized`, padding 32px, radius 12px. Used sparingly.

**`card-testimonial`** — background `canvas-elevated`, `body-lg` (21px / 360), padding 40px, radius 12px. Category pill, quote, photo, attribution.

### Pills & signature components

**`pill-tag-soft`** — the only place indigo runs as a fill outside the CTA. Background `primary` at 10% alpha, text `primary`, `caption`, padding `4px 8px`, radius 8px.

**`hero-disclaimer`** — fine print beneath the hero. Background `canvas`, text `ink-subdued`, `caption` (12px / 400 / +0.24px), padding `0 32px`, height 41px, width capped at 950px.

**`logo-strip-cell`** — background `canvas`, padding 20px, no card chrome. Wordmarks flat against the canvas at equal optical weight.

**`footer`** — background `canvas`, text `ink-subdued`, `caption`, padding `112px 32px`.

**`link-inline`** — text `primary`, `body-relaxed`, no underline by default, underline on hover.

## Do's and don'ts

### Do

- Reserve `#5266eb` for filled CTAs, inline links, and focus rings — one filled pill per band.
- Default every marketing surface to `#171721` with `#ededf3` text.
- Render display tiers at weight 480 with positive 0.42–0.48px tracking.
- Use weight 420 for UI body — buttons, nav, inputs.
- Pair every product feature with a scene card on `#1e1e2a` at 12px radius.
- Treat photography as the hero's depth medium; below the fold, switch to the surface ladder.

### Don't

- Don't use `#000000` anywhere — Mercury's black is `#171721` or `#1e1e2a`.
- Don't use `#ffffff` as a marketing text color. Pure white is only for text on indigo fills.
- Don't render `body-default` at 400 or 500 — the brand uses 420.
- Don't apply negative letter-spacing to display sizes.
- Don't fill `#9cb4e8` or `#cdddff` on buttons or interactive surfaces — decoration only.
- Don't use a 16px or 20px corner radius; the scale is 4 / 8 / 12 / 32 / 40.
- Don't swap `#d03275` for a conventional red — pink-magenta is deliberate.

## Responsive behavior

| Name | Width | Key changes |
|---|---|---|
| Wide | ≥ 1440px | 16-column grid at 1952px max; hero display 65px |
| Desktop | 1024–1440px | Default max-width; hero display 49px; product grid 4-up |
| Tablet | 768–1023px | Product grid 2-up; nav sub-menus collapse; hero display 42px |
| Mobile | < 768px | Product grid 1-up; hamburger nav; hero display 32px |

- Display tiers stair-step 65 → 49 → 42 → 32 → 28px.
- Pill buttons hold 40px height on desktop; the email-capture pill bumps to 46px on mobile.
- Form fields stay at 46px minimum across all breakpoints.
- Hero photography re-crops on mobile to keep the horizon visible.
- Top-nav links collapse into a drawer below 768px; the primary CTA stays visible.

## Motion

`--default-transition-duration: 0.15s` with `--ease-in-out: cubic-bezier(0.4, 0, 0.2, 1)`. Full motion token set (stagger durations, spring physics) is not captured.

## Known gaps

- **Dashboard semantic palette:** loading states, transaction-status pills, balance-change deltas, and financial-direction green/red live in the authenticated app and are not specified here.
- **Hover states:** only button hover and pressed states are documented. Card and nav hover specs were not reliably extractable.
- **Hero photography stops:** treated as photography, not a gradient. The tonal map is not tokenized.
- **Sub-brand accents:** Treasury, Personal, and Venture Debt carry small accent shifts on top of the core indigo system.
- **Frosted glass:** `--surface-frosted` and `--background-frosted` are declared as low-alpha blur layers but their composition was not visible on the captured surface.
