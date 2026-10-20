---
name: Technical Editorial
colors:
  surface: '#faf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#faf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f4f0'
  surface-container: '#efeeea'
  surface-container-high: '#e9e8e4'
  surface-container-highest: '#e3e2df'
  on-surface: '#1b1c1a'
  on-surface-variant: '#454743'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ed'
  outline: '#767872'
  outline-variant: '#c6c7c1'
  surface-tint: '#5e5e5c'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1c1a'
  on-primary-container: '#848481'
  inverse-primary: '#c7c6c3'
  secondary: '#5a6244'
  on-secondary: '#ffffff'
  secondary-container: '#dee7c1'
  on-secondary-container: '#60684a'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1b1c19'
  on-tertiary-container: '#84847f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e4e2df'
  primary-fixed-dim: '#c7c6c3'
  on-primary-fixed: '#1b1c1a'
  on-primary-fixed-variant: '#464744'
  secondary-fixed: '#dee7c1'
  secondary-fixed-dim: '#c2caa7'
  on-secondary-fixed: '#171e07'
  on-secondary-fixed-variant: '#424a2e'
  tertiary-fixed: '#e4e3dd'
  tertiary-fixed-dim: '#c7c7c1'
  on-tertiary-fixed: '#1b1c19'
  on-tertiary-fixed-variant: '#464743'
  background: '#faf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e3e2df'
typography:
  display-hero:
    fontFamily: Newsreader
    fontSize: 3.75rem
    fontWeight: '400'
    lineHeight: '1.15'
    letterSpacing: -0.025em
  display-hero-mobile:
    fontFamily: Newsreader
    fontSize: 2.25rem
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 2.5rem
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Newsreader
    fontSize: 1.75rem
    fontWeight: '400'
    lineHeight: '1.25'
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Geist
    fontSize: 1.5rem
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Geist
    fontSize: 1.125rem
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: -0.005em
  body-md:
    fontFamily: Geist
    fontSize: 0.9375rem
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-sm:
    fontFamily: Geist
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0.005em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 0.75rem
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.04em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 0.6875rem
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies the rigor of enterprise requirements engineering tempered with the refined aesthetics of a high-end Swiss editorial publication. It positions the practitioner at the intersection of strategic business analysis, machine learning architecture, and structured agile execution. 

The emotional signature is composed, authoritative, and deliberate. Interfaces should feel like a finely bound technical field notebook: disciplined, highly structured, devoid of decorative noise, yet deeply tactile through typographic precision, mathematical proportions, and thoughtful micro-surfaces.

### Design Principles
- **Editorial Legibility:** Generous negative space, disciplined hierarchy, and asymmetric balance prioritize complex case study narratives without visual fatigue.
- **Architectural Utility:** Visual devices mirror engineering and agile artifacts—tabular systems, monospace metadata tickers, systemic tags, and structured process flows.
- **Understated Restraint:** Rely on precise hair-line boundaries and quiet tonal shifts rather than dramatic shadows, skeuomorphism, or aggressive ornamentation.

## Colors

The palette draws inspiration from archival stationery and industrial computing artifacts. 

- **Canvas & Backdrops:** Warm off-white (`#F7F6F2`) acts as the universal ground plane, neutralizing harsh digital glare. Pure white (`#FFFFFF`) is reserved exclusively for elevated structural cards, active workspace panels, and metric tiles.
- **Typography & Structure:** Near-black (`#171816`) serves as the primary ink for headlines, body copy, and structural anchors, ensuring high-contrast readability.
- **Accent & Strategic Focus:** Muted olive (`#737B5C`) functions as an editorial accent, indicating operational states, live enterprise rollouts, agile velocity flags, and technical highlights.
- **Separation & Borders:** Soft grey (`#E7E6E0`) produces delicate 1px grid guides, dividing columns, data tables, and card perimeters without high-contrast friction.

## Typography

Typographic hierarchy bridges human-centric leadership and technical rigor through a triad of typefaces:

- **Editorial Narrative (`Newsreader`):** Applied to major personal statements, philosophy introductions, and case study titles. Evokes the authority of long-form academic and economic journals.
- **Structural Clarity (`Geist`):** Delivers clean, neutral information architecture for enterprise requirements, agile processes, body copy, and UI controls.
- **Technical Metadata (`JetBrains Mono`):** Surfaces sprint metrics, AI model parameters, status flags, timestamps, and architectural specifications with machine-grade precision. Always set with positive letter spacing when capitalized.

## Layout & Spacing

The layout is grounded in a Swiss typographic grid, enforcing discipline across complex enterprise case studies and artifact breakdowns.

### Grid Construction
- **Desktop (≥ 1024px):** 12-column fluid grid, max container width of `1280px`, `3rem` canvas margins, and `1.5rem` gutters. Narrative case studies occupy an 8-column spine with a 4-column dedicated metadata sidebar.
- **Tablet (768px – 1023px):** 8-column fluid grid, `2rem` outer margin, `1.25rem` gutters.
- **Mobile (< 768px):** 4-column fluid grid, `1.25rem` outer margin, `1rem` gutters. Linear vertical stack; sidebars reflow to precede or follow narrative blocks as technical briefs.

### Rhythmic Discipline
Vertical cadence adheres to a strict 4px/8px modular scale. Spacing tokens dictate component padding and internal element relationships. Structural dividers align strictly with column edges, maintaining the continuous lines of an open architectural ledger.

## Elevation & Depth

This design system dispenses with heavy drop shadows and faux blur effects in favor of **low-contrast outlines** and **tonal surface layering**.

### Surface Hierarchy
1. **Base (Canvas):** Warm off-white (`#F7F6F2`) provides the foundational environment.
2. **Layer 1 (Containers & Cards):** Pure white (`#FFFFFF`) surfaces delineate interactive zones, case study summaries, and workflow canvases.
3. **Layer 2 (Floating Overlays):** Modal dialogs, expanded system diagrams, and dropdown menus utilize Pure white (`#FFFFFF`) paired with a micro-diffused ambient shadow: `0 4px 20px -2px rgba(23, 24, 22, 0.06)`.

### Boundary System
Separation between elements is defined by a 1px solid hairline border in Soft grey (`#E7E6E0`). On interactive hover states, this border transitions smoothly to Muted olive (`#737B5C`) or Near-black (`#171816`) without altering element dimensions.

## Shapes

The geometric signature is architectural and controlled. A `Soft` corner profile (`roundedness: 1`) is applied across all standard components:
- Cards, containers, and data tables use `0.25rem` (4px) corner radii.
- Modals, prominent workflow containers, and large preview viewports scale to `0.5rem` (8px).
- Badges, technical pill tags, and status dots leverage full pill radiuses (`9999px`) to establish deliberate contrast against rectangular grid cells.

## Components

### Buttons
- **Primary:** Near-black (`#171816`) fill, pure white text, 4px border radius. Micro-interaction: subtle opacity shift (`90%`) and a 1px vertical translation on active state.
- **Secondary (Editorial Wire):** Pure white (`#FFFFFF`) background with a 1px Soft grey (`#E7E6E0`) border and Near-black (`#171816`) text. Hover induces a border color shift to Muted olive (`#737B5C`).
- **Tertiary / Inline Monospace:** Unframed, `JetBrains Mono` label, paired with a directional arrow (`→`) with a 2px hover translation.

### Chips & Badges
- **Status Badges:** Pill-shaped, Soft grey (`#E7E6E0`) background with a leading 6px circular indicator (e.g., active olive `#737B5C` for live initiatives). Text is set in uppercase monospace.
- **Competency Chips:** Pure white (`#FFFFFF`) surface, 1px border (`#E7E6E0`), `0.25rem` radius, subtle metadata tag style.

### Metric Cards
- Designed for quantifiable business impact (e.g., "38% Cycle Time Reduction", "99.4% Model Precision").
- Crisp white surface with a continuous 1px outline, featuring a small monospace label at the top, a prominent numerical metric in `Geist Medium`, and an explanatory editorial footnote in `Newsreader Italic`.

### Workflow & Agile Process Diagrams
- Step indicators connected by 1px horizontal or vertical rules (`#E7E6E0`).
- Process nodes utilize white surfaces with monospace phase counters (`01`, `02`, `03`), accompanied by clear requirements deliverables beneath each phase.

### Form Inputs & Controls
- **Input Fields:** Pure white background, 1px Soft grey border, 4px corner radius. Placeholder text in muted neutral, active focus indicated by a 1px Near-black border. No heavy focus rings.
- **Checkboxes & Radios:** Sharp, understated controls with 1px Near-black borders when active, featuring solid olive or near-black fills.

### Lists & Tables
- Editorial data lists utilize hairline bottom borders without alternating row stripes. Monospace indices (`001`, `002`) anchor the left margin for enterprise project breakdowns.