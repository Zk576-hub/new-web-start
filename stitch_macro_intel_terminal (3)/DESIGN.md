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
    fontFamily: JetBrains Mono
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: JetBrains Mono
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: JetBrains Mono
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: JetBrains Mono
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  data-mono:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.02em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
  panel-gap: 1px
---

## Brand & Style

The design system is engineered to evoke the high-stakes, high-precision environment of institutional quantitative finance. It positions the product as a "personal hedge-fund analyst," blending the authority of traditional Bloomberg terminals with the fluidity of next-generation AI interfaces.

The aesthetic is **Futuristic Glassmorphism**. It utilizes deep, layered depth to organize complex data hierarchies without overwhelming the user. The UI feels "expensive" through the use of micro-interactions, subtle luminescence, and a strict adherence to a "dark mode first" philosophy. It avoids the clutter of legacy finance software, opting instead for a breathable, high-contrast, and hyper-modern workspace that feels both cutting-edge and impeccably secure.

## Colors

The palette is anchored in a multi-layered dark spectrum to reduce eye strain during long research sessions.

- **Primary (Electric Blue):** Used for actionable insights, AI status indicators, and focus states. It should possess a subtle outer glow (bloom) to simulate a high-end display terminal.
- **Surface Palette:** The base is a deep charcoal (#0a0a0b). Panels use varying opacities of Slate Gray with backdrop blurs to create the glass effect.
- **Functional Semantic Colors:** Success (Soft Emerald), Warning (Amber), and Risk (Crimson) are desaturated slightly to remain sophisticated, only reaching full saturation during critical alerts.
- **Gradients:** Use linear gradients from Primary to a deeper navy for headers and "AI Thinking" states.

## Typography

This design system uses a dual-font strategy to balance technical precision with readability.

- **JetBrains Mono:** Employed for all "Hard Data"—headlines, tickers, numbers, and AI-generated code snippets. It provides the "terminal" feel and ensures numerical alignment (tabular figures) is perfect.
- **Inter:** Used for "Narrative Content"—AI research summaries, news feeds, and long-form reports. It provides a clean, neutral balance to the technicality of the monospaced font.
- **Styling:** Headlines should use a slight negative letter spacing to feel "tighter" and more authoritative. Labels should be uppercase with wide tracking for a high-end architectural feel.

## Layout & Spacing

The layout is a **3-panel professional workspace** designed for high-density information.

- **Desktop:** A sticky left navigation (collapsed to icons), a primary research "Stage" (center), and a contextual "Intelligence Insight" panel (right).
- **Mobile:** A vertical stack using "Sheets." The primary data remains fixed while the AI insights slide up from the bottom as a high-density overlay.
- **Spacing Rhythm:** Based on a 4px grid. Use 1px "gaps" between panels with a subtle border-image gradient to create the appearance of "laser-cut" glass panes. 
- **Density:** Elements are packed tightly but separated by light and shadow rather than heavy margins to maximize data visible on one screen.

## Elevation & Depth

Visual hierarchy is achieved through **Backdrop Blurs and Inner Glows** rather than traditional drop shadows.

- **Level 1 (Base):** Deep Charcoal (#0a0a0b).
- **Level 2 (Panels):** Slate Gray with 40% opacity and a 20px backdrop blur. A 1px border with 10% white opacity creates a "rim light" effect.
- **Level 3 (Modals/Popovers):** Higher opacity (60%) with a subtle Primary Color outer glow (bloom: 0px 0px 15px rgba(0, 162, 255, 0.2)).
- **Transitions:** Use "spring" physics for panel expansions. AI responses should "stream" in with a fade-in-and-slide-up animation for each paragraph.

## Shapes

The shape language is **Soft-Technical**. We use small radii to maintain a professional, sharp look while avoiding the "aggression" of 90-degree corners.

- **Default (0.25rem):** Used for input fields, buttons, and small data cards.
- **Large (0.5rem):** Used for main workspace panels and modals.
- **Pill:** Reserved exclusively for status indicators (e.g., "Market Open") and AI tags.

## Components

- **Buttons:** Primary buttons use a solid Electric Blue to Black gradient with an inner 1px highlight on the top edge. Ghost buttons use the "rim light" border style.
- **Data Cards:** Glassmorphic containers with a "monospace header" and a "sparkline" chart integrated into the background.
- **Input Fields:** Bottom-border only or very subtle 4-sided borders. Upon focus, the border glows with the Primary color.
- **AI Chat Interface:** Messages appear in "bubbles" that lack a solid background, instead using a left-accent border color to denote the speaker (Blue for AI, Slate for User).
- **Tickers:** Horizontal scrolling data strips at the very top or bottom of the screen with "Pulse" animations for real-time price changes.
- **Risk Gauges:** Circular progress indicators using the Crimson to Emerald spectrum to visualize portfolio volatility.