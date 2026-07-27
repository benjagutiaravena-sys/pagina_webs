---
name: Directo Digital
colors:
  surface: '#f9f9fb'
  surface-dim: '#d9dadc'
  surface-bright: '#f9f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f5'
  surface-container: '#eeeef0'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e4'
  on-surface: '#1a1c1d'
  on-surface-variant: '#434656'
  inverse-surface: '#2f3132'
  inverse-on-surface: '#f0f0f2'
  outline: '#737688'
  outline-variant: '#c3c5d9'
  surface-tint: '#004dea'
  primary: '#0041c8'
  on-primary: '#ffffff'
  primary-container: '#0055ff'
  on-primary-container: '#e3e6ff'
  inverse-primary: '#b6c4ff'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#972500'
  on-tertiary: '#ffffff'
  tertiary-container: '#c13301'
  on-tertiary-container: '#ffe1d9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#001551'
  on-primary-fixed-variant: '#0039b3'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#ffdbd1'
  tertiary-fixed-dim: '#ffb5a0'
  on-tertiary-fixed: '#3b0900'
  on-tertiary-fixed-variant: '#872100'
  background: '#f9f9fb'
  on-background: '#1a1c1d'
  surface-variant: '#e2e2e4'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 80px
    fontWeight: '800'
    lineHeight: 90px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 54px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: 0em
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 32px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 24px
  stack-xl: 128px
  stack-lg: 80px
  stack-md: 48px
  stack-sm: 24px
---

## Brand & Style

The design system is engineered for a freelance developer portfolio targeting the Chilean market, where professionalism and directness are paramount. The personality is authoritative yet approachable, stripping away technical jargon to focus on business outcomes. 

The aesthetic is **Modern Minimalist with a focus on Bold Typography**. It avoids the generic corporate look by utilizing extreme scale in typography and generous whitespace, creating a sense of confidence and "Santiago-chic" sophistication. The UI is designed to feel high-end, reliable, and impeccably organized, reflecting the quality of the code behind the interface.

## Colors

The palette is built on high-contrast foundations to ensure maximum readability and impact. 

- **Primary (#0055FF):** An Electric Blue used exclusively for calls to action, active states, and critical highlights. It provides a modern, energetic pulse against the monochromatic base.
- **Secondary/Surface (#1A1A1A):** A Dark Charcoal used for footer sections, dark-mode cards, or high-impact text blocks. It provides weight and "seriedad" (seriousness) to the brand.
- **Background (#FFFFFF):** Pure white serves as the canvas, maximizing the effect of purposeful whitespace.
- **Neutral (#F5F5F7):** A subtle grey used for secondary backgrounds and subtle dividers to maintain depth without adding visual noise.

## Typography

This design system uses a pairing of **Montserrat** for headlines and **Inter** for body copy. 

Headlines use heavy weights and tight letter-spacing to create a "wall of text" impact that feels authoritative. Large display sizes (Headline XL) should be used for hero sections to immediately capture attention. Body text is set with generous line heights to ensure comfortable reading of case studies. All labels and overlines should use Inter in Semi-Bold with slight tracking for a technical, precise feel. All Chilean Spanish copy should be direct and results-oriented.

## Layout & Spacing

The layout follows a **Fluid Grid** model with strict vertical rhythm. 

- **Desktop:** A 12-column grid with a maximum width of 1280px. Use 32px gutters to give content room to breathe.
- **Mobile:** A 4-column grid with 24px side margins. 
- **Spacing Rhythm:** Use the "Stack" variables for vertical separation between sections. Hero sections should use `stack-xl`, while internal card elements use `stack-sm`.
- **White Space:** Do not fear empty columns. Use them to center content or create asymmetrical layouts that feel custom-designed rather than template-based.

## Elevation & Depth

This design system utilizes **Tonal Layers** combined with **Ambient Shadows** to create a sophisticated sense of hierarchy without excessive ornament.

- **Level 0 (Base):** Pure #FFFFFF background.
- **Level 1 (Cards):** Use #FFFFFF background with a 1px border of #E5E5E5 and a subtle, large-radius shadow: `0 10px 40px rgba(0,0,0,0.04)`.
- **Level 2 (Hover/Active):** When interacting with cards or buttons, the shadow deepens to `0 20px 50px rgba(0,0,0,0.08)` and the element lifts slightly (2px translation).
- **Overlays:** Modals or mobile menus should use a solid #FFFFFF background with a 40% backdrop blur on the layer below to maintain focus.

## Shapes

The shape language is defined by **Soft Roundedness**. 

Standard components (inputs, small buttons) use a `0.5rem` (8px) radius. Larger containers, cards, and primary "Call to Action" buttons use a `rounded-lg` (16px) radius to create a friendly, approachable contrast against the sharp, bold typography. This balance prevents the site from feeling too aggressive while maintaining its professional edge.

## Components

- **Primary Button:** Large (min-height 56px), #0055FF background, white Montserrat Bold text. Use 16px corner radius.
- **Secondary Button:** Transparent background, 2px stroke of #1A1A1A, charcoal text.
- **Cards (Proyectos):** White background, 16px radius, subtle ambient shadow. Images within cards should have a top-only radius of 16px to sit flush.
- **Input Fields:** 8px radius, #F5F5F7 background, no border. On focus, add a 2px #0055FF stroke.
- **Chips (Tech Stack):** Small, #F5F5F7 background, Inter Medium text, 4px radius. Keep these subtle so they don't distract from the main project description.
- **Lists:** Use custom icons (e.g., small electric blue squares) instead of standard bullets to maintain the geometric theme.
- **Navigation:** Minimalist top bar, 100% width, transparent background that turns solid #FFFFFF with a subtle bottom border on scroll.