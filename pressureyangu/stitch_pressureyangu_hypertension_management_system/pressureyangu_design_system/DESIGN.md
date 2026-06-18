---
name: PressureYangu Design System
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daea'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eefe'
  surface-container-high: '#e2e8f8'
  surface-container-highest: '#dce2f3'
  on-surface: '#151c27'
  on-surface-variant: '#444653'
  inverse-surface: '#2a313d'
  inverse-on-surface: '#ebf1ff'
  outline: '#757684'
  outline-variant: '#c4c5d5'
  surface-tint: '#3755c3'
  primary: '#00288e'
  on-primary: '#ffffff'
  primary-container: '#1e40af'
  on-primary-container: '#a8b8ff'
  inverse-primary: '#b8c4ff'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#4c2e00'
  on-tertiary: '#ffffff'
  tertiary-container: '#6b4200'
  on-tertiary-container: '#ffa929'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b8c4ff'
  on-primary-fixed: '#001453'
  on-primary-fixed-variant: '#173bab'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f9f9ff'
  on-background: '#151c27'
  surface-variant: '#dce2f3'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  data-display:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.03em
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
  margin-desktop: 40px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is anchored in the dual necessity of clinical authority and compassionate patient care. It targets a broad demographic in the Kenyan market, ranging from tech-savvy youth managing family health to elderly patients requiring high legibility and intuitive navigation.

The style is **Professional / Modern** with a strong emphasis on **Accessibility**. It utilizes a card-based architecture to modularize complex health data, making it digestible and less intimidating. To foster local resonance, the design system incorporates subtle geometric patterns inspired by Kenyan beadwork as low-opacity decorative backgrounds or dividers, ensuring the product feels homegrown and culturally relevant without sacrificing its medical precision.

The emotional response should be one of "calm empowerment"—reducing the anxiety often associated with medical monitoring through generous whitespace and a clear, guided information hierarchy.

## Colors

The palette is functional and semantic, prioritizing immediate comprehension of health status:

- **Primary (Health Blue):** Used for primary actions, branding, and navigation. It establishes trust and stability.
- **Secondary (Life Green):** Reserved for "Normal" blood pressure readings and success states, reinforcing positive health outcomes.
- **Warning Amber:** Used for "Elevated" or "Pre-hypertension" readings, signaling caution without inducing panic.
- **Critical Red:** Strictly reserved for "Hypertensive Crisis" alerts and destructive actions.
- **Neutrals:** A range of soft grays are used for borders, secondary text, and surface backgrounds to maintain a clean, sterile, yet warm environment.

Backgrounds are kept white to maximize contrast and maintain a clinical feel, while light gray surfaces are used to group related health metrics.

## Typography

This design system utilizes **Inter** for its exceptional legibility and modern, neutral tone. Given the elderly target audience, font sizes are scaled up significantly compared to standard SaaS applications.

- **Headlines:** Bold and impactful to provide clear context of the current view.
- **Body Text:** Increased line-height (1.5x minimum) to reduce cognitive load during reading.
- **Data Display:** A specific role for blood pressure numbers (e.g., 120/80), using high-weight, tight letter spacing to ensure they are the most prominent element on the screen.
- **Accessibility:** Never use font sizes below 14px. Primary body text should default to 18px on health summary screens.

## Layout & Spacing

The layout follows a **Fluid Grid** system based on an 8px spacing logic. 

- **Desktop:** 12-column grid with a maximum width of 1280px to prevent line lengths from becoming too long for easy reading.
- **Mobile:** Single column layout with 16px side margins. Elements like health cards should stretch to the margins.
- **Rhythm:** Vertical rhythm is strictly enforced using `stack` units. Heavy spacing (32px+) is used to separate distinct health metrics (e.g., Blood Pressure vs. Heart Rate) to ensure no visual overlap or confusion.
- **Touch Targets:** All interactive elements maintain a minimum hit area of 48x48px to accommodate users with limited dexterity.

## Elevation & Depth

This design system uses **Tonal Layers** combined with **Ambient Shadows** to create a clear sense of interactability and hierarchy.

- **Level 0 (Background):** Pure white (#FFFFFF).
- **Level 1 (Sectioning):** Light gray (#F3F4F6) with no shadow. Used for grouping items within a page.
- **Level 2 (Cards):** White background with a very soft, diffused shadow (10% opacity, 12px blur, 4px Y-offset) using the Primary color as a tint for the shadow. This indicates the element is interactive or contains critical data.
- **Level 3 (Modals/Popovers):** Higher elevation with a 20% opacity shadow and a 1px neutral-200 border for crisp definition against the white background.

## Shapes

The shape language is **Rounded**, avoiding sharp edges to appear more approachable and less "clinical" in a sterile sense.

- **Primary Radius:** 0.5rem (8px) for buttons and input fields.
- **Large Radius:** 1rem (16px) for cards and containers, creating a friendly, "holding" aesthetic for data.
- **Buttons:** Large buttons use a 0.5rem radius, while smaller utility tags (chips) can be fully rounded (pill-shaped) to distinguish them from actionable buttons.

## Components

### Buttons
Primary buttons use the 'Health Blue' background with white text. Secondary buttons use a 'Health Blue' 2px border with a transparent background. All buttons must have a height of at least 48px on mobile.

### Cards
The core of the UI. Cards represent "Health Records." They should have a 16px padding, a 1px light gray border, and a Level 2 shadow. The top edge of the card may include a 4px colored accent bar (Green, Amber, or Red) to indicate status at a glance.

### Input Fields
Large, accessible inputs with 16px internal padding. Labels are always visible (never use placeholder-only labels) to ensure users don't lose context. Error states use a 2px 'Critical Red' border.

### Status Chips
Small indicators for health trends (e.g., "Stable," "Improving"). Use low-saturation versions of the semantic colors for backgrounds with high-saturation text for contrast.

### Icons
Use a thick-stroke (2px) rounded icon set. Icons should be paired with text labels whenever possible to ensure universal understanding, especially for the elderly.

### Local Accents
Use a subtle, repeating geometric pattern as a background footer element or a header texture, rendered in #F3F4F6 on white background to keep it unobtrusive.