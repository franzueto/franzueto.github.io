---
name: Nocturne Portfolio
colors:
  surface: '#08132a'
  surface-dim: '#08132a'
  surface-bright: '#2f3952'
  surface-container-lowest: '#030d25'
  surface-container-low: '#101b33'
  surface-container: '#151f37'
  surface-container-high: '#1f2942'
  surface-container-highest: '#2a344d'
  on-surface: '#d9e2ff'
  on-surface-variant: '#c5c6cd'
  inverse-surface: '#d9e2ff'
  inverse-on-surface: '#263049'
  outline: '#8f9097'
  outline-variant: '#44474d'
  surface-tint: '#b9c7e4'
  primary: '#b9c7e4'
  on-primary: '#233148'
  primary-container: '#0a192f'
  on-primary-container: '#74829d'
  inverse-primary: '#515f78'
  secondary: '#41e4c0'
  on-secondary: '#00382d'
  secondary-container: '#00c7a5'
  on-secondary-container: '#004d3f'
  tertiary: '#b6c6ed'
  on-tertiary: '#20304f'
  tertiary-container: '#061836'
  on-tertiary-container: '#7282a5'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b9c7e4'
  on-primary-fixed: '#0d1c32'
  on-primary-fixed-variant: '#39475f'
  secondary-fixed: '#5ffbd6'
  secondary-fixed-dim: '#38debb'
  on-secondary-fixed: '#002019'
  on-secondary-fixed-variant: '#005142'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#b6c6ed'
  on-tertiary-fixed: '#091b39'
  on-tertiary-fixed-variant: '#374767'
  background: '#08132a'
  on-background: '#d9e2ff'
  surface-variant: '#2a344d'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: '0'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  xs: 0.5rem
  sm: 1rem
  md: 2rem
  lg: 4rem
  xl: 8rem
  gutter: 24px
  margin: max(5vw, 24px)
  max_width: 1100px
---

## Brand & Style

This design system is built for a professional portfolio aesthetic that emphasizes intellectual depth and meticulous attention to detail. The brand personality is authoritative yet understated, positioning the individual as an expert who values clarity over flashiness. 

The design style is a hybrid of **Minimalism** and **Modern Corporate**, utilizing a restricted color palette and expansive whitespace to create a focused, "gallery-like" experience. By stripping away unnecessary ornamentation, the system ensures that the work itself—the projects and the thought processes—remains the singular focus. The emotional response is intended to be one of calm confidence and high-trust professionalism.

## Colors

The palette is centered on a deep navy foundation to establish a sophisticated, high-contrast environment. 

- **Primary (#0A192F):** Used for the global background to provide a sense of depth and focus.
- **Secondary (#64FFDA):** A vibrant aquamarine used sparingly for high-visibility accents, active states, and essential call-to-actions.
- **Tertiary (#112240):** A lighter navy for component surfaces, creating subtle layering without breaking the dark aesthetic.
- **Neutral (#CCD6F6):** The primary text color, chosen for its high readability and softer contrast compared to pure white, reducing eye strain in dark mode.
- **Muted (#8892B0):** Used for secondary text, descriptions, and decorative borders to establish hierarchy.

## Typography

This design system utilizes **Inter** exclusively to maintain a utilitarian and systematic feel. The typography relies on scale and weight rather than font switching to indicate hierarchy. 

Headlines use tighter tracking and heavier weights to anchor sections. Body copy is set with a generous line height (1.6) to ensure maximum readability against the dark background. Labels and small metadata should be set in uppercase with increased letter spacing to distinguish them from prose.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy, centered on the screen with a maximum width of 1100px to ensure line lengths remain optimal for reading. 

Generous whitespace (the "xl" and "lg" units) is used to separate major sections, creating a pacing that feels deliberate and unhurried. Content is organized into a 12-column system, but for a minimal portfolio, most content should be restricted to the central 8 columns to increase the surrounding negative space. Vertical rhythm is strictly enforced through 4px increments.

## Elevation & Depth

Depth in this design system is achieved through **Tonal Layers** and **Low-Contrast Outlines** rather than traditional shadows. 

The primary background is the deepest layer. Component surfaces (cards, navigation bars) use the Tertiary color (#112240). To define these surfaces further, a subtle 1px border (#233554) is applied. Shadows are avoided to maintain a flat, architectural feel. Interactive elements may use a subtle glow effect using the Secondary color for a "digital-first" neon hint, but this should be applied with extreme restraint.

## Shapes

The design system uses **Soft** geometry. Standard UI elements like buttons and cards feature a 0.25rem (4px) corner radius. This slight rounding takes the "edge" off the brutalist tendencies of the layout while maintaining a crisp, professional structure. Larger containers use a 0.5rem radius to feel slightly more approachable, but the overall language remains primarily rectangular and disciplined.

## Components

- **Buttons:** Primary buttons feature a 1px solid border of the Secondary color with a transparent background; text is also the Secondary color. On hover, the button fills with a 10% opacity of the Secondary color.
- **Chips/Tags:** Small, rectangular shapes with the Tertiary background and Muted text. Used for skill sets or categories.
- **Lists:** Clean, vertical stacks with no bullets. Use 1px bottom borders in a muted tone to separate items.
- **Input Fields:** Darker than the primary background, using the Tertiary color. Focus state is indicated by a Secondary color border transition.
- **Cards:** Simple containers with the Tertiary background and a 1px border. No shadows. Content inside should have generous internal padding (sm or md spacing units).
- **Navigation:** A minimal top bar that becomes semi-transparent on scroll, using a backdrop-blur (10px) to maintain legibility over content.
- **Project Links:** Large-scale text links that use a subtle underline animation on hover, transitioning from left to right.