---
name: Aeronautical Gold & Carbon
colors:
  surface: '#111317'
  surface-dim: '#111317'
  surface-bright: '#37393d'
  surface-container-lowest: '#0c0e11'
  surface-container-low: '#1a1c1f'
  surface-container: '#1e2023'
  surface-container-high: '#282a2d'
  surface-container-highest: '#333538'
  on-surface: '#e2e2e6'
  on-surface-variant: '#d2c5b0'
  inverse-surface: '#e2e2e6'
  inverse-on-surface: '#2f3034'
  outline: '#9b8f7c'
  outline-variant: '#4f4636'
  surface-tint: '#f2bf54'
  primary: '#f2bf54'
  on-primary: '#402d00'
  primary-container: '#c99a32'
  on-primary-container: '#4a3400'
  inverse-primary: '#7a5900'
  secondary: '#e9c16c'
  on-secondary: '#402d00'
  secondary-container: '#6d5000'
  on-secondary-container: '#edc46f'
  tertiary: '#f0bf63'
  on-tertiary: '#412d00'
  tertiary-container: '#c79a43'
  on-tertiary-container: '#4b3400'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdea3'
  primary-fixed-dim: '#f2bf54'
  on-primary-fixed: '#261900'
  on-primary-fixed-variant: '#5d4200'
  secondary-fixed: '#ffdf9f'
  secondary-fixed-dim: '#e9c16c'
  on-secondary-fixed: '#261a00'
  on-secondary-fixed-variant: '#5c4300'
  tertiary-fixed: '#ffdea7'
  tertiary-fixed-dim: '#f0bf63'
  on-tertiary-fixed: '#271900'
  on-tertiary-fixed-variant: '#5e4200'
  background: '#111317'
  on-background: '#e2e2e6'
  surface-variant: '#333538'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-telemetry:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.12em
  button:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
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

The brand personality conveys elite aeronautical precision, quiet authority, and bespoke executive luxury tailored for private aviators, diplomatic delegations, and discerning charter clientele traversing South America through Luque, Paraguay. The aesthetic merges technical aviation discipline with the hospitality of an ultra-luxury private terminal.

The design movement combines **Glassmorphism** and **Technical Precision Minimalism**:
- Translucent dark carbon surfaces resting over deep atmospheric layers.
- Hairline metallic gold borders echoing brushed brass instrument panels and navigational charts.
- Restrained, architectural space distribution that avoids visual clutter, projecting absolute composure, safety, and exclusivity.

## Colors

The palette draws directly from cockpit avionics at dusk and the refined appointments of bespoke aircraft interiors:

- **Primary (`#C99A32`)**: Satin Metallic Gold. Used for high-priority actions, key wayfinding, verification badges, and primary interactive states.
- **Secondary (`#E5BD68`)**: Shimmer Accent Gold. Reserved for subtle linear highlights, active glow states, and fine gradient stops.
- **Tertiary (`#9A721D`)**: Burnished Deep Gold. Used for pressed states, subtle framing shadows, and low-contrast perimeter dividers.
- **Neutral Dark (`#0B0D10`)**: Carbon Black. The bedrock background surface providing depth, high legibility, and an immersive executive night-flight ambiance.
- **Surface Elevation Layers**:
  - `Surface-0 (Canvas)`: `#0B0D10`
  - `Surface-1 (Base Panel)`: `#13171D`
  - `Surface-2 (Glass Card)`: `#20242A` at 65% to 85% opacity with backdrop blur.
  - `Surface-3 (Elevated Float)`: `#2C323B` at 90% opacity.
- **Text & Foreground**:
  - `Text Primary`: `#FFFFFF` (pure white for pristine readability).
  - `Text Secondary`: `#8E95A2` (slate silver for flight telemetry, sub-labels, and metadata).
  - `Text Accent`: `#E5BD68` (shimmer gold for status confirmations, tail numbers, and VIP identifiers).

## Typography

The typographic hierarchy balances modern corporate authority with aeronautical instrumentation.

- **Primary Brand & Structure (Plus Jakarta Sans)**: Delivers geometric clarity and international polish. Wide-open counters ensure flawless legibility across terminal kiosks, mobile operations, and flight planning dashboards.
- **Instrument & Operational Layer (Space Grotesk)**: Introduced selectively for operational tokens, ICAO/IATA codes (e.g., `SGAS / ASU`), runway coordinates, fuel quantities, and aircraft tail numbers. All caps with expanded letter spacing reinforce aeronautical rigor.
- Uppercase styling should always be paired with increased letter spacing (`0.08em` to `0.14em`) and restricted to metadata, badges, and section overhead tags.

## Layout & Spacing

The layout operates on a standard 12-column responsive grid anchored by generous negative space to maintain an unhurried, executive environment:

- **Desktop (1200px and up)**: 12 columns, `1.5rem` (`24px`) gutters, `3rem` (`48px`) outer margins, maximum container width capped at `1440px`.
- **Tablet (768px - 1199px)**: 8 columns, `1.25rem` (`20px`) gutters, `2rem` (`32px`) outer margins.
- **Mobile (Below 768px)**: 4 columns, `1rem` (`16px`) gutters, `1.25rem` (`20px`) outer margins. Operational telemetry grids collapse from multi-column rows into clean stacked data lists.

Section gaps utilize wide pacing (`space-xl` scaled to `4rem` for hero transitions) to evoke exclusivity, whereas functional telemetry modules utilize dense micro-pacing (`space-xs` and `space-sm`) to keep vital flight and ground-handling data grouped logically.

## Elevation & Depth

Visual hierarchy relies on translucent carbon layering paired with hairline metallic gold boundaries rather than heavy drop shadows:

- **Base Canvas**: Solid Carbon Black (`#0B0D10`).
- **Glassmorphic Paneling**: Background color set to `#20242A` at 70% opacity with a `16px` to `24px` backdrop blur (`backdrop-filter: blur(20px)`).
- **Hairline Perimeter Borders**: All panels feature a crisp `1px` border using a subtle linear gradient: `linear-gradient(135deg, rgba(201, 154, 50, 0.4) 0%, rgba(32, 36, 42, 0.2) 50%, rgba(229, 189, 104, 0.15) 100%)`.
- **Atmospheric Glows**: Interactive hover and active focus states introduce a directional gold ambient aura: `box-shadow: 0 8px 32px -4px rgba(201, 154, 50, 0.12), inset 0 1px 0 rgba(229, 189, 104, 0.3)`.

## Shapes

The design system employs a **Soft (`1`)** shape language (`4px` base border radius, `8px` for cards/panels, `12px` for focal modal surfaces).

Sharp, structured geometry reflects the aerospace context—evoking machined aircraft-grade alloys, avionics consoles, and architectural terminal louvers. Pill shapes and exaggerated circular corners are strictly prohibited except for micro status-dot indicators.

## Components

### Buttons
- **Primary (Executive Gold)**: Rich gradient fill (`linear-gradient(135deg, #C99A32 0%, #9A721D 100%)`), text in `#0B0D10` (bold weight), subtle gold glow on hover (`0 0 16px rgba(201, 154, 50, 0.35)`).
- **Secondary (Glass / Outline)**: Background transparent or `#20242A` at 40%, border `1px solid rgba(201, 154, 50, 0.5)`, text `#FFFFFF`. Hover transitions border to full `#E5BD68` with surface tint.
- **Ghost / Utility**: Text `#8E95A2`, no background, hover state `#FFFFFF` with faint gold underline.

### Cards & Containers
- Grounded on `#20242A` (75% opacity) with `backdrop-filter: blur(16px)`.
- Border `1px solid rgba(201, 154, 50, 0.25)`.
- Card headers utilize uppercase tracking labels in Space Grotesk (`label-caps`).

### Input Fields & Selectors
- Background: Solid `#13171D` or Glass `#20242A` (60%).
- Border: `1px solid rgba(142, 149, 162, 0.25)`.
- Focus State: Border snaps to `#C99A32` accompanied by a micro glow `0 0 0 1px #C99A32`.
- Floating labels in `#8E95A2`, shifting to `#E5BD68` on active input.

### Checkboxes & Radios
- Square base (`4px` radius for checkboxes, circular for radios).
- Unselected: Dark background `#13171D` with `1px` border in `#8E95A2`.
- Selected: Background `#C99A32` with an inner carbon icon/dot in `#0B0D10`.

### Chips & Status Badges
- Compact padding (`0.25rem 0.75rem`).
- VIP / Cleared: Translucent gold fill (`rgba(201, 154, 50, 0.15)`), border `1px solid #C99A32`, text `#E5BD68`.
- In-Transit / Ground Ops: Translucent slate fill (`rgba(142, 149, 162, 0.15)`), border `1px solid #8E95A2`, text `#FFFFFF`.

### Aeronautical Flight & Service Strips
- Specialized horizontal card component for apron requests, fuel dispatch, and VIP passenger clearance.
- Features left-hand vertical accent bar (`2px` solid `#C99A32`), monospace ICAO coordinates, and real-time step progress indicators.