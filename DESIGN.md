---
name: Verdant Enterprise
colors:
  surface: '#f7f9ff'
  surface-dim: '#d7dadf'
  surface-bright: '#f7f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f9'
  surface-container: '#ebeef3'
  surface-container-high: '#e5e8ee'
  surface-container-highest: '#e0e3e8'
  on-surface: '#181c20'
  on-surface-variant: '#414844'
  inverse-surface: '#2d3135'
  inverse-on-surface: '#eef1f6'
  outline: '#717973'
  outline-variant: '#c1c8c2'
  surface-tint: '#3f6653'
  primary: '#012d1d'
  on-primary: '#ffffff'
  primary-container: '#1b4332'
  on-primary-container: '#86af99'
  inverse-primary: '#a5d0b9'
  secondary: '#4c6452'
  on-secondary: '#ffffff'
  secondary-container: '#cce6d0'
  on-secondary-container: '#506856'
  tertiary: '#312400'
  on-tertiary: '#ffffff'
  tertiary-container: '#4c3900'
  on-tertiary-container: '#c1a35a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1ecd4'
  primary-fixed-dim: '#a5d0b9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#274e3d'
  secondary-fixed: '#cee9d3'
  secondary-fixed-dim: '#b3cdb7'
  on-secondary-fixed: '#092012'
  on-secondary-fixed-variant: '#354c3b'
  tertiary-fixed: '#ffdf96'
  tertiary-fixed-dim: '#e3c377'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#594401'
  background: '#f7f9ff'
  on-background: '#181c20'
  surface-variant: '#e0e3e8'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  section-gap: 80px
---

## Brand & Style

This design system is built for a premium B2B wholesale context, balancing the organic vitality of fresh produce with the structured reliability of a corporate distributor. The aesthetic combines **Minimalism** with **Modern Corporate** sensibilities, emphasizing clarity, high-end quality, and trust.

The visual narrative centers on "Freshness through Precision." It utilizes generous white space to evoke a clean, premium atmosphere, moving away from the cluttered layouts typical of wholesale platforms. The emotional response should be one of confidence, efficiency, and professional warmth. 

Key stylistic pillars:
- **High-Quality Imagery:** Large, crisp photography of fresh goods acts as a core UI element.
- **Organic Professionalism:** Using soft geometry to humanize industrial-scale logistics.
- **Uncluttered Hierarchy:** Prioritizing data density without sacrificing legibility.

## Colors

The palette is rooted in a "Forest to Table" philosophy.

- **Primary (Forest Green):** Used for primary actions, navigation headers, and authoritative UI elements. It represents the depth of experience and ecological connection.
- **Secondary (Mint):** Used for subtle backgrounds, highlight chips, and success states. It provides a "fresh" visual break from the deep primary tones.
- **Accent (Earthy Gold):** Reserved for "Premium" or "Executive" tiers, loyalty indicators, and high-value call-to-outs.
- **Neutral (Charcoal & Cream):** Charcoal provides professional weight for typography, while the soft Cream background reduces eye strain compared to pure white, maintaining a sophisticated "editorial" feel.

## Typography

The typography strategy pairs the assertive, geometric character of **Montserrat** for headings with the systematic clarity of **Inter** for body and data.

**Headings:** Utilize tight tracking (letter-spacing) to create a "locked-in," professional look. Bold weights are preferred for product categories and section titles to ensure clear information architecture.

**Body:** Employs generous line-height (150%+) to maintain a premium, airy feel even when displaying dense wholesale product descriptions or logistics data.

**Labels:** Small caps or slightly tracked-out weights are used for metadata, such as SKU numbers or "In Stock" statuses, to differentiate them clearly from narrative text.

## Layout & Spacing

The design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. 

- **The "Breathe" Rule:** A minimum section gap of 80px is used on desktop to ensure the "Premium" brand promise isn't compromised by information density.
- **Modular Scaling:** Spacing follows an 8px linear scale. Internal card padding should strictly use the `24px` (3x) unit to maintain a consistent internal rhythm.
- **Alignment:** Content is centered in a max-width container of 1280px for standard pages, while the dashboard views utilize a full-width "Canvas" layout with fixed side-navigation (280px).

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and **Tonal Layering**.

- **Surface 0 (Background):** Soft Cream (#F8F9FA).
- **Surface 1 (Cards/Content):** Pure White (#FFFFFF) with a very soft, diffused shadow (0px 4px 20px, 4% opacity Charcoal).
- **Surface 2 (Hover/Active):** An elevated state with a slightly more pronounced shadow (0px 8px 30px, 8% opacity Charcoal) and a subtle upward translation (-2px).

Avoid harsh borders. Instead, use thin 1px strokes in a slightly darker cream or very light mint (#E9EDEA) to define boundaries in high-density data tables.

## Shapes

The design system adopts a **Rounded** language to move away from the "industrial" sharpness of traditional B2B.

- **Standard Components:** Buttons, input fields, and small chips use a `0.5rem` (8px) radius.
- **Containers:** Content cards and feature blocks use a `1rem` (16px) radius to create a soft, inviting frame for product photography.
- **Selection Indicators:** Checkboxes maintain a slight `4px` rounding to match the system, while Radio buttons remain fully circular.

## Components

### Buttons
- **Primary:** Forest Green fill, White text. 8px corner radius. On hover, darken the green slightly and apply a subtle lift.
- **Secondary:** Mint fill, Forest Green text. Used for "Add to Quote" or secondary navigation.
- **Ghost:** Forest Green border and text. Used for "View Details" or less urgent actions.

### Cards
- Cards must feature a dedicated image area (top-aligned). 
- Use a 16px corner radius for the container.
- On hover, the card should lift -4px with a secondary shadow transition.

### Form Fields
- Labels should always be visible above the input (never use placeholder-only labels).
- Inputs use a 1px border (#E9EDEA) that transitions to Forest Green on focus.
- Include "B2B specific" patterns: Bulk quantity selectors and account-specific pricing toggles.

### Status Chips
- **In Stock:** Mint background, Deep Green text.
- **Low Stock:** Soft Amber background, Brown text.
- **Special Order:** Light Grey background, Charcoal text.

### Interactive Elements
- All transitions should be `200ms ease-out` to ensure the interface feels responsive and high-end.