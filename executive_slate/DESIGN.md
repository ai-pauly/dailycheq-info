---
name: Executive Slate
colors:
  surface: '#141313'
  surface-dim: '#141313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353434'
  on-surface: '#e5e2e1'
  on-surface-variant: '#cfc2d6'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#988d9f'
  outline-variant: '#4d4354'
  surface-tint: '#ddb7ff'
  primary: '#ddb7ff'
  on-primary: '#490080'
  primary-container: '#b76dff'
  on-primary-container: '#400071'
  inverse-primary: '#842bd2'
  secondary: '#cfbcff'
  on-secondary: '#3a0092'
  secondary-container: '#6200ea'
  on-secondary-container: '#cfbcff'
  tertiary: '#c4c1fb'
  on-tertiary: '#2d2a5b'
  tertiary-container: '#8e8bc2'
  on-tertiary-container: '#262354'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#f0dbff'
  primary-fixed-dim: '#ddb7ff'
  on-primary-fixed: '#2c0051'
  on-primary-fixed-variant: '#6900b3'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#cfbcff'
  on-secondary-fixed: '#22005d'
  on-secondary-fixed-variant: '#5400cc'
  tertiary-fixed: '#e3dfff'
  tertiary-fixed-dim: '#c4c1fb'
  on-tertiary-fixed: '#181445'
  on-tertiary-fixed-variant: '#444173'
  background: '#141313'
  on-background: '#e5e2e1'
  surface-variant: '#353434'
  slate-surface: '#0F1115'
  glass-stroke: rgba(255, 255, 255, 0.08)
  success-emerald: '#10B981'
  error-rose: '#F43F5E'
  text-dim: '#94A3B8'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  data-point:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: '0'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  container-padding: 24px
  gutter: 16px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system is built for the "Mittelstand" B2B fintech sector, emphasizing absolute security, operational clarity, and premium craftsmanship. The aesthetic blends **Corporate Modernism** with **Glassmorphism**, creating a digital environment that feels like a high-end physical workspace. 

The brand personality is authoritative yet innovative—avoiding the volatile visual language of consumer "fin-tech" in favor of structured, data-dense layouts that provide immediate utility. The UI should evoke a sense of "quiet luxury," where the complexity of financial data is housed within a calm, controlled, and deeply professional interface. High-contrast elements ensure legibility, while glass effects provide a sense of layered organization without clutter.

## Colors

The palette is anchored in a **Deep Dark Mode** strategy. The base is an ultra-black (#030303) used for the canvas, while surfaces are rendered in a slightly lighter "Slate Surface" to provide depth. 

- **Primary Accent:** A vibrant but professional purple (#A855F7) used for high-importance actions and brand identity.
- **Secondary Accent:** A deeper indigo-purple (#7733FF) for interactive states and data visualization.
- **Structural Neutral:** White and high-gray scales are reserved strictly for typography and iconography to maintain a high-contrast ratio against the dark background.
- **Functional Colors:** Success and Error states use highly saturated emeralds and roses, designed to "pop" against the monochromatic base.

## Typography

The typography system uses a tri-font strategy to balance character with utility:
- **Plus Jakarta Sans** provides a modern, geometric feel for headlines and large display values, ensuring the brand feels "current."
- **Inter** handles all body copy and form inputs. Its high x-height and neutral character are essential for the legibility of complex financial information.
- **JetBrains Mono** is utilized sparingly for labels and technical data points (IBANs, transaction IDs), lending a precise, "engineered" feel that resonates with corporate stakeholders.

All headings should use a tight letter-spacing for a more "locked-in" appearance, while data-heavy labels should be in uppercase with generous tracking to aid quick scanning.

## Layout & Spacing

The system follows a strict **4px baseline grid** to ensure mathematical harmony.
- **Desktop:** Uses a 12-column fixed grid with a max-width of 1440px. This creates "breathing room" on the sides, reinforcing a premium, focused dashboard feel.
- **Mobile:** Switches to a fluid single-column layout with 20px side margins.
- **Content Blocks:** Use "Stack" spacing logic. Grouped items (like an icon and its label) use 8px, while unrelated sections use 32px+.

Layout logic should mirror the Framer site: content is vertically stacked in cards that span defined column widths, with clear hierarchical separation between the primary navigation and the operational workspace.

## Elevation & Depth

Depth is established through **Glassmorphism** and **Tonal Layering** rather than traditional drop shadows.
1. **Level 0 (Canvas):** Pure black (#030303).
2. **Level 1 (Cards/Panels):** Slate Surface (#0F1115) with a 1px "Glass-stroke" (8% white).
3. **Level 2 (Overlays/Modals):** A semi-transparent blur (Backdrop-filter: 20px) with a subtle purple-tinted inner glow.

Shadows, when used, are "Ambient Shadows"—extremely diffused, large-radius glows that use the primary purple color at 5-10% opacity, making the components appear as if they are floating above a light source.

## Shapes

The shape language is "Structural." This means edges are primarily crisp to maintain a serious corporate tone, but with enough rounding to feel premium and ergonomic.
- **Base Components (Inputs, Small Buttons):** 8px radius.
- **Containers (Cards, Section Blocks):** 16px radius (rounded-lg).
- **Major Focus Areas (Modals, Large Cards):** 24px radius (rounded-xl).

Avoid any perfectly circular "pill" shapes for buttons unless they are icon-only triggers; a rectangular button with 8px rounding feels more stable and "German-industrial" than a bubbly pill.

## Components

- **Buttons:** Primary buttons use a solid gradient from Secondary to Primary purple. Secondary buttons are "Ghost" style with the 1px glass-stroke and Inter SemiBold text.
- **Inputs:** Fields are dark (#030303) with a 1px border that glows Purple when focused. Labels always use JetBrains Mono in caps above the field.
- **Cards:** Financial data is housed in cards with the "Slate-surface" background. Use a subtle top-to-bottom linear gradient (White 4% to White 0%) to simulate a light source from above.
- **Chips:** Used for statuses (e.g., "LIVE", "PENDING"). These should be small, 12px Mono text, with a subtle background tint of the status color (e.g., 10% Emerald for "LIVE").
- **Charts:** Lines should use a 2px stroke with a "Money Stream" glow effect. Data points should be sharp circles (4px) with high-contrast fills.
- **Navigation:** A floating bottom bar or fixed left sidebar using the Glassmorphism style, ensuring the main canvas remains the focus of the user's workflow.