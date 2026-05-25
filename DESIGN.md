---
name: Editorial Luxury
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#4d4635'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#7f7663'
  outline-variant: '#d0c5af'
  surface-tint: '#735c00'
  primary: '#735c00'
  on-primary: '#ffffff'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#e9c349'
  secondary: '#5e5f5c'
  on-secondary: '#ffffff'
  secondary-container: '#e0e0dd'
  on-secondary-container: '#626361'
  tertiary: '#5d5f5f'
  on-tertiary: '#ffffff'
  tertiary-container: '#b2b3b3'
  on-tertiary-container: '#434546'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e3e2e0'
  secondary-fixed-dim: '#c7c6c4'
  on-secondary-fixed: '#1a1c1a'
  on-secondary-fixed-variant: '#464745'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: ebGaramond
    fontSize: 80px
    fontWeight: '400'
    lineHeight: 88px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: ebGaramond
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
  headline-md:
    fontFamily: ebGaramond
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-sm:
    fontFamily: ebGaramond
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: inter
    fontSize: 18px
    fontWeight: '300'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-md:
    fontFamily: inter
    fontSize: 16px
    fontWeight: '300'
    lineHeight: 24px
  label-lg:
    fontFamily: inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
spacing:
  unit: 8px
  margin-desktop: 80px
  margin-mobile: 24px
  gutter: 32px
  section-gap: 160px
---

## Brand & Style
This design system is anchored in the aesthetic of high-end editorial magazines, prioritizing tranquility, exclusivity, and precision. It is designed for a discerning clientele who values understated elegance over loud marketing. 

The visual direction follows **Minimalism** with a **Tactile** edge through the use of fine-line art. By utilizing extreme whitespace, we create a "gallery" effect where every image and piece of information is treated as a curated artifact. The experience should feel like walking into a quiet, sun-drenched marble atelier—intentional, airy, and profoundly calm.

## Colors
The palette is a sophisticated triptych of light and metal. 

*   **Alabaster (#F9F8F5):** Used as the primary canvas for backgrounds to provide warmth that pure white lacks, evoking the feel of premium heavy-stock paper.
*   **Champagne Gold (#D4AF37):** Reserved for delicate accents, interactive states, and fine-line borders. It should be used sparingly to maintain its status as a "precious" element.
*   **Deep Charcoal (#1A1A1A):** Used for all typography and structural iconography to ensure high legibility and a grounded, authoritative feel.
*   **Pure White (#FFFFFF):** Used exclusively for high-level surface containers or to create subtle contrast against the Alabaster background.

## Typography
The typographic hierarchy relies on the tension between a romantic, high-contrast serif and a clinical, ultra-light sans-serif.

**Headlines** utilize **ebGaramond**. Large display sizes should use tight letter-spacing to emphasize the elegance of the serifs. For mobile views, `display-lg` should scale down to `headline-lg`.

**Body Copy** uses **Inter** with a light weight (300) to maintain the airy aesthetic. Tracking should be slightly increased for body and labels to improve legibility and convey a sense of "breathing room." All labels and small metadata should be set in uppercase to mimic luxury brand labeling.

## Layout & Spacing
The layout follows a **Fixed Grid** model to ensure the editorial composition is preserved across varying screen sizes. 

*   **Desktop:** 12-column grid with a max-width of 1440px. Use 80px side margins to force content into a central "runway."
*   **Section Gaps:** Use an aggressive 160px vertical gap between major content sections to reinforce the luxury of space.
*   **Mobile:** 4-column grid. Margins reduce to 24px, and section gaps reduce to 80px.

Layouts should be asymmetrical where possible, utilizing empty columns to lead the eye through the content in a non-linear, magazine-style flow.

## Elevation & Depth
This design system rejects shadows and gradients entirely to maintain a flat, modernist look. Depth is achieved through **Tonal Layering** and **Fine-line Outlines**:

1.  **Level 0 (Background):** Soft Alabaster.
2.  **Level 1 (Cards/Surfaces):** Pure White surfaces with a 1px Gold (#D4AF37) border.
3.  **Interaction:** Use "Ghost" layers—semi-transparent overlays of Gold (10% opacity) to indicate hover states without breaking the flat aesthetic.

Structural wireframes and hairline dividers (0.5pt to 1pt) should be used to define zones rather than traditional drop shadows.

## Shapes
The shape language is strictly **Sharp (0px)**. 

Rectilinear forms evoke architectural precision and the high-end packaging found in medical aesthetics. This applies to buttons, input fields, image containers, and cards. The only exception to the sharp rule is for specialized decorative elements like circular fine-line watermarks or specific iconography, which serve as organic counterpoints to the rigid structural grid.

## Components
Consistent styling across components ensures the system remains cohesive and premium.

*   **Buttons:** Rectangular with no radius. Primary buttons use a 1px Gold border with Charcoal text. For a "call to action," use a solid Gold background with White text, but limit this to one per page.
*   **Input Fields:** Minimalist design with only a 1px Charcoal bottom border. Labels should sit above the line in `label-sm` uppercase.
*   **Cards:** Pure White backgrounds with a 1px Gold border. Image-heavy cards should have no padding, allowing photography to meet the border edge.
*   **Fine-Line Watermarks:** Use vector-based golden wireframes (line-art leaves or geometric shapes) at 20% opacity behind text blocks to add a layer of brand texture.
*   **Lists:** Items separated by 1px Alabaster-on-Charcoal hairline dividers, utilizing generous vertical padding (24px+).
*   **Chips/Tags:** Small uppercase text with a 1px Gold border, no fill.