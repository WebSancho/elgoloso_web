---
name: El Goloso
colors:
  surface: '#fff9f0'
  surface-dim: '#dfd9d1'
  surface-bright: '#fff9f0'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f9f3ea'
  surface-container: '#f3ede4'
  surface-container-high: '#ede7df'
  surface-container-highest: '#e7e2d9'
  on-surface: '#1d1b16'
  on-surface-variant: '#584140'
  inverse-surface: '#32302a'
  inverse-on-surface: '#f6f0e7'
  outline: '#8c706f'
  outline-variant: '#e0bfbd'
  surface-tint: '#ae2f34'
  primary: '#ae2f34'
  on-primary: '#ffffff'
  primary-container: '#ff6b6b'
  on-primary-container: '#6d0010'
  inverse-primary: '#ffb3b0'
  secondary: '#705d00'
  on-secondary: '#ffffff'
  secondary-container: '#fdd73b'
  on-secondary-container: '#715d00'
  tertiary: '#006a65'
  on-tertiary: '#ffffff'
  tertiary-container: '#1eada5'
  on-tertiary-container: '#003a37'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad8'
  primary-fixed-dim: '#ffb3b0'
  on-primary-fixed: '#410006'
  on-primary-fixed-variant: '#8c1520'
  secondary-fixed: '#ffe173'
  secondary-fixed-dim: '#e8c426'
  on-secondary-fixed: '#221b00'
  on-secondary-fixed-variant: '#554500'
  tertiary-fixed: '#7cf6ec'
  tertiary-fixed-dim: '#5dd9d0'
  on-tertiary-fixed: '#00201e'
  on-tertiary-fixed-variant: '#00504c'
  background: '#fff9f0'
  on-background: '#1d1b16'
  surface-variant: '#e7e2d9'
typography:
  display:
    fontFamily: Nunito Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Nunito Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Nunito Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Nunito Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  gutter: 16px
  margin-mobile: 20px
  margin-desktop: 40px
  stack-sm: 4px
  stack-md: 12px
  stack-lg: 24px
---

## Brand & Style

The design system is built to evoke the warmth of a local neighborhood shop—the kind where the owner knows your name and your favorite treat. It avoids the sterile, high-tech polish of modern apps in favor of a **Tactile & Friendly** aesthetic that feels approachable and human.

The visual narrative is centered on sweetness and community. By blending **Minimalism** with **Skeuomorphic touches**, the interface uses soft shadows and organic shapes to make digital elements feel like physical items on a countertop. The emotional goal is to create a sense of belonging, comfort, and cheerfulness through a "high-touch" digital experience.

## Colors

The palette is anchored in a warm "Pan dulce" spectrum. The primary **Coral (#FF6B6B)** provides energy and appetite appeal, while the **Sunny Yellow (#FFD93D)** acts as a cheerful highlight for secondary actions and accents. 

To maintain the "neighborhood shop" feel, the background is never a stark, clinical white; instead, a **Soft Cream (#FFF9F0)** is used to provide a parchment-like warmth. A tertiary **Muted Teal (#4ECDC4)** is introduced sparingly for success states or to balance the warmth with a touch of freshness. Text should primarily use a deep chocolate-charcoal rather than pure black to maintain the soft visual harmony.

## Typography

The typography strategy pairs the rounded, friendly geometry of **Nunito Sans** for headings with the contemporary clarity of **Be Vietnam Pro** for body text. 

Headings should utilize tighter letter-spacing and heavier weights to feel "plump" and inviting. For body text, the line height is intentionally generous to ensure high legibility and a relaxed reading pace. All labels and buttons use medium to semi-bold weights of Be Vietnam Pro to maintain a clear information hierarchy without feeling overly formal.

## Layout & Spacing

This design system employs a **Fluid Grid** with generous inner paddings to prevent the UI from feeling cramped. The spacing rhythm is based on an 8px scale, but emphasizes "breathing room" to reflect a relaxed, unhurried shop environment.

On **Mobile**, we use a 4-column grid with 20px side margins to ensure touch targets are comfortable for all ages. On **Desktop**, the layout expands to a 12-column centered grid with a maximum content width of 1200px. Containers and cards should use dynamic padding that scales with the viewport to maintain a cozy, balanced appearance.

## Elevation & Depth

To achieve the "neighborhood shop" feel, depth is communicated through **Tonal Layers** and **Soft Ambient Shadows**. We avoid harsh drop shadows. Instead, surfaces use "pillowy" elevation:
- **Level 1 (Base):** The Cream background.
- **Level 2 (Cards):** Subtly raised with a large-blur, low-opacity shadow (e.g., 10% opacity of the primary color) to make elements feel like they are resting on the surface.
- **Level 3 (Interactive):** Elements like buttons use a slightly deeper shadow that "squishes" (reduces in size) when pressed, providing tactile feedback.

Inner shadows can be used on input fields to create a "pressed-in" look, reinforcing the physical metaphor.

## Shapes

The shape language is strictly **Rounded**. Sharp corners are non-existent in this design system, as they feel too aggressive and corporate. 

- **Standard Buttons/Inputs:** 0.5rem (8px) radius.
- **Feature Cards/Product Images:** 1rem (16px) radius.
- **Floating Action Buttons/Tags:** Fully pill-shaped to invite interaction.

Icons should follow an illustrative, monolinear style with rounded terminals and soft corners to match the UI's friendliness.

## Components

### Buttons
Primary buttons use the Coral background with white text and a subtle 2px bottom "border-shadow" of a darker coral to give them a 3D, pressable feel. Secondary buttons use the Yellow accent.

### Chips & Tags
Used for categories (e.g., "Freshly Baked," "Local"). These should be pill-shaped with light tinted backgrounds and darker text of the same hue to keep the interface colorful but organized.

### Input Fields
Fields should have a soft, thick border (2px) in a muted version of the primary color. When focused, they should glow with a soft yellow halo.

### Cards
Cards are the primary container for products and services. They should feature "edge-to-edge" imagery with rounded top corners and a generous text area below. 

### Interactive "Treats"
Incorporate small illustrative flourishes—like a small crumb or a heart icon—near notification badges or success messages to reinforce the "neighborhood shop owner" voice.