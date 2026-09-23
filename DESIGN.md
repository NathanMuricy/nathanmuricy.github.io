---
name: Nathan Muricy Portfolio Design System
colors:
  surface: '#16083b'
  surface-dim: '#16083b'
  surface-bright: '#3c3163'
  surface-container-lowest: '#100336'
  surface-container-low: '#1e1243'
  surface-container: '#221748'
  surface-container-high: '#2d2253'
  surface-container-highest: '#382d5e'
  on-surface: '#e7deff'
  on-surface-variant: '#cac4d2'
  inverse-surface: '#e7deff'
  inverse-on-surface: '#33285a'
  outline: '#938f9b'
  outline-variant: '#484550'
  surface-tint: '#cbbeff'
  primary: '#cbbeff'
  on-primary: '#33236c'
  primary-container: '#4e3f88'
  on-primary-container: '#c0b0ff'
  inverse-primary: '#62539d'
  secondary: '#ffb1c7'
  on-secondary: '#640231'
  secondary-container: '#86214a'
  on-secondary-container: '#ff9bb9'
  tertiary: '#d5cb00'
  on-tertiary: '#353200'
  tertiary-container: '#b8af00'
  on-tertiary-container: '#454100'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e7deff'
  primary-fixed-dim: '#cbbeff'
  on-primary-fixed: '#1e0857'
  on-primary-fixed-variant: '#4a3b84'
  secondary-fixed: '#ffd9e2'
  secondary-fixed-dim: '#ffb1c7'
  on-secondary-fixed: '#3f001c'
  on-secondary-fixed-variant: '#831f48'
  tertiary-fixed: '#f3e700'
  tertiary-fixed-dim: '#d5cb00'
  on-tertiary-fixed: '#1e1c00'
  on-tertiary-fixed-variant: '#4c4800'
  background: '#16083b'
  on-background: '#e7deff'
  surface-variant: '#382d5e'
typography:
  display-hero:
    fontFamily: Bebas Neue
    fontSize: 96px
    fontWeight: '400'
    lineHeight: 92px
    letterSpacing: 0.04em
  display-hero-mobile:
    fontFamily: Bebas Neue
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 56px
    letterSpacing: 0.03em
  headline-lg:
    fontFamily: Bebas Neue
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: 0.03em
  headline-lg-mobile:
    fontFamily: Bebas Neue
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 42px
    letterSpacing: 0.02em
  headline-md:
    fontFamily: Bebas Neue
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 38px
    letterSpacing: 0.02em
  headline-sm:
    fontFamily: Bebas Neue
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.03em
  title-lg:
    fontFamily: Open Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
  body-lg:
    fontFamily: Open Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Open Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Open Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Open Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Open Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes the visual and architectural language for the personal portfolio of a multidisciplinary Graphic Designer and Front-end Developer. The aesthetic bridges high-energy graphic design with meticulous programmatic structure.

The design movement is **High-Contrast Bold meets Neo-Brutalism**: sharp structural tension, confident color blocking, geometric clarity, and deliberate typographic drama. Rooted deeply in Robin Williams' **C.R.A.P.** principles:
- **Contrast:** Dramatic scale differences between compressed display typography and structured body copy, reinforced by vibrant clashing accents against deep, saturated backgrounds.
- **Repetition:** Consistent geometric block silhouettes, hairline stroke accents, distinct accent borders, and recurrent color pairings for interaction states.
- **Alignment:** Unyielding vertical and horizontal baselines, razor-sharp edge alignments, and crisp multi-column discipline that visually communicates code craftsmanship.
- **Proximity:** Strict spatial grouping to differentiate code-level meta tags, design case study narratives, and technical toolings without visual clutter.

The experience commands authority, technical capability, creative fearlessness, and tactile precision.

## Colors

The color architecture is built around dynamic color-blocking inspired by contemporary editorial design and dark-mode coding environments.

- **Primary (`#4e3f88`):** Deep Vibrant Violet. Functions as the signature brand tone, primary surface layer, and structural container tone.
- **Neutral Deep (`#312657`):** Obsidian Purple. Serves as the bedrock canvas background, card baselines, and lowest tonal foundation.
- **Secondary (`#e97099`):** Punchy Magenta Pink. Deployed for high-energy accents, category tags, interactive states, and graphic dividers.
- **Tertiary Accent (`#f5e900`):** Electric Neon Yellow. Reserved for primary calls to action, focus indicators, highlight underlines, and crucial badges.
- **Complementary Cyan (`#33d8ca`):** Digital Turquoise. Acts as a syntax and status indicator, code snippet highlight, and creative tag identifier.
- **Light Contrast Base (`#f7f6f2`):** Warm Off-White. Provides stark editorial contrast for light-theme modals, pill labels, and crisp typography rendering over dark surfaces.

Accessibility rules enforce high legibility: Electric Yellow and Cyan strictly host dark text (`#312657`), while Purple and Obsidian foundations carry pure white or light off-white copy.

## Typography

Typographic scale is structured around aggressive contrast between condensed impact and humanist readability:

- **Display & Headings (`Bebas Neue`):** Condensed, geometric, and assertive. All headline levels are set in uppercase to maximize poster-like weight and structural alignment. Letter-spacing is intentionally relaxed slightly (`0.02em` to `0.04em`) to ensure optical balance across large formats.
- **Body & Information Delivery (`Open Sans` / Humanist Sans):** Chosen for balanced geometric neutralism and high screen legibility. Ensures dense code blocks, project case descriptions, and methodology breakdowns maintain effortless clarity.
- **Labels & Microcopy:** Rendered with elevated tracking (`0.06em` to `0.08em`) and semi-bold weights for rapid scannability in project tags, tech stacks, and metadata indicators.

## Layout & Spacing

The layout is built upon an 8pt architectural rhythm using a 12-column grid on desktop and a 4-column grid on mobile devices.

- **Desktop (12 Columns):** Fixed max-width container of `1280px`, with 24px (`1.5rem`) gutters and generous 48px (`3rem`) margins. Allows split editorial columns—such as sticky oversized headlines paired with scrolling project feeds.
- **Tablet (8 Columns):** Fluid grid with 20px gutters and 32px margins.
- **Mobile (4 Columns):** Fluid grid with 16px (`1rem`) gutters and 20px (`1.25rem`) edge margins. Headlines collapse cleanly to preserve proportional impact without horizontal overflow.
- **Vertical Spacing & Proximity:** Component internals rely strictly on `space-xs` and `space-sm` for unified cohesion, while sections separate boldly using `space-xl` and higher multiples to establish unmistakable thematic shifts.

## Elevation & Depth

This system intentionally rejects muddy, generic drop shadows in favor of **Tonal Layers and Neo-Brutalist Hard Offsets**:

- **Ground Level (Base):** Deep Obsidian (`#312657`). Forms the canvas foundation.
- **Tier 1 (Surface Containers):** Deep Vibrant Violet (`#4e3f88`) or stark contrasting blocks with zero blur.
- **Hard Cast Shadows:** Interactive cards and active elements project a crisp, unblurred hard shadow: `4px 4px 0px #000000` or `4px 4px 0px #f5e900`. This reinforces the tactile, engineered feel of modern developer interfaces.
- **Hairline Structural Borders:** Crisp, solid 1px or 2px borders using high-contrast tones (`#f5e900`, `#e97099`, or `#33d8ca`) replace subtle gradients, maintaining a graphic art feel.
- **Overlays & Modals:** Sharp solid backdrops with high-contrast outlines and a pure deep opacity tint (`rgba(49, 38, 87, 0.85)`).

## Shapes

The shape system adopts a **Soft Geometric (`roundedness: 1`)** standard.

- Standard UI containers, cards, and input fields utilize `4px` (`0.25rem`) border radii, striking the balance between the precision of terminal command lines and modern interface polish.
- Large portfolio display cards and modal dialogs use `8px` (`rounded-lg`).
- Interactive pills, tags, and category chips retain flat rectangular or subtle chamfered corners rather than pill shapes, upholding the strong block-based graphic language.

## Components

### Buttons
- **Primary CTA:** Solid Neon Yellow (`#f5e900`) background, Dark Obsidian (`#312657`) bold text, uppercase `Bebas Neue` or bold sans, `4px 4px 0px #000000` hard shadow. On hover, translate `-2px, -2px` with expanded shadow (`6px 6px 0px #000000`). On active, translate `2px, 2px` with zero shadow.
- **Secondary Action:** Magenta Pink (`#e97099`) surface with white or deep violet text.
- **Tertiary / Ghost:** Transparent background, 2px solid border (`#33d8ca`), text in `#33d8ca`. Hover state fills the background solid with `#33d8ca` and inverts text to `#312657`.

### Chips & Tech Badges
- Compact rectangles with 4px border radius.
- Categorized by domain:
  - **Design / Creative:** Magenta Pink (`#e97099`) background or border.
  - **Code / Front-End:** Digital Turquoise (`#33d8ca`) background or border.
  - **Tools / Frameworks:** Deep Violet background with bright yellow typography.

### Cards (Portfolio & Case Studies)
- Composed of modular color blocks.
- Container: `#4e3f88` or `#312657` with a 1px solid `#e97099` or `#33d8ca` stroke.
- Header block: Distinct contrasting color banner hosting project categories and year in Bebas Neue.
- Image area: High-contrast frame with crisp 2px inner borders.

### Input Fields & Controls
- **Inputs:** Dark Obsidian background (`#312657`), 2px solid primary violet border, crisp white text. Focus state triggers a 2px solid Neon Yellow (`#f5e900`) outline without fuzzy glows.
- **Checkboxes & Radios:** Sharp square and clipped geometric geometries with 2px borders. Checked state filled with Neon Yellow and a solid black marker.

### Custom Component: Terminal / Code Inspector Box
- Dedicated component for showcasing front-end capabilities alongside design assets.
- Dark Obsidian body with a 3-dot bar in Magenta, Yellow, and Cyan. Monospaced code snippets highlighting technical architecture, stack decisions, and live links.