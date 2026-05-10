---
name: Cilician Heritage
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
  on-surface-variant: '#5a403e'
  inverse-surface: '#303221'
  inverse-on-surface: '#f2f2d9'
  outline: '#8e706d'
  outline-variant: '#e2beba'
  surface-tint: '#b52424'
  primary: '#8f000d'
  on-primary: '#ffffff'
  primary-container: '#b22222'
  on-primary-container: '#ffc8c2'
  inverse-primary: '#ffb4ac'
  secondary: '#3a5f94'
  on-secondary: '#ffffff'
  secondary-container: '#9fc2fe'
  on-secondary-container: '#294f83'
  tertiary: '#374655'
  on-tertiary: '#ffffff'
  tertiary-container: '#4e5e6d'
  on-tertiary-container: '#c6d7e9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ac'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#92030f'
  secondary-fixed: '#d5e3ff'
  secondary-fixed-dim: '#a7c8ff'
  on-secondary-fixed: '#001b3c'
  on-secondary-fixed-variant: '#1f477b'
  tertiary-fixed: '#d4e4f6'
  tertiary-fixed-dim: '#b8c8da'
  on-tertiary-fixed: '#0d1d2a'
  on-tertiary-fixed-variant: '#394857'
  background: '#fbfbe2'
  on-background: '#1b1d0e'
  surface-variant: '#e4e4cc'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The design system embodies a "Contemporary Antiquity" aesthetic, merging the architectural precision of Roman engineering with modern minimalist interfaces. It is designed for learners, history enthusiasts, and travelers exploring the Roman-era history of Talas and Cilicia. 

The visual style is characterized by extreme clarity, purposeful use of whitespace (reminiscent of open-air forums), and high-contrast color pairings that ensure legibility while evoking a sense of enduring stone and deep water. Subtle stone-like textures are applied sparingly to background layers to provide a tactile, grounded feel without compromising the modern, digital-first experience.

## Colors
This design system utilizes a palette inspired by the Mediterranean landscape and Roman materials. 

- **Travertine Beige (#F5F5DC):** The primary canvas color, used for backgrounds to reduce eye strain compared to pure white, mimicking sun-bleached stone.
- **Roman Terracotta (#B22222):** The primary action and highlight color. It represents pottery, brickwork, and vitality.
- **Deep Mediterranean Blue (#003366):** Used for navigation, high-level headers, and secondary emphasis, reflecting the coastal identity of Cilicia.
- **Slate Grey (#708090):** Used for supporting text and structural lines, providing a cool contrast to the warmth of the beige and terracotta.

## Typography
The typography strategy contrasts the historic authority of Roman inscriptions with modern digital readability.

- **Headlines (Libre Caslon Text):** Chosen for its elegant serifs and classical proportions. It should be used for titles and section headers. High-level displays should use increased letter spacing to mimic the rhythm of stone-carved lettering.
- **Body & UI (Inter):** A clean, highly legible sans-serif that ensures clarity for educational content. It handles complex historical data and descriptions with ease.
- **Labels:** Always use Inter. For category tags or small headers, use the `label-lg` style with uppercase transformations to maintain an "official" institutional feel.

## Layout & Spacing
This design system utilizes a **fluid grid** with a strong emphasis on "The Rule of the Forum"—ample open space that allows content to breathe.

- **Mobile:** 4-column grid with 16px margins and 16px gutters.
- **Tablet:** 8-column grid with 32px margins and 24px gutters.
- **Desktop:** 12-column grid with a max-width of 1280px, 64px margins, and 24px gutters.

The vertical rhythm is strictly based on 8px increments. Use `xl` (80px) spacing between major sections to emphasize the minimalistic and spacious nature of the system.

## Elevation & Depth
In alignment with the stone-like aesthetic, depth is conveyed through **tonal layers** and **precision outlines** rather than heavy shadows.

- **Surface Tiers:** The base layer is Travertine Beige. Interactive elements like cards sit on a pure white surface.
- **Outlines:** Use 1px solid Slate Grey (#708090) borders at 20% opacity for most containers. For active states, increase the opacity or switch to Roman Terracotta.
- **Depth:** When necessary, use a "Dry Stone Shadow"—a very low-blur, high-distance shadow (e.g., 0px 4px 12px) with a Slate Grey tint at 10% opacity, suggesting a flat object resting on a solid surface.
- **Texture Overlay:** Apply a subtle noise or "grain" SVG filter to the background (opacity 0.03) to simulate the feel of limestone or parchment.

## Shapes
This design system utilizes **Sharp (0px)** corners. This decision reinforces the architectural, lapidary nature of Roman inscriptions and masonry. 

- **Containers:** All cards, buttons, and input fields must have perfectly square corners.
- **Visual Interest:** Use diagonal line accents or perpendicular grid intersections to create a sense of structure and engineering.
- **Exceptions:** Standardized system icons (e.g., Apple or Android system bars) remain in their native formats, but all custom iconography should follow a geometric, sharp-edged path.

## Components
- **Buttons:** Primary buttons are filled with Roman Terracotta with white text. Secondary buttons use a Slate Grey outline (1px) with Deep Mediterranean Blue text. All buttons use the `label-lg` typography style.
- **Cards:** White backgrounds with no shadow, defined by a 1px Slate Grey border at 15% opacity. Content within cards should have generous padding (24px).
- **Input Fields:** Bottom-border only, using Slate Grey. Upon focus, the border transitions to Roman Terracotta and thickens to 2px.
- **Chips/Tags:** Used for historical periods or locations. These use a Deep Mediterranean Blue background with white text, using the `label-sm` style.
- **Interactive Map Pins:** High-contrast Terracotta circles with a Slate Grey "target" ring, ensuring they pop against the Travertine beige maps.
- **Artifact Lists:** Clean, high-contrast rows separated by 1px horizontal lines. Each row features a small thumbnail image of the artifact and a `headline-md` title.
- **Progress Indicators:** Use a "Segmented Column" metaphor—linear horizontal bars divided into blocks, evoking the look of a stone colonnade.