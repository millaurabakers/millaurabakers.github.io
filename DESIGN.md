---
name: Artisanal Confectionery System
colors:
  surface: '#fcf9f2'
  surface-dim: '#dcdad3'
  surface-bright: '#fcf9f2'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ec'
  surface-container: '#f0eee7'
  surface-container-high: '#ebe8e1'
  surface-container-highest: '#e5e2db'
  on-surface: '#1c1c18'
  on-surface-variant: '#424752'
  inverse-surface: '#31312c'
  inverse-on-surface: '#f3f0ea'
  outline: '#737783'
  outline-variant: '#c3c6d3'
  surface-tint: '#255cb1'
  primary: '#003b81'
  on-primary: '#ffffff'
  primary-container: '#1552a6'
  on-primary-container: '#b1c9ff'
  inverse-primary: '#adc7ff'
  secondary: '#845400'
  on-secondary: '#ffffff'
  secondary-container: '#fdae3b'
  on-secondary-container: '#6d4400'
  tertiary: '#004811'
  on-tertiary: '#ffffff'
  tertiary-container: '#196122'
  on-tertiary-container: '#90da8d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc7ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004493'
  secondary-fixed: '#ffddb6'
  secondary-fixed-dim: '#ffb95a'
  on-secondary-fixed: '#2a1800'
  on-secondary-fixed-variant: '#643f00'
  tertiary-fixed: '#a9f5a4'
  tertiary-fixed-dim: '#8ed88a'
  on-tertiary-fixed: '#002204'
  on-tertiary-fixed-variant: '#035316'
  background: '#fcf9f2'
  on-background: '#1c1c18'
  surface-variant: '#e5e2db'
typography:
  display-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 38px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Bricolage Grotesque
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-md:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '700'
    lineHeight: 26px
  body-lg:
    fontFamily: DM Sans
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: DM Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: DM Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: DM Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.06em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-desktop: 2rem
  margin: 1rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 2.5rem
---

## Brand & Style

This design system translates the wholesome, handcrafted spirit of warm artisanal baking into an expressive digital experience. Drawing directly from tactile confectionery packaging, it blends vibrant royal lapis blue with rich butter-cookie gold and milky buttermilk ivory. 

The aesthetic is playful, heartwarming, and nutritious—bridging traditional bakery warmth with modern, tactile packaging cues. Organic ribbon pill badges, friendly packaging icons, and undulating wave containers celebrate wholesome ingredients (pure butter, natural millets, and unrefined jaggery). The interface balances generous breathing room with high-energy, artisanal personality, making digital ordering and brand discovery feel joyful, tactile, and comforting.

## Colors

The color palette is built around high-spirited confectionery contrasts:
- **Primary Royal Blue (`#1552a6`)**: Evokes the heritage packaging background, anchoring navigation headers, focal interactive actions, and primary narrative containers.
- **Secondary Butter Gold (`#e59a27`)**: Echoes freshly baked crusts and roasted grains. Applied to call-to-actions, featured product highlights, and star ratings.
- **Tertiary Millet Sage (`#438945`)**: Denotes organic, wholesome ingredients, vegan recipes, and dietary certifications (such as "No Palm Oil" and "Millet Goodness").
- **Neutral Buttermilk Ivory (`#fcf9f2`)**: The foundational canvas color that eliminates stark digital white in favor of velvety, warm dairy-cream tones.

For text hierarchy, the system relies on deep warm navy (`#0d284f`) for ultra-crisp editorial readability, while soft cookie-crust beige (`#f3ebd8`) provides subtle section separations.

## Typography

Typography balances artisanal personality with legible commerce mechanics:
- **Headlines & Display (`Bricolage Grotesque`)**: With eccentric curves, organic joints, and bold ink traps, this typeface reflects the hand-piped character of artisanal pastry titles while maintaining modern screen crispness.
- **Body & Functional UI (`DM Sans`)**: Provides geometric clarity and open apertures for ingredient lists, nutrition cards, descriptions, and transactional elements without distracting from the display typography.
- **Micro-copy & Ingredient Ribbons**: Set in uppercase tracked `DM Sans` (`label-sm`), providing the punchy legibility of physical food packaging stamps.

## Layout & Spacing

The layout uses a fluid responsive grid system (4 columns on mobile, 8 on tablet, 12 on desktop) set within a maximum content boundary of `1280px`. 

Containers celebrate the undulating horizontal wave motifs seen in the packaging: alternating between deep royal blue backdrops and warm ivory sections. Elements have generous vertical spacing to reinforce an unhurried, handcrafted feel. Nested components use tight micro-gaps (`space-xs` and `space-sm`) within badge clusters and pill groups, but expansive macro-gaps (`space-lg` and `space-xl`) between collection cards to highlight photography and ingredient stories.

## Elevation & Depth

Depth is tactile, physical, and layered—reminiscent of stacked packaging cutouts and confectionery tins:
- **Tonal Layering**: Deep royal blue backgrounds contain layered buttermilk ivory (`#fcf9f2`) cards, producing maximum contrast and pop without harsh visual noise.
- **Warm Ambient Drop Shadows**: Instead of cold grays, elevations utilize low-opacity, warm amber-tinted shadows (`rgba(21, 82, 166, 0.08)` to `rgba(217, 119, 6, 0.14)`).
- **Subtle Organic Borders**: Cards resting on ivory surfaces use a fine, warm-tinted line (`1.5px solid rgba(229, 154, 39, 0.25)`) to echo embossed paper labels.
- **Floating Pill Badges**: Wholesome highlight chips feature a gentle lift with dual micro-shadows, creating the appearance of applied sticker seals.

## Shapes

The visual language is hyper-rounded and soft:
- **Maximum Pill Radius (Level 3)**: Interactive buttons, collection ribbons, dietary tags, and search inputs utilize full pill styling (`9999px` / `rounded-full`).
- **Cards and Display Pods**: Large cards feature generous corners (`rounded-lg: 2rem` to `rounded-xl: 3rem`), mirroring tin containers and packaging die-cuts.
- **Icon Enclosures**: Stamp icons and badge highlights are enclosed inside circular containers (`border-radius: 50%`) with decorative dashed or scalloped outer ring accents.

## Components

### Buttons
- **Primary**: Solid royal blue (`#1552a6`) with crisp white typography, fully rounded pill radius, and active states transitioning to an amber-gold glow.
- **Secondary**: Rich butter gold (`#e59a27`) with dark navy typography, used for high-intent ordering buttons and cart checkouts.
- **Packaging Outlines**: Cream base with a 2px blue or golden border, housing a small heart or leaf leading icon.

### Wholesome Badges & Dietary Chips
- Circular and ribbon-styled badges ("Pure Butter", "No Palm Oil", "Millet Goodness", "Made with Love").
- Styled with crisp micro-line icons inside circular badges, accompanied by uppercase tracked subtext.
- Collection header ribbons feature scalloped ribbon-tail cutouts and directional color-coding (blue for signatures, green for millets, golden for butter, orange for minis).

### Cards
- **Product & Cookie Tiles**: Buttermilk ivory surfaces elevated over blue or cream sections, capped with rounded photography viewports (`rounded-xl`). They feature top-corner dietary badge floats and bottom-aligned ingredient chips.
- **Nutritional & Collection Pods**: Crisp white backings with 2rem corner radii, separated by dashed warm golden dividing rules.

### Input Fields & Controls
- **Search & Text Inputs**: Full pill geometry with subtle buttermilk background fills, a 1.5px royal blue focused outline, and generous horizontal padding (`1.5rem`).
- **Checkboxes & Radios**: Rendered as smooth circular selectors; selected states fill with royal blue and display an ivory heart or checkmark glyph.

### Lists & Ingredients
- List items feature custom heart and grain bullet points colored in golden amber, paired with relaxed line-heights and warm dark-navy typography.