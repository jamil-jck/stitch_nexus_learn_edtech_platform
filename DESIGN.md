---
name: Nexus Academic Precision
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#75777e'
  outline-variant: '#c5c6ce'
  surface-tint: '#525e7d'
  primary: '#000a24'
  on-primary: '#ffffff'
  primary-container: '#14213d'
  on-primary-container: '#7c89aa'
  inverse-primary: '#b9c6ea'
  secondary: '#0051d5'
  on-secondary: '#ffffff'
  secondary-container: '#316bf3'
  on-secondary-container: '#fefcff'
  tertiary: '#000d16'
  on-tertiary: '#ffffff'
  tertiary-container: '#002535'
  on-tertiary-container: '#0093c6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d9e2ff'
  primary-fixed-dim: '#b9c6ea'
  on-primary-fixed: '#0d1b36'
  on-primary-fixed-variant: '#3a4664'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 3.5rem
    fontWeight: '800'
    lineHeight: 4.25rem
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Manrope
    fontSize: 2.25rem
    fontWeight: '800'
    lineHeight: 2.75rem
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Manrope
    fontSize: 2.5rem
    fontWeight: '700'
    lineHeight: 3.25rem
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Manrope
    fontSize: 1.875rem
    fontWeight: '700'
    lineHeight: 2.375rem
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Manrope
    fontSize: 2rem
    fontWeight: '700'
    lineHeight: 2.5rem
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Manrope
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Manrope
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
  body-lg:
    fontFamily: Manrope
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Manrope
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-sm:
    fontFamily: Manrope
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
  label-lg:
    fontFamily: Manrope
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-md:
    fontFamily: Manrope
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Manrope
    fontSize: 0.6875rem
    fontWeight: '700'
    lineHeight: 0.875rem
    letterSpacing: 0.04em
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
  margin: 3rem
  margin-mobile: 1rem
  margin-tablet: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system establishes a high-trust, rigorous, and empowering digital learning environment. Tailored for ambitious professionals, lifelong scholars, and university-grade institutional partners, the visual language balances Ivy League stature with modern computational velocity. 

The aesthetic is Modern Corporate with architectural clarity:
- **Clean Structure & Spatial Restraint:** Deliberate whitespace isolates content to reduce cognitive load during complex study modules.
- **Academic Authority:** Anchored in deep navy and balanced by vibrant electric blues to project credibility, precision, and technological progression.
- **Refined Micro-interactions:** Precise, low-latency visual responses (subtle 1px border highlights, gentle scale shifts) reinforce competence and momentum without causing distraction.

## Colors

The palette balances authoritative weight with actionable digital vitality:

- **Primary Deep Navy (`#14213D`):** Primary branding, master layout frames, global headers, and dominant editorial typography. Establishes institutional gravity.
- **Secondary Blue (`#2563EB`):** Primary interactive state (action buttons, primary tabs, active focus indicators, highlighted course pathways).
- **Tertiary Cyan (`#38BDF8`):** Focus rings, active progress nodes, skill badges, and high-engagement visual accents against navy canvases.
- **Surface & Canvas:** Canvas base sits at `#F8FAFC` (Slate 50), with modular layers utilizing `#FFFFFF` cards framed by `#E2E8F0` (Slate 200) micro-borders.
- **Functional Semantics:** Success verification uses Emerald (`#16A34A`), text body relies on Slate Black (`#111827`) for optimal legibility, and secondary meta-information utilizes Muted Slate (`#64748B`).

## Typography

Manrope delivers geometric clarity, structural legibility, and modern academic tone across all scales:
- **Display & Headlines:** Set tight tracking (`-0.02em` to `-0.03em`) with heavy font weights (700/800) to provide structured framing for editorial headlines and program titles.
- **Body Text:** Uses regular weight (400) with generous line heights (`1.5` to `1.65`) to optimize reading stamina across long syllabus summaries, transcripts, and technical course documentation.
- **Labels & Micro-copy:** Rendered with medium to bold weights (600/700) and slightly expanded letter spacing to ensure crisp legibility on UI controls, metadata tags, and lecture timers.

## Layout & Spacing

The layout is built upon an 8pt architectural rhythm combined with a 12-column responsive fluid grid:

- **Desktop (1280px+):** 12-column layout with max-width constrained to `1440px`, centered, using `3rem` canvas margins and `1.5rem` gutters.
- **Tablet (768px – 1279px):** 8-column layout with `2rem` margins and `1.25rem` gutters.
- **Mobile (below 768px):** 4-column layout with `1rem` margins and `1rem` gutters. Stacks sidebars beneath primary curriculum views.

Use `space-xs` and `space-sm` for inline badges, icon pairings, and compact list rows. Use `space-md` and `space-lg` for interior card padding and form stacks. Apply `space-xl` for sectional transitions within course workspaces.

## Elevation & Depth

Visual hierarchy uses subtle layered surfaces paired with soft, tinted shadows to preserve an airy, modern academic environment:

- **Surface Levels:** 
  - Level 0 (Base Canvas): `#F8FAFC`
  - Level 1 (Cards, Modules, Input Fields): `#FFFFFF` bounded by a 1px solid `#E2E8F0` border.
  - Level 2 (Floating Popovers, Filter Menus): `#FFFFFF` bounded by `#CBD5E1`.
  - Level 3 (Modals, Global Drawers): `#FFFFFF` over a `#14213D` backdrop with 40% alpha.
- **Shadow Tokens:**
  - *Resting Card:* `0 1px 3px 0 rgba(20, 33, 61, 0.04), 0 1px 2px -1px rgba(20, 33, 61, 0.02)`
  - *Interactive Hover:* `0 10px 15px -3px rgba(20, 33, 61, 0.06), 0 4px 6px -4px rgba(20, 33, 61, 0.03)` with an elevation translate-Y of `-2px`.
  - *Dropdown / Floating Surface:* `0 20px 25px -5px rgba(20, 33, 61, 0.08), 0 8px 10px -6px rgba(20, 33, 61, 0.04)`.

## Shapes

The interface uses standard `0.5rem` (`8px`) radii for structured modular balance:
- **Base Components (Inputs, Buttons, Badges):** `0.5rem` (`8px`) corners maintain structural discipline without feeling sharp.
- **Container Surfaces (Course Cards, Video Panels):** `rounded-lg` (`1rem` / `16px`) to frame rich content neatly against the canvas.
- **Overlay Elements (Modals, Floating Panels):** `rounded-xl` (`1.5rem` / `24px`).
- **Pill Exceptions:** Filter chips and status tags may use full pill radiuses (`9999px`) to distinguish categorical metadata from clickable rectangular surfaces.

## Components

### Buttons
- **Primary:** Solid `#2563EB` fill, `#FFFFFF` text, `0.5rem` border radius, font `label-lg`. Padding: `0.75rem 1.5rem`. Hover state: `#1D4ED8` with a subtle elevation shift. Focus: `0 0 0 3px rgba(56, 189, 248, 0.45)`.
- **Secondary / Academic Navy:** Solid `#14213D` fill, `#FFFFFF` text, ideal for high-level actions such as "Enroll Now" or "Institutional Sign In".
- **Outline / Ghost:** 1px `#E2E8F0` border, transparent background, `#14213D` text. On hover: `#F1F5F9` surface with `#CBD5E1` border.

### Course Cards
- Background: `#FFFFFF` with a 1px border of `#E2E8F0`. Padding: `1.25rem`.
- Contains: Aspect ratio 16:9 thumbnail, category pill badge top-left, title (`headline-sm`), instructor credit (`body-sm`, `#64748B`), and an inline rating node featuring Emerald (`#16A34A`). Hover activates the interactive shadow and a border shift to `#CBD5E1`.

### Chips & Badges
- **Status / Category:** Pill radius (`9999px`), `0.25rem 0.75rem` padding, font `label-md`. Background: `#EFF6FF` with text `#2563EB` for active disciplines; `#ECFDF5` with text `#16A34A` for verified credentials.
- **Interactive Filter Chip:** 1px border (`#E2E8F0`), background `#FFFFFF`. Selected state switches to `#14213D` text and background `#F1F5F9` with a `#14213D` border.

### Form Inputs
- **Text Fields:** 1px solid `#E2E8F0`, `#FFFFFF` surface, `0.5rem` radius, `0.75rem 1rem` padding, font `body-md`. Placeholder in `#94A3B8`. Focus: border shifts to `#2563EB` with an ambient ring of `rgba(56, 189, 248, 0.25)`.
- **Checkboxes & Radios:** `1.125rem` square/circle, 1.5px border `#CBD5E1`. Checked state fills `#2563EB` with white checkmark glyph.

### Learning Progress Indicators
- Linear track: `0.375rem` height, background `#E2E8F0`, radius `9999px`. Filled with a gradient from `#2563EB` to `#38BDF8`.
- Syllabus Module Item: Border-l-2 accent line (`#2563EB` active, `#E2E8F0` inactive), nested in a padded vertical list displaying lesson duration and status icons.