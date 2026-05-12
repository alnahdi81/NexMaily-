---
name: Velocity Auction System
colors:
  surface: '#fcf8f8'
  surface-dim: '#ddd9d9'
  surface-bright: '#fcf8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f1eded'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#44474a'
  inverse-surface: '#313030'
  inverse-on-surface: '#f4f0ef'
  outline: '#75777a'
  outline-variant: '#c5c6ca'
  surface-tint: '#5d5e61'
  primary: '#000101'
  on-primary: '#ffffff'
  primary-container: '#1a1c1e'
  on-primary-container: '#838486'
  inverse-primary: '#c6c6c9'
  secondary: '#bb0027'
  on-secondary: '#ffffff'
  secondary-container: '#e51a38'
  on-secondary-container: '#fffbff'
  tertiary: '#000001'
  on-tertiary: '#ffffff'
  tertiary-container: '#191c20'
  on-tertiary-container: '#818489'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e5'
  primary-fixed-dim: '#c6c6c9'
  on-primary-fixed: '#1a1c1e'
  on-primary-fixed-variant: '#454749'
  secondary-fixed: '#ffdad8'
  secondary-fixed-dim: '#ffb3b1'
  on-secondary-fixed: '#410007'
  on-secondary-fixed-variant: '#92001d'
  tertiary-fixed: '#e0e2e8'
  tertiary-fixed-dim: '#c4c6cc'
  on-tertiary-fixed: '#181c20'
  on-tertiary-fixed-variant: '#44474b'
  background: '#fcf8f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Tajawal
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Tajawal
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Tajawal
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Almarai
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Almarai
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-bold:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  price-display:
    fontFamily: Work Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.1'
  headline-lg-mobile:
    fontFamily: Tajawal
    fontSize: 26px
    fontWeight: '700'
    lineHeight: '1.3'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 1.5rem
  margin-mobile: 1rem
  section-gap: 4rem
  card-gap: 1.5rem
---

## Brand & Style

This design system is engineered for a high-stakes, professional car auction environment. The brand personality is **authoritative, precise, and high-octane**. It balances the technical precision of automotive engineering with the urgency of a live marketplace.

The visual style follows a **Corporate Modern** aesthetic with **Tactile** accents. It prioritizes clarity and speed, ensuring users can make split-second bidding decisions without cognitive overload. The interface leverages high-end photography as a primary design element, framed by clean, structured layouts that reflect the premium nature of the vehicles listed. The emotional goal is to evoke a sense of exclusive access and absolute reliability.

## Colors

The palette is anchored by **Deep Charcoal (#1A1C1E)** to provide a sophisticated, heavy contrast against the light background. **Metallic Silver (#E2E4E9)** is used for structural dividers and secondary surfaces to mimic automotive materials.

**Racing Red (#E31837)** is reserved strictly for high-priority actions: Call to Actions (CTAs), live "Hot" auction indicators, and final countdown timers. **Subtle Blue (#0052CC)** functions as a trust anchor, utilized for verified seller badges, inspection report links, and secure payment icons. The background maintains a **Very Light Grey (#F8F9FA)** to reduce glare and ensure car photography pops.

## Typography

This design system utilizes a dual-language typographic approach. **Tajawal** is the primary choice for headings due to its modern, architectural structure that complements automotive design. For body text, **Almarai** provides exceptional legibility for technical car specifications and bidding history.

**Work Sans** is used specifically for numerical data, such as VIN numbers, prices, and odometer readings, ensuring that characters remain distinct and easy to scan. Hierarchies are strictly enforced to guide the user from the vehicle name (Headline) down to the bid status (Label).

## Layout & Spacing

The design system employs a **Fixed Grid** model for desktop to maintain a high-end, editorial feel, transitioning to a fluid layout for mobile devices. 

- **Desktop:** A 12-column grid with a 1280px max-width. Content is grouped in logical clusters using generous white space to prevent the "cluttered marketplace" look.
- **Tablet:** 8-column grid with reduced margins.
- **Mobile:** 4-column grid where cards stack vertically, utilizing the full width to showcase vehicle imagery.

Vertical rhythm is maintained through a base 8px spacing unit. Car listing cards use a consistent 24px internal padding to ensure data isn't cramped against the edges.

## Elevation & Depth

Hierarchy is established using **Tonal Layers** and **Ambient Shadows**. 

The base background is at Level 0. Car cards sit at Level 1 with a very soft, diffused shadow (15% opacity Deep Charcoal, 20px blur) to appear slightly lifted. Interactive elements, like the "Place Bid" input area, use a slight inner shadow to create a tactile, recessed feel, suggesting it is a functional "console" area. 

Hover states on listing cards increase the shadow spread and slightly shift the Y-axis to give a responsive, physical feedback to the user.

## Shapes

In alignment with the Salla platform style, this design system uses a **Rounded (Level 2)** shape language. This softens the "industrial" feel of the car auction, making the professional environment more approachable and modern.

- **Standard Buttons:** 0.5rem (8px) radius.
- **Listing Cards:** 1rem (16px) radius to frame photography elegantly.
- **Input Fields:** 0.5rem (8px) radius.
- **Status Tags (e.g., "Live"):** Pill-shaped (Full radius) to distinguish them from functional buttons.

## Components

### Buttons
Primary CTAs (e.g., "Bid Now") use **Racing Red** with white text. Secondary buttons (e.g., "View Details") use the **Deep Charcoal** or a **Metallic Silver** outline. All buttons feature a subtle transition effect on hover.

### Car Listing Cards
These are the core components. They feature a 16:9 image ratio at the top, followed by a bold title, a three-point spec summary (Year, Mileage, Transmission), and a high-contrast footer containing the current price and the time remaining.

### Bidding Status Indicators
- **Live:** A pulsing Racing Red dot next to "Live Auction".
- **Winning:** A Subtle Blue badge with a checkmark.
- **Outbid:** A Deep Charcoal badge with an alert icon.

### Input Fields
Bidding inputs should feel substantial. They use a larger font size for the currency and a "Quick Increment" button (+$500, +$1000) styled as soft-grey chips to facilitate fast-paced interaction.

### Progress Bars
Auction countdowns utilize a thin, high-contrast bar. If an auction is in "Overtime" (last 2 minutes), the bar changes from Charcoal to Red to increase urgency.