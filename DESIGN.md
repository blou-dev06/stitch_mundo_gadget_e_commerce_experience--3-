---
name: Ether Glaze Tech
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0edec'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#484554'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#797585'
  outline-variant: '#cac4d6'
  surface-tint: '#6343d1'
  primary: '#5330c1'
  on-primary: '#ffffff'
  primary-container: '#6c4ddb'
  on-primary-container: '#ebe3ff'
  inverse-primary: '#cbbeff'
  secondary: '#603fd2'
  on-secondary: '#ffffff'
  secondary-container: '#7a5bec'
  on-secondary-container: '#fffbff'
  tertiary: '#3e4b8b'
  on-tertiary: '#ffffff'
  tertiary-container: '#5663a5'
  on-tertiary-container: '#e3e5ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e7deff'
  primary-fixed-dim: '#cbbeff'
  on-primary-fixed: '#1d0061'
  on-primary-fixed-variant: '#4b24b9'
  secondary-fixed: '#e7deff'
  secondary-fixed-dim: '#cbbeff'
  on-secondary-fixed: '#1d0061'
  on-secondary-fixed-variant: '#4b22bc'
  tertiary-fixed: '#dee1ff'
  tertiary-fixed-dim: '#b9c3ff'
  on-tertiary-fixed: '#021355'
  on-tertiary-fixed-variant: '#354281'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
  surface-white: '#F8F8FA'
  surface-gray: '#ECECF1'
  glass-stroke: rgba(255, 255, 255, 0.4)
  accent-gradient-start: '#6C4DDB'
  accent-gradient-end: '#AAB7FF'
typography:
  display-lg:
    fontFamily: Sora
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 80px
    letterSpacing: -0.04em
  headline-xl:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.1em
  button:
    fontFamily: Sora
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  section-gap: 120px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system embodies a "Futuristic Premium" aesthetic, merging high-end tech commerce with an ethereal, digital atmosphere. The visual narrative is driven by the concept of **Liquid Glass**—where interfaces feel like semi-transparent, polished surfaces floating in a vast, atmospheric space. It targets affluent tech enthusiasts who value innovation as much as status.

The style is a sophisticated blend of **Glassmorphism** and **Minimalism**. It utilizes large amounts of whitespace (negative space) to allow product photography to breathe, while employing vibrant background blurs and "aurora" gradients to provide depth and a sense of high-technology. The emotional response should be one of calm, awe, and effortless precision.

## Colors

The palette is anchored by a deep **Main Purple**, representing the core of the brand's identity and power. **Bright Violet** and **Lavender Blue** are used exclusively for highlights, interactive states, and soft background "glow" effects that simulate light refracting through glass.

While the default mode is `light`, it utilizes a "High-Contrast Light" approach where backgrounds are near-white (`#F8F8FA`) but deep charcoal elements (`#151515`) provide structural grounding. Gradients should be used sparingly and with high diffusion to create the "liquid" feel—avoiding sharp transitions in favor of soft, atmospheric transitions between the purples and blues.

## Typography

The typography system relies on **Sora** for its geometric, futuristic construction in headlines. To ensure a premium editorial feel, headlines feature tight letter-spacing and substantial scale differences. **Hanken Grotesk** provides a sharp, contemporary legibility for body copy, maintaining the technical aesthetic without sacrificing readability.

A specialized label tier using **JetBrains Mono** is utilized for technical specifications, prices, and small metadata, reinforcing the "gadget" and "engineering" roots of the brand. All "Display" and "Headline XL" styles must be used with generous vertical rhythm to maintain the minimalist luxury feel.

## Layout & Spacing

This system uses a **Fixed Grid** model for desktop to ensure product imagery remains perfectly composed within the center of the viewport. A 12-column grid is standard, but the "Minimalist Tech" aesthetic requires frequent use of "offset" layouts where content spans columns 2 through 10 to create massive horizontal margins.

The spacing rhythm is expansive. Section gaps (`120px+`) are used to separate different product categories or brand stories, preventing visual clutter. For mobile, the grid collapses to a single column with a fluid 20px margin, while maintaining the "stack-lg" vertical rhythm to preserve the premium feel.

## Elevation & Depth

Hierarchy is established through **Glassmorphism** and **Backdrop Blurs**. Rather than traditional drop shadows, depth is created by:
1.  **Surface Tiers:** Cards use a semi-transparent white background with a `20px` backdrop blur.
2.  **Floating Elements:** Product images are often placed without containers, utilizing a "floating" shadow—a soft, low-opacity violet glow—to appear as if they are hovering.
3.  **Reflective Borders:** Elements use a 1px solid border with a gradient stroke (White at 40% to White at 10%) to simulate the edge of a glass pane catching the light.
4.  **Aurora Blurs:** Large, colorful blobs of Primary and Tertiary colors are placed deep in the background layer (z-index: -1) with a blur radius of `100px+` to create a sense of three-dimensional atmosphere.

## Shapes

The shape language is dominated by **Pill-shapes** and hyper-rounded corners. This "soft-tech" approach balances the futuristic coldness of the tech subject matter with an approachable, organic feel. 

- **Primary Buttons:** Always full-pill (`999px` radius).
- **Product Cards:** Use `rounded-xl` (1.5rem) to ensure they feel like smooth, handheld devices.
- **Input Fields:** Follow the pill-shape convention of the buttons.
- **Glass Overlays:** Should always have a subtle rounding to avoid a "sharp" industrial feel.

## Components

### Buttons
Primary buttons are pill-shaped with a vibrant violet-to-blue gradient. Text is uppercase or semi-bold Sora. Secondary buttons use the "Glass" effect: a transparent background, 1px white-semi-transparent border, and backdrop blur.

### Chips & Tags
Technical specs (e.g., "5G", "OLED") should use the **JetBrains Mono** label style inside small, subtle gray pill containers with high transparency.

### Cards
Cards are the primary vehicle for the Glassmorphism effect. They feature a 1px "glass-stroke" border and a light background blur. On hover, the blur intensity should increase, and the border-color should shift toward the Main Purple.

### Input Fields
Inputs are minimalist, using only a bottom border or a very faint pill-shaped outline. The focus state triggers a soft purple outer glow (aura) rather than a hard border change.

### Floating Product Visuals
Product imagery should be high-fidelity PNGs with no background, layered over background blurs. Occasional "liquid" spheres or glass shards can be placed behind or in front of products to enhance the futuristic depth.