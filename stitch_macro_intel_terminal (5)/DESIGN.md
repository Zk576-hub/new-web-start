---
name: Macro-Intel Dark Grid
colors:
  surface: '#131314'
  surface-dim: '#131314'
  surface-bright: '#3a393a'
  surface-container-lowest: '#0e0e0f'
  surface-container-low: '#1c1b1c'
  surface-container: '#201f20'
  surface-container-high: '#2a2a2b'
  surface-container-highest: '#353436'
  on-surface: '#e5e2e3'
  on-surface-variant: '#c1c6d7'
  inverse-surface: '#e5e2e3'
  inverse-on-surface: '#313031'
  outline: '#8b90a0'
  outline-variant: '#414755'
  surface-tint: '#adc6ff'
  primary: '#adc6ff'
  on-primary: '#002e69'
  primary-container: '#4b8eff'
  on-primary-container: '#00285c'
  inverse-primary: '#005bc1'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#ffb95f'
  on-tertiary: '#472a00'
  tertiary-container: '#ca8100'
  on-tertiary-container: '#3e2400'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004493'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#131314'
  on-background: '#e5e2e3'
  surface-variant: '#353436'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  data-mono-lg:
    fontFamily: JetBrains Mono
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1'
  data-mono-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
  label-xs:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  gutter: 12px
  margin-desktop: 24px
  margin-mobile: 16px
  container-max: 1600px
---

## Brand & Style

The design system is engineered for high-stakes institutional analysis, blending the authoritative data density of a Bloomberg Terminal with the fluid, modern interface of an AI-native workstation. It targets macroeconomists, hedge fund analysts, and quantitative researchers who require rapid information ingestion and precision control.

The aesthetic follows a **Modern Corporate** foundation enhanced by **Glassmorphism** and **High-Contrast** data visualization. The interface feels like a "mission control" center: deep, layered, and strictly functional. It prioritizes data integrity and rapid pattern recognition through a dark-only mode that reduces eye strain during extended research sessions.

**Key Visual Pillars:**
- **Institutional Authority:** Serious, dark, and uncompromisingly professional.
- **AI-Native Fluidity:** Soft glassmorphic blurs indicate the presence of the AI Copilot layer.
- **Precision Density:** Maximum data-to-ink ratio with ultra-sharp borders and monospaced quantitative values.

## Colors

The palette is anchored in **Deep Charcoal Black** to provide a high-contrast backdrop for financial data. 

- **Primary (Electric Blue):** Used for active states, primary actions, and the AI Copilot's "intelligence" indicators.
- **Secondary (Soft Emerald):** Specifically reserved for positive market movement, success states, and bullish signals.
- **Tertiary (Amber):** Used for warnings, neutral-to-cautious signals, and volatility alerts.
- **Risk (Crimson):** High-visibility red for bearish data, significant losses, or system-critical errors.
- **Neutrals:** A range of cool grays used to establish hierarchy in text and UI chrome, ensuring the data itself remains the primary focus.

## Typography

This design system utilizes a three-font strategy to differentiate between narrative analysis and raw data.

- **Headings (Hanken Grotesk):** Provides a sharp, contemporary "fintech" feel for page titles and section headers.
- **Body (Inter):** Ensures maximum legibility for long-form AI research reports and macroeconomic commentary.
- **Data (JetBrains Mono):** Monospaced fonts are mandatory for all numeric values, tickers, and time-series labels. This ensures that columns of numbers align perfectly for rapid scanning.

**Mobile Scaling:** Display titles should drop to 28px on mobile devices, while data tables should transition to a horizontal scroll or condensed card view to maintain legibility.

## Layout & Spacing

The layout utilizes a **12-column Fluid Grid** designed for high information density. 

- **Density:** Spacing is tighter than consumer apps (4px/8px increments) to maximize the amount of data visible above the fold. 
- **The Dashboard Model:** Content is organized into "Widgets" or "Panels." On desktop, these panels can span various column widths (e.g., a 4-column sidebar for AI chat and an 8-column main area for charting).
- **Responsive Behavior:** On tablet, the grid collapses to 8 columns. On mobile, it becomes a single-column 4-unit grid with 16px side margins. Horizontal scrolling is preferred for data tables on small screens over font-size reduction.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Glassmorphism** rather than traditional shadows.

- **Base Layer:** Deepest neutral (#0A0A0B).
- **Surface Layer:** Subtle elevation (#121214) with a 1px border (#262629) to define panel boundaries.
- **AI Copilot Layer:** Uses a glassmorphic treatment (12px backdrop blur, 40% opacity fill) to signify a "smart" overlay that exists above the static data.
- **Outlines:** Low-contrast ghost borders are used for interactive elements like input fields and inactive buttons. High-contrast (Primary Blue) outlines appear only on focus or active selection.

## Shapes

The shape language is primarily **Soft (0.25rem)** to maintain a disciplined, institutional appearance. 

- **Standard Elements:** Buttons, input fields, and data panels use a 4px corner radius.
- **Data Chips:** Ticker symbols and status indicators use a "Rounded-LG" (8px) radius to distinguish them from structural UI elements.
- **AI Elements:** AI-driven suggestions or floating action buttons may use a Pill-shape to denote their unique, non-tabular nature.

## Components

- **Buttons:** Primary buttons are solid Electric Blue with white text. Secondary buttons are ghost-style (border only). Tertiary buttons are text-only with monospaced labels.
- **Data Tables:** Row height is condensed (32px - 40px). Zebra striping is avoided; use 1px divider lines or hover highlights instead. Monospaced font is used for all numeric cells.
- **Input Fields:** Dark background (#0A0A0B) with a subtle 1px border. Focus state triggers an Electric Blue glow and a 1px solid border.
- **AI Research Copilot (Chat):** A persistent sidebar or modal with glassmorphic background blurs. Messages are distinct bubbles with subtle gradients to separate User from AI.
- **Market Tickers:** Scrolling marquee or horizontal list at the very top or bottom of the viewport, using monospaced green/red values for real-time price action.
- **Charts:** Line charts use a 2px stroke width with a subtle glow (bloom) effect for the primary data line. Grid lines should be faint (#1A1A1D).