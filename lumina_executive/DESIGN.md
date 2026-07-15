---
name: Lumina Executive
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#414655'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#727787'
  outline-variant: '#c1c6d8'
  surface-tint: '#0058c9'
  primary: '#0056c4'
  on-primary: '#ffffff'
  primary-container: '#006df5'
  on-primary-container: '#fefcff'
  inverse-primary: '#afc6ff'
  secondary: '#006493'
  on-secondary: '#ffffff'
  secondary-container: '#40b7ff'
  on-secondary-container: '#004668'
  tertiary: '#a13b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#ca4c00'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d9e2ff'
  primary-fixed-dim: '#afc6ff'
  on-primary-fixed: '#001944'
  on-primary-fixed-variant: '#00429a'
  secondary-fixed: '#cae6ff'
  secondary-fixed-dim: '#8dcdff'
  on-secondary-fixed: '#001e30'
  on-secondary-fixed-variant: '#004b70'
  tertiary-fixed: '#ffdbcd'
  tertiary-fixed-dim: '#ffb598'
  on-tertiary-fixed: '#360f00'
  on-tertiary-fixed-variant: '#7e2c00'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
  deep-navy: '#001A33'
  surface-white: '#FFFFFF'
  border-subtle: '#E5E5E5'
typography:
  headline-xl:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Nunito Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Nunito Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
  button:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  section-gap-desktop: 120px
  section-gap-mobile: 64px
  gutter: 24px
  margin-safe: 32px
---

## Brand & Style

The design system is engineered for a luxury workspace brand that balances professional authority with modern fluidity. The target audience includes high-level executives, innovative startups, and real estate investors who value precision, cleanliness, and premium hospitality.

The visual style is **Corporate Modern with a Minimalist edge**. It leverages heavy whitespace and a restricted, high-fidelity color palette to create an atmosphere of calm and focus. Surfaces are crisp and structural, moving away from decorative clutter toward a "functional luxury" aesthetic. The interface should feel expensive through its restraint, utilizing high-quality typography and deliberate alignment rather than excessive ornamentation.

## Colors

This design system uses a sophisticated "Blue-on-White" palette that emphasizes clarity and professional trust. 

- **Primary & Secondary:** A duo of vibrant blues (#0072FF and #009EE5) are used for high-impact actions and brand signifiers. These should be used sparingly against white backgrounds to maintain a premium feel.
- **Neutrals:** The system relies heavily on pure `#FFFFFF` for primary surfaces and `#F7F7F7` for secondary sections or background fills to create subtle depth without visual weight.
- **Accents:** Text should primarily utilize a "Deep Navy" instead of pure black to maintain a softer, more editorial look.

## Typography

The typography strategy focuses on geometric precision paired with high readability. 

**Sora** is utilized for headlines to provide a modern, tech-forward edge with its distinct geometric character. **Nunito Sans** serves as the primary body face, offering a warm and approachable feel that balances the technicality of the headlines. **Hanken Grotesk** is reserved for labels and functional UI elements where clarity and "architectural" alignment are paramount.

For large display text, use tight letter-spacing to create a "locked-in" editorial look. Ensure all body text maintains generous line-height to facilitate reading in information-dense layouts.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop environments to maintain a "contained" and curated feel, transitioning to a fluid model for mobile devices.

- **Desktop:** 12-column grid with a maximum container width of 1280px. Gutters are fixed at 24px to ensure breathing room between components.
- **Sectioning:** Large vertical gaps (120px) are used to separate major content blocks, reinforcing the minimalist "luxury" aesthetic where space is a design element itself.
- **Rhythm:** All spacing (padding, margins, internal gaps) must be multiples of the 8px base unit.

## Elevation & Depth

This design system utilizes **Tonal Layers and Low-Contrast Outlines** rather than heavy shadows to convey hierarchy. 

Depth is achieved through:
1.  **Background Shifts:** Moving from pure `#FFFFFF` (Base) to `#F7F7F7` (Secondary) to define distinct content zones.
2.  **Soft Outlines:** Elements like cards and input fields should use a 1px border in `border-subtle` (#E5E5E5).
3.  **High-Finesse Shadows:** When elevation is absolutely necessary (e.g., modals or floating navigation), use a "Zero-Gravity" shadow: a very large blur (32px+) with extremely low opacity (4-6%) and no offset, creating a soft glow rather than a directional drop shadow.

## Shapes

The shape language is **Soft (0.25rem)**. This choice maintains a professional, structured feel that aligns with architectural lines while subtly softening the user experience. 

- **Standard Elements:** Buttons, input fields, and small tags use a 4px corner radius.
- **Large Containers:** Cards or featured sections can scale up to `rounded-lg` (8px) to emphasize their role as distinct containers.
- **Exceptions:** No pill-shaped or fully rounded elements should be used, as they detract from the corporate-modern precision of the brand.

## Components

- **Buttons:** Primary buttons use a solid gradient or flat fill of the primary blue with white text. Secondary buttons should be "Ghost" style—transparent with a 1px border and primary-colored text.
- **Input Fields:** Use a minimal approach—white background, subtle grey border, and the `label-caps` typography style positioned strictly above the field.
- **Cards:** Cards should have no shadow by default. They are defined by a `border-subtle` and a white background. On hover, a card may exhibit the "Zero-Gravity" shadow mentioned in the Elevation section.
- **Chips/Tags:** Small, rectangular tags with a light `#F7F7F7` fill and `label-caps` typography. Use these for categorizing office types or amenities.
- **Lists:** Use generous vertical padding (16px) between list items and thin, full-bleed horizontal dividers to maintain an organized, ledger-like appearance.
- **Navigation:** A sticky, high-blur (glassmorphism) header with a white tint ensures the "luxury" feel remains present as the user scrolls.