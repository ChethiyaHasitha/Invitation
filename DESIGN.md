---
name: Ethereal Heritage
colors:
  surface: '#fbf9f0'
  surface-dim: '#dcdad2'
  surface-bright: '#fbf9f0'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f4eb'
  surface-container: '#f0eee5'
  surface-container-high: '#eae8df'
  surface-container-highest: '#e4e3da'
  on-surface: '#1b1c17'
  on-surface-variant: '#4f4535'
  inverse-surface: '#30312b'
  inverse-on-surface: '#f3f1e8'
  outline: '#817563'
  outline-variant: '#d3c4af'
  surface-tint: '#7b5800'
  primary: '#785600'
  on-primary: '#ffffff'
  primary-container: '#986d00'
  on-primary-container: '#fffbff'
  inverse-primary: '#f7bd48'
  secondary: '#8f4b45'
  on-secondary: '#ffffff'
  secondary-container: '#ffa79f'
  on-secondary-container: '#7a3a35'
  tertiary: '#4f604f'
  on-tertiary: '#ffffff'
  tertiary-container: '#677966'
  on-tertiary-container: '#f7fff2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdea6'
  primary-fixed-dim: '#f7bd48'
  on-primary-fixed: '#271900'
  on-primary-fixed-variant: '#5d4200'
  secondary-fixed: '#ffdad6'
  secondary-fixed-dim: '#ffb3ac'
  on-secondary-fixed: '#3a0908'
  on-secondary-fixed-variant: '#72342f'
  tertiary-fixed: '#d4e8d1'
  tertiary-fixed-dim: '#b8ccb6'
  on-tertiary-fixed: '#0f1f11'
  on-tertiary-fixed-variant: '#3a4b3a'
  background: '#fbf9f0'
  on-background: '#1b1c17'
  surface-variant: '#e4e3da'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: 0.05em
  body-lg:
    fontFamily: Merriweather
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Merriweather
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: Libre Franklin
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.15em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  margin-page: 3rem
  gutter-grid: 1.5rem
  stack-sm: 0.5rem
  stack-md: 1.5rem
  stack-lg: 4rem
---

## Brand & Style

This design system embodies a sophisticated and timeless aesthetic, drawing inspiration from classical editorial design and delicate botanical illustrations. It is crafted for high-end lifestyle products, wedding planning, luxury hospitality, or cultural archives where elegance and emotional resonance are paramount.

The visual style is **Classic Modernism** with a tactile, paper-like quality. It prioritizes grace over speed, using generous whitespace and ornate flourishes to create a sense of occasion. The emotional response should be one of warmth, prestige, and quiet celebration. Every interaction is designed to feel deliberate and premium.

## Colors

The palette is rooted in a warm, organic foundation. The primary **Antique Gold** (#B8860B) is used for accents, iconography, and subtle borders, evoking quality and tradition. The secondary **Muted Rose** (#A65D57) provides a romantic contrast for key interactive elements and featured headlines.

The **Sage Green** (#6B7D6A) tertiary color is reserved for naturalistic elements and success states, maintaining the botanical theme. The background is a rich **Cream Parchment** (#FDFBF2), which provides a softer, more premium feel than pure white. Text is set in a deep, warm charcoal rather than pure black to preserve the soft-contrast aesthetic.

## Typography

The typography system relies on a high-contrast pairing between an elegant serif and a functional, modern sans-serif. 

**Playfair Display** is used for large headlines and display elements, often utilizing its italic variant to mimic the fluidity of calligraphy seen in traditional invitations. **Merriweather** provides high legibility for body copy, maintaining the classic "printed" look. For functional UI elements like buttons, navigational links, and small labels, **Libre Franklin** is used with increased letter-spacing and uppercase styling to provide a clean, modern anchor to the more decorative serif faces.

## Layout & Spacing

This design system uses a **Fixed Grid** approach for large screens to maintain the composition of an invitation or editorial spread. On desktop, content is centered within a maximum width of 1200px, utilizing a 12-column structure. 

Vertical rhythm is intentionally "airy," with significant padding between sections to allow the botanical illustrations and high-end typography to breathe. On mobile devices, margins transition to a standard 20px, and complex decorative elements are simplified or moved to the background to ensure content clarity.

## Elevation & Depth

Depth is achieved through **Tonal Layers** rather than heavy shadows. We use subtle differences in background luminosity and thin, gold-toned borders to define hierarchy. 

When elevation is required (such as for a primary call-to-action or a modal), use a very soft, diffused "Ambient Shadow" with a slight warm tint (#5D4037) at very low opacity (5-8%). Backdrop blurs should be used sparingly on navigation bars to maintain the "paper" texture of the design system while providing modern functionality.

## Shapes

The shape language is primarily **Soft** and rectilinear, favoring the structure of a high-quality card. While UI elements like buttons and input fields feature a subtle 0.25rem radius, the overall "frame" of the design often uses sharp corners to mimic the edges of stationery.

Decorative motifs utilize organic, fluid shapes derived from watercolor florals. These elements should never feel "boxy"; they should bleed off the edges of containers or overlap structural lines to break the grid and add a handcrafted feel.

## Components

### Buttons
Primary buttons use a solid **Muted Rose** fill with white **Libre Franklin** text in uppercase. Secondary buttons are "Ghost" style, featuring an **Antique Gold** 1px border and matching text.

### Input Fields
Inputs are minimalist, consisting of a single bottom border in a light gold or warm grey, with labels floating above in small caps.

### Cards
Cards use the **Cream Parchment** background but are distinguished by a thin, inner-inset border in gold. This "frame-within-a-frame" effect is central to the design system's aesthetic.

### Flourishes & Dividers
Horizontal dividers are not just plain lines; they feature a small center ornament (like a heart or diamond) in gold. Watercolor floral illustrations are used as "anchors" in the corners of major containers or page sections.

### List Items
Lists should use custom bullet points—either small gold dots or miniature botanical icons—to maintain the themed experience.