---
name: Floribelle Knots
colors:
  surface: '#fbfbe2'
  surface-dim: '#dbdcc3'
  surface-bright: '#fbfbe2'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f5dc'
  surface-container: '#efefd7'
  surface-container-high: '#eaead1'
  surface-container-highest: '#e4e4cc'
  on-surface: '#1b1d0e'
  on-surface-variant: '#514346'
  inverse-surface: '#303221'
  inverse-on-surface: '#f2f2d9'
  outline: '#837376'
  outline-variant: '#d5c2c5'
  surface-tint: '#844f5d'
  primary: '#844f5d'
  on-primary: '#ffffff'
  primary-container: '#e6a4b4'
  on-primary-container: '#693846'
  inverse-primary: '#f8b4c4'
  secondary: '#4f6359'
  on-secondary: '#ffffff'
  secondary-container: '#d2e8dc'
  on-secondary-container: '#55695f'
  tertiary: '#725858'
  on-tertiary: '#ffffff'
  tertiary-container: '#cfaeae'
  on-tertiary-container: '#594141'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9e1'
  primary-fixed-dim: '#f8b4c4'
  on-primary-fixed: '#350d1b'
  on-primary-fixed-variant: '#693846'
  secondary-fixed: '#d2e8dc'
  secondary-fixed-dim: '#b6cbc0'
  on-secondary-fixed: '#0c1f18'
  on-secondary-fixed-variant: '#384b42'
  tertiary-fixed: '#fedada'
  tertiary-fixed-dim: '#e0bfbf'
  on-tertiary-fixed: '#291617'
  on-tertiary-fixed-variant: '#594141'
  background: '#fbfbe2'
  on-background: '#1b1d0e'
  surface-variant: '#e4e4cc'
typography:
  display-lg:
    fontFamily: Fraunces
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Fraunces
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Fraunces
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Quicksand
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.6'
  body-md:
    fontFamily: Quicksand
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: Quicksand
    fontSize: 13px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 8px
  container-padding: 24px
  gutter: 16px
  section-gap: 64px
  safe-area: 32px
---

## Brand & Style

This design system embodies the warmth of handcrafted fiber arts through a **Tactile Minimalism** approach. It balances the organized aesthetic of premium Instagram boutiques with the playful, organic energy of Gen-Z Pinterest boards. The UI focuses on high-quality whitespace, soft-focus imagery, and "squishy" interactive elements that mimic the physical texture of crochet work.

The emotional response should be one of "cozy premium"—feeling high-end and curated, yet approachable and personal. Design elements should avoid harsh edges or corporate rigidity, opting instead for a fluid, human-centric interface that celebrates the "slow fashion" movement and the unique identity of a student-run, sustainable brand.

## Colors

The palette is derived from natural yarn dyes and organic fibers. 
- **Primary (Blush Pink):** Used for call-to-actions, primary buttons, and highlighting "Personal/Custom" features.
- **Secondary (Soft Sage Green):** Represents the "Sustainable" and "Handmade" nature of the brand; used for success states and organic badges.
- **Tertiary (Muted Brown):** Used for secondary UI elements and grounding borders.
- **Neutral (Warm Beige / Cream):** The foundation of the UI, used for surface containers to reduce the starkness of pure white.
- **Typography:** Avoid pure black; use the Muted Brown (#4A3728) to maintain a soft, low-contrast readability that feels warm and inviting.

## Typography

The typographic pairing emphasizes the brand's dual nature. **Fraunces** provides a literary, editorial feel for product names and storytelling headers, featuring soft, bulbous serifs that mirror yarn loops. **Quicksand** handles the functional UI with its rounded terminals, ensuring even the most technical information feels friendly and accessible.

Large display type should use tighter letter-spacing to create a "knitted" look. For mobile, scale down headings significantly to ensure the organic curves of the serif don't overwhelm the smaller viewport.

## Layout & Spacing

This design system utilizes a **Fluid Organic Grid**. While based on a standard 12-column structure for desktop, elements are encouraged to "break the grid" with slight offsets or asymmetrical margins to simulate the non-uniform nature of handmade items.

- **Desktop:** 12-column, 1140px max-width, center-aligned. Use generous margins (32px+) to create a boutique look.
- **Mobile:** Single column with 24px horizontal padding. 
- **Rhythm:** Use an 8px base unit. Gaps between related product cards should be tight (16px), while gaps between different editorial sections should be wide (64px+) to allow the design to "breathe."

## Elevation & Depth

Depth is conveyed through **Tonal Layering** and **Soft Ambient Shadows** rather than traditional elevation.

1.  **Surfaces:** Use Off-white (#FFFDF9) for the base and Warm Beige (#F5F5DC) for floating containers or "cards."
2.  **Shadows:** Shadows should be extremely diffused (Blur: 20px+) with low opacity (10%) and a slight tint of Muted Brown or Blush Pink to avoid a "grey/dirty" look.
3.  **Interaction:** On hover, elements should appear to "sink" or "press down" slightly (simulating the squish of yarn) rather than lifting further away from the surface.

## Shapes

The shape language is defined by "The Loop." There are no sharp corners in this design system. 
- **Containers:** All primary containers use `rounded-2xl` (1.5rem) or `rounded-3xl` (2rem). 
- **Buttons:** Buttons are fully pill-shaped.
- **Details:** Use dashed or dotted borders (1.5px) sparingly to represent "stitch patterns" between sections or as separators in lists.
- **Masks:** Photos should often use organic, blob-like masks instead of standard rectangles to enhance the handcrafted aesthetic.

## Components

### Buttons & Chips
- **Primary Button:** Pill-shaped, Blush Pink background, White text. High-contrast but soft.
- **Secondary Button:** Warm Beige background with a thin 1px Muted Brown border.
- **Chips (Categories):** Use Sage Green for "Sustainable" labels and Muted Brown for product categories.

### Input Fields
- Inputs should have a background color slightly darker than the surface they sit on. Use 1.5px borders in Muted Brown only when focused. Placeholder text should be in a lighter shade of the Muted Brown.

### Cards
- Product cards are borderless with a Soft Ambient Shadow. The product image should have a `rounded-2xl` top-corner treatment. Titles use Fraunces (Headline-sm) and prices use Quicksand (Bold).

### Custom Detail: The "Stitch" Separator
- A unique component for this system: a horizontal divider that looks like a dashed crochet stitch. Use this to separate product descriptions from reviews or to divide homepage sections.

### Lists
- Lists should use organic icons (like a small yarn ball or a loop) instead of standard bullet points.