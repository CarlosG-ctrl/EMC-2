---
name: EMC² Calculator
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c1c6d6'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8b909f'
  outline-variant: '#414754'
  surface-tint: '#adc6ff'
  primary: '#adc6ff'
  on-primary: '#002e68'
  primary-container: '#4a8eff'
  on-primary-container: '#00285c'
  inverse-primary: '#005bc0'
  secondary: '#c7c5cd'
  on-secondary: '#303036'
  secondary-container: '#4b4b51'
  on-secondary-container: '#bcbbc2'
  tertiary: '#c8c5cb'
  on-tertiary: '#303034'
  tertiary-container: '#919095'
  on-tertiary-container: '#29292d'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004493'
  secondary-fixed: '#e4e1e9'
  secondary-fixed-dim: '#c7c5cd'
  on-secondary-fixed: '#1b1b21'
  on-secondary-fixed-variant: '#46464c'
  tertiary-fixed: '#e4e1e7'
  tertiary-fixed-dim: '#c8c5cb'
  on-tertiary-fixed: '#1b1b1f'
  on-tertiary-fixed-variant: '#47464b'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '300'
    lineHeight: 72px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 44px
    fontWeight: '300'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-expression:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  keypad-symbol:
    fontFamily: Inter
    fontSize: 26px
    fontWeight: '400'
    lineHeight: 32px
    letterSpacing: 0em
  keypad-digit:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 32px
    letterSpacing: -0.01em
  keypad-utility:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 0.75rem
  margin: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style
The design system establishes a high-precision, tactile dark-mode aesthetic engineered for computational clarity and modern desktop/mobile workflows. Inspired by Cupertino industrial design and focused utilitarian instruments, the interface delivers an immediate sense of weight, premium materials, and zero visual noise.

Targeted at software engineers, designers, mathematicians, and discerning professionals, the UI evokes razor-sharp focus and tactile satisfaction. The style synthesizes **Minimalism** and **Tactile Glassmorphism**: ultra-deep carbon surfaces, micro-beveled borders mimicking matte aluminum anodization, subtle optical depth through inner top-highlights, and high-luminance electric blue keying for operators.

## Colors
The palette balances an ultra-deep stage with micro-gradations of graphite and a focused optical pop of pure electric blue.

- **Background & Canvas:** Pitch carbon black (`#0C0C0C` to `#101010`) provides absolute contrast and OLED power efficiency.
- **Surface & Panel Enclosures:** Graphite charcoal (`#18181B` to `#1A1A1A`) accented with micro-borders (`rgba(255, 255, 255, 0.08)`) that evoke milled physical hardware.
- **Keypad Surfaces (Neutral / Numerics):** Deep charcoal keycaps (`#2A2A2E`, hover `#36363B`, active `#1F1F22`).
- **Function Keys (AC, ±, %):** Cool slate steel (`#3A3A40`, hover `#47474F`, active `#2E2E33`) to visually segment computational modifiers from numerical entry.
- **Operator Keys (÷, ×, −, +):** Electric blue accent (`#3987FF`, hover `#4F95FF`, active `#2672EA`), maintaining persistent state highlights when an operator is active.
- **Execute Key (=):** Solid radiant electric blue (`#3987FF`) with stark pure white text for unambiguous terminal execution.
- **Typography & Glyphs:** `#FFFFFF` for hero readout figures; `#8E8E93` through `#A1A1AA` for operational history, tape trails, and inactive memory markers.

## Typography
Typography is strictly built around `Inter` utilizing tabular numeric figures (`font-variant-numeric: tabular-nums; font-feature-settings: "tnum" on, "zero" on;`) to ensure numbers align flawlessly during input and expression parsing.

- **Dynamic Readout Scaling:** Primary output sizes down programmatically from `64px` (`display-hero`) to `36px` when character counts exceed 9 digits, preventing edge clipping.
- **Weight Strategy:** Numerical output leverages light weights (`300`) to present a sophisticated, technical instrument aesthetic. Utility and secondary history lines step up to medium (`400`–`500`) for legibility against darker backgrounds.

## Layout & Spacing
The layout follows a compact mathematical grid engineered for zero wasted space and immediate thumb/pointer reachability.

- **Keypad Matrix:** Standard 4-column layout with fixed proportional keys. Gaps between keys are locked strictly to `0.75rem` (`12px`) to maintain key isolation without dispersing cluster density.
- **Chassis Shell:** Outer calculator housing is constrained to `360px`–`420px` width on desktop and spans full width with `1.5rem` outer page margins on mobile devices.
- **Display Stage:** Vertical stack featuring secondary calculation tape (`1.25rem` bottom padding) followed by primary output display, maintaining a distinct separation from the input key array via `1.5rem` vertical spacing.

## Elevation & Depth
Depth is created through hardware physical simulation rather than traditional drop shadows:

- **Surface Container (Chassis):** Layered with a diffuse drop shadow (`0 24px 48px -12px rgba(0, 0, 0, 0.75)`) and a delicate perimeter keyline border (`1px solid rgba(255, 255, 255, 0.08)`).
- **Physical Key Caps:** Flat surfaces with subtle tactile highlights:
  - Default: `box-shadow: inset 0 1px 0 0 rgba(255, 255, 255, 0.08), 0 2px 4px 0 rgba(0, 0, 0, 0.4)`.
  - Active/Pressed: `transform: scale(0.96); box-shadow: inset 0 1px 2px 0 rgba(0, 0, 0, 0.6)`.
- **Operator Selection:** Active operators feature a faint diffuse inner halo (`0 0 12px rgba(57, 135, 255, 0.35)`) and inverted white-on-blue key surface.
- **Frosted Backdrops:** Overlays, history panels, and settings drawers use `backdrop-filter: blur(20px)` over `rgba(24, 24, 27, 0.8)`.

## Shapes
Geometry balances organic curvature with industrial tooling accuracy:

- **Chassis Outer Bounds:** Smooth continuous rounding at `20px` to `24px` radius (`rounded-xl`), creating a modern hardware slab appearance.
- **Keycaps:** Buttons use a uniform squircle/rounded-pill radius of `16px` (`rounded-lg`) on mobile and desktop, providing a soft target that remains structured inside the rectangular 4-column grid.
- **Double-Width Key ("0"):** Retains matched `16px` corner curvature while spanning across two columns without pill morphing.

## Components

### Numeric Buttons
- **Surface:** `#2A2A2E` fill with subtle upper hairline reflection.
- **States:** Hover advances to `#36363B`; active state depresses to `#1F1F22` with a `0.96` scale transformation.
- **Type:** Centered tabular glyphs in `#FFFFFF`.

### Utility Buttons (AC, ±, %)
- **Surface:** `#3A3A40` matte slate finish.
- **States:** Hover `#47474F`, active `#2E2E33`.
- **Type:** `#D1D1D6` font weight `500` for crisp legibility.

### Arithmetic Operators (+, −, ×, ÷)
- **Default Surface:** `#3987FF` with pure white vector symbols.
- **States:** Hover shifts to `#4F95FF`; active press drops to `#2672EA`.
- **Selected State:** Remains inverted with an exterior glow (`0 0 0 1.5px #FFFFFF`) while operand input is awaited.

### Equals Key (=)
- **Surface:** High-luminance `#3987FF` solid fill.
- **Emphasis:** Anchors the bottom-right corner with enhanced micro-shadow to signal completion.

### Display Stage
- Single-line right-aligned primary output with dynamic truncation or text-scaling.
- Top aligned, low-contrast history track showing live stack operations (e.g., `1,024 × 8`).
- Direct copy-on-click trigger with brief toast indicator confirming clipboard copy.

### History Slide Panel / Tape Drawer
- Translucent slide-out surface (`rgba(20, 20, 22, 0.95)` with `backdrop-filter: blur(24px)`).
- Chronological list of calculation items with muted timestamps, click-to-restore capabilities, and a micro-segmented clear control.