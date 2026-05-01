---
name: Botanical Alchemy
colors:
  surface: '#0c1607'
  surface-dim: '#0c1607'
  surface-bright: '#323c29'
  surface-container-lowest: '#071103'
  surface-container-low: '#141e0e'
  surface-container: '#182212'
  surface-container-high: '#232d1b'
  surface-container-highest: '#2d3825'
  on-surface: '#dae7cc'
  on-surface-variant: '#c5c8bc'
  inverse-surface: '#dae7cc'
  inverse-on-surface: '#293321'
  outline: '#8e9287'
  outline-variant: '#44483f'
  surface-tint: '#b7cea0'
  primary: '#b7cea0'
  on-primary: '#233515'
  primary-container: '#394c29'
  on-primary-container: '#a5bc8f'
  inverse-primary: '#50643f'
  secondary: '#ddc490'
  on-secondary: '#3d2e07'
  secondary-container: '#58471e'
  on-secondary-container: '#ceb683'
  tertiary: '#f9b981'
  on-tertiary: '#4b2700'
  tertiary-container: '#673c0e'
  on-tertiary-container: '#e5a871'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d3eabb'
  primary-fixed-dim: '#b7cea0'
  on-primary-fixed: '#0f2003'
  on-primary-fixed-variant: '#394c29'
  secondary-fixed: '#fae0a9'
  secondary-fixed-dim: '#ddc490'
  on-secondary-fixed: '#251a00'
  on-secondary-fixed-variant: '#56441c'
  tertiary-fixed: '#ffdcc0'
  tertiary-fixed-dim: '#f9b981'
  on-tertiary-fixed: '#2d1600'
  on-tertiary-fixed-variant: '#683c0e'
  background: '#0c1607'
  on-background: '#dae7cc'
  surface-variant: '#2d3825'
typography:
  headline-xl:
    fontFamily: Newsreader
    fontSize: 4.5rem
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 3rem
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Newsreader
    fontSize: 2.25rem
    fontWeight: '600'
    lineHeight: '1.3'
  subtitle-lg:
    fontFamily: Manrope
    fontSize: 1.25rem
    fontWeight: '700'
    lineHeight: '1.5'
    letterSpacing: 0.1em
  subtitle-md:
    fontFamily: Manrope
    fontSize: 1rem
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Noto Serif
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.7'
  body-md:
    fontFamily: Noto Serif
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Manrope
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-edge: 40px
  section-gap: 120px
  element-gap: 16px
---

## Brand & Style

This design system is built upon the intersection of ancestral wisdom and peak human performance. It conveys a sense of "Botanical Alchemy"—where raw, grounded nature meets high-end, scientific precision. The brand personality is professional and powerful, yet deeply connected to the earth.

The design style follows **Tactile Minimalism**. It utilizes heavy whitespace and clean layouts common in modern minimalism but introduces subtle organic textures and a rich, earthy color palette to create a physical, grounded feeling. The goal is to evoke the sensation of a luxury apothecary: clean, authoritative, and timeless. The interface should feel like an invitation to a high-performance ritual, emphasizing quality and depth over fleeting trends.

## Colors

The palette is rooted in the natural world, using high-contrast pairings to signify both growth and sophistication. 

- **Ancestral Green (#394C29):** The foundation of the design system. It acts as the primary dark background, providing a deep, forest-like atmosphere that suggests stability and ancient knowledge.
- **Erva-Doce Beige (#EBD19C):** Used for secondary backgrounds and primary text on dark surfaces. It provides a soft, parchment-like contrast that is easier on the eyes than pure white.
- **Ritual Terracotta (#B37C49):** The active accent color. Reserved for primary actions and buttons, it represents the transformative fire of alchemy and the red earth.
- **Deep Neutral (#1A2413):** A darker shade of the primary green used for deep shadows and UI elements that require further recession in the visual stack.

## Typography

The typographic hierarchy balances editorial elegance with functional clarity.

- **Titles (Newsreader):** Chosen for its high-contrast serifs that mirror the "Black/Serif" weight of Fraunces. It commands authority and feels like a masthead for a luxury journal.
- **Subtitles (Manrope):** A modern, geometric sans-serif that substitutes Montserrat. It is used in all-caps with generous letter spacing to provide a professional, clean contrast to the serif headings.
- **Body Text (Noto Serif):** A refined serif that ensures long-form readability. It maintains the sophisticated, literary tone established by the headlines.

Use high-contrast sizing to create a clear vertical rhythm. Large headlines should be set with tight leading, while body text requires generous line heights to feel open and breathable.

## Layout & Spacing

This design system employs a **Fixed Grid** model to maintain a controlled, editorial feel. The layout is centered on a 12-column grid with a maximum container width of 1280px. 

Large-scale vertical spacing (Section Gaps) should be used aggressively to create a "gallery" effect, where each piece of content has room to breathe. Internal component spacing follows an 8px base unit. Margins at the edges of the screen should be substantial (40px+) to frame the content, reinforcing the premium nature of the brand.

## Elevation & Depth

Depth is achieved through **Tonal Layering** rather than traditional drop shadows. Because the primary background is a deep green, elevation is indicated by subtle shifts in lightness and opacity.

- **Surface Levels:** The primary background is the lowest level. Secondary containers use a slightly lighter tint of green or a low-opacity overlay of Erva-Doce Beige.
- **Tactile Details:** Elements like cards or buttons may use a 1px "inner glow" or a very soft, tinted ambient shadow (using the Ritual Terracotta color at 10% opacity) to suggest they are physically resting on the surface.
- **Glassmorphism:** Use backdrop blurs sparingly on navigation bars or modal overlays to maintain a modern, "high-performance" edge without losing the grounded, natural feel.

## Shapes

The shape language is **Soft (Level 1)**. 

While the brand is rooted in nature, it is also professional and scientific. Sharp corners are avoided to keep the feel organic, but high roundedness (pills) is avoided to prevent the UI from appearing too casual or "bubbly." A subtle 0.25rem (4px) radius on buttons and 0.5rem (8px) on cards provides a structured yet approachable silhouette. Larger containers, such as hero images or section blocks, may use larger radii (0.75rem) to mimic the soft edges of river stones or botanical leaves.

## Components

### Buttons
Primary buttons use the **Ritual Terracotta** background with Erva-Doce Beige text in bold, uppercase Manrope. They should have a slight inner-top shadow to appear tactile. Secondary buttons are "Ghost" style, using an Erva-Doce Beige border and text.

### Input Fields
Inputs are dark-themed, using a deep green stroke that brightens to Erva-Doce Beige on focus. Labels are always positioned above the field in uppercase Manrope.

### Cards
Cards are used to house botanical profiles or performance metrics. They should have no visible border, instead using a slightly lighter green surface than the primary background. Subtle 1px borders in low-opacity beige can be used to define boundaries on very complex screens.

### Chips & Tags
Used for "Ingredients" or "Performance Benefits." These should be small, pill-shaped elements with Erva-Doce Beige backgrounds and dark green text, creating a high-contrast, "label" effect.

### Imagery
Images should feature high-contrast photography of botanicals or human movement, using deep shadows and natural lighting. Avoid stock-style brightness; lean into "Chiaroscuro" (light/dark) effects.