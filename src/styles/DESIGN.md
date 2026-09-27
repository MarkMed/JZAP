---
name: Shadow Wave Protocol
colors:
  surface: '#230a1e'
  surface-dim: '#230a1e'
  surface-bright: '#4d3045'
  surface-container-lowest: '#1d0618'
  surface-container-low: '#2c1326'
  surface-container: '#30172b'
  surface-container-high: '#3c2135'
  surface-container-highest: '#482b41'
  on-surface: '#ffd7f1'
  on-surface-variant: '#dabfcd'
  inverse-surface: '#ffd7f1'
  inverse-on-surface: '#43273c'
  outline: '#a28a97'
  outline-variant: '#54414c'
  surface-tint: '#ffaceb'
  primary: '#ffaceb'
  on-primary: '#5d0056'
  primary-container: '#aa189d'
  on-primary-container: '#ffccf0'
  inverse-primary: '#a8159b'
  secondary: '#f0b0ff'
  on-secondary: '#54006d'
  secondary-container: '#9003b9'
  on-secondary-container: '#f3baff'
  tertiary: '#ffade3'
  on-tertiary: '#59104a'
  tertiary-container: '#92437d'
  on-tertiary-container: '#ffcceb'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffd7f2'
  primary-fixed-dim: '#ffaceb'
  on-primary-fixed: '#390034'
  on-primary-fixed-variant: '#830079'
  secondary-fixed: '#fbd7ff'
  secondary-fixed-dim: '#f0b0ff'
  on-secondary-fixed: '#330044'
  on-secondary-fixed-variant: '#770099'
  tertiary-fixed: '#ffd8ee'
  tertiary-fixed-dim: '#ffade3'
  on-tertiary-fixed: '#3a0030'
  on-tertiary-fixed-variant: '#742962'
  background: '#230a1e'
  on-background: '#ffd7f1'
  surface-variant: '#482b41'
typography:
  display-brand:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  code-data:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.5'
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  slogan:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '300'
    lineHeight: '1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 48px
  gutter: 20px
  container-max: 1200px
---

## Brand & Style

The design system is built on the "Critical Operational Support" philosophy—a blend of arcane mysticism and high-precision engineering. Inspired by the duality of life-saving utility and shadow-realm aesthetics, the visual language balances the "Rigor" of technical execution with the "Flash" of unexpected brilliance.

The chosen style is **Mystical Minimalism**. It utilizes a deep, dark canvas to allow vibrant "Utility Beams" of color to direct user attention to critical actions. The atmosphere is one of dark mode efficiency, using electric gradients and subtle glows to simulate "Shadow Wave" energy moving through a structured, technical interface. 

The target audience consists of high-stakes operators and developers who value both distinctive personality and uncompromising reliability.

## Colors

The palette is divided into two conceptual zones: the **Nothl Realm** (Backgrounds) and the **Shadow Wave** (Actions).

- **Nothl Realm:** Uses `#1A0416` as the void. Surfaces are layered using darker tones to create a sense of depth without relying on traditional grey scales.
- **Shadow Wave:** The primary utility beam `#a8159b` provides the structural color for interactive elements, emphasizing a vivid magenta-purple. 
- **Electric Flash:** `#a023c8` is a more intense violet reserved exclusively for hover states, critical notifications, and active "glow" halos to simulate a surge of energy.

Gradients should transition from `Surface High` to `Primary Accent` to suggest energy flowing toward an interaction point.

## Typography

The typography strategy, "Rigor and Flash," employs **Space Grotesk** for brand-heavy moments and headlines to inject a futuristic, geometric personality. For technical data, body copy, and UI labels, **Inter** is used for its exceptional legibility and systematic rigor.

- **Brand Slogan:** Always rendered in `slogan` style, prioritizing a lighter weight and subtle italics to contrast against the bold brand name.
- **Data Display:** For URLs, timestamps, or technical metrics, use the `code-data` style to emphasize precision.
- **Hierarchy:** Use `Text Secondary` for descriptions to ensure the `Text Primary` "mystical white" stands out as the primary narrative path.

## Layout & Spacing

This design system utilizes a **Fixed Grid** philosophy for desktop (12 columns) and a fluid model for mobile. The rhythm is based on a **4px base unit**, ensuring that all components align to a technical, predictable scale.

- **Margins:** Container margins are set to `xl` on desktop to focus content in the center, simulating a "portal" into the system.
- **Gutters:** Tight `gutter` spacing (20px) reinforces the utilitarian, information-dense nature of the operational support theme.
- **Padding:** Use `md` (16px) for internal card padding to maintain a compact, high-density feel.

## Elevation & Depth

Depth is communicated through **Tonal Layering** and **Luminescent Halos** rather than traditional shadows.

1.  **Base:** The `#1A0416` background is the lowest level.
2.  **Surface:** Floating cards use layered surface container values.
3.  **Elevated/Active:** Elements requiring focus use the tertiary background with a 1px border of `Primary Accent`.
4.  **Glow:** High-priority elements or focused inputs receive a `2px` spread outer glow using the `Electric Flash` color (`#a023c8`). This creates an "electric" effect that mimics a magical pulse or technical surge.

Avoid standard black shadows; if a shadow is required for legibility, it must be tinted with the `Primary Accent` color at very low opacity (15-20%).

## Shapes

The shape language is **Soft-Technical**. We have transitioned to a more **Rounded** aesthetic (Roundedness level 2) to soften the aggressive technical grid while maintaining operational clarity.

- **Standard Radius:** 8px (rounded-DEFAULT) for small components (Inputs, Buttons).
- **Container Radius:** 16px (rounded-lg) for Cards and Modals.
- **Interactive States:** On hover, the border-radius remains static, but the "glow" halo follows the 8px curvature perfectly.

## Components

### Buttons
- **Primary:** Background `#a8159b`, Text `#1A0416`. On hover, the background shifts to `#a023c8` with a subtle white text-shadow to simulate "brightening."
- **Secondary/Ghost:** No background, border 1.5px `#a8159b`, Text `#a8159b`. Hover state fills the background with `#a8159b` at 10% opacity.

### Input Fields
- **Default:** Background based on surface levels, Border 1px tertiary, Text on-surface.
- **Focus:** Border changes to `#a8159b` with a `2px #a023c8` glow halo. The transition should be an abrupt "flash" (0.1s ease-out).

### Cards
- **Style:** Background surface level, 16px (rounded-lg) corners. Use a top-border gradient (2px height) from `#a8159b` to `#59104a` for "Critical" cards to denote high-importance operational data.

### Chips/Tags
- Small, uppercase labels using the `label-sm` typography. Background `#59104a` with `Text Secondary` for inactive states, and `Primary Accent` for active/filter states.

### Status Indicators
- **Critical/Heal:** Use the `Electric Flash` color (`#a023c8`) for pulsating dots or progress bars, indicating "active support" or critical system health.