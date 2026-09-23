---
name: Quiet Ledger
colors:
  surface: '#f9faf2'
  surface-dim: '#dbdad3'
  surface-bright: '#fbfaf2'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4ed'
  surface-container: '#edefe7'
  surface-container-high: '#e7e9e1'
  surface-container-highest: '#e1e3dc'
  on-surface: '#191c18'
  on-surface-variant: '#45483c'
  inverse-surface: '#30312c'
  inverse-on-surface: '#f2f1e9'
  outline: '#646657'
  outline-variant: '#c6c8b8'
  surface-tint: '#51652f'
  primary: '#4f632d'
  on-primary: '#ffffff'
  primary-container: '#677c43'
  on-primary-container: '#faffe8'
  inverse-primary: '#b7cf8d'
  secondary: '#626034'
  on-secondary: '#ffffff'
  secondary-container: '#e9e5ad'
  on-secondary-container: '#686639'
  tertiary: '#5f5c4f'
  on-tertiary: '#ffffff'
  tertiary-container: '#787467'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d3eba7'
  primary-fixed-dim: '#b7cf8d'
  on-primary-fixed: '#131f00'
  on-primary-fixed-variant: '#3a4d19'
  secondary-fixed: '#e9e5ad'
  secondary-fixed-dim: '#b7cf8d'
  on-secondary-fixed: '#1e1d00'
  on-secondary-fixed-variant: '#3a4d19'
  tertiary-fixed: '#e8e2d2'
  tertiary-fixed-dim: '#ccc6b7'
  on-tertiary-fixed: '#1e1c12'
  on-tertiary-fixed-variant: '#62385e'
  background: '#fbfaf2'
  on-background: '#1b1c17'
  surface-variant: '#e4e3db'
  warning-amber: '#b78220'
  on-warning-surface: '#7a4d00'
  error-red: '#ba1a1a'
  outline-ghost: '#c6c8b8'
typography:
  display-lg:
    fontFamily: Newsreader
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-md:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
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
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.14em
  button:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  financial-data:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
rounded:
  xs: 2px
  md: 4px
  lg: 8px
  xl: 12px
  xxl: 24px
  full: 9999px
spacing:
  baseline: 4px
  section-padding-desktop: 64px
  container-padding: 32px
  gutter: 24px
  stack-sm: 8px
  stack-md: 16px
---

# OurPot — Web Design System

> Desktop adaptation of the mobile-first design system. This system maintains the "Quiet Ledger" aesthetic while optimizing for larger viewports, utilizing higher-density layouts and refined typography for a premium, archival feel.

## 1. Voice

**Observational, never emotional.**

- Use factual, restrained language: "We spent ₹52,000 this month."
- Avoid judgments, red alarms, or coaching.

### Vocabulary

Mirrors the app's normative table in `docs/DESIGN.md` §1. The **plain-language ruling of
2026-08-26** replaced the engine's verbs — Record / Void / Supersede — with everyday ones,
after real users could not parse "void".

| Concept                | CTA / button     | Past tense       | Not, in copy                 |
| ---------------------- | ---------------- | ---------------- | ---------------------------- |
| Append an expense      | **Add**          | **Added**        | record, log, submit          |
| Remove an expense      | **Delete**       | **Deleted**      | void, remove, archive        |
| Replace an expense     | **Save changes** | **Edited**       | supersede, update, overwrite |
| Stop a recurring rule  | **Stop**         | **Stopped**      | void, delete                 |
| Default expense mode   | —                | **pooled**       | shared, joint                |
| Secondary expense mode | —                | **split**        | divided, shared between      |
| Settlement state       | —                | **even**         | square                       |
| Settlement act         | **Settle up**    | **settled up**   | record a settlement          |

**"recorded" survives in prose** — "recorded by Priya", "Nothing recorded yet" — it is
ordinary English there. Only the verb on a button, and the confirmation right after it,
moved to Add / Added. This page follows the same line: headings and body copy may say
record, the scratchpad's button and its toast say Add / Added.

Also retired in the same pass and not to be reintroduced here: **long-press** (now *press
and hold*), **occurrence** (now *entry*), **margin note** (now *note*).

Kept deliberately: notebook, pot, pooled/split, sync, sign off, Settlement, archive,
recovery phrase.

## 2. Tokens

### Palette — Quiet Ledger

> Colour and radius values mirror `src/theme.ts` (light palette) in the app repo,
> which is the source of truth. Keys with no counterpart there are web-only.


- **Surface**: `#f9faf2` (Paper-like warmth)
- **On Surface**: `#191c18` (Deep ink)
- **Primary**: `#4f632d` (Obsidian Sage - the accent of calm)
- **Primary Container**: `#677c43`
- **Warning**: `#b78220` (Dusty Amber - for budget near/over, fragile backup)
- **Error**: `#ba1a1a` (Muted Red - for hard system failures only)
- **Outline Variant**: `#c6c8b8` (Ghost borders @ 15% opacity)

### Typography — Newsreader, Manrope & Space Grotesk

- **Serif (Newsreader, italic)**: For narrative moments, headlines, and large hero amounts. Evokes the feeling of a physical journal. Only the italic cuts ship in the app's `assets/fonts`, so upright Newsreader would be a web-only face — the web uses italic too.
- **Sans (Manrope)**: Body copy, prose, and financial figures. Clean and readable.
- **Grotesk (Space Grotesk)**: Web-only third face, for the uppercase eyebrow labels, buttons, section chips, and inline code. It carries the machine voice; Manrope carries the human one.
- **Tabular Numbers**: Mandatory for all financial figures.

### The web body steps

The app's scale carries two body sizes. A 1080px reading column needs more, so the
web adds five steps — and these are the whole of it. A text size that is neither in
the table above nor in this one is drift, not a decision.

| Step        | Size | Where                                                            |
| ----------- | ---- | ---------------------------------------------------------------- |
| `body-read` | 17px | Section prose, the lead under a headline, disclosure claims       |
| `body-sm`   | 15px | Index and comparison rows, form fields, the rows inside a panel   |
| `chrome`    | 14px | Nav links and footer text, in Manrope; the button token owns 14px in Space Grotesk, and inline code rides it |
| `meta`      | 13px | Status lines, entry notes, the line under the scratchpad          |
| `ordinal`   | 12px | Tabular numerals only — the index ordinal, the scratchpad's date |

Line-height is the body's 1.65 in all five; only display and headline set their own.
18px and above belongs to glyphs and the wordmark, never to running text.

### Spacing & Radius

- **Spacing**: 4px baseline. Desktop sections use generous padding (32px to 64px) to create breathing room.
- **Radius**: `md` (4px) for inline code, `lg` (8px) for form fields, 16px for the raised panels (scratchpad, sync demo), 26px for device screenshots, `full` for pills and primary actions.

## 3. Web Components

This is a marketing page, not an app shell. There is no side nav, no avatar, and
no global search.

### TopNavBar

- Sticky, `surface` at 82% with a 20px backdrop blur; the bottom rule fades in on scroll.
- Left: "ourpot" wordmark in Newsreader italic, beside the app icon.
- Right: section links (What it is, Sync, Inside, Limits, FAQ), the three-way theme
  toggle mirroring the app's own system/light/dark preference, and the primary CTA.
- Under 720px the links collapse behind a menu button; without script they stay in
  the bar and wrap, so the collapsed menu is the enhancement, not the baseline.

### Ruled index

- Rows on a ruled page, not cards on a dashboard: a hairline `divider` above each row,
  a tabular ordinal, and a uppercase chip naming where the thing lives in the app.
- Two columns from 880px, three for the shorter `index-3` lists.

### The tonal ladder

Four values, all from the app palette. Each element sits one **visible** step from
its own ground:

| Role                                   | Token             |
| -------------------------------------- | ----------------- |
| Page ground                            | `surface`         |
| Alternating band, raised panel         | `raised`          |
| Emphasis inside a panel (totals, bars) | `raised-inner`    |
| Form fields                            | `surface-lowest`  |

`raised` and `raised-inner` are web-only aliases onto `surface-container` and
`surface-high`. They exist because the original pairing — `surface` against
`surface-low` — measures **1.053:1** in light and 1.066:1 in dark. That is a step
you cannot see, so the tonal rhythm the system claimed was not actually shipping.
The current pairing measures 1.104:1 / 1.124:1. Still quiet; now legible.

### Raised panels

- The sync demo and the browser scratchpad sit on `raised` inside a `divider`
  border at 16px radius, on sections that stay on the base ground so the panel still
  reads as laid on top of it.
- Panels carry no shadow. Tonal layering and white-space do the separating.

### Elevation — exactly one, for one job

`--elev-object` is the only shadow in the system, and it is reserved for **device
screenshots**, which are physical objects resting on the page rather than regions
of it. Everything else separates tonally.

Its mechanics differ by theme and that is deliberate: light lifts the device with a
shadow, dark lifts it with a brighter fill against a near-black ground. The **order**
holds in both — the device reads above the page either way — which is the part that
has to be stable.

### Ledger ruling

The hero carries faint horizontal rules on the 8px baseline, masked so they fade in
at the top and out before the copy ends. It is the one decorative device on the page
and it earns its place semantically: the product is an account book, and the ruling
says so before the headline does.

Rules are derived from `on-surface` at 10%, not from an outline token, so they land
at the same quietness in both themes — 1.22:1 light, 1.27:1 dark against their own
ground. Off `outline-variant` they measured 1.32:1 / 1.45:1, which read as a table
rather than as paper.

**One place only.** Repeated down the page this becomes wallpaper and stops meaning
anything.

### Disclosure

One pattern serves the FAQ, the honest limits, and the wire panel: a **claim** that is
always visible, and an explanation behind a `+`. The claim is the part that must be
read; the explanation is opt-in.

This is what keeps the page honest without making it long. The limits section reads as
eight one-line admissions rather than eight paragraphs — and a reader who scans all
eight has actually taken in more of them than one who bounced off the wall of text.

**Each fact gets one home.** Before this pattern the page stated "there is no server"
in five sections, "CSV export" in six, and Bluetooth in four. Depth belongs in the
disclosure that owns the subject, not repeated in prose beside it.

### Interactive edges

- Form fields and outlined buttons take `outline`, not `outline-variant`:
  `outline-variant` measures 1.6:1 on `surface` and WCAG 1.4.11 asks 3:1 of a control
  boundary. `outline-variant` stays on decorative rules and dividers, which are exempt.
- Hover moves the edge to `primary`.

## 4. Design Guardrails

- **No red for money**: Over-budget is always Amber.
- **Tabular figures**: Essential for aligning decimals in lists.
- **Verbatim content**: Always reproduce user-provided labels exactly.
