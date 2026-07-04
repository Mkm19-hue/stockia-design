---
name: Stockia Design System
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#434655'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#784b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#996100'
  on-tertiary-container: '#ffeedd'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  currency-display:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  baseline: 4px
  container-padding: 16px
  stack-gap: 12px
  section-gap: 24px
  grid-columns-mobile: '4'
  grid-columns-tablet: '8'
  grid-columns-desktop: '12'
---

## Brand & Style
The design system is engineered for the modern Malagasy merchant, blending the structured reliability of Material Design 3 with the refined, high-performance aesthetic of top-tier fintech platforms. It targets professional efficiency, offering a "Google Play ready" experience that feels both native to Android and premium in its execution.

The style is **Minimalist / Corporate Modern**. It prioritizes precision through clear data visualization, generous whitespace to reduce cognitive load during busy retail hours, and a sophisticated interplay of light and depth. The emotional response is one of institutional trust and fluid technological empowerment.

## Colors
The palette is rooted in a "Trust Blue" primary, used for core actions and brand identity. The secondary "Growth Green" is strictly reserved for positive financial indicators and successful transaction states, while the accent "Alert Orange" highlights pending tasks or low stock levels.

- **Primary (#2563EB):** Logic, loyalty, and brand presence.
- **Secondary (#10B981):** Profit, inventory health, and "Success" states.
- **Tertiary (#F59E0B):** Attention, warnings, and "Pending" states.
- **Neutral:** A range of slates used for typography and de-emphasized UI elements.

In Dark Mode, the background shifts to a deep charcoal to maintain contrast ratios and reduce eye strain in low-light market environments.

## Typography
The system utilizes **Inter** for its exceptional legibility on mobile screens and its neutral, professional tone. For specialized data like currency (Ariary) and SKU codes, **JetBrains Mono** is employed as the label font to provide a technical, "Linear-like" precision that aids in rapid scanning of numbers.

**Localization Rules:**
- **Currency:** Always format as `1.000 Ar` with a non-breaking space.
- **Dates:** Strictly `DD/MM/YYYY` (e.g., 25/12/2023).
- **Language:** UI strings should account for French word lengths, which often exceed English equivalents by 20-30%.

## Layout & Spacing
Following Material Design 3 principles, the layout uses a **4px baseline grid**. 

- **Margins:** A standard 16px outer margin for mobile, increasing to 24px on tablets.
- **Touch Targets:** Minimum 48x48dp for all interactive elements to ensure ease of use in fast-paced retail settings.
- **Grid:** Use a fluid grid where cards typically span the full width on mobile but reflow into 2 or 3 columns on tablets to maximize dashboard utility.

## Elevation & Depth
Depth is communicated through **Tonal Layers** and **Ambient Shadows**, avoiding heavy drop shadows for a cleaner, flatter "Stripe-inspired" look.

- **Level 0 (Surface):** The base background (#F9FAFB).
- **Level 1 (Cards):** White background with a 1px border (#E2E8F0) or a very soft, diffused shadow (0px 2px 4px rgba(0,0,0,0.05)).
- **Level 2 (Modals/Menus):** Elevated with a medium-diffused shadow to draw focus.
- **Interaction:** On press, elements should "sink" slightly (shadow reduction) rather than lift, emphasizing a tactile, responsive feel.

## Shapes
This design system uses a **Rounded** shape language to feel approachable yet professional.

- **Standard Components:** 16px (1rem) corner radius for cards and primary input fields.
- **Buttons:** 12px corner radius to distinguish them slightly from larger containers.
- **Small Elements:** 8px for chips and checkboxes.
- **Icons:** Use "Rounded" or "Soft" icon sets (e.g., Material Symbols Rounded) to match the UI's corner radius.

## Components
- **Buttons:** Primary buttons use a solid #2563EB fill with white text. Secondary buttons use a tonal grey or outline style. No heavy gradients; use subtle 2% brightness shifts on hover/press.
- **Inputs:** Outlined style with a 16px radius. The label sits on the border (Material 3 style). Active state uses a 2px Primary Blue border.
- **Cards:** The workhorse of the app. Use a white background, 16px radius, and a subtle 1px border. Internal padding should be a generous 16px or 20px.
- **Chips:** Used for "In Stock", "Out of Stock", and "Low Stock" statuses. Use low-opacity backgrounds of the status color (e.g., Green at 10% opacity) with high-contrast text.
- **Data Tables:** High-density but legible. Use JetBrains Mono for Ariary values to ensure decimal alignment.
- **Bottom Navigation:** Clean icons with short French labels. Active state indicated by a pill-shaped tonal highlight behind the icon.