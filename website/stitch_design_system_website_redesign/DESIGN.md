---
name: Quiet Ledger
colors:
  surface: '#faf9f6'
  surface-dim: '#dbdad3'
  surface-bright: '#fbfaf2'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f4ec'
  surface-container: '#efeee6'
  surface-container-high: '#e9e8e1'
  surface-container-highest: '#e4e3db'
  on-surface: '#1b1c1a'
  on-surface-variant: '#45483d'
  inverse-surface: '#30312c'
  inverse-on-surface: '#f2f1e9'
  outline: '#75786b'
  outline-variant: '#c5c8b9'
  surface-tint: '#51652f'
  primary: '#384b18'
  on-primary: '#ffffff'
  primary-container: '#4f632d'
  on-primary-container: '#c6de9b'
  inverse-primary: '#b7cf8d'
  secondary: '#51652f'
  on-secondary: '#ffffff'
  secondary-container: '#d0e8a5'
  on-secondary-container: '#556933'
  tertiary: '#60365b'
  on-tertiary: '#ffffff'
  tertiary-container: '#7a4d74'
  on-tertiary-container: '#fcc4f1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d3eba7'
  primary-fixed-dim: '#b7cf8d'
  on-primary-fixed: '#131f00'
  on-primary-fixed-variant: '#3a4d19'
  secondary-fixed: '#d3eba7'
  secondary-fixed-dim: '#b7cf8e'
  on-secondary-fixed: '#131f00'
  on-secondary-fixed-variant: '#3a4d19'
  tertiary-fixed: '#ffd7f5'
  tertiary-fixed-dim: '#edb5e2'
  on-tertiary-fixed: '#310c2f'
  on-tertiary-fixed-variant: '#62385d'
  background: '#f9fbeb'
  on-background: '#1a1d13'
  surface-variant: '#e2e4d4'
  outline-ghost: '#c6c8b8'
  warning-amber: '#b78220'
  error-red: '#ba1a1a'
typography:
  display-lg:
    fontFamily: Newsreader
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Newsreader
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  headline-sm:
    fontFamily: Newsreader
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Manrope
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  financial-data:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 2rem
  margin-mobile: 1rem
  margin-desktop: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4rem
---

## Brand & Style

This design system establishes an archival, contemplative financial space tailored for domestic accounting, shared households, and intentional ledgers. Rooted in tactile editorial minimalism, the interface deliberately rejects the urgent, gamified ethos of contemporary fintech. It acts not as a scolding manager, but as an observational, calm physical journal rendered in digital form.

### Voice and Tone
The brand voice is strictly observational and emotionally restrained. It avoids congratulatory flourishes, alarmist banners, or moralizing advice. Transactions are stated with dispassionate clarity:
- **Recorded** replaces "saved."
- **Voided** replaces "deleted."
- **Superseded** replaces "edited."
- **Pooled** serves as the default state, with **split** as an explicit secondary partition.

### Visual Character
The aesthetic relies on physical print references: warm paper-grain surfaces, dense deep ink typography, hairline ghost borders, and vegetal moss-green accents. Financial tension is softened through deliberate color restraint; monetary boundaries trigger dusty amber alerts rather than punitive reds, treating financial records with dignity and permanence.

## Colors

The color system is calibrated around tactile paper stocks and organic mineral inks. Light mode is the default state to preserve the warm stationery experience.

### Core Roles & Palette Philosophy
- **Primary (`#4f632d` — Obsidian Sage):** An understated, earthy olive used for purposeful interactive moments, focus indicators, active ledger states, and affirmative commitment buttons.
- **Secondary (`#51652f`):** A tonal sibling to the primary tone, deployed across subtle category pills, badge backdrops, and active tab highlights.
- **Tertiary (`#60365b` — Archival Plum):** A muted, deep violet reserved for retrospective annotations, long-range planning metrics, and partner contributions.
- **Neutral (`#75786b`):** Balanced, low-chroma slate derived from graphite. Defines neutral outlines, metadata stamps, and muted iconography.

### Financial Guardrails
- **Zero Red for Monetary Balances:** Deficits, negative balances, and category limits must never use red. Budget exhaustion and fragile sync states are styled strictly with `warning-amber` (`#b78220`).
- **Error Red (`#ba1a1a`):** Strictly isolated to hard technological failures—database read errors, connection losses, or invalid hardware access.
- **Ghost Structure:** Structural divisions rely on `outline-ghost` (`#c6c8b8`) at 15% to 40% opacity or organic shifts between `surface-container-lowest` (`#ffffff`) and `surface-container-low` (`#f5f4ec`).

## Typography

The typography unites two distinct typographic spirits: the literary warmth of an editorial journal and the exactness of a double-entry ledger.

### Font Pairings & Roles
- **Display & Headings (Newsreader):** Brings humanistic rhythm, organic optical sizing, and quiet authority. Reserved for primary dashboard totals, section headers, monthly summaries, and reflective narrative intros.
- **Body & Controls (Manrope):** A geometric, modern grotesque with open apertures. It delivers uncompromised clarity across data-dense rows, button labels, and operational prompts.

### Tabular Numerical Setting
All numerical figures, monetary totals, dates, and timestamp strings must enforce `font-feature-settings: "tnum" on, "lnum" on`. This guarantees vertical alignment across column structures in ledger views and comparison sheets.

## Layout & Spacing

The layout is constructed on a 4px baseline rhythm. While born from a mobile-first paradigm, the desktop adaptation scales into a calm, spacious multi-column ledger that rejects clutter.

### Desktop Adaptations & Grid
- **12-Column Fluid Frame:** Desktop viewports utilize a 12-column grid capped at 1320px maximum width, centered with `margin-desktop` (64px) padding.
- **Section Rhythm:** Major sections use generous vertical separation (`space-3xl` or 64px) to preserve cognitive breathing room.
- **Ledger Density:** Tabular panels maintain compact internal spacing (`space-sm` to `space-md`), balancing breathing room with information density.

### Breakpoints & Reflow
- **Mobile (<768px):** 4-column layout, bottom tab navigation, full-width cards with `margin-mobile` (16px) gutters.
- **Tablet (768px–1023px):** 8-column layout, top navigation bar, collapsible filter sheets.
- **Desktop (≥1024px):** 12-column layout. Top sticky navigation bar (`h-16`) paired with an optional functional secondary side-rail for high-volume ledger filtering and batch categorization.

## Elevation & Depth

This design system deliberately eliminates synthetic drop shadows and heavy multi-layered z-depth. Visual stacking and order of importance are established through surface color stepping, subtle borders, and intentional white space.

### Tonal Stratification
Depth is communicated through warm paper tiers:
- **Base Canvas:** `surface` (`#faf9f6`) or `surface-bright` (`#fbfaf2`).
- **Resting Containers & Cards:** `surface-container-low` (`#f5f4ec`) creates subtle contrast without hard lines.
- **Interactive Surfaces & Input Wells:** `surface-container-lowest` (`#ffffff`) invites input by mimicking clean white stationery.
- **Hovered / Selected Layers:** Shifts into `surface-container` (`#efeee6`) or `surface-container-high` (`#e9e8e1`).

### Ghost Outlines & Translucency
- **Ghost Outlines:** Where separation is required without heavy contrast, hairline boundaries use `outline-ghost` (`#c6c8b8`) set at 20% to 35% opacity.
- **Backdrop Diffusion:** Overlays, floating summaries, and the sticky navigation bar utilize `surface` at 85% opacity paired with a `backdrop-blur-xl` filter. This blurs background typography into soft, muted paper grain.

## Shapes

The geometric framework balances human warmth with tabular order. Forms are soft enough to feel inviting, yet disciplined enough to organize financial data without feeling childlike.

### Shape Tiers
- **Soft Rounding (4px / `rounded-sm`):** Data cells, financial chips, and status flags. Keeps data-dense ledger grids tidy.
- **Component Rounding (8px / `rounded-md`):** Buttons, inputs, search fields, and contextual menus.
- **Notebook Rounding (12px to 16px / `rounded-lg` & `rounded-xl`):** Primary account cards, summary blocks, and modular containers. Evokes physical notebooks and bound journals.
- **Pill (9999px / `rounded-full`):** Floating primary actions, conversational tag filters, and user avatars.

## Components

### Buttons
- **Primary:** Background in Obsidian Sage (`#4f632d`), foreground in `#ffffff`, 8px or pill radius, vertical padding `space-sm`, horizontal `space-lg`. Hover shifts to `#384b18` with zero shadow.
- **Secondary / Ghost:** Transparent surface, foreground in `on-surface-variant` (`#45483d`), ghost outline at 30% opacity. On hover, fills with `surface-container`.
- **Destructive / Voiding:** Ghost outline with `on-surface-variant` text. Active confirmation turns to `error-container` with `error-red` text. Never use neon red buttons.

### Notebook Cards
- **Structure:** Built on `surface-container-low` with no drop shadow. Border is 1px solid `outline-ghost` at 25% opacity, with 12px to 16px border-radius.
- **Padding:** 24px internal padding on mobile, 32px on desktop.
- **Header:** Features Newsreader serif headline accompanied by a quiet Manrope label.

### Chips & Badges
- **Pills:** Rounded-full, height 28px, text styled in `label-sm`.
- **Status Amber:** For budget alerts and approaching thresholds. Background is `warning-amber` at 12% opacity, text is `#8c5f0e`.
- **Category Badges:** Low-saturation backgrounds (`surface-container-high`) paired with `on-surface-variant` text.

### Input Fields & Controls
- **Inputs:** Crisp `#ffffff` container set into paper surfaces with a 1px border using `outline-variant`. Focus states use a clean 1.5px border in Obsidian Sage (`#4f632d`) with no outer glow.
- **Checkboxes & Radios:** 4px radius for checks, full circle for radios. Checked state fills with Obsidian Sage and displays a white glyph.
- **Amounts:** Rendered with tabular Manrope numerals and prepended currency symbols styled in `outline` gray.

### Ledger Lists & Tables
- **Rows:** Alternating rows rely on pure white space or 1px subtle divider lines. Hover states highlight with `surface-container-lowest`.
- **Decimals & Alignments:** Currency amounts right-align using tabular numerals. Status tags sit center-right, while narrative descriptions anchor left.

### Top Navigation Bar
- Sticky bar at `surface/85` with `backdrop-blur-xl`.
- Height: 64px.
- Left: "OurPot" wordmark rendered in Newsreader (`24px`, weight 600).
- Center: Understated text navigation links with indicator dots in Obsidian Sage.
- Right: Monogram profile pill and ledger search entry point.