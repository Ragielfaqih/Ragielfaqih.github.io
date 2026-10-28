---
name: Atelier Curated Portfolio
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#45464d'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fe932c'
  on-secondary-container: '#663500'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#100069'
  on-tertiary-container: '#7771ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#e3dfff'
  tertiary-fixed-dim: '#c3c0ff'
  on-tertiary-fixed: '#100069'
  on-tertiary-fixed-variant: '#372abf'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display:
    fontFamily: Newsreader
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Newsreader
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Newsreader
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Newsreader
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 30px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-desktop: 2.5rem
  margin: 1.25rem
  margin-tablet: 2.5rem
  margin-desktop: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
  space-2xl: 5rem
---

## Brand & Style
The brand personality reflects an exacting, editorial, and sophisticated presence. It communicates quiet confidence, mastery of craft, and disciplined intellect. Designed for senior creative directors, software architects, design engineers, and researchers, the interface acts as a bespoke monograph rather than a standard corporate resume.

The design movement combines **Contemporary Editorial Minimalism** with structural architectural grids. Heavy whitespace, razor-sharp typographic hierarchy, and tactile, understated surface contrasts elevate content without visual gimmickry. The emotional response is one of authority, discernment, and timeless elegance.

## Colors
The palette balances classical warmth with deliberate, high-intent technical accents:

- **Neutral Canvas (`#FDFBF7`)**: A tailored warm alabaster/cream background, eliminating harsh clinical white while imparting the tactility of premium archival paper.
- **Primary Ink (`#0F172A`)**: Deep Slate Navy. Used for core typography, authoritative structural rules, and primary high-priority surfaces.
- **Secondary Accent (`#D97706`)**: Warm Amber. Applied sparingly for chronological markers, milestone tags, award ribbons, and subtle callouts.
- **Tertiary Interactive (`#4338CA`)**: Electric Indigo. Reserved for deliberate interactions, link hovers, active tab indicators, and live showcase previews.

Tonal variations rely on opacity overlays of the primary ink (e.g., 4% slate for subtle panel fills, 12% slate for hair-thin architectural borders), maintaining absolute chromatic cohesion.

## Typography
Typographic rhythm relies on a deliberate triad pairing:

1. **Newsreader (Display & Headlines)**: Delivers an authoritative literary pedigree. Headlines should feature italicized emphasis on evocative keywords to punctuate narrative flow.
2. **Plus Jakarta Sans (Body & Structural UI)**: Provides crisp, modern legibility with balanced proportions, ensuring frictionless scanning across resumes, descriptions, and metadata.
3. **JetBrains Mono (Labels, Chronology & Badges)**: Imparts structural rigor for timeline dates, index numerations (e.g., `01 / SHOWCASE`), tags, and technical specifications.

All uppercase labels must maintain generous tracking (`0.06em` to `0.08em`) for optical clarity.

## Layout & Spacing
The layout follows a modular 12-column fixed-max grid (capped at `1280px` outer container width) centered upon the warm cream canvas.

- **Breakpoints**:
  - `Mobile` (< 768px): 4-column layout, `1.25rem` margin, content stacks linearly.
  - `Tablet` (768px – 1024px): 8-column layout, `2.5rem` margin, split asymmetric blocks.
  - `Desktop` (> 1024px): 12-column layout, `4rem` margin, multi-column editorial spreads.

- **Rhythm & Structure**:
  - Sections are demarcated by generous vertical breathing room (`space-2xl`) and single-pixel structural hairline rules rather than heavy background box containers.
  - Asymmetric distributions are encouraged: Project indices leverage 5-column narrative overviews coupled with 7-column media displays.

## Elevation & Depth
Depth is created through tonal layering and hair-thin, low-contrast boundaries rather than heavy drop shadows:

- **Surfaces**: Core background sits at `#FDFBF7`. Lifted surfaces (cards, floating navigation bars, modal dialogs) sit on solid `#FFFFFF` or translucent `rgba(253, 251, 247, 0.85)` with a `16px` backdrop blur.
- **Hairline Outlines**: Elements are defined by a crisp `1px solid rgba(15, 23, 42, 0.08)`. On interaction or focus, this shifts to `rgba(15, 23, 42, 0.25)` or the Electric Indigo tone.
- **Ambient Shadow**: When elevation is required (such as project preview hovers or sticky header bars), apply an imperceptible, multi-stop diffuse shadow: `0 12px 32px -8px rgba(15, 23, 42, 0.04), 0 4px 12px -2px rgba(15, 23, 42, 0.02)`.

## Shapes
The aesthetic is sharp, architectural, and restrained (`roundedness: 1`). 

- Default elements (cards, text fields, certificates) utilize a subtle `4px` (`0.25rem`) border radius, preserving clean horizontal and vertical lines.
- Medium components (buttons, dialog frames) scale up to `8px` (`0.5rem`).
- Pills and circles are strictly reserved for status dots, index badges, and icon buttons. Avoid bubbly geometry to protect the serious editorial tone.

## Components

### Buttons
- **Primary**: Solid Deep Slate Navy (`#0F172A`) with Warm Alabaster text (`#FDFBF7`). Subtle `4px` radius. Hover shifts background to an enriched slate with a micro translation upwards (`-1px`).
- **Secondary / Ghost**: Transparent fill, 1px border `rgba(15, 23, 42, 0.15)`, text in Slate Navy. Hover yields `rgba(15, 23, 42, 0.04)` fill and border color shifts to `#0F172A`.
- **Text Action**: Unbordered, underlined with an offset 1px rule, transitioning into Electric Indigo on hover.

### Chips & Tags
- Set in `label-sm` (`JetBrains Mono`).
- Category tags use an off-white fill (`#FFFFFF`), a 1px border (`rgba(15, 23, 42, 0.08)`), and text in muted slate.
- Milestone/Award tags use Warm Amber text (`#D97706`) with an amber tint fill (`rgba(217, 119, 6, 0.08)`).

### Showcase Project Cards
- Media-first with strict 16:10 or 4:3 aspect ratios.
- Clean caption block beneath the media rather than overlaid, featuring an index number (`01`, `02`), serif project title, brief role description, and monospace technical stack tags.
- On hover, image exhibits an effortless scale (`scale(1.02)`) masked within an overflow-hidden frame with a 4px corner radius.

### Education & Internship Timeline
- Linear minimalist layout anchored by a 1px vertical slate rule (`rgba(15, 23, 42, 0.12)`).
- Timeframes rendered in `label-md` using Warm Amber or Muted Slate.
- Institutional names in `headline-sm`, complemented by concise body descriptions detailing measurable achievements and key competencies.

### Certification Credentials
- Compact split grid with 1px border enclosing each credential.
- Displays issuing organization, verification hash or link, issue date, and an external verification icon that shifts to Electric Indigo on hover.

### Form Inputs (Contact & Inquiries)
- Underlined or softly boxed input fields with `#FFFFFF` background and `1px solid rgba(15, 23, 42, 0.12)`.
- Focus state eliminates standard browser outlines and introduces a crisp `1px solid #4338CA` border with a subtle 2px Indigo glow ring (`rgba(67, 56, 202, 0.12)`).