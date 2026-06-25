---
name: MHS CART
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#3f484c'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#6f787d'
  outline-variant: '#bfc8cd'
  surface-tint: '#0c6780'
  primary: '#0c6780'
  on-primary: '#ffffff'
  primary-container: '#87ceeb'
  on-primary-container: '#005870'
  inverse-primary: '#89d0ed'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dfe0e0'
  on-secondary-container: '#616363'
  tertiary: '#565e74'
  on-tertiary: '#ffffff'
  tertiary-container: '#bcc4de'
  on-tertiary-container: '#495167'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#baeaff'
  primary-fixed-dim: '#89d0ed'
  on-primary-fixed: '#001f29'
  on-primary-fixed-variant: '#004d62'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#dae2fd'
  tertiary-fixed-dim: '#bec6e0'
  on-tertiary-fixed: '#131b2e'
  on-tertiary-fixed-variant: '#3f465c'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 32px
  xl: 48px
  margin-mobile: 20px
  gutter-mobile: 12px
---

## Brand & Style

This design system is built for a premium, high-end e-commerce experience that prioritizes clarity, breathability, and tactile sophistication. The brand persona is "Curated Elegance"—it feels light and airy yet technically precise. 

The aesthetic leverages **Minimalist Glassmorphism**. We move away from heavy solid surfaces in favor of translucent layers, soft background blurs, and whisper-thin borders. This creates a sense of depth and hierarchy without the visual clutter of traditional shadows. The interface should feel like a series of polished glass panes floating in a bright, ethereal space, evoking a premium shopping environment that lets the products take center stage.

## Colors

The palette is anchored by **Sky Blue (#87CEEB)**, used strategically for primary actions and brand accents to maintain a calm, trustworthy atmosphere. 

- **Primary:** Sky Blue is used for "Add to Cart" buttons, active navigation states, and price highlights.
- **Surface:** The "White" palette is primarily expressed through glass surfaces. In Light Mode, surfaces use a highly translucent white with a 20px-40px backdrop blur. 
- **On-Surface:** Slate-900 (#0F172A) is the primary text color, providing high-contrast readability against the airy background.
- **Dark Mode:** Surfaces shift to a deep Slate-950 with 40% opacity, maintaining the glass effect while protecting night-time viewing.

## Typography

We use **Inter** for its systematic perfection and readability at small sizes. The typographic hierarchy relies on weight and tight tracking for headlines to create a "editorial" feel. 

Headlines use a semi-bold weight with slight negative letter-spacing to feel premium and compact. Body text is set with generous line heights (1.6) to ensure the interface feels open and easy to scan. Labels for categories and price tags use increased letter spacing and uppercase styling to provide a distinct visual anchor against product titles.

## Layout & Spacing

This design system utilizes a **Fluid Grid** system optimized for mobile-first consumption. The layout follows an 8px rhythmic scale to ensure consistent alignment.

- **Mobile:** A 2-column grid is standard for product listings, using 20px outer margins and 12px internal gutters.
- **Vertical Spacing:** Generous whitespace (32px - 48px) is used between logical sections (e.g., "Related Products" vs "Product Details") to reinforce the minimalist brand values.
- **Safe Areas:** All interactive elements maintain a minimum 44px touch target height to ensure accessibility on mobile devices.

## Elevation & Depth

Depth is not communicated through heavy drop shadows but through **Layered Translucency**. 

- **Level 1 (Base):** The application background, usually a soft gradient of sky blue and white.
- **Level 2 (Glass Cards):** Use a 70% white fill with a 20px backdrop blur. These carry a very subtle, diffused 15% opacity sky-blue shadow to lift them off the base.
- **Level 3 (Modals/Popovers):** Higher opacity (85%) with a more pronounced 40px backdrop blur and a crisp 1px solid white border at 40% opacity.

The key to this depth model is the 1px interior border on glass elements, which simulates the light-catching edge of a physical pane of glass.

## Shapes

The shape language is defined by **Rounded-2XL** corners. This softness counteracts the "cold" nature of glass and makes the app feel approachable and modern.

- **Product Cards:** Use 1.5rem (24px) corner radii.
- **Buttons:** Use fully pill-shaped (rounded-full) corners to denote high interactivity.
- **Inputs:** Use 0.75rem (12px) corners for a more structured, functional feel.
- **Inner Elements:** When nesting elements (like a chip inside a card), the inner radius should be 4-8px smaller than the outer radius to maintain visual harmony.

## Components

### Buttons
Primary buttons use a solid Sky Blue fill with white text. Secondary buttons use the "Glass" style (translucent white) with a 1px border. Interactive states should involve a subtle scale-down (0.98) on tap and a slight increase in backdrop blur opacity.

### Glass Cards
The core container. Cards must have `backdrop-filter: blur(20px)` and a `border: 1px solid rgba(255, 255, 255, 0.4)`. The content inside should have a padding of 16px to 24px.

### Inputs
Search bars and form fields use a "Recessed Glass" look—slightly darker than the card they sit on, with an inner shadow to suggest depth. The active state is indicated by the border glowing in Sky Blue.

### Chips & Badges
Small, pill-shaped glass elements used for categories or "New Arrival" tags. These should have a lower blur radius (8px) to keep text sharp.

### Navigation Bar
A fixed glass bar at the bottom (mobile) or top (desktop). It uses a heavy backdrop blur (50px) to ensure that content scrolling underneath does not interfere with the legibility of the icons.