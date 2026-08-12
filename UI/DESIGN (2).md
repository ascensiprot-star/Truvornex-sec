---
name: Truvornex Core
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
  on-surface-variant: '#444748'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e4e2e1'
  on-secondary-container: '#656464'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#100069'
  on-tertiary-container: '#7771ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#e4e2e1'
  secondary-fixed-dim: '#c8c6c6'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#e3dfff'
  tertiary-fixed-dim: '#c3c0ff'
  on-tertiary-fixed: '#100069'
  on-tertiary-fixed-variant: '#372abf'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: '0'
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.1em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 28px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  xxl: 64px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style

The design system is built on the philosophy of "Simple Surface, Deep System." It functions as an architectural operating layer for local economic infrastructure, prioritizing clarity, permanence, and technical precision over transient trends. The aesthetic is ultra-premium and calm, avoiding typical startup exuberance in favor of a stable, institutional intelligence.

The visual style is **Corporate Modern with Architectural Minimalism**. It utilizes a "White-Label Infrastructure" approach where the UI recedes to allow neighborhood data and commerce to take center stage. High-quality whitespace, crisp 1px lines, and a disciplined modular grid evoke the feeling of a well-planned urban blueprint. The emotional response should be one of absolute trust, as if interacting with a digital utility or a high-end physical space.

## Colors

The palette is intentionally restrained to maintain a sophisticated, neutral environment. 

- **Surfaces:** Use `#FFFFFF` for primary work surfaces. `#F9F9F9` (Off-white) is used for the background "bed" or secondary container levels. `#F0F0F0` (Light Grey) is reserved for subtle grouping or inactive states.
- **Ink & Contrast:** Primary text and high-importance UI elements use `#1A1A1A` (Deep Charcoal). Secondary information and supporting iconography use `#2D2D2D` (Graphite).
- **System Indicators:** A single precision accent of `#4338CA` (Indigo) is used exclusively for primary actions, system status indicators, and subtle highlights. It should be used sparingly to maintain its significance.
- **Borders:** A universal border color of `#E5E7EB` is used for all structural divisions and card outlines.

## Typography

This design system utilizes **Geist** for its technical precision and neutral clarity. For data-heavy labels and system-level metadata, **JetBrains Mono** is introduced to provide a subtle "infrastructure" feel.

- **Headlines:** Use generous tracking (0.02em to 0.05em) for all-caps sub-headers to create an editorial, architectural feel. Main headlines should be tight and impactful.
- **Body:** Prioritize legibility with a 1.6 line-height on larger reading blocks to ensure the UI feels calm and unhurried.
- **Labels:** Use `label-caps` (JetBrains Mono) for status badges, table headers, and small metadata to differentiate "system data" from "content."

## Layout & Spacing

The layout philosophy is based on a **Modular Fixed Grid**. It is designed to mimic the structured nature of physical urban planning.

- **Grid:** A 12-column grid for desktop (max-width 1440px) and a 4-column grid for mobile.
- **Rhythm:** An 8px base unit (with a 4px half-step for micro-adjustments) governs all padding and margins. 
- **Adaptation:** On mobile, margins reduce to 16px, and modular cards stack vertically. On tablet and desktop, cards utilize the grid to span 4, 6, or 8 columns depending on content density.
- **Whitespace:** Use whitespace as a functional tool to separate distinct economic sectors or data types without relying on heavy lines.

## Elevation & Depth

Hierarchy in this design system is achieved through **Low-Contrast Outlines** and **Tonal Layering** rather than heavy shadows or blurs.

- **The Base:** The lowest level is the background (`#F9F9F9`).
- **The Card:** Elements sit on a white (`#FFFFFF`) surface with a 1px border (`#E5E7EB`). 
- **Shadows:** Use "Z-shadows" that are sharp and architectural. For a resting card, use a 1px vertical offset with 2px blur at 5% opacity. For "active" or "hovered" states, increase the vertical offset to 4px with 8px blur at 8% opacity. Shadows should always be neutral (no color tinting).
- **Z-Index:** Content is layered logically: Navigation (top) > Modals/Overlays > Floating Actions > Cards > Base Surface.

## Shapes

The shape language is **Modular and Precise**. 

- **Corner Radii:** A consistent `4px` or `8px` radius is used for all containers. This small radius retains a sense of modernism while feeling more approachable than perfectly sharp corners.
- **Iconography:** Icons use a 2px stroke weight with geometric forms. Ends are squared or slightly rounded to match the container radius.
- **Buttons:** Buttons follow a `4px` radius to maintain the structural look, avoiding "pill" shapes which are considered too informal for this system.

## Components

- **Buttons:** 
  - *Primary:* Solid `#1A1A1A` background, white text. No gradient. 
  - *Secondary:* 1px border `#E5E7EB`, white background, `#1A1A1A` text.
  - *Tertiary:* Text-only with the accent color `#4338CA` for high-importance actions or `#2D2D2D` for navigation.
- **Cards:** White background, 1px border, 8px corner radius. Used as the primary vessel for all economic data.
- **Input Fields:** 1px border `#E5E7EB`, 4px radius. On focus, the border changes to the accent `#4338CA` with no outer glow.
- **Chips/Badges:** Use a light grey background `#F0F0F0` with `label-caps` typography. Success/Error states use muted versions of green/red (e.g., `#059669` and `#DC2626`).
- **Data Tables:** Highly structured with 1px horizontal dividers only. Header row uses `label-caps` in `#2D2D2D`.
- **Imagery:** Photography must be professional, documentary-style shots of local architecture, markets, and transit. Avoid stock photos with "smiling models"; prioritize the environment and the infrastructure.