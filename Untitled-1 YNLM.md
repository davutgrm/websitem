---
name: Precision Automation System
colors:
  surface: '#111318'
  surface-dim: '#111318'
  surface-bright: '#37393e'
  surface-container-lowest: '#0c0e12'
  surface-container-low: '#1a1c20'
  surface-container: '#1e2024'
  surface-container-high: '#282a2e'
  surface-container-highest: '#333539'
  on-surface: '#e2e2e8'
  on-surface-variant: '#c2c6d6'
  inverse-surface: '#e2e2e8'
  inverse-on-surface: '#2f3035'
  outline: '#8c909f'
  outline-variant: '#424754'
  surface-tint: '#adc6ff'
  primary: '#adc6ff'
  on-primary: '#002e6a'
  primary-container: '#4d8eff'
  on-primary-container: '#00285d'
  inverse-primary: '#005ac2'
  secondary: '#bcc7de'
  on-secondary: '#263143'
  secondary-container: '#3e495d'
  on-secondary-container: '#aeb9d0'
  tertiary: '#b7c8e1'
  on-tertiary: '#213145'
  tertiary-container: '#8292aa'
  on-tertiary-container: '#1a2b3e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#d8e3fb'
  secondary-fixed-dim: '#bcc7de'
  on-secondary-fixed: '#111c2d'
  on-secondary-fixed-variant: '#3c475a'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#111318'
  on-background: '#e2e2e8'
  surface-variant: '#333539'
typography:
  h1:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  h3:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0em
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0em
  label-sm:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.02em
  footer:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0em
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
  gutter: 16px
  container-max: 1280px
---

## Brand & Style

The design system is built for a high-performance automation agency where efficiency and technical rigor meet premium service. The brand personality is rooted in reliability and sophistication, aiming to evoke a sense of "quiet power"—complex technology delivered through a simple, high-end interface.

Drawing from **Corporate Minimalism**, this design system avoids decorative flourishes in favor of structural integrity. It utilizes a dark-mode-first aesthetic to reduce eye strain and emphasize the luminous blue accent, creating a workspace that feels like a professional mission control center. The visual language is intentionally compact to facilitate dense information architecture without sacrificing clarity.

## Colors

The palette is anchored by a deep, monochromatic foundation. The primary background (#0A0C10) provides a void-like depth that allows white typography and blue accents to pop with high contrast. 

The **Accent Blue (#3B82F6)** is used sparingly for interactive elements, status indicators, and primary calls to action, ensuring it retains its impact as a "signal" color. Secondary neutrals are utilized for borders and surface layering to distinguish between different functional zones of the UI without relying on heavy shadows.

## Typography

This design system utilizes **Manrope** for its technical yet approachable character. The hierarchy is intentionally restrained; headers are kept compact to allow for more content density, while the body text is slightly enlarged to 18px to ensure effortless legibility against the dark background.

Standardization of line heights is critical here to maintain the "compact" feel. Tight tracking is applied to headlines to give them a modern, editorial edge, while body copy maintains a generous line height (1.6) to prevent text blocks from feeling cramped.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model with a 12-column structure, optimized for desktop productivity. Spacing is governed by a strict 4px baseline grid, favoring "md" (16px) and "lg" (24px) increments to keep elements tightly grouped.

To achieve the requested compact feel, vertical margins between sections are reduced, relying on clear borders and subtle background shifts rather than large gaps of empty space to define hierarchy. Components should utilize internal padding that is consistent across all card types to maintain a rhythmic visual flow.

## Elevation & Depth

In this design system, depth is conveyed through **Low-Contrast Outlines** and **Tonal Layering** rather than traditional shadows. This creates a "flat-premium" look that feels more modern and technical.

- **Level 0 (Base):** The primary background (#0A0C10).
- **Level 1 (Surface):** A slightly lighter navy (#111827) used for cards and containers, defined by a 1px solid border (#1F2937).
- **Level 2 (Interaction):** Hover states use a subtle inner glow or a brightness shift. 
- **Backdrop Blurs:** When modals are necessary, a heavy backdrop blur (20px) is used to maintain context without adding visual clutter.

## Shapes

The shape language is precise and geometric. A **Soft (Level 1)** roundedness is applied throughout the system, giving elements a 4px to 8px corner radius. This subtle rounding softens the technical edge of the interface just enough to feel professional and modern without appearing "bubbly" or consumer-grade.

Buttons, input fields, and cards all share this identical radius to reinforce a sense of system-wide unity.

## Components

### Buttons
Primary buttons utilize a solid Blue (#3B82F6) fill with white text. Hover effects should involve a subtle scale-down (98%) and a slight brightening of the background color. Secondary buttons use a ghost style with a 1px border.

### Cards
Cards are the primary organizational unit. They feature a #111827 background with a #1F2937 border. Internal padding is fixed at 24px (lg).

### Input Fields
Inputs are dark-filled with a subtle border. On focus, the border transitions to the primary blue with a 2px outer "ring" (at 20% opacity) to provide clear feedback for automation workflows.

### Chips & Tags
Used for status indicators (e.g., "Active", "Pending"). These should be compact, using 12px Manrope SemiBold, with low-opacity blue backgrounds to keep them secondary to the main content.

### Data Tables
Given the agency focus, tables are clean with no vertical lines; only horizontal separators in #1F2937 are used to maintain a horizontal reading rhythm. Row heights are kept compact (48px).