---
name: Unity & Innovation
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daef'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e9edff'
  surface-container-high: '#e1e8fd'
  surface-container-highest: '#dce2f7'
  on-surface: '#141b2b'
  on-surface-variant: '#3f4944'
  inverse-surface: '#293040'
  inverse-on-surface: '#edf0ff'
  outline: '#6f7973'
  outline-variant: '#bec9c2'
  surface-tint: '#1b6b51'
  primary: '#004532'
  on-primary: '#ffffff'
  primary-container: '#065f46'
  on-primary-container: '#8bd6b7'
  inverse-primary: '#8bd6b6'
  secondary: '#795900'
  on-secondary: '#ffffff'
  secondary-container: '#ffc329'
  on-secondary-container: '#6f5100'
  tertiary: '#7f0008'
  on-tertiary: '#ffffff'
  tertiary-container: '#ab000f'
  on-tertiary-container: '#ffb5ad'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a6f2d1'
  primary-fixed-dim: '#8bd6b6'
  on-primary-fixed: '#002116'
  on-primary-fixed-variant: '#00513b'
  secondary-fixed: '#ffdf9f'
  secondary-fixed-dim: '#f9bd22'
  on-secondary-fixed: '#261a00'
  on-secondary-fixed-variant: '#5c4300'
  tertiary-fixed: '#ffdad6'
  tertiary-fixed-dim: '#ffb4ab'
  on-tertiary-fixed: '#410002'
  on-tertiary-fixed-variant: '#93000b'
  background: '#f9f9ff'
  on-background: '#141b2b'
  surface-variant: '#dce2f7'
typography:
  display-lg:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Sora
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system is built to bridge two worlds: the stability and vast natural landscapes of Canada and the vibrant, rhythmic energy of African innovation. The brand personality is **vibrant, professional, and celebratory**, evoking a sense of forward-moving partnership.

The aesthetic follows a **Corporate / Modern** base enhanced with **Tactile** geometric motifs. It avoids excessive minimalism in favor of a "rich-media" approach where whitespace is active and intentional, housing traditional motifs (like maple leaf abstractions and Adinkra-inspired patterns) that appear as subtle, tone-on-tone textures in the background. The goal is a UI that feels like a prestigious invitation to a global summit.

## Colors

The palette is rooted in a **Deep Forest Green** representing growth and Canadian landscapes, paired with an **Energetic Sun-Yellow** that symbolizes the warmth and bright future of African innovation.

- **Primary (Forest Green):** Used for primary navigation, hero backgrounds, and main action buttons.
- **Secondary (Sun Yellow):** Used for "Secure Your Pass" calls-to-action, highlighting key stats, and interactive states to ensure high visibility.
- **Tertiary (Heritage Red):** A subtle nod to the Canadian flag, used sparingly for accents, notifications, or specific decorative patterns.
- **Neutral:** A range of deep charcoals and clean whites to maintain professional readability and provide a canvas for the vibrant primary colors.

## Typography

This design system utilizes **Sora** for headlines to provide a geometric, technical, and bold appearance that screams "Innovation." Its unique apertures give it a friendly yet futuristic edge. For body copy, **Hanken Grotesk** is used for its exceptional legibility and sharp, contemporary professional feel.

Hierarchy is established through significant weight shifts. Large display type should be used for festival dates and locations, while labels use all-caps with increased letter spacing to denote secondary information like "Toronto, Canada."

## Layout & Spacing

The layout follows a **12-column Fluid Grid** for desktop and a **4-column grid** for mobile. A consistent 8px spatial scale governs all padding and margins. 

Large-scale sections (Hero, Speaker Grid) should utilize "safe areas" of 64px on desktop to ensure the content feels prestigious and uncrowded. Components like cards should use a 24px gutter to maintain clear separation while allowing for the dense information typical of festival schedules.

## Elevation & Depth

To maintain a "Professional Festival" feel, the system uses **Tonal Layers** rather than heavy shadows. 
- **Surface Level 0:** The main page background, typically white or very light grey.
- **Surface Level 1:** Cards and input fields, using a subtle 1px border in a lightened version of the Forest Green or a soft grey.
- **Interactive Depth:** Only the primary "Sun Yellow" buttons receive a soft, diffused ambient shadow (`0 10px 15px -3px rgba(251, 191, 36, 0.3)`) to make them appear "lifted" and ready for interaction.
- **Glassmorphism:** Use backdrop blurs (12px) on navigation bars to maintain context of the vibrant patterns beneath.

## Shapes

The shape language is defined by **Rounded (0.5rem)** corners, striking a balance between corporate structure and approachable community. 

Special decorative elements—such as photo frames for speakers—may use "pill-shaped" top corners with sharp bottom corners to mimic the architectural motifs found in the festival's logo. Patterns should consist of repeated geometric shapes (squares and quarter-circles) to create a rhythmic, textile-like background texture.

## Components

- **Buttons:** Primary buttons are Sun Yellow with bold, Forest Green text. They use a "pill" shape (`rounded-xl`) to stand out from the rest of the UI.
- **Cards:** Event and Speaker cards use a white background with a 1px Forest Green border. Images should be clipped with the system's standard roundedness.
- **Chips:** Used for "Innovation Tracks" (e.g., "Agri-Tech," "AI"). These use Forest Green backgrounds with white text or Forest Green outlines on white.
- **Input Fields:** Clean, high-contrast borders (1px solid grey-300). On focus, the border transitions to Forest Green with a 2px width.
- **Pattern Overlays:** Use a repeatable SVG pattern of the festival's "Four Squares" logo at 5% opacity over Forest Green sections to add cultural depth and texture without distracting from the text.
- **Schedule Lists:** High-contrast rows with Forest Green vertical accents on the left to indicate the current or upcoming session.