---
name: Artisanal Botanical Atelier
colors:
  surface: '#fef9ec'
  surface-dim: '#dedacd'
  surface-bright: '#fef9ec'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f3e6'
  surface-container: '#f3eee1'
  surface-container-high: '#ede8db'
  surface-container-highest: '#e7e2d5'
  on-surface: '#1d1c14'
  on-surface-variant: '#424842'
  inverse-surface: '#323128'
  inverse-on-surface: '#f5f0e3'
  outline: '#737971'
  outline-variant: '#c2c8bf'
  surface-tint: '#48654c'
  primary: '#18331e'
  on-primary: '#ffffff'
  primary-container: '#2e4a33'
  on-primary-container: '#99b99b'
  inverse-primary: '#aecfb0'
  secondary: '#9b451e'
  on-secondary: '#ffffff'
  secondary-container: '#fe9164'
  on-secondary-container: '#752903'
  tertiary: '#283100'
  on-tertiary: '#ffffff'
  tertiary-container: '#3c4905'
  on-tertiary-container: '#a8b86a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#caebcb'
  primary-fixed-dim: '#aecfb0'
  on-primary-fixed: '#05210d'
  on-primary-fixed-variant: '#314d36'
  secondary-fixed: '#ffdbce'
  secondary-fixed-dim: '#ffb599'
  on-secondary-fixed: '#370e00'
  on-secondary-fixed-variant: '#7c2e08'
  tertiary-fixed: '#daeb97'
  tertiary-fixed-dim: '#bece7e'
  on-tertiary-fixed: '#171e00'
  on-tertiary-fixed-variant: '#3f4c08'
  background: '#fef9ec'
  on-background: '#1d1c14'
  surface-variant: '#e7e2d5'
typography:
  display:
    fontFamily: Vollkorn
    fontSize: 52px
    fontWeight: '700'
    lineHeight: 60px
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Vollkorn
    fontSize: 38px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Vollkorn
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Vollkorn
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: '0'
  headline-md:
    fontFamily: Vollkorn
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: '0'
  headline-sm:
    fontFamily: Vollkorn
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0.01em
  title-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1.25rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system crafts a sanctuary-like, tactile digital presence for a boutique artisanal plant atelier. It merges the warmth of Chilean flora, terracotta craftsmanship, and slow-living aesthetics with high-end editorial commerce. The emotional tone is grounded, lush, nurturing, and refined—evoking the sensory calm of stepping into an airy glasshouse filled with rare foliage, damp earth, and hand-thrown ceramic planters.

The visual direction pairs **Tactile / Organic Craft** with **Editorial Warmth**:
- Generous, breathable layouts anchored by rich botanical hues and raw earthenware accents.
- Soft, organic pill contours balanced by delicate framing lines reminiscent of traditional conservatory mullions.
- Ambient leafy shadows, micro-textures, and warm tonal layering that avoid sterile digital flatness in favor of material depth.

## Colors

The palette draws directly from living canopies and artisanal studio materials:

- **Primary (`#2E4A33` - Forest Green):** The brand anchor. Applied to dominant UI chrome, primary action buttons, key editorial headers, and structural headers.
- **Secondary (`#C8673E` - Terracotta):** Warm, ceramic energy. Reserved for secondary interactions, notifications, hover highlights, and warm textural accents.
- **Tertiary (`#A8B86A` - Olive):** Soft sunlight through leaves. Utilized for promotional tags, price pills, active status pills, and light visual emphasis.
- **Neutral Canvas (`#F5F0E3` - Cream):** A warm, unbleached linen surface replacing clinical white across all canvas backgrounds and layered card surfaces.
- **High-Contrast Text (`#1B3022` - Deep Evergreen):** The primary typographic ink, providing deep botanical legibility that is softer and richer than pure black.
- **Muted Linework (`rgba(46, 74, 51, 0.12)`): Subtle botanical borders that define boundaries without harsh division.

## Typography

The type system blends literary warmth with clinical functional clarity:

- **Display & Headlines (Vollkorn):** Rich, sturdy, and organically bracketed serifs that mirror botanical publications and antique seed catalog typography. Generous x-height and warm curves anchor editorial titles and emotional storytelling.
- **Interface & Text (Inter):** Highly legible, neutral grotesque sans-serif handling product metadata, specs, care guides, and purchasing flows.
- **Labels & Micro-copy:** Uppercase settings with expanded tracking (`0.04em`–`0.06em`) in Inter provide structure to prices, botanical classifications, and navigation markers.

## Layout & Spacing

A mobile-first fluid layout that effortlessly expands into an expansive multi-column desktop layout:

- **Mobile (< 768px):** Single-column stack with dynamic safe area handling (`env(safe-area-inset-bottom)`). Uses an outer canvas margin of `1.25rem` and internal component gutters of `1rem`. Fixed bottom navigation anchors standard thumb flow.
- **Tablet (768px – 1024px):** 6-column fluid grid, `1.5rem` gutter, transforming card listings into rhythmic 2- and 3-up showcases.
- **Desktop (> 1024px):** 12-column layout capped at `1280px` max-width. Outer margins expand to `3rem` with `1.5rem` gutters, allowing side-by-side plant imagery, care specifications, and editorial sidebars.

## Elevation & Depth

Visual hierarchy uses warm, sunlight-filtered ambient occlusion rather than sterile synthetic drop shadows:

- **Surface Tiers:**
  - Base canvas: `#F5F0E3` (Cream).
  - Elevated surfaces & cards: `#FFFFFF` or translucent cream tint `rgba(255, 255, 255, 0.72)` over `#F5F0E3`.
  - Drawers & overlays: `#FAF7F0` backed by a blurred organic scrim (`rgba(27, 48, 34, 0.45)` backdrop filter blur of `8px`).
- **Leaf Shadow & Ambient Occlusion:** Cards and floating actions project deeply diffused, green-tinted cast shadows:
  - Low elevation (cards): `0 4px 20px -2px rgba(46, 74, 51, 0.08)`.
  - High elevation (drawers, modals, floating CTA): `0 12px 36px -4px rgba(27, 48, 34, 0.16)`.
- **Botanical Borders:** Soft structural lines use `1px solid rgba(46, 74, 51, 0.1)` to frame products and card containers without visual weight.

## Shapes

The interface embraces organic curvature inspired by plant leaves, pebbles, and hand-built pottery:

- **Cards and Panels:** Standardized to `16px` (`1rem`, `rounded-lg`) corner radii to achieve soft, approachable pill-like containers without losing content density.
- **Badges, Tags & Buttons:** Full pill geometry (`rounded-full` / `9999px`) for quick tactile scanning and comfortable mobile tap targets.
- **Drawers & Modals:** Generously curved top edges at `24px` (`1.5rem`, `rounded-xl`) for natural bottom-sheet anchoring.

## Components

### Buttons
- **Primary:** Solid Forest Green (`#2E4A33`), white text, full-pill shape (`9999px`), minimum height `48px`. Hover: shifts to `#1B3022` with a subtle organic scale transform (`scale(1.02)`).
- **Secondary (Terracotta):** Solid Terracotta (`#C8673E`), white text, full-pill. Used for immediate purchasing or adoption calls to action.
- **Outlined / Ghost:** Transparent surface with `1.5px` border in `#2E4A33`, Deep Evergreen text.

### Interactive Flip Cards
- Built on a fixed `16px` border radius container with perspective wrapping.
- **Front Face:** High-resolution botanical photography, pill-shaped Olive (`#A8B86A`) price tag anchored in top-right, variety title in Vollkorn, and discrete tap cue.
- **Back Face:** Textured cream background (`#F5F0E3`) detailing light requirements, watering cadence, pet toxicity indicators, and quick-add button. Smooth 3D flip animation (`500ms cubic-bezier(0.4, 0, 0.2, 1)`).

### Price Badges & Chips
- **Olive Price Badges:** Pill-shaped capsules filled with `#A8B86A`, text set in `#1B3022` bold `13px`, creating instant eye-tracking contrast against dark foliage.
- **Filter Chips:** Unselected chips feature a semi-transparent cream background with `#2E4A33` border. Selected chips fill with `#2E4A33` with white text.

### Form Inputs & Checkboxes
- **Input Fields:** Generous `48px` height, `12px` roundedness, `#FAF7F0` surface with `1px` border in `rgba(46, 74, 51, 0.2)`. Focus state transitions to `1.5px` Forest Green ring with zero offset.
- **Checkboxes & Radios:** Rounded pill styling for radio elements; checkboxes use custom leaf-check glyphs rendered in Forest Green when active.

### Floating Pulsed WhatsApp CTA
- Positioned dynamically in bottom-right corner, `20px` clear of the fixed bottom navigation on mobile.
- Circular `56px` container filled with vibrant brand-friendly botanical green or WhatsApp emerald, housed in a double-ring ripple pulse animation utilizing `rgba(168, 184, 106, 0.45)`.

### Mobile Navigation & Drawer
- **Fixed Bottom Navigation Bar:** Frosted glass background (`rgba(245, 240, 227, 0.92)` with `12px` blur), border-top in `rgba(46, 74, 51, 0.08)`, housing 4 primary destinations with active state highlighted in Terracotta (`#C8673E`).
- **Mobile Drawer:** Sweeps from the bottom or left with `24px` rounded corners, carrying lush plant category exploration and care guides with warm botanical iconography.