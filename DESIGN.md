---
version: alpha
name: Leedlime
description: |
  Leedlime's design system embodies a clean, sophisticated aesthetic grounded in
  natural imagery and refined typography. The interface prioritizes clarity and
  trust, using a restrained neutral palette anchored by deep charcoal (#161412)
  paired with warm accent tones. The visual atmosphere is professional yet
  approachable, with generous whitespace and deliberate use of natural landscape
  photography as contextual backdrop. Serif headlines convey editorial
  authority, while a lean sans-serif body ensures legibility at all scales. The
  system favors sharp edges over rounded softness, except for pill-shaped
  buttons and discrete UI toggles, creating visual rhythm between rigid
  structure and organic interaction moments.
source:
  url: "https://leedlime.com/"
  pagesAnalyzed: 1
  extractedAt: 2026-11-04
  tokensMeasured: true
colors:
  primary: "#161412"
  accent: "#DA7756"
  canvas: "#F9F8F6"
  on-primary: "#F9F8F6"
  ink: "#161412"
  body: "#2D2D2D"
  muted: "#6B6B6B"
  faint: "#FFFFFF"
  hairline: "#000000"
  accent-1: "#84CC16"
  neutral-1: "#262626"
typography:
  display-xl:
    fontFamily: Newsreader
    fontSize: 72px
    fontWeight: 400
    lineHeight: 1
    letterSpacing: -1.44px
  display-lg:
    fontFamily: Newsreader
    fontSize: 64px
    fontWeight: 400
    lineHeight: 1
    letterSpacing: -1.28px
  display-md:
    fontFamily: Newsreader
    fontSize: 48px
    fontWeight: 400
    lineHeight: 1
    letterSpacing: -0.96px
  display-md-strong:
    fontFamily: Newsreader
    fontSize: 48px
    fontWeight: 500
    lineHeight: 1
    letterSpacing: -0.96px
  heading-lg:
    fontFamily: Newsreader
    fontSize: 36px
    fontWeight: 400
    lineHeight: 1.11
    letterSpacing: -0.72px
  heading-lg-strong:
    fontFamily: Newsreader
    fontSize: 36px
    fontWeight: 500
    lineHeight: 1.11
    letterSpacing: 0px
  heading-md:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: 400
    lineHeight: 1.33
    letterSpacing: -0.48px
  heading-sm:
    fontFamily: "Inter Sans"
    fontSize: 18px
    fontWeight: 700
    lineHeight: 1.56
    letterSpacing: -0.36px
  heading-xs:
    fontFamily: "Inter Sans"
    fontSize: 17px
    fontWeight: 700
    lineHeight: 1.5
    letterSpacing: -0.34px
  body-xl:
    fontFamily: "Inter Sans"
    fontSize: 20px
    fontWeight: 300
    lineHeight: 1.4
    letterSpacing: 0px
  body-lg:
    fontFamily: "Inter Sans"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.56
    letterSpacing: 0px
  body-md:
    fontFamily: "Inter Sans"
    fontSize: 16px
    fontWeight: 300
    lineHeight: 1.63
    letterSpacing: 0px
  body-sm:
    fontFamily: "Inter Sans"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.63
    letterSpacing: 0px
  body-sm-tight:
    fontFamily: "Inter Sans"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.43
    letterSpacing: 0px
  body-xs:
    fontFamily: "Inter Sans"
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.63
    letterSpacing: 0px
  nav:
    fontFamily: "Inter Sans"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.43
    letterSpacing: 0px
  button-md:
    fontFamily: "Inter Sans"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0px
  button-md-strong:
    fontFamily: "Inter Sans"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: 0px
  button-sm:
    fontFamily: "Inter Sans"
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: 0px
  label:
    fontFamily: "Inter Sans"
    fontSize: 9px
    fontWeight: 700
    lineHeight: 1.5
    letterSpacing: 0.72px
    textTransform: uppercase
  caption-md:
    fontFamily: "Inter Sans"
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1.33
    letterSpacing: 0px
  caption-sm:
    fontFamily: "Inter Sans"
    fontSize: 11px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0px
  caption-xs:
    fontFamily: "Inter Sans"
    fontSize: 10px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0px
  code:
    fontFamily: ui-monospace
    fontSize: 11px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 1.32px
    textTransform: uppercase
rounded:
  none: 0px
  xs: 4px
  sm: 8px
  md: 16px
  full: 9999px
spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 20px
  xl: 24px
  xxl: 28px
  xxxl: 32px
  section: 40px
  band: 44px
borderWidths:
  thin: 1px
shadows:
  sm: "rgba(0, 0, 0, 0.05) 0px 1px 2px 0px"
  md: "rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px"
  lg: "rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px"
  xl: "rgba(0, 0, 0, 0.25) 0px 25px 50px -12px"
elevationStrategy: layered-micro
themes:
  derived: dark   # the other theme is the site's measured palette
  light:
    bg: "#F9F8F6"
    surface: "#F2F1EF"
    surfaceRaised: "#E9E8E6"
    text: "#161412"
    textMuted: "#2D2D2D"
    border: "#000000"
    accent: "#161412"
    accentFg: "#FFFFFF"
    focusRing: "#161412"
    elevation: shadow
  dark:
    bg: "#0F0F0F"
    surface: "#1D1D1D"
    surfaceRaised: "#292929"
    text: "#F6F6F6"
    textMuted: "#9E9E9E"
    border: "#353535"
    accent: "#867A6E"
    accentFg: "#0B0B0C"
    focusRing: "#70665B"
    elevation: "border+surface"
gradients:
  - context: section
    kind: linear
    value: "linear-gradient(to top, rgb(250, 250, 250), rgba(0, 0, 0, 0))"
  - context: section
    kind: linear
    value: "linear-gradient(to right, rgb(10, 10, 10), rgba(0, 0, 0, 0))"
  - context: section
    kind: linear
    value: "linear-gradient(to left, rgb(10, 10, 10), rgba(0, 0, 0, 0))"
  - context: section
    kind: linear
    value: "repeating-linear-gradient(to right, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0) 23px, rgb(255, 255, 255) 23px, rgb(255, 255, 255) 24px)"
  - context: section
    kind: radial
    value: "radial-gradient(circle, rgb(209, 213, 219) 1px, rgba(0, 0, 0, 0) 1px)"
  - context: section
    kind: linear
    value: "linear-gradient(rgba(0, 0, 0, 0), rgba(249, 248, 246, 0.5), rgb(249, 248, 246))"
components:
  button-primary:
    textColor: "{colors.on-primary}"
    border: "1px solid {colors.neutral-1}"
    height: 62px
    padding: "16px 32px 16px 32px"
    fontSize: 18px
    boxShadow: "{colors.faint} 0px 0px 0px 0px, {colors.primary} 0px 0px 0px 2px, rgba(0, 0, 0, 0) 0px 0px 0px 0px"
    fontFamily: "Inter Sans"
    fontWeight: 500
    lineHeight: 1.56
    rounded: "{rounded.md}"
    backgroundColor: "{colors.primary}"
  button-primary-sm:
    typography: "{typography.button-md-strong}"
    textColor: "{colors.on-primary}"
    border: "1px solid rgba(0, 0, 0, 0.05)"
    height: 50px
    padding: "12px 24px 12px 24px"
    boxShadow: "rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px"
    rounded: "{rounded.sm}"
    backgroundColor: "{colors.primary}"
  button-filled:
    typography: "{typography.button-sm}"
    textColor: "rgba(22, 20, 18, 0.7)"
    border: "1px solid rgba(0, 0, 0, 0.1)"
    height: 33.5px
    padding: "6px 14px 6px 14px"
    boxShadow: "rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0.05) 0px 1px 2px 0px"
    rounded: "{rounded.full}"
    backgroundColor: "{colors.faint}"
  navigation:
    typography: "{typography.button-md}"
    textColor: "{colors.ink}"
    height: 20px
  footer:
    typography: "{typography.button-md}"
    textColor: "{colors.ink}"
    backgroundColor: "{colors.canvas}"
  link:
    typography: "{typography.button-md}"
    textColor: "{colors.on-primary}"
    padding: "24px 24px 24px 24px"
    backgroundColor: "{colors.primary}"
  link-sm:
    typography: "{typography.nav}"
    textColor: "{colors.on-primary}"
    padding: "8px 16px 8px 16px"
    rounded: "{rounded.sm}"
    backgroundColor: "{colors.primary}"
states:
  other-hover:
    target: other
    state: hover
    borderColor: "rgba(0, 0, 0, 0.2)"
  card-hover:
    target: card
    state: hover
    backgroundColor: "rgba(255, 255, 255, 0.4)"
breakpoints:
  - width: 375
    containerWidth: 325
    gridColumns: 4
    navLinksVisible: 0
    menuToggleVisible: true
    headingPx: 48
    bodyPx: 16
    sectionPaddingX: 24
  - width: 768
    containerWidth: 670
    gridColumns: 4
    navLinksVisible: 4
    menuToggleVisible: false
    headingPx: 60
    bodyPx: 16
    sectionPaddingX: 48
  - width: 1024
    containerWidth: 926
    gridColumns: 3
    navLinksVisible: 4
    menuToggleVisible: false
    headingPx: 72
    bodyPx: 16
    sectionPaddingX: 48
  - width: 1280
    containerWidth: 1238
    gridColumns: 3
    navLinksVisible: 4
    menuToggleVisible: false
    headingPx: 72
    bodyPx: 16
    sectionPaddingX: 48
  - width: 1440
    containerWidth: 1238
    gridColumns: 3
    navLinksVisible: 4
    menuToggleVisible: false
    headingPx: 72
    bodyPx: 16
    sectionPaddingX: 48
coverage:
  statesFound: 61
  gradientsFound: 6
  rolesUnassigned: 2
  archetypesUnnamed: 0
  archetypesDetected: 0
  responsiveMeasured: true
  stylesheetsBlocked: true
  semanticRampDeclared: false
---

# Design System Inspired by Leedlime

## 1. Visual Theme & Atmosphere

Leedlime's design system embodies a clean, sophisticated aesthetic grounded in natural imagery and refined typography. The interface prioritizes clarity and trust, using a restrained neutral palette anchored by deep charcoal (`{colors.primary}` — `#161412`) paired with warm accent tones. The visual atmosphere is professional yet approachable, with generous whitespace and deliberate use of natural landscape photography as contextual backdrop. Serif headlines convey editorial authority, while a lean sans-serif body ensures legibility at all scales. The system favors sharp edges over rounded softness, except for pill-shaped buttons and discrete UI toggles, creating visual rhythm between rigid structure and organic interaction moments.

**Key Characteristics**

- Deep charcoal primary with warm terracotta and lime accents for visual contrast
- Serif display typography (Newsreader) for headlines; lean sans-serif (Inter) for body and UI
- Generous whitespace and asymmetric layouts emphasizing breathing room
- Sharp edges (`{rounded.none}`) on core UI; pill-shaped buttons (`{rounded.full}`) for primary CTAs
- Layered micro-shadows creating barely-there elevation without visual weight
- Natural landscape imagery as thematic backdrop to product features
- Minimal use of color — mostly ink, canvas, and strategic accent deployment

## 2. Color Palette & Roles

### Primary

- **Brand Ink** (`{colors.primary}` — `#161412`): Deep charcoal serving as primary text, headings, CTAs, and active states. The core brand voice — authoritative and grounded.

### Accent Colors

- **Warm Accent** (`{colors.accent}` — `#DA7756`): Terracotta-toned secondary accent used in hero bands and decorative elements for warmth and visual relief.
- **Lime Green** (`{colors.accent-1}` — `#84CC16`): Bright lime accent applied decoratively; no primary interaction role assigned. Used as a tertiary highlight and decorative flourish.

### Interactive

- **Primary CTA Background** (`{colors.primary}` — `#161412`): Button fills and active link states, always paired with canvas text.
- **Canvas Text on Primary** (`{colors.canvas}` — `#F9F8F6`): Label and call-to-action text rendered against dark backgrounds.

### Neutral Scale

- **Canvas** (`{colors.canvas}` — `#F9F8F6`): Default page background, card surfaces, and the neutral baseline for all layouts.
- **Body Text** (`{colors.body}` — `#2D2D2D`): Primary body copy and paragraph text ensuring strong contrast on light surfaces.
- **Muted Text** (`{colors.muted}` — `#6B6B6B`): Secondary text, captions, and de-emphasized information.
- **Faint Text** (`{colors.faint}` — `#FFFFFF`): Placeholder and tertiary text on dark backgrounds; pure white.
- **Neutral Dark** (`{colors.neutral-1}` — `#262626`): Intermediate neutral for subtle surface separation and discrete UI elements.

### Surface & Borders

- **Hairline** (`{colors.hairline}` — `#000000`): 1px borders and dividers rendered as pure black with opacity modulation for subtlety.

## 3. Typography Rules

### Font Family

**Primary (Display & Headings):** Newsreader, serif
Fallback: Georgia, Garamond, serif

**Secondary (Body & UI):** Inter, sans-serif
Fallback: -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, sans-serif

**Monospace:** ui-monospace
Fallback: Menlo, Monaco, Courier New, monospace

### Hierarchy

| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|---|---|---|---|---|---|---|
| Display XL | Newsreader | 72px | 400 | 1.0 | -1.44px | Hero headlines; maximum impact |
| Display LG | Newsreader | 64px | 400 | 1.0 | -1.28px | Section headlines; tight leading |
| Display MD | Newsreader | 48px | 400 | 1.0 | -0.96px | Large section intro; editorial scale |
| Display MD Strong | Newsreader | 48px | 500 | 1.0 | -0.96px | Emphasized display; stronger weight |
| Heading LG | Newsreader | 36px | 400 | 1.11 | -0.72px | Feature section headers |
| Heading LG Strong | Newsreader | 36px | 500 | 1.11 | 0px | Emphasized heading; no tracking |
| Heading MD | Newsreader | 24px | 400 | 1.33 | -0.48px | Subsection headers; moderate emphasis |
| Heading SM | Inter | 18px | 700 | 1.56 | -0.36px | Small headings; sans-serif weight |
| Heading XS | Inter | 17px | 700 | 1.5 | -0.34px | Minor headings; tight tracking |
| Body XL | Inter | 20px | 300 | 1.4 | 0px | Large paragraph text; light weight |
| Body LG | Inter | 18px | 400 | 1.56 | 0px | Feature body; standard weight |
| Body MD | Inter | 16px | 300 | 1.63 | 0px | Primary body copy; light weight |
| Body SM | Inter | 14px | 400 | 1.63 | 0px | Secondary body; baseline body size |
| Body SM Tight | Inter | 14px | 400 | 1.43 | 0px | Link text; compact leading |
| Body XS | Inter | 13px | 500 | 1.63 | 0px | Annotation; medium weight |
| Button MD | Inter | 16px | 400 | 1.5 | 0px | Standard button text |
| Button MD Strong | Inter | 16px | 500 | 1.5 | 0px | Emphasized button; bolder action |
| Button SM | Inter | 13px | 500 | 1.5 | 0px | Compact button; semi-bold |
| Navigation | Inter | 14px | 500 | 1.43 | 0px | Nav links and primary menus |
| Label | Inter | 9px | 700 | 1.5 | 0.72px | Form labels; all caps; high tracking |
| Caption MD | Inter | 12px | 500 | 1.33 | 0px | Medium caption; semi-bold |
| Caption SM | Inter | 11px | 400 | 1.5 | 0px | Small caption; standard weight |
| Caption XS | Inter | 10px | 400 | 1.5 | 0px | Minimal caption; auxiliary text |
| Code | ui-monospace | 11px | 400 | 1.5 | 1.32px | Inline code; all caps; wide tracking |

### Principles

- **Display hierarchy uses tight leading (1.0) and negative letter-spacing** to create visual compression and editorial authority. This is a defining trait of the system.
- **Body text uses lighter weights (300–400)** to maintain approachability and reduce visual mass compared to headings.
- **Inter sans-serif provides secondary hierarchy and UI copy**, establishing clear functional distinction from Newsreader's editorial presence.
- **All-caps labels and code blocks** use elevated letter-spacing (`0.72px`, `1.32px`) to signal functional precision.
- **Line-height ratios increase as type size decreases**, ensuring comfortable reading at body and caption scales.

## 4. Component Stylings

### Buttons

#### Primary Button (Large)
- **Background:** `{colors.primary}` (`#161412`)
- **Text Color:** `{colors.canvas}` (`#F9F8F6`)
- **Padding:** 16px 32px
- **Height:** 62px
- **Font Size:** 18px (custom size; use `{typography.body-lg}` equivalent)
- **Font Weight:** 500 (Inter Sans)
- **Line Height:** 28px (1.56)
- **Border:** 1px solid `#262626`
- **Border Radius:** `{rounded.md}` (16px)
- **Box Shadow:** `rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgb(22, 20, 18) 0px 0px 0px 2px, rgba(0, 0, 0, 0) 0px 0px 0px 0px`
- **Width:** 262px (fitted)
- **Usage:** Primary call-to-action; hero and section CTAs

#### Primary Button (Small)
- **Background:** `{colors.primary}` (`#161412`)
- **Text Color:** `{colors.canvas}` (`#F9F8F6`)
- **Padding:** 12px 24px
- **Height:** 50px
- **Font Size:** 16px (`{typography.button-md-strong}`)
- **Font Weight:** 500
- **Line Height:** 24px (1.5)
- **Border:** 1px solid `rgba(0, 0, 0, 0.05)`
- **Border Radius:** `{rounded.sm}` (8px)
- **Box Shadow:** `rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px`
- **Usage:** Secondary actions; navigation and utility buttons

#### Filled Pill Button
- **Background:** `#FFFFFF` (white)
- **Text Color:** `rgba(22, 20, 18, 0.7)` (muted ink)
- **Padding:** 6px 14px
- **Height:** 33.5px
- **Font Size:** 13px (`{typography.button-sm}`)
- **Font Weight:** 500
- **Line Height:** 19.5px
- **Border:** 1px solid `rgba(0, 0, 0, 0.1)`
- **Border Radius:** `{rounded.full}` (9999px)
- **Box Shadow:** `rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0.05) 0px 1px 2px 0px`
- **Usage:** Soft actions; tags, filters, status indicators

### Cards & Containers

#### Card Surface
- **Background:** `{colors.canvas}` (`#F9F8F6`)
- **Border:** None or subtle hairline (`{colors.hairline}` at `0.05` opacity)
- **Border Radius:** `{rounded.md}` (16px) or `{rounded.sm}` (8px) per role
- **Padding:** `{spacing.xl}` (24px) or `{spacing.lg}` (20px)
- **Box Shadow:** Layered micro (see Elevation section)
- **Hover State:** Background transitions to `rgba(255, 255, 255, 0.4)` (lifted appearance)
- **Usage:** Feature blocks, results containers, product showcase panels

### Inputs & Forms

#### Text Input / Form Field
- **Background:** White or `{colors.canvas}` (`#F9F8F6`)
- **Text Color:** `{colors.body}` (`#2D2D2D`)
- **Placeholder Color:** `{colors.muted}` (`#6B6B6B`)
- **Border:** 1px solid `rgba(0, 0, 0, 0.1)` (light hairline)
- **Border Radius:** `{rounded.sm}` (8px)
- **Padding:** `{spacing.md}` (16px) horizontal, `{spacing.sm}` (12px) vertical
- **Font Size:** 14px (`{typography.body-sm}`)
- **Focus State:** Border color transitions to `{colors.primary}` (`#161412`) or accent
- **Usage:** Search bars, email inputs, text fields

#### Checkbox / Radio
- **Size:** 16px × 16px
- **Border Radius:** `{rounded.xs}` (4px) for checkbox; `{rounded.full}` for radio
- **Border:** 1px solid `rgba(0, 0, 0, 0.2)`
- **Checked State:** Background `{colors.primary}` (`#161412`), border matches
- **Usage:** Form toggles, multi-select options

### Navigation

#### Header Navigation (Default)
- **Background:** Transparent or `{colors.canvas}` (`#F9F8F6`)
- **Text Color:** `{colors.primary}` (`#161412`)
- **Font Size:** 14px (`{typography.nav}`)
- **Font Weight:** 500
- **Padding:** 0px (links only; no vertical container padding in measured state)
- **Border:** None
- **Border Radius:** `{rounded.none}` (0px)
- **Line Height:** 24px (1.43)
- **Active/Hover State:** Text color transitions to `{colors.accent-1}` (`#84CC16`) or underline appears
- **Usage:** Top navigation, main menu links

#### Footer Navigation
- **Background:** `{colors.canvas}` (`#F9F8F6`)
- **Text Color:** `{colors.primary}` (`#161412`)
- **Font Size:** 14px (`{typography.body-sm}`)
- **Font Weight:** 400
- **Padding:** `{spacing.section}` (40px) top/bottom, `{spacing.xxxl}` (32px) left/right (per section layout)
- **Link Color:** `{colors.body}` (`#2D2D2D`); hover transitions to `{colors.primary}`
- **Usage:** Footer links, secondary navigation

#### Link (Inline / Standalone)
- **Text Color (Dark Background):** `{colors.canvas}` (`#F9F8F6`)
- **Text Color (Light Background):** `{colors.primary}` (`#161412`)
- **Background (CTA Link):** `{colors.primary}` (`#161412`)
- **Padding (CTA Link):** 24px (standalone button-like link)
- **Font Size (Standard Link):** 14px (`{typography.body-sm-tight}`)
- **Font Weight:** 400 (standard) or 500 (medium link)
- **Underline:** Implicit on hover; no baseline underline in rest state
- **Border Radius (CTA Link):** `{rounded.sm}` (8px)
- **Usage:** Hyperlinks, downloadable resources, auxiliary CTAs

## 5. Layout Principles

### Spacing System

**Base Unit:** 4px (`{spacing.xxs}`)

**Scale:**
- `{spacing.xxs}` = 4px — Micro gaps, icon spacing
- `{spacing.xs}` = 8px — Tight component spacing
- `{spacing.sm}` = 12px — Form field padding, small component spacing
- `{spacing.md}` = 16px — Standard component padding, base body margin
- `{spacing.lg}` = 20px — Moderate section spacing, card padding
- `{spacing.xl}` = 24px — Generous component spacing, container padding
- `{spacing.xxl}` = 28px — Larger section breaks
- `{spacing.xxxl}` = 32px — Major section padding, container inset
- `{spacing.section}` = 40px — Section vertical spacing, padding between logical blocks
- `{spacing.band}` = 44px — Hero band and full-width section padding

**Usage Context:**
- **Micro (xxs, xs):** Icon margins, nested list indentation, tight component clusters
- **Small (sm, md):** Form field padding, button internal spacing, list item margins
- **Standard (lg, xl):** Card padding, section padding, container inset, component gutter
- **Large (xxl, xxxl, section):** Hero padding, between-section vertical rhythm, full-bleed layout margins

### Grid & Container

- **Max Width (Large Screens):** 1238px — Measured on 1280px+ viewports
- **Column Structure:** 3 columns on desktop (1024px+); 4 columns on tablet (768px); responsive narrowing on mobile (375px)
- **Section Padding Horizontal:** `{spacing.band}` (44px) on desktop; `{spacing.section}` (40px) on tablet; `{spacing.xl}` (24px) on mobile
- **Content Column (375px):** 325px available after gutters
- **Content Column (768px):** 670px available after gutters
- **Content Column (1024px+):** 926px–1238px depending on viewport

### Whitespace Philosophy

Leedlime prioritizes generous breathing room and asymmetric composition. Layouts use substantial negative space to guide eye flow and reduce cognitive load. Sections are separated by `{spacing.section}` (40px) minimum vertical padding, often increasing to `{spacing.band}` (44px) or more around hero and feature blocks. Horizontal margins expand at wider breakpoints to prevent content from compressing. Cards and components maintain internal padding of `{spacing.xl}` (24px) to ensure content feels spacious, not crowded.

### Border Radius Scale

- `{rounded.none}` = 0px — Sharp edges; buttons, images, full-bleed sections
- `{rounded.xs}` = 4px — Minimal rounding; subtle form elements, small UI chips
- `{rounded.sm}` = 8px — Moderate rounding; form inputs, secondary buttons, cards
- `{rounded.md}` = 16px — Generous rounding; primary card surfaces, feature blocks
- `{rounded.full}` = 9999px — Pill-shaped; primary CTAs, toggle buttons, badges

**Component-Specific Radius:**
- Primary buttons: `{rounded.md}` (16px)
- Secondary buttons: `{rounded.sm}` (8px)
- Filled pill buttons: `{rounded.full}` (9999px)
- Card surfaces: `{rounded.md}` (16px)
- Form inputs: `{rounded.sm}` (8px)
- Images: `{rounded.none}` (0px; sharp corners)

### Border Widths

- **Thin:** 1px — Used for hairline borders, input fields, button strokes, and subtle dividers throughout the system.

## 6. Depth & Elevation

| Level | Treatment | Use |
|---|---|---|
| Flat | No shadow; `box-shadow: none` | Backgrounds, containers, large text areas |
| Micro (sm) | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | Small buttons, subtle lift; minimal elevation |
| Small (md) | `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px` | Primary buttons, form fields, standard cards |
| Medium (lg) | `rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px` | Feature cards, modal backgrounds, lifted sections |
| Large (xl) | `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px` | Modals, overlays, maximum elevation emphasis |

**Shadow Philosophy:**
Leedlime employs a layered-micro elevation strategy where depth emerges from stacked near-transparent shadows rather than bold, dark drops. This creates a barely-there lift that guides hierarchy without overwhelming the interface. Primary buttons and interactive cards use the small (md) shadow to signal affordance. Feature blocks and modals escalate to medium (lg) and large (xl) shadows only when critical separation is needed. The system avoids aggressive contrast; shadows remain soft and diffuse, consistent with the refined, editorial aesthetic.

### Opacity Levels

- **40%** (`0.40`) — Disabled states, secondary overlays
- **60%** (`0.60`) — Hover state backgrounds on dark surfaces
- **78%** (`0.78`) — Muted text on light backgrounds
- **80%** (`0.80`) — Hover state elevation, slight transparency on interactive elements
- **90%** (`0.90`) — Near-opaque; subtle hover or active states
- **100%** (`1.00`) — Fully opaque; primary text, images, solid surfaces

### Z-index / Layering

- **Base (0):** Default page content, cards, standard components
- **Dropdown (10):** Expanded menus, small floating UI
- **Elevated Dropdown (20):** Secondary dropdowns, tooltips
- **Modal/Overlay (50):** Modal dialogs, full-screen overlays, maximum foreground emphasis

## 7. Do's and Don'ts

### Do

- **Use negative letter-spacing on display type** (as measured: -1.44px to -0.48px). This is the typographic signature of the system and ensures headlines feel compressed and editorial.
- **Apply `{rounded.full}` exclusively to primary CTAs and pill-shaped toggles.** Secondary buttons and cards use `{rounded.sm}` or `{rounded.md}`.
- **Maintain generous section padding** (`{spacing.section}` to `{spacing.band}`) between logical blocks. This breathing room is central to the visual calm.
- **Layer micro-shadows (`md` and `lg` levels)** for elevation rather than using hard borders or color shifts. Shadows create depth without visual conflict.
- **Deploy the lime accent (`{colors.accent-1}` — `#84CC16`) sparingly** for decorative accents and hover states; it is not a primary semantic color.
- **Use `{colors.body}` (`#2D2D2D`) for all body copy** at 16px or smaller to ensure readability on light backgrounds.
- **Render form labels in all-caps with elevated tracking** (`{typography.label}`: 9px, 0.72px spacing). This signals structural clarity.
- **Reserve `{rounded.none}` for images and full-bleed sections.** Sharp edges here contrast with softer button and card rounding, creating visual rhythm.

### Don't

- **Do not invent semantic color roles.** The system has no error/success/warning palette; avoid introducing red/green/amber unless explicitly extractable from measured interactions.
- **Do not round button corners to 8px if they are measured as 16px or 9999px.** Radius consistency per component role is critical to visual coherence.
- **Do not use sans-serif for display headlines.** Newsreader serif is the primary editorial voice; reserve Inter sans-serif for body, UI, and navigation only.
- **Do not apply harsh shadows (xl level) to small components.** The system favors subtlety; use `md` and `lg` shadows; reserve `xl` for modals and critical overlays.
- **Do not center-align body text in cards or sections.** Layouts favor left alignment except for hero headlines and display type, which may be centered for impact.
- **Do not use opacity above 90% for interactive hover states.** Keep hovers subtle; full opacity is reserved for rest states and solid backgrounds.
- **Do not mix pill-shaped (`{rounded.full}`) and sharp (`{rounded.none}`) radius on buttons in the same context.** If primary CTAs are pills, secondary buttons must be rounded (`{rounded.sm}` or `{rounded.md}`), not sharp.
- **Do not omit the 1px hairline border from form inputs and secondary buttons.** Borders add structural clarity and signal interactivity.

## 8. Responsive Behavior

### Breakpoints

| Breakpoint | Viewport Width | Content Width | Grid Columns | Nav Links Visible | Key Changes |
|---|---|---|---|---|---|
| Mobile | 375px | 325px | 4 | 0 (toggle menu) | Single column; maximum padding reduction; hero text scales to 48px |
| Tablet | 768px | 670px | 4 | 4 visible | Two-column grid available; nav links appear; section padding increases to 48px |
| Desktop | 1024px | 926px | 3 | 4 visible | Three-column grid; full nav visible; largest heading reaches 72px; max width enforced |
| Large Desktop | 1280px–1440px | 1238px (capped) | 3 | 4 visible | Max-width container locks at 1238px; content centered; no further growth |

**Breakpoint Strategy:**
- **Mobile (375px):** Menu toggle appears; nav links hidden; display type scales from 72px down to 48px; padding compresses to `{spacing.xl}` (24px) horizontal.
- **Tablet (768px):** Full navigation emerges; heading size increases to 60px; section padding expands to 48px; grid becomes 4 columns.
- **Desktop (1024px+):** Display type reaches 72px maximum; grid becomes 3 columns; max-width container enforced; full feature reveal.

### Touch Targets

- **Minimum Interactive Height:** 50px (measured on primary-sm button)
- **Minimum Interactive Width:** 50px per button; 62px for primary CTAs
- **Link/Text Hit Area:** At least `{spacing.md}` (16px) padding around all clickable text and icons
- **Button Padding:** `{spacing.md}` (16px) horizontal minimum; `{spacing.sm}` (12px) vertical minimum
- **Form Field Height:** 50px (small) to 62px (large) to ensure comfortable mobile interaction

### Collapsing Strategy

- **Navigation:** Full link array collapses to hamburger toggle menu below 768px viewport. Links reappear at tablet breakpoint.
- **Multi-Column Layouts:** 3-column grids collapse to 4 columns on tablet (768px), then to single-column stack on mobile (375px).
- **Hero Text:** Display XL (72px) scales down to Display MD (48px) on mobile; line-height remains tight (1.0).
- **Section Padding:** Horizontal padding contracts from `{spacing.band}` (44px) on desktop to `{spacing.section}` (40px) on tablet, then to `{spacing.xl}` (24px) on mobile. Vertical padding maintains proportional breathing room.
- **Cards & Containers:** Full-width containers on mobile; multi-column grids appear only at tablet (768px) and above.
- **Button Widths:** Large primary buttons (262px) adjust to fit container width on mobile; small buttons (194px) may stack vertically in forms.

## 9. Agent Prompt Guide

### Quick Color Reference

- **Primary CTA / Brand Ink:** Brand Ink (`{colors.primary}` — `#161412`)
- **CTA Text on Dark:** Canvas (`{colors.canvas}` — `#F9F8F6`)
- **Body Text:** Body (`{colors.body}` — `#2D2D2D`)
- **Secondary Text:** Muted (`{colors.muted}` — `#6B6B6B`)
- **Page Background:** Canvas (`{colors.canvas}` — `#F9F8F6`)
- **Accent (Decorative):** Lime Green (`{colors.accent-1}` — `#84CC16`)
- **Borders & Dividers:** Hairline (`{colors.hairline}` — `#000000`)

### Iteration Guide

1. **Display headlines always use Newsreader serif with tight leading (1.0) and negative letter-spacing.** Sizes range from 48px to 72px depending on hierarchy. Never use sans-serif for headlines.

2. **Primary buttons are pill-shaped (`{rounded.full}`) with dark background (`{colors.primary}`), canvas text, and layered micro-shadow (`md` level).** Secondary buttons use `{rounded.sm}` (8px) with smaller shadow. All buttons carry 1px hairline borders.

3. **Body copy is set in Inter sans-serif at 14–16px (`{typography.body-sm}` or `{typography.body-md}`) with light weight (300–400) and 1.4–1.63 line-height.** Color is `{colors.body}` (`#2D2D2D`) on light backgrounds, `{colors.canvas}` on dark.

4. **Section spacing is governed by the spacing scale: use `{spacing.section}` (40px) as baseline vertical separation, expanding to `{spacing.band}` (44px) for hero and feature blocks.** Horizontal padding mirrors this rhythm, compressing on mobile to `{spacing.xl}` (24px).

5. **Cards use `{rounded.md}` (16px) corner radius with canvas background, `{spacing.xl}` (24px) internal padding, and `md` or `lg` layered shadow.** Borders are optional hairline at low opacity. Hover state lifts with `rgba(255, 255, 255, 0.4)` background transparency.

6. **Form inputs are `{rounded.sm}` (8px) with light hairline border (`rgba(0, 0, 0, 0.1)`), `{spacing.md}` padding, and 14px body text.** Labels are all-caps, 9px, weight 700, with 0.72px letter-spacing.

7. **Navigation is 14px medium weight, no underline at rest, with hover transitions (color or underline depending on context).** Nav links appear on tablet (768px+); mobile uses hamburger toggle.

8. **Opacity and shadow work together to create elevation:** use `md` shadow (10px blur) for standard interactive elements, `lg` shadow (20px blur) for feature cards, and `xl` shadow (25px blur) only for modals. Opacity levels (60–90%) apply to overlays and disabled states.

9. **Breakpoints are 375px (mobile), 768px (tablet), 1024px (desktop), 1280px+ (large desktop).** Adjust heading sizes, padding, and column counts at each boundary. Max-width caps at 1238px.

10. **Responsive images and backgrounds use `{rounded.none}` (0px) — sharp corners — while UI components round progressively from `xs` to `full` depending on functional role.**

## 10. Known Gaps

- **Interaction states (focus, active, disabled):** The extraction captured hover states only. Focus rings, disabled button styling, and active link states were not measured; implement these following WCAG AA standards (minimum 3px focus outline, typically `2px solid {colors.primary}` with offset).

- **Semantic color palette:** No error, success, warning, or info colors were detected in the site's markup or stylesheets. The system does not expose a status-color ramp; if such affordances are needed, they must be designed and added to this system.

- **Dark mode or theme variants:** Only a single light theme was measured. The extraction tool did not detect or measure a dark-mode theme. If dark mode is in use, it was not captured.

- **Animation and motion:** Transition timings, keyframe animations, and gesture-driven interactions were not extracted. Measured `transform` and `translate` properties indicate motion capability, but duration and easing were not recorded.

- **Interaction states for form fields:** Placeholder, invalid, and success states for inputs were not explicitly measured. Implement these using standard color and border conventions (e.g., error: `#DC2626`, success: `#16A34A`).

- **Component state variants:** Only button primary, secondary, and filled states were measured. Other states (loading, loading-button spinners, skeleton screens, empty states) were not captured and should be designed to extend the measured palette.

- **Accessibility token details:** No aria-labels, focus-visible styles, or sr-only text patterns were extracted. Ensure all interactive elements have proper ARIA attributes and keyboard navigation support.

- **Third-party library overrides:** Navigation and link components show some cross-origin CSS, suggesting use of external libraries. Precise style overrides for those libraries may not be fully reflected in this extraction.

- **Surfaces behind authentication:** The home page alone was analyzed. Logged-in dashboard, account settings, or admin interfaces were not visited and their styling is unknown.

- **Two colors have no assigned role:** `{colors.accent}` (terracotta, `#DA7756`) and `{colors.accent-1}` (lime, `#84CC16`) were observed but have no primary semantic function beyond decoration. Use them sparingly and document their purpose when deployed.