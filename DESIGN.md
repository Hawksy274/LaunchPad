---
name: Orbital Glass
project: LaunchPad (projects/9271854620978772108)
origin: STITCH
deviceType: DESKTOP
colorMode: DARK
colorVariant: FIDELITY
customColor: '#a855f7'
headlineFont: Space Grotesk
bodyFont: Geist
labelFont: JetBrains Mono
roundness: ROUND_EIGHT
colors:
  surface: '#0f131d'
  surface-dim: '#0f131d'
  surface-bright: '#353944'
  surface-container-lowest: '#0a0e18'
  surface-container-low: '#171b26'
  surface-container: '#1c1f2a'
  surface-container-high: '#262a35'
  surface-container-highest: '#313540'
  surface-variant: '#313540'
  on-surface: '#dfe2f1'
  on-surface-variant: '#cfc2d6'
  inverse-surface: '#dfe2f1'
  inverse-on-surface: '#2c303b'
  outline: '#988d9f'
  outline-variant: '#4d4354'
  surface-tint: '#ddb7ff'
  primary: '#ddb7ff'
  on-primary: '#490080'
  primary-container: '#b76dff'
  on-primary-container: '#400071'
  inverse-primary: '#842bd2'
  primary-fixed: '#f0dbff'
  primary-fixed-dim: '#ddb7ff'
  on-primary-fixed: '#2c0051'
  on-primary-fixed-variant: '#6900b3'
  secondary: '#7bd0ff'
  on-secondary: '#00354a'
  secondary-container: '#00a6e0'
  on-secondary-container: '#00374d'
  secondary-fixed: '#c4e7ff'
  secondary-fixed-dim: '#7bd0ff'
  on-secondary-fixed: '#001e2c'
  on-secondary-fixed-variant: '#004c69'
  tertiary: '#d2bbff'
  on-tertiary: '#3f008e'
  tertiary-container: '#a476ff'
  on-tertiary-container: '#36007d'
  tertiary-fixed: '#eaddff'
  tertiary-fixed-dim: '#d2bbff'
  on-tertiary-fixed: '#25005a'
  on-tertiary-fixed-variant: '#5a00c6'
  background: '#0f131d'
  on-background: '#dfe2f1'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
typography:
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  display-md:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-md-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 26px
    letterSpacing: 0em
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  telemetry-data:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: -0.02em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

# LaunchPad Design System — Orbital Glass

> Sourced and extracted directly from Google Stitch project **LaunchPad** (`projects/9271854620978772108`).

---

## 1. Brand & Style

This design system blends deep-space minimalism with high-precision aerospace telemetry and luminous glassmorphism. Engineered for complex space-tech SaaS platforms, mission planning consoles, and satellite analytics interfaces, the aesthetic balances scientific rigor with an aspirational, cinematic atmosphere.

### Personality & Emotional Response
- **Sovereign & Advanced:** Evokes precision engineering, orbital control rooms, and next-generation spacecraft telemetry.
- **Atmospheric Depth:** Deep cosmos-inspired dark layers set against piercing optical glows that guide operator attention without inducing visual fatigue.
- **Calm Authority:** High-density data metrics remain legible, balanced, and serene even during critical mission events.

### Design Movement: Atmospheric Glassmorphism & High-Precision Tech
The aesthetic relies on multi-layered translucent glass panels floating above midnight voids. Interfaces use ultra-fine 1px perimeter lighting, directional luminosity, vibrant violet-to-cyan energy channels, and restrained technical data visualization accents.

---

## 2. Color Palette & Optical Signals

The color system uses deep spatial voids as foundational canvasses, illuminated by high-energy optical accents.

### Core Canvas & Surfaces
| Surface Level | Token / Value | Purpose |
| :--- | :--- | :--- |
| **Void Base** | `#070913` / `#0f131d` | Canvas root, ultra-deep backgrounds, viewport backdrop |
| **Surface Level 1** | `#0B0F19` / `#171b26` | Primary panel layer, sidebars, navigation rails with alpha overlays |
| **Surface Level 2** | `#0F172A` / `#1c1f2a` | Interactive cards, elevated modules, popovers |
| **Surface Level 3** | `#1E293B` / `#262a35` | Hover states, active segment fills, nested wells |
| **Surface Bright** | `#353944` | High-contrast elevated borders & chips |

### Luminescence & Data Signals
- **Primary Energy (`#A855F7` / `#C084FC` / `#ddb7ff`):** Primary actions, focal states, active trajectory vectors, and glowing focus borders.
- **Engine Core / Deep Violet (`#7C3AED` / `#9333EA` / `#490080`):** Structural backdrops for active toggles, deep glow gradients, and telemetry badge fills.
- **Secondary Cyan / Starlight (`#38BDF8` / `#7bd0ff`):** Telemetry readouts, locked targets, dynamic status metrics, and secondary focal points.
- **Functional Status:**
  - *Nominal (Emerald):* `#34D399`
  - *Anomaly / Alert (Amber):* `#FBBF24`
  - *Critical / Abort (Rose):* `#F43F5E` / `#ffb4ab`

### Border & Sheer Strokes
- **Outer Glass Perimeter:** `rgba(255, 255, 255, 0.08)` transitioning to `rgba(168, 85, 247, 0.35)` on top/left edges to simulate starlight refraction.
- **Subtle Partition:** `rgba(255, 255, 255, 0.04)`.

---

## 3. Typography Hierarchy

The typographic hierarchy balances geometric futurism, optical clarity, and technical precision:

| Level | Family | Size | Weight | Line Height | Letter Spacing | Usage |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `display-lg` | Space Grotesk | 56px | 700 | 64px | -0.03em | Hero headlines |
| `display-lg-mobile` | Space Grotesk | 36px | 700 | 44px | -0.02em | Hero mobile |
| `display-md` | Space Grotesk | 40px | 600 | 48px | -0.02em | Major section headers |
| `display-md-mobile` | Space Grotesk | 28px | 600 | 36px | -0.01em | Major section mobile |
| `headline-lg` | Space Grotesk | 30px | 600 | 38px | -0.015em | Module headers |
| `headline-md` | Space Grotesk | 22px | 500 | 30px | -0.01em | Modal & drawer titles |
| `headline-sm` | Space Grotesk | 18px | 500 | 26px | 0em | Card headers, groups |
| `body-lg` | Geist | 16px | 400 | 24px | 0em | Primary documentation |
| `body-md` | Geist | 14px | 400 | 20px | 0em | Default body, tables |
| `body-sm` | Geist | 12px | 400 | 18px | 0.01em | Captions, metadata |
| `telemetry-data` | JetBrains Mono | 14px | 600 | 20px | -0.02em | Coordinate grids, counters |
| `label-caps` | JetBrains Mono | 11px | 500 | 16px | 0.08em | Status pills, badges |
| `label-code` | JetBrains Mono | 12px | 400 | 16px | 0.02em | Code snippets, keys |

- **Headlines (Space Grotesk):** Provides structured geometric character with aerodynamic terminals, conveying advanced technological engineering.
- **Interface & Reading Copy (Geist):** Clean, neutral, and razor-sharp across retina displays. Neutralizes cognitive strain in dense monitoring modules.
- **Telemetry & Labels (JetBrains Mono):** Reserved for coordinate grids, live sensor telemetry, raw code outputs, timestamps (UTC), and micro-caps status pills. Enforces tabular numeric consistency across real-time dynamic streaming updates.

---

## 4. Layout & Spacing

Built upon an 8-point spatial matrix within a responsive 12-column dynamic grid.

### Canvas Layout
- **Desktop (1440px+):** 12-column layout with 24px (`1.5rem`) gutters and 32px (`2rem`) margins. Max-width constraints sit at 1680px for standard control dashboards, while telemetry command centers scale fluidly across 100vw edge-to-edge workspaces.
- **Tablet (768px - 1024px):** 8-column layout with 16px gutters and 24px outer margins. Secondary visualization rails collapse into switchable bottom-sheet monitors.
- **Mobile (< 768px):** 4-column layout with 12px (`0.75rem`) gutters and 16px (`1rem`) outer margins. Critical metrics display in horizontal scroll ribbons with persistent status bars.

### Density Tiers
- **Analytical Grid Density:** Micro gaps (`space-xs` [4px] and `space-sm` [8px]) applied strictly to instrument clusters, vector coordinates, and launch timeline scrubbers.
- **Executive & Workspace Density:** Standard modules utilize `space-md` (16px) to `space-lg` (24px) padding to preserve visual calm and card legibility.

---

## 5. Elevation, Depth & Glassmorphism

Visual hierarchy relies on refractive glass layers, optical luminosity, dynamic backdrop blurs, and layered alpha containers.

### Surface Tiers
- **Void Substrate (Canvas):** Flat `#070913` with subtle radial atmospheric gradient sweeps of `rgba(124, 58, 237, 0.06)` centered behind dominant charts.
- **Floating Glass Panels (Level 1):** Background `rgba(15, 23, 42, 0.65)`, backdrop blur `16px`, bordered with `1px solid rgba(255, 255, 255, 0.08)`.
- **Active / Elevated Modules (Level 2):** Background `rgba(30, 41, 59, 0.55)`, backdrop blur `24px`, top edge stroke `1px solid rgba(192, 132, 252, 0.25)`, side/bottom stroke `1px solid rgba(255, 255, 255, 0.06)`.
- **Flyouts & Modals (Level 3):** Background `rgba(11, 15, 25, 0.85)`, backdrop blur `32px`, box-shadow `0 0 40px rgba(0, 0, 0, 0.6), 0 0 24px rgba(168, 85, 247, 0.15)`.

### Optical Energy Glows
Interactive triggers generate soft neon back-glows:
- **Purple Luminescence:** `box-shadow: 0 0 20px -2px rgba(168, 85, 247, 0.45);`
- **Cyan Lock Glow:** `box-shadow: 0 0 16px -2px rgba(56, 189, 248, 0.45);`

---

## 6. Shapes & Roundness

- **Base Cards & Panels:** Standard `rounded` (8px / `0.5rem`) up to `rounded-lg` (16px / `1rem`) for large cockpit panels.
- **Telemetry Chips & Badges:** Full radius pill geometry (`9999px`) to visually contrast against structured rectangular data frames.
- **Nested Controls (Inputs, Micro Buttons):** `rounded` (8px / `0.5rem`) aligned with panel inner-radius rules (`outer_radius - padding = inner_radius`).

---

## 7. Component Specifications

### Buttons
- **Primary Glowing Action:**
  - Background: linear gradient `135deg, #9333EA 0%, #7C3AED 100%`
  - Border: `1px solid rgba(192, 132, 252, 0.4)`
  - Text: White, medium weight
  - Rest state shadow: `0 0 16px rgba(147, 51, 234, 0.3)`
  - Hover state: elevates glow to `0 0 24px rgba(168, 85, 247, 0.6)`, background `135deg, #A855F7 0%, #9333EA 100%`
- **Secondary Glass Trigger:**
  - Background: `rgba(255, 255, 255, 0.04)`
  - Border: `1px solid rgba(255, 255, 255, 0.12)`
  - Text: `#38BDF8`
  - Hover state: border becomes `rgba(56, 189, 248, 0.4)`, background fills to `rgba(56, 189, 248, 0.08)`
- **Ghost Action:**
  - Background: Transparent, Text `#94A3B8`
  - Hover: Text `#F8FAFC`, background `rgba(255, 255, 255, 0.05)`

### Telemetry Pills & Status Chips
- Pill-shaped (`rounded-full`) wrappers with padding `2px 10px`. Text rendered in `label-caps`.
- Contains a live 6px pulsing circular beacon on the leading edge.
- **Nominal Variant:** `rgba(52, 211, 153, 0.1)` fill, `1px solid rgba(52, 211, 153, 0.3)` border, `#34D399` text.
- **Tracking / Active Variant:** `rgba(56, 189, 248, 0.1)` fill, `1px solid rgba(56, 189, 248, 0.3)` border, `#38BDF8` text.

### Cards & Container Panels
- Multi-layered frosted glass structure: `backdrop-filter: blur(20px)`, fill `rgba(15, 23, 42, 0.6)`.
- Subtle dual border stroke: top/left border highlight `rgba(168, 85, 247, 0.25)`, bottom/right perimeter `rgba(255, 255, 255, 0.05)`.
- Inner content separated by faint gradient rules `linear-gradient(90deg, transparent, rgba(255,255,255,0.08), transparent)`.

### Input Fields & Search Bars
- Background `rgba(7, 9, 19, 0.6)`, border `1px solid rgba(255, 255, 255, 0.1)`.
- Typography set to `body-md` in `#F8FAFC`, placeholder text `#64748B`.
- Focus state: border transforms to `#A855F7`, outer ring emits a diffuse aura `0 0 0 3px rgba(168, 85, 247, 0.2)`.

---

## 8. Associated Project Screens

1. **LaunchPad Brand Logo**
   - Screen ID: `projects/9271854620978772108/screens/19027c33c1e44dffa2abe23aac906457`
   - Dimensions: `512 x 512`
   - Type: Vector SVG Brandmark

2. **LaunchPad — Space-Tech SaaS Landing Page**
   - Screen ID: `projects/9271854620978772108/screens/9834564431c24dc4a599bb1baac3c22d`
   - Dimensions: `2560 x 9962` (Desktop)
   - Type: Complete Space-Tech SaaS Landing Page & Telemetry Console
