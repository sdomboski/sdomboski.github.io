---
name: Lunar Solarium
colors:
  surface: '#051424'
  surface-dim: '#051424'
  surface-bright: '#2c3a4c'
  surface-container-lowest: '#010f1f'
  surface-container-low: '#0d1c2d'
  surface-container: '#122131'
  surface-container-high: '#1c2b3c'
  surface-container-highest: '#273647'
  on-surface: '#d4e4fa'
  on-surface-variant: '#d7c3ae'
  inverse-surface: '#d4e4fa'
  inverse-on-surface: '#233143'
  outline: '#9f8e7a'
  outline-variant: '#524534'
  surface-tint: '#ffb955'
  primary: '#ffc880'
  on-primary: '#452b00'
  primary-container: '#f5a623'
  on-primary-container: '#644000'
  inverse-primary: '#835500'
  secondary: '#ffb964'
  on-secondary: '#482a00'
  secondary-container: '#c8811f'
  on-secondary-container: '#3e2400'
  tertiary: '#9bdaff'
  on-tertiary: '#00354a'
  tertiary-container: '#40c2fd'
  on-tertiary-container: '#004d6a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffddb4'
  primary-fixed-dim: '#ffb955'
  on-primary-fixed: '#291800'
  on-primary-fixed-variant: '#633f00'
  secondary-fixed: '#ffddba'
  secondary-fixed-dim: '#ffb964'
  on-secondary-fixed: '#2b1700'
  on-secondary-fixed-variant: '#663e00'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#051424'
  on-background: '#d4e4fa'
  surface-variant: '#273647'
typography:
  display-xl:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
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
    letterSpacing: 0.01em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
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
  space-2xl: 4rem
---

## Brand & Style

This design system translates the stark, atmospheric beauty of a barren lunar body illuminated by intense solar radiation into a contemporary, high-precision personal portfolio and resume platform. The aesthetic merges **minimalist technical precision** with **restrained tactile glassmorphism**—drawing direct inspiration from Apollo-era telemetry interfaces, high-tech orbital mechanics, and clean aerospace engineering.

### Target Audience & Personality
- **Audience:** Engineering leaders, design directors, frontier tech recruiters, and discerning clients seeking senior-tier talent.
- **Brand Attributes:** Precise, disciplined, illuminating, resilient, and forward-looking.
- **Emotional Response:** Inspires quiet confidence, effortless clarity, and an unmistakable sense of craft. It feels like observing an impeccably organized control module against the vastness of the cosmos.

## Colors

The palette grounds itself in deep cosmic voids and lunar crater slates, punctuated by radiant solar gold and beacon copper that evoke solar arrays capturing unmitigated sunlight.

### Color Tiers & Mapping
- **Canvas / Space Surface (`#0F1218`):** The foundational absolute dark; represents deep space vacuum.
- **Crater Basin / Elevated Surfaces (`#181D26`, `#222936`):** Modular panels, card backdrops, and navigation shells.
- **Subtle Surface Overlays (`#273142`):** Translucent card tiers receiving faint solar reflections.
- **Primary / Solar Flare (`#F5A623`, `#E59A38`):** Active status indicators, timeline nodes, primary calls to action, and focal typography.
- **Tertiary / Atmosphere Ion (`#38BDF8`):** Crisp secondary telemetry accents, active link states, and verified metric markers.
- **Neutral Silver / Lunar Dust (`#F3F4F6`, `#E2E8F0`, `#94A3B8`, `#475569`):**
  - `#F3F4F6` for stark high-contrast primary headings.
  - `#E2E8F0` for body copy and core resume narratives.
  - `#94A3B8` for dates, secondary labels, and metadata.
  - `#475569` for subtle borders, inactive tracks, and grid rules.

## Typography

The pairing of **Space Grotesk** and **Inter** creates a balance between technical instrumentation and effortless editorial readability.

- **Headlines and Labels (Space Grotesk):** Provides mathematical geometry, sharp letterforms, and mechanical authority reminiscent of flight manifests and deep space telemetry.
- **Body & Continuous Reading (Inter):** Ensures flawless legibility for exhaustive project briefs, technical papers, and resume chronology.
- **Micro-Metrics & Badges:** Upper-case Space Grotesk in `label-sm` with loose tracking (+0.08em) delivers instantaneous clarity for skills, tooling versions, and timeframes.

## Layout & Spacing

Layouts follow an asymmetric 12-column grid anchored by an 8px atomic grid. Space is treated deliberately as void; ample negative space isolates complex ideas and lets career highlights command immediate attention.

### Grid Breakpoints
- **Mobile (0 – 639px):** Single-column stack, `1.25rem` outer margins, `1rem` vertical gutters. Compact timeline view with simplified inline timestamps.
- **Tablet (640px – 1023px):** 6-column grid, `2rem` outer margins, `1.25rem` gutters. Project cards reflow into 2-column arrays.
- **Desktop (1024px+):** 12-column fixed-max layout (1280px maximum container width), `3rem` margins, `1.5rem` gutters. Split-screen layout options for sticky profile overview and scrollable experience logs.

## Elevation & Depth

Visual hierarchy does not rely on traditional muddy dropshadows. Instead, elevation simulates atmospheric depth using fine-edged structural borders, translucent matte finishes, and warm solar luminescence.

### Elevation Hierarchy
- **Level 0 (Cosmic Floor):** `#0F1218` solid background with a faint, repeating 24px subtle dot-grid mask rendered in `#222936` at 40% opacity.
- **Level 1 (Crater Panel / Surface Card):** Background `#181D26` blended with 70% opacity and `backdrop-filter: blur(12px)`. Enclosed in a razor-thin 1px perimeter border of `#334155` (60% opacity).
- **Level 2 (Interactive Floating Card):** Hover or active elevation tier utilizing `#222936` fill with an updated 1px border shift to `#F5A623` at 40% opacity.
- **Level 3 (Solar Glow / Active State):** A diffused accent glow: `0px 0px 24px -4px rgba(245, 166, 35, 0.25)` and a razor border of `rgba(245, 166, 35, 0.6)`. Used selectively on primary project milestones and active status indicators.

## Shapes

The design system maintains a **Soft (Level 1)** geometric form language. 
- Core containers, surface panels, and code blocks leverage `0.25rem` (4px) or `0.5rem` (8px) corners, echoing machined aluminum housing and instrumentation consoles.
- Badges, technical skill chips, and timeline nodules utilize tight, controlled rounding (`0.25rem`) or strict pill styling solely for category badges, preventing any childish or bubble-like aesthetic.
- Buttons retain `0.25rem` radius to preserve sharp, technical precision.

## Components

### Buttons
- **Solar Primary:** Solid `#F5A623` fill with dark `#0F1218` text set in `label-md` weight. Hover transitions to `#E59A38` with a subtle amber ambient halo (`0 0 16px rgba(245,166,35,0.4)`).
- **Crater Secondary:** Background `#222936` with a crisp 1px border in `#475569`. Text in `#F3F4F6`. Hover triggers border transition to `#94A3B8` and background to `#273142`.
- **Ghost Beacon:** Transparent background, text in `#F5A623`, underlines replaced by an expanding 1px indicator line on hover.

### Skill Badges & Chips
- Matte `#1E2533` pill surfaces bounded by a 1px border in `#334155`. Text styled in `label-sm` with color `#E2E8F0`.
- Category indicator: A 4px solid dot before the label (e.g., `#F5A623` for Frontend/Core, `#38BDF8` for Cloud/Systems).

### Timeline & Resume Log
- Continuous 1px vertical guide rail rendered in `#222936`.
- Nodes: 9px square markers rotated 45 degrees (diamond beacons). Unfilled nodes use 1.5px `#475569` borders; active or current positions receive a glowing `#F5A623` fill with an outer 4px halo.
- Section dates set in `Space Grotesk` tabular figures (`label-md`), positioned alongside company credentials.

### Project & Experience Cards
- Structured as frosted glass modules (`#181D26` with 1px border `#334155`).
- Upper right: Technical link anchors with crisp 45-degree arrow icons (`↗`).
- Inner content: Section tags, project metric summary pills, and high-contrast headlines in `#F3F4F6`.

### Inputs & Contact Surface
- Single-line fields with flush dark background `#12161F` and bottom-border emphasis.
- Static state: 1px border `#334155`.
- Focus state: Border transitions to `#F5A623`, elevating the field with an amber hairline focus ring. Zero unnecessary helper chrome.