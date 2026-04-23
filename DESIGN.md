---
name: Industrial Precision
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1c1b1d'
  surface-container: '#201f22'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e5e1e4'
  on-surface-variant: '#d1c6ab'
  inverse-surface: '#e5e1e4'
  inverse-on-surface: '#313032'
  outline: '#9a9078'
  outline-variant: '#4d4632'
  surface-tint: '#eec200'
  primary: '#ffecb9'
  on-primary: '#3c2f00'
  primary-container: '#facc15'
  on-primary-container: '#6c5700'
  inverse-primary: '#735c00'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#efecf0'
  on-tertiary: '#303033'
  tertiary-container: '#d2d0d4'
  on-tertiary-container: '#59595c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe083'
  primary-fixed-dim: '#eec200'
  on-primary-fixed: '#231b00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e4e1e5'
  tertiary-fixed-dim: '#c8c6c9'
  on-tertiary-fixed: '#1b1b1e'
  on-tertiary-fixed-variant: '#47464a'
  background: '#131315'
  on-background: '#e5e1e4'
  surface-variant: '#353437'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-bold:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 32px
  margin-mobile: 20px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
  section-gap: 96px
---

## Brand & Style

This design system embodies the intersection of heavy-duty utility and high-end professional service. It moves away from the "gritty" industrial aesthetic in favor of "Precision Industrial"—a style defined by surgical cleanliness, structural integrity, and the confidence of an expert operator. 

The visual language utilizes **Minimalism** with a **High-Contrast** edge. It leans on vast amounts of negative space to signify a premium, unhurried service where every detail is accounted for. The interface should feel like a high-performance dashboard: functional, authoritative, and sophisticated. It targets commercial contractors and high-value project managers who prioritize reliability and technical skill over low-cost alternatives.

## Colors

The palette is rooted in a **Dark Mode** default to evoke the strength of steel and the authority of nighttime industrial operations. 

- **Deep Black (#09090b):** Used as the primary canvas. It provides a "void" that allows technical information to stand out without distraction.
- **Industrial Yellow (#facc15):** Reserved strictly for primary actions, critical status indicators, and brand highlights. It represents the "utility" and should be used sparingly to maintain its impact.
- **Pure White (#ffffff):** Used for primary typography and high-level icons to ensure maximum readability against the dark base.
- **Secondary Zinc (#27272a):** A subtle mid-tone used for structural elements like borders, dividers, and surface elevations to prevent the UI from feeling flat.

## Typography

The typography utilizes **Plus Jakarta Sans** to bridge the gap between modern tech and industrial bold. By utilizing heavy weights (Bold and ExtraBold) for headings and tightened letter-spacing, the typeface takes on an architectural quality.

Hierarchy is established through extreme scale shifts. Large display headers should feel "heavy" and grounded, while labels and utility text use uppercase styling with increased tracking to mimic the stamped technical plates found on machinery. Body text is kept clean and spacious to ensure legibility during field operations.

## Layout & Spacing

This design system employs a **Fixed Grid** model for desktop to maintain a "blueprint" feel, centering content within a generous 1280px container. The spacing philosophy is "Generous and Intentional"—using large gaps between sections to prevent the interface from feeling cluttered or "cheap."

A strict 8px rhythmic scale governs all padding and margins. Vertical rhythm is prioritized, with significant white space (section-gap) used to separate different service tiers or technical specifications. Elements should feel "anchored" to the grid, emphasizing the skilled operator's precision.

## Elevation & Depth

To maintain a high-end industrial feel, the design system avoids heavy drop shadows, which can look "soft" and unrefined. Instead, it uses **Tonal Layers** and **Low-Contrast Outlines**.

Depth is created by stacking surfaces:
1.  **Level 0 (Base):** Deep Black (#09090b).
2.  **Level 1 (Cards/Panels):** A slight lift using a secondary dark grey or a 1px border (#27272a).
3.  **Level 2 (Modals/Popovers):** Subtle 1px borders in Pure White at 10% opacity.

When depth is absolutely necessary for interaction, a "Hard Shadow" (0% blur, 4px offset) in pure black can be used to give elements a physical, "machined" appearance against the background.

## Shapes

The shape language is **Soft (0.25rem)**. This mimics the "milled edge" of industrial components—not sharp enough to be dangerous, but not rounded enough to lose its structural rigidity.

Large components like cards and containers use `rounded-lg` (0.5rem) to provide a premium feel, while buttons and input fields use the base `rounded` (0.25rem) to maintain a technical, tool-like appearance. Icons should follow a geometric, "line-art" style with consistent stroke weights.

## Components

### Buttons
Primary buttons are the hallmark of the system: solid Industrial Yellow backgrounds with Deep Black text, using bold weights. Hover states should invert or slightly darken the yellow. Secondary buttons use a white 1px border with no fill.

### Input Fields
Inputs should feel like a digital logbook. They use a solid black background with a Zinc border that highlights to Industrial Yellow on focus. Labels sit strictly above the field in the `label-bold` uppercase style.

### Cards
Cards are used to house service details or truck specifications. They feature a 1px border (#27272a) with no background fill, or a slightly lighter black fill. Padding inside cards must be generous (32px+) to maintain the premium feel.

### Status Chips
Industrial status is conveyed through small, rectangular chips. "Available" uses a white border; "In Use" or "Maintenance" uses the yellow accent.

### Interactive Lists
Lists for equipment specs or service logs should use thin horizontal dividers and high-contrast typography, ensuring that technical data is the hero of the component.