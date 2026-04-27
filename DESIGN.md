---
name: Sci-Fi World Digital Archive
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1c1b1d'
  surface-container: '#201f21'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e5e1e4'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#e5e1e4'
  inverse-on-surface: '#313032'
  outline: '#849495'
  outline-variant: '#3a494b'
  surface-tint: '#00dbe7'
  primary: '#e1fdff'
  on-primary: '#00363a'
  primary-container: '#00f2ff'
  on-primary-container: '#006a71'
  inverse-primary: '#00696f'
  secondary: '#ebb2ff'
  on-secondary: '#520072'
  secondary-container: '#b600f8'
  on-secondary-container: '#fff6fc'
  tertiary: '#f8f7f7'
  on-tertiary: '#2f3131'
  tertiary-container: '#dbdbdb'
  on-tertiary-container: '#5f6060'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#74f5ff'
  primary-fixed-dim: '#00dbe7'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#f8d8ff'
  secondary-fixed-dim: '#ebb2ff'
  on-secondary-fixed: '#320047'
  on-secondary-fixed-variant: '#74009f'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c6'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131315'
  on-background: '#e5e1e4'
  surface-variant: '#353437'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 4rem
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 2.5rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 1.5rem
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.7'
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.15em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin: 48px
  container-max: 1440px
---

## Brand & Style
The design system is engineered to evoke the sensation of a high-end, near-future operating system. It targets a sophisticated audience seeking an immersive, cinematic experience that feels like navigating a secured data archive.

The visual style is a hybrid of **Glassmorphism** and **High-Contrast Technicality**. It prioritizes atmospheric depth through the use of translucent layers and vibrant light-emitting accents. The aesthetic is clean and functional, avoiding unnecessary clutter in favor of precision-engineered UI elements that feel like physical light projections.

## Colors
The palette is rooted in the void of deep space. The primary background is a rich, matte black (#0a0a0c), while nested containers utilize midnight navy (#101218) to create structural hierarchy. 

Accents function as light sources: 
- **Glowing Cyan** is the primary interaction and data-state color.
- **Electric Purple** is used for secondary highlights, editorial categories, and rare interactive states.
- **Metallic Silver** provides high-legibility contrast for labels and inactive structural elements.
- **Gradients** should primarily move from cyan to purple at a 45-degree angle for hero elements.

## Typography
This design system employs a dual-font strategy to balance futuristic character with extreme readability. 

**Space Grotesk** is used for headlines and technical labels to provide a geometric, cutting-edge feel. For technical metadata, it should be used in all-caps with increased letter spacing.

**Inter** serves as the primary workhorse for long-form editorial content. Its neutral, utilitarian structure ensures that the "digital archive" feel remains functional and easy on the eyes during extended reading sessions.

## Layout & Spacing
The layout follows a **Fixed Grid** model within a maximum container width of 1440px to maintain a cinematic aspect ratio. A 12-column grid is used for content organization, with generous 48px margins that act as a "frame" for the interface.

A 4px base unit governs all spacing, ensuring a mathematical rhythm. Elements should be aligned to a visible but subtle 10% opacity grid overlay when possible to reinforce the technical nature of the design system.

## Elevation & Depth
Depth is conveyed through **Glassmorphism** rather than traditional drop shadows. Surfaces use backdrop blurs (20px to 40px) and semi-transparent fills of the midnight navy (#101218) at 60-80% opacity.

Hierarchy is further defined by:
- **Inner Glows:** 1px borders with a 4px blur in cyan or purple create the effect of light bleeding from the edges.
- **Data-Stream Lines:** Ultra-thin (0.5pt) metallic silver lines that run horizontally or vertically across the UI to connect related modules.
- **Z-Axis Stacking:** Higher-level elements (like modals or hovering cards) should have a slightly lighter background tint and more intense backdrop blur.

## Shapes
The shape language is precise and controlled. A **Soft** roundedness level (0.25rem) is used for standard interactive elements to maintain a modern, high-end feel without appearing "bubbly." 

For a more aggressive technical look, use clipped corners (chamfers) at 45-degree angles on large layout containers or primary action buttons.

## Components
### Buttons
Buttons are defined by 1px solid borders in Cyan or Purple. They feature a subtle inner glow. On hover, the button should fill with a low-opacity version of the accent color, and the outer glow should expand.

### Story Cards
Cards utilize a heavy backdrop blur (Glassmorphism). The top border should be a 2px "data-line" in Cyan or Silver. Typography within cards should be strictly aligned to the left, using the `label-caps` style for categories.

### Input Fields
Inputs are minimal, consisting of a bottom-only border in Metallic Silver that glows Cyan when focused. Use monospaced-style fonts for user input to maintain the technical archive aesthetic.

### Data Stream Dividers
Vertical or horizontal lines used to separate sections. These should be 0.5px thick, colored Metallic Silver at 30% opacity, with occasional "nodes" (2x2px squares) placed at intersections.

### Progress & Status Indicators
Utilize "scanline" animations—a horizontal light beam that moves vertically across a component—to indicate loading or active data processing.