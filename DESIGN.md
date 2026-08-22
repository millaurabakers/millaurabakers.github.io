---
name: Obsidian & Gold
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#383939'
  surface-container-lowest: '#0d0e0f'
  surface-container-low: '#1b1c1c'
  surface-container: '#1f2020'
  surface-container-high: '#292a2a'
  surface-container-highest: '#343535'
  on-surface: '#e3e2e2'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e3e2e2'
  inverse-on-surface: '#2f3031'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#4a4949'
  on-secondary-container: '#bab8b7'
  tertiary: '#d0cdcd'
  on-tertiary: '#313030'
  tertiary-container: '#b4b2b2'
  on-tertiary-container: '#454544'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#121414'
  on-background: '#e3e2e2'
  surface-variant: '#343535'
typography:
  display-lg:
    fontFamily: Bodoni Moda
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.15em
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 24px
  section-gap: 120px
---

## Brand & Style

The design system is centered on the concept of "Elite Gourmet," evoking the atmosphere of a private, high-end culinary club. The brand personality is prestigious, exclusive, and artisanal. It targets a discerning audience that values heritage, precision, and luxury.

The visual style is **High-Contrast Minimalist** with a **Tactile** edge. By utilizing a deep, near-black foundation contrasted against polished metallic accents, the UI creates an emotional response of sophistication and quiet power. Layouts are spacious and intentional, prioritizing high-quality imagery and editorial-grade typography over decorative clutter.

## Colors

This design system utilizes a restricted, high-impact palette to maintain an atmosphere of prestige.

- **Primary (Polished Gold):** Used sparingly for key calls to action, active states, and brand-defining accents. It should feel like a metallic foil on an expensive menu.
- **Secondary (Obsidian):** The primary background color. A near-black with a slight warmth to prevent a cold, digital feel.
- **Tertiary (Graphite):** Used for surface elevation, card backgrounds, and subtle layering.
- **Neutral (Warm Grey):** Used for secondary text and borders to maintain legibility without breaking the dark aesthetic.

Avoid pure blacks (#000) and pure whites (#FFF). All light text should be slightly off-white (#F5F5F5) to reduce eye strain against the obsidian background.

## Typography

The typography hierarchy is designed for editorial impact. 

**Bodoni Moda** is the voice of the brand, used for large headlines and display text. Its high contrast between thick and thin strokes provides the "Luxury Gourmet" feel. Use optical sizing where available to ensure elegance at all scales.

**Hanken Grotesk** provides a modern, airy counterbalance. It is used for body copy and labels to ensure maximum clarity and a refined, contemporary technical feel. 

For navigation and small metadata, use `label-caps` to add a sense of structured, high-end labeling reminiscent of luxury packaging.

## Layout & Spacing

This design system follows a **Fixed Grid** philosophy on desktop to create a centered, focused experience that mimics a printed lookbook. 

- **Desktop:** 12-column grid with wide 32px gutters and generous 64px outer margins.
- **Spacing Rhythm:** Use a strict 8px base unit. Whitespace is used aggressively; section gaps should be substantial (120px+) to allow content to breathe and signify exclusivity.
- **Alignment:** Content should be primarily center-aligned for hero sections and left-aligned for data-heavy sections. Right-aligned labels can be used for pricing or metadata to create a menu-like structure.

## Elevation & Depth

Elevation is achieved through **Tonal Layers** combined with **Dramatic Shadows**.

1.  **Base:** Obsidian (#121212) serves as the ground.
2.  **Surface:** Elevated cards and modals use Graphite (#1A1A1A).
3.  **Shadows:** Use deep, large-radius shadows with a slight color tint. Shadows should have a 15-20% opacity and a 30px-60px blur to create a sense of the UI floating in a void.
4.  **Accents:** Thin, 1px gold borders (using a linear gradient for a metallic effect) can be used to define the edge of high-priority elements like a "Book Now" card or a "Special Selection" container.

## Shapes

To maintain the "Prestige" aesthetic, this design system utilizes **Sharp** edges. 0px border radii are the standard for buttons, cards, and input fields. This creates a sense of architectural precision and high-end craftsmanship. 

Rounded elements are strictly forbidden except for circular profile avatars or icon backgrounds. Sharp corners reinforce the sophisticated, "unrefined yet precise" nature of the gourmet theme.

## Components

- **Buttons:** Primary buttons are solid Gold (#D4AF37) with black text. Secondary buttons are ghost-style with a 1px gold border and gold text. All buttons use `label-caps` for the label.
- **Cards:** Cards use the Graphite (#1A1A1A) background with no border, relying on deep ambient shadows for separation. Use a 1px gold top-border for "Featured" items.
- **Input Fields:** Bottom-border only (1px Warm Grey). On focus, the border transitions to Gold. Labels should sit above the field in `label-caps`.
- **Lists:** Menu-style lists with dotted leaders connecting the item name (Bodoni Moda) to the price or detail (Hanken Grotesk).
- **Checkboxes/Radios:** Square and sharp-edged. Checked state uses a solid gold fill with a black checkmark.
- **Chips:** Dark grey background with small caps text. Used for "Sold Out," "Limited Edition," or "Artisanal" tags.