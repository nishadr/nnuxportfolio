---
name: Modern Portfolio System
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
  on-surface-variant: '#c3c5d9'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8d90a2'
  outline-variant: '#434656'
  surface-tint: '#e4b88a'
  primary: '#e4b88a'
  on-primary: '#002682'
  primary-container: '#0052ff'
  on-primary-container: '#dfe3ff'
  inverse-primary: '#004ced'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#ffb4a1'
  on-tertiary: '#611300'
  tertiary-container: '#bf3003'
  on-tertiary-container: '#ffddd5'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#e4b88a'
  on-primary-fixed: '#001452'
  on-primary-fixed-variant: '#0038b6'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffdbd2'
  tertiary-fixed-dim: '#ffb4a1'
  on-tertiary-fixed: '#3c0800'
  on-tertiary-fixed-variant: '#891e00'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-xl:
    fontFamily: Inter
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label-sm:
    fontFamily: Inter
    fontSize: 12px
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
  container-max: 1280px
  gutter: 32px
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 128px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
---

## Brand & Style

This design system is built upon the principles of **Minimalism** and **Precision-driven Corporate Modernism**. It is designed to evoke a sense of professional authority, technical mastery, and editorial clarity. The target audience includes design recruiters, creative directors, and high-end stakeholders who value clarity of thought over decorative excess.

The aesthetic relies on "the beauty of the void"—using generous whitespace to frame work as if it were in a physical gallery. Visual interest is generated through perfect alignment, intentional scale shifts in typography, and a "function-first" philosophy where every element serves a navigational or informational purpose.

## Colors

The palette utilizes a high-contrast binary foundation to ensure maximum readability and a striking modern presence. 

- **Primary:** A sophisticated Deep Blue (#0052FF) serves as the primary action color, providing a sense of trust and digital fluency.
- **Secondary:** Emerald (#10B981) is used sparingly for success states, active indicators, and secondary highlights.
- **Contrast Strategy:** In dark mode, surfaces use a true-black or near-black (#0A0A0A) to let case study imagery "pop" without bezel interference. In light mode, the system transitions to a clinical gallery white (#FFFFFF). 
- **Accent Logic:** Calls to action (CTAs) should exclusively use the Primary Blue or Emerald to maintain a clear hierarchy against the monochromatic background.

## Typography

This design system utilizes **Inter** exclusively to leverage its systematic, utilitarian nature. The type scale is aggressive, creating a clear distinction between the "Display" level (used for hero headers) and the "Body" level (used for deep-dive case study analysis).

- **Case Study Body Text:** Long-form reading is prioritized. Use `body-lg` for introductions and `body-md` for standard paragraphs. 
- **Tracking:** Headlines use negative letter-spacing to appear more cohesive and "logo-like," while labels use increased tracking for legibility at small sizes.
- **Vertical Rhythm:** A strict baseline rhythm is maintained by ensuring line heights are multiples of 4px or 8px.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to ensure content remains digestible and doesn't stretch awkwardly on ultra-wide monitors.

- **The 12-Column Grid:** A standard 12-column structure is used for the case study grid. 
- **Whitespace:** Massive vertical gaps (`section-gap`) are used between major content blocks to prevent cognitive overload.
- **The "Case Study" Width:** While the hero section may span the full 1280px, body text for case studies should be constrained to a 8-column center-aligned width (approx. 800px) to maintain an ideal character count per line (CPL).

## Elevation & Depth

To maintain a "Clean Line" aesthetic, this design system avoids heavy drop shadows. Instead, it uses **Tonal Layers** and **Low-Contrast Outlines**.

- **Surfaces:** In dark mode, secondary surfaces (like cards) use a slightly lighter grey (#1A1A1A) than the background (#0A0A0A). 
- **Borders:** Elements are defined by 1px solid borders. In light mode, use a very faint grey (#E5E5E5). In dark mode, use a subtle charcoal (#262626).
- **Interactive States:** Lift is communicated via subtle scale transforms (e.g., 1.02x) or by changing the border color to the Primary Blue, rather than adding a shadow.

## Shapes

The shape language is **Soft** and architectural. 

- **Radius:** A consistent 0.25rem (4px) radius is applied to buttons, input fields, and small UI components. 
- **Cards:** Larger containers like case study cards use `rounded-lg` (8px) to soften the overall grid.
- **Buttons:** CTAs are rectangular with slight rounding; they should never be fully pill-shaped, as the sharp corners align better with the "Professional" aesthetic.

## Components

### Navigation & Toggle
The navigation bar is a "Sticky Blur" component. It uses a backdrop-filter (blur) to maintain context while scrolling. The dark/light toggle is a simple icon switch (Sun/Moon) placed at the far right, maintaining a minimal footprint.

### Hero Section
The Hero uses `display-xl` type. It should be stripped of all imagery to focus on a bold value proposition statement, using the Primary accent color for one or two key words.

### Case Study Cards
Cards are image-first. The typography (Title and Category) sits below the image. On hover, the image should subtly scale up within its container, and the border color should transition to the Primary Blue.

### Accessible Contact Forms
Inputs use a "floating label" or a persistent top-aligned label for accessibility. The border-bottom is emphasized over the full box to maintain a clean, airy feel. Focus states must use a high-visibility Primary Blue outline.

### Case Study Typography
Case studies must utilize:
- **Blockquotes:** Large-scale, primary-colored text for key insights.
- **Ordered Lists:** Bold numbers to denote process steps.
- **Captions:** `label-sm` centered under all process artifacts and images.
