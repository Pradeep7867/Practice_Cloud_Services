---
name: Deep Tech Terminal
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#ddb7ff'
  on-tertiary: '#490080'
  tertiary-container: '#b76dff'
  on-tertiary-container: '#400071'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#f0dbff'
  tertiary-fixed-dim: '#ddb7ff'
  on-tertiary-fixed: '#2c0051'
  on-tertiary-fixed-variant: '#6900b3'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.005em
  code-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: -0.01em
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0em
  label-badge:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 4rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies an elite, architectural, and production-hardened engineering ethos. It is tailored for high-scale backend and distributed systems engineering showcases, balancing technical rigor with cinematic cyberpunk aesthetics.

### Key Tenets
- **Precision Engineering:** Sharp, high-density information architecture paired with deliberate monospaced metrics to evoke console stability, system telemetry, and mission-critical uptime.
- **Atmospheric Depth:** Deep-space slate substrates illuminated by focused, coherent photonic glows rather than indiscriminate gradients.
- **Tactile High-Tech Glass:** Layered translucent surfaces displaying physical edge bevels, mimicking military-grade heads-up displays and high-performance developer environments.

### Audience & Mood
Targeting engineering leaders, enterprise architects, and technical recruiters. The interface creates an impression of deep technical command, architectural scale, uncompromising code discipline, and contemporary full-stack mastery.

## Colors

The palette relies on absolute dark substrate foundations offset by reactive photonic accents.

### Substrate Surfaces
- **Void Canvas (`#090d16`):** Deepest structural canvas backdrop.
- **Surface Base (`#0f172a`):** Primary panel and foundational container surface.
- **Surface Raised (`#1e293b`):** Elevation layer for secondary interactive containers, code blocks, and floating sheets.
- **Surface Hover (`#334155`):** Subtle interactive hover state for high-density components.

### Photonic Accents & Signals
- **Electric Indigo (`#6366f1`):** Primary driver for actions, structural accents, and focused states.
- **Hyper Cyan (`#06b6d4`):** Secondary accent reserved for distributed telemetry, live system metrics, and architectural paths.
- **Void Purple (`#a855f7`):** Tertiary focal accent for high-value highlights, badges, and peripheral ambient glow.
- **Telemetry Emerald (`#10b981`):** System health, live service indicators, uptime statuses, and verification tags.

### Boundary & Glass Tints
- **Border Ghost (`rgba(148, 163, 184, 0.08)`):** Base structural card and panel borders.
- **Border Active (`rgba(99, 102, 241, 0.4)`):** Highlighted card borders with ambient indigo transmission.

## Typography

The typographic hierarchy implements a functional triad:

1. **Plus Jakarta Sans** provides structural authority for major headings, architectural titles, and hero callouts. High tracking suppression ensures dense visual power without legibility sacrifice.
2. **Inter** handles content density, technical storytelling, and project descriptions, optimized for prolonged reading against high-contrast dark backgrounds.
3. **JetBrains Mono** surfaces all execution-layer data: language identifiers, cloud architectures, timestamp metadata, terminal code lines, and technical metric callouts. Always render badges, system statuses, and metrics in uppercase when paired with `label-badge`.

## Layout & Spacing

### System Architecture
The layout operates on a 12-column dynamic grid system capped at a maximum width of `1280px` (`80rem`), centered within the viewport.

- **Desktop (>= 1024px):** 12 columns, `1.5rem` (24px) gutters, `4rem` (64px) outer horizontal boundaries.
- **Tablet (768px - 1023px):** 8 columns, `1.25rem` (20px) gutters, `2.5rem` (40px) outer margins.
- **Mobile (< 768px):** 4 columns, `1rem` (16px) gutters, `1.25rem` (20px) outer margins.

### Spacing Cadence
- Use `space-xs` and `space-sm` for internal component padding, inline badges, and micro-metrics.
- Use `space-md` for standard card interiors, code block paddings, and related node linkages.
- Use `space-lg` to separate intra-card components and group sub-sections.
- Use `space-xl` for macroscopic section breaks, timeline milestone gaps, and portfolio project grids.

## Elevation & Depth

Visual depth is achieved through glassmorphic diffraction and laser-focused radial back-lighting rather than standard drop shadows.

### Elevation Strata
- **Level 0 (Base Canvas):** `#090d16`. Solid, non-reflective base plane with a subtle `rgba(255, 255, 255, 0.02)` 32px radial dot grid.
- **Level 1 (Glass Container):** Background `rgba(15, 23, 42, 0.65)` layered with `backdrop-filter: blur(16px)` and a directional top highlight border: `1px solid rgba(255, 255, 255, 0.07)`.
- **Level 2 (Active System / Interactive Hover):** Background `rgba(30, 41, 59, 0.8)` with `backdrop-filter: blur(24px)`, framed by a border of `rgba(99, 102, 241, 0.35)` and an ambient exterior glow: `box-shadow: 0 0 25px -5px rgba(99, 102, 241, 0.25), inset 0 1px 0 0 rgba(255, 255, 255, 0.1)`.
- **Level 3 (Modal / Telemetry Drawer):** Background `rgba(15, 23, 42, 0.95)`, `backdrop-filter: blur(32px)`, bordered by `rgba(6, 182, 212, 0.4)` and a deep directional drop shadow: `box-shadow: 0 20px 50px -10px rgba(0, 0, 0, 0.8), 0 0 30px -10px rgba(6, 182, 212, 0.2)`.

### Conic & Radial Light Injection
Behind prominent project cards or architectural diagrams, place ambient radial spots of `radial-gradient(circle at 50% 0%, rgba(99, 102, 241, 0.15), transparent 70%)` to establish focused, localized energy wells.

## Shapes

The design uses balanced `0.5rem` (8px) base corners to preserve an industrial, calibrated aesthetic while avoiding harsh brutality.

- **Base Radius (`0.5rem` / 8px):** Buttons, inputs, terminal panes, interactive cards, and tooltips.
- **Large Radius (`1rem` / 16px):** Project display matrices, architectural overview panels, and modal bounds.
- **Pill Radius (`9999px`):** Live telemetry tags, protocol indicators, and technology chips.

## Components

### Buttons
- **Primary Cyber:** Solid Electric Indigo (`#6366f1`) with crisp white text (`#ffffff`), `box-shadow: 0 0 15px rgba(99, 102, 241, 0.4)`. Transitions on hover to an elevated glow (`0 0 25px rgba(99, 102, 241, 0.6)`) and a slight upward translateY (-1px).
- **Secondary Glass:** `rgba(30, 41, 59, 0.6)` background, `1px solid rgba(148, 163, 184, 0.2)`, text color `#e2e8f0`. On hover, the border shifts to `rgba(6, 182, 212, 0.6)` with light cyan back-wash.
- **Monospace Action (Terminal Trigger):** Background `transparent`, `1px dashed rgba(99, 102, 241, 0.4)`, font family `JetBrains Mono`, text `#a5b4fc`. On hover, transitions to solid `rgba(99, 102, 241, 0.15)`.

### Badges & Technology Chips
- Pill-shaped (`roundedness: 3`) with `label-badge` typography.
- Filled with `rgba(15, 23, 42, 0.7)` and bounded by a `1px` border matching the contextual tech family (e.g., Spring Boot / Java: `#6366f1`; AWS / Cloud: `#06b6d4`; Kafka / Queues: `#a855f7`).
- Includes a leading `6px` circular pulse dot that glows via `box-shadow: 0 0 8px currentColor`.

### Career & Milestone Timeline
- Single vertical stem with a linear gradient running from `#6366f1` to `#06b6d4` against the slate backdrop.
- Milestones feature glass node containers anchored by circuit-style breakout points. Active roles show a pulsing cyan status ping.
- Body blocks feature split headers: high-level job title alongside right-aligned monospaced service dates and tenure indicators.

### Interactive Project Cards
- Composed of Level 1 glass elevation with an overflow-hidden chassis.
- Header showcases system metrics (e.g., "TPS: 45,000", "Latency: <12ms") rendered in `code-sm`.
- Card border transitions smoothly on hover to Level 2 elevation, revealing an interactive interactive beam across the top edge via a moving gradient border.
- Integrated quick-action links to GitHub, architectural blueprints, and interactive live consoles.

### Architecture / Code Panes
- Embedded styled terminal instances featuring standard macOS/UNIX frosted header controls (`#ef4444`, `#eab308`, `#22c55e`).
- Syntax highlighting uses the dark palette: Keywords (`#a855f7`), Strings (`#06b6d4`), Variables (`#f8fafc`), Annotations/Decorators (`#6366f1`).