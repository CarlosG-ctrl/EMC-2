---
name: Executive Precision
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
  on-surface-variant: '#434655'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#006242'
  on-tertiary: '#ffffff'
  tertiary-container: '#007d55'
  on-tertiary-container: '#bdffdb'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.005em
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  title-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
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
  gutter-sm: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

The design system projects clarity, control, and calm efficiency. Designed for small business owners and sales leads navigating pipeline volume, customer interactions, and high-stakes conversion cycles, the interface removes cognitive friction in favor of structural legibility.

### Design Style & Philosophy
The aesthetic is **Modern Minimalist SaaS** anchored by architectural discipline:
- **Clean Whitespace:** Intentional negative space frames high-density business metrics without clutter.
- **Structural Contrast:** A deeply grounded dark slate sidebar anchors the application frame, establishing immediate focus on the main workspace.
- **Restraint Over Decoration:** High-fidelity data tables, pipeline boards, and contact timelines prioritize data scannability over ornamental graphics.

## Colors

The palette balances utility and focus:

- **Primary (`#2563EB`):** High-energy electric sapphire dedicated exclusively to primary actions, selected navigation states, active toggles, and conversion paths.
- **Secondary (`#0F172A`):** Deep oceanic obsidian providing structural density for the persistent global sidebar, modals headers, and primary typographic weight.
- **Tertiary (`#10B981`):** Precision emerald green used strictly for positive momentum—won deals, revenue velocity, and healthy lead scores.
- **Neutral (`#64748B`):** Cool slate gray balancing intermediate text, icons, gridlines, and inactive components.

### Surfaces & Backgrounds
- **App Canvas:** `#F8FAFC` (Slate 50) delivers a soft, glare-free working background.
- **Card & Data Surfaces:** `#FFFFFF` (Pure White) with subtle `#E2E8F0` borders creates clear spatial separation.
- **Navigation Canvas:** `#0F172A` (Slate 900) isolates administrative context from active record editing.

## Typography

Inter serves as the single typographic voice across all viewports to ensure uniform tracking, rendering sharpness, and micro-metric clarity. Numerical tabular alignment (`tnum`) should be enabled across pipeline deal boards, currency columns, and analytics counters.

## Layout & Spacing

The layout uses an asymmetric fluid grid anchored by a fixed 260px desktop navigation rail.

- **Desktop (1024px+):** Fluid content container with `margin: 2rem` and 12-column layout. Gutter width stays fixed at `1.5rem` (`24px`).
- **Tablet (768px - 1023px):** Collapsible sidebar rail (reduced to 72px icon rail), 8-column layout, and `margin: 1.5rem`.
- **Mobile (<768px):** Single-column layout with off-canvas slideover navigation, `margin: 1rem`, and sticky top context header.

## Elevation & Depth

Visual hierarchy uses flat surfaces separated by hairline borders, complemented by low-opacity, atmospheric drop shadows:

- **Base Canvas:** Flat `#F8FAFC`, zero shadow.
- **Card / Surface Default:** `#FFFFFF` with a 1px border (`#E2E8F0`) and an ambient micro-shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.02)`.
- **Interactive Card (Hover):** Border transitions to `#CBD5E1` with elevated depth: `0 4px 6px -1px rgba(15, 23, 42, 0.06), 0 2px 4px -2px rgba(15, 23, 42, 0.04)`.
- **Overlays & Modals:** Borderless with deep atmospheric elevation: `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.06)`.
- **Global Sidebar:** Positioned at elevation-0 with a right vertical border (`#1E293B`) anchoring the workspace.

## Shapes

The design uses balanced curves to balance professional precision with modern software ergonomics:

- **Inputs, Buttons, and Selects:** `0.5rem` (8px, `rounded-md`/`rounded-lg`) for compact touch targets and crisp borders.
- **Cards, Panels, and Modals:** `0.75rem` to `1rem` (12px to 16px, `rounded-xl`) to frame segmented data visually.
- **Pills & Status Chips:** Fully circular (`rounded-full`) to contrast against rectilinear data rows.

## Components

### Buttons
- **Primary:** Solid `#2563EB`, text `#FFFFFF`, font weight 500, radius `0.5rem`. Hover state shifts to `#1D4ED8`. Focus ring: 2px offset with `#93C5FD`.
- **Secondary:** Surface `#FFFFFF`, border 1px solid `#E2E8F0`, text `#0F172A`. Hover shifts background to `#F8FAFC`.
- **Ghost / Tertiary:** No fill, text `#64748B`. Hover fill `#F1F5F9`, text `#0F172A`.

### Input Fields & Selects
- Height: 40px standard (36px for dense tables).
- Surface: `#FFFFFF`, border: 1px solid `#CBD5E1`.
- Typography: `body-md` (`#0F172A`), placeholder `#94A3B8`.
- Focus state: Border transitions to `#2563EB` with `0 0 0 3px rgba(37, 99, 235, 0.15)`.

### Badges & Status Chips
- Height: 24px, pill-shaped (`rounded-full`), padding: 0 10px.
- **Success / Won:** Surface `#ECFDF5`, text `#065F46`, 1px solid `#A7F3D0`.
- **Lead / Prospect:** Surface `#EFF6FF`, text `#1E40AF`, 1px solid `#BFDBFE`.
- **Neutral / Draft:** Surface `#F1F5F9`, text `#475569`, 1px solid `#E2E8F0`.

### Cards & Metrics
- Background `#FFFFFF`, 1px border `#E2E8F0`, padding `1.5rem`.
- KPI blocks pair `label-md` tracking labels above high-contrast `headline-md` metrics with tertiary velocity badges.

### Lists & Data Tables
- Header row: Surface `#F8FAFC`, uppercase `label-sm` text (`#64748B`), 1px bottom border `#E2E8F0`.
- Data rows: 52px fixed height, alternating row hover `#F8FAFC`, bottom divider `#F1F5F9`.

### Pipeline Deal Stage Board
- Column background `#F1F5F9`, rounded `0.75rem`, padding `0.75rem`.
- Deal cards within columns: Solid white, micro-shadow, 1px border `#E2E8F0`, with drag-state elevation token.