---
name: Aurora AI Research Terminal
colors:
  surface: '#0f1419'
  surface-dim: '#0f1419'
  surface-bright: '#353a40'
  surface-container-lowest: '#0a0f14'
  surface-container-low: '#171c22'
  surface-container: '#1b2026'
  surface-container-high: '#262a30'
  surface-container-highest: '#30353b'
  on-surface: '#dfe3eb'
  on-surface-variant: '#bec7d4'
  inverse-surface: '#dfe3eb'
  inverse-on-surface: '#2c3137'
  outline: '#89919d'
  outline-variant: '#3f4852'
  surface-tint: '#99cbff'
  primary: '#99cbff'
  on-primary: '#003355'
  primary-container: '#00a2ff'
  on-primary-container: '#003659'
  inverse-primary: '#00629d'
  secondary: '#b7c8e1'
  on-secondary: '#213145'
  secondary-container: '#3a4a5f'
  on-secondary-container: '#a9bad3'
  tertiary: '#ffb77d'
  on-tertiary: '#4d2600'
  tertiary-container: '#ea8001'
  on-tertiary-container: '#512900'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#cfe5ff'
  primary-fixed-dim: '#99cbff'
  on-primary-fixed: '#001d34'
  on-primary-fixed-variant: '#004a78'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#ffdcc3'
  tertiary-fixed-dim: '#ffb77d'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6e3900'
  background: '#0f1419'
  on-background: '#dfe3eb'
  surface-variant: '#30353b'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.5'
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.6'
  data-lg:
    fontFamily: JetBrains Mono
    fontSize: 16px
    fontWeight: '500'
    lineHeight: '1.4'
  data-md:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: '1.4'
  data-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '400'
    lineHeight: '1.2'
  label-caps:
    fontFamily: Geist
    fontSize: 10px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.08em
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
  gutter: 12px
  margin: 16px
---

## Brand & Style
This design system is built for elite financial analysts and quantitative researchers who require a high-performance, institutional-grade interface. The brand personality is authoritative, precise, and technologically advanced, evoking the feeling of a sophisticated "command center" for global markets.

The aesthetic blends the data-rich density of traditional financial terminals with the sleek, refined minimalism of modern developer tools. It utilizes a **Glassmorphic** approach layered over a deep, dark canvas, creating a sense of depth and focus. Visual elements are sharp and intentional, prioritizing rapid data ingestion and clarity under pressure. The emotional response is one of controlled power and absolute reliability.

## Colors
The palette is rooted in a deep charcoal foundation to minimize eye strain during extended research sessions. The primary electric blue is used sparingly but impactfully to denote interactive states, primary actions, and active data streams.

- **Primary:** Electric Blue (#00a2ff) for focus and high-priority interactions.
- **Surface:** A series of tiered charcoal and slate grays are used to create structural hierarchy. 
- **Semantic:** Success and Danger colors are calibrated for high legibility against dark backgrounds, using vibrant greens and reds for instant trend recognition.
- **Overlays:** Semi-transparent slate grays are utilized for glassmorphic panels, ensuring the background remains visible while maintaining text contrast.

## Typography
The typographic system employs a dual-font strategy. **Geist** serves as the primary UI font, providing a clean, modern, and highly legible framework for navigation, headings, and instructional text. **JetBrains Mono** is reserved exclusively for financial data, ticker symbols, code snippets, and tabular information.

The use of monospaced fonts for data ensures that numerical values align perfectly in columns, facilitating rapid visual comparison of market movements. High information density is achieved by using smaller-than-average base font sizes (13px/14px) with generous line heights to maintain readability.

## Layout & Spacing
This design system utilizes a **Fluid Grid** model optimized for ultra-wide monitors and multi-window setups. The spacing rhythm is based on a strict 4px baseline grid to ensure mathematical precision in element alignment.

- **Desktop:** A 12-column or 24-column grid depending on the analytical complexity. Gutters are kept tight (12px) to maximize the "data-per-pixel" ratio.
- **Panels:** The layout relies on resizable sidebars and persistent utility docks. 
- **Density:** Padding within data tables and charts is minimal, favoring horizontal scanning. Information is grouped into logical modules separated by thin, low-contrast dividers.

## Elevation & Depth
Depth is conveyed through a combination of **Glassmorphism** and **Tonal Layering**. Unlike consumer apps that use heavy drop shadows, this system uses subtle inner glows and border highlights to simulate light hitting the edges of glass panels.

- **Base Layer:** The deepest charcoal (#0a0c10).
- **Surface Layer:** Background blur (20px to 40px) with a semi-transparent fill (#161b22 at 60% opacity).
- **Edge Treatment:** 1px solid borders in Slate Gray (#64748b at 20% opacity) define the boundaries of each module.
- **Active State:** Elements in focus or active "cards" receive a subtle 1px Electric Blue top-border or an outer "bloom" effect rather than a traditional shadow.

## Shapes
The shape language is disciplined and geometric. A "Soft" approach is used, with small 4px radii (`roundedness: 1`) applied to main containers and buttons. This provides a hint of modern refinement without sacrificing the professional, "hard-edged" feel of an institutional tool.

Interactive elements like tags or status indicators may use a slightly higher radius for distinction, but circles and large pills are avoided to maintain the technical aesthetic.

## Components
- **Buttons:** Primary buttons are solid Electric Blue with white text. Secondary buttons use a ghost style with a subtle slate border that illuminates on hover.
- **Data Tables:** High-density rows with alternating subtle fills. Sorting headers utilize monospaced labels. Cells containing negative values are automatically tinted red.
- **Input Fields:** Recessed, dark backgrounds with a 1px border that glows Electric Blue when focused. Labels are positioned as tiny caps above the field.
- **Chips/Badges:** Used for tickers and status. Tickers use a monospaced font; status badges (e.g., "Live", "Closed") use a small dot indicator and Geist sans-serif.
- **Cards:** Glassmorphic containers with a 1px border. Header areas are strictly separated by a horizontal rule.
- **Terminal Input:** A specialized command-line component at the bottom of the interface for power users, utilizing JetBrains Mono and a pulsing cursor.