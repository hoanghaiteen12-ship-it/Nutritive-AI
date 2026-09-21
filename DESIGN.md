---
name: Nutrivibe AI
colors:
  surface: '#101418'
  surface-dim: '#101418'
  surface-bright: '#36393f'
  surface-container-lowest: '#0b0e13'
  surface-container-low: '#191c21'
  surface-container: '#1d2025'
  surface-container-high: '#272a2f'
  surface-container-highest: '#32353a'
  on-surface: '#e1e2e9'
  on-surface-variant: '#b9cbbd'
  inverse-surface: '#e1e2e9'
  inverse-on-surface: '#2e3036'
  outline: '#849588'
  outline-variant: '#3b4a40'
  surface-tint: '#00e293'
  primary: '#cdffde'
  on-primary: '#003921'
  primary-container: '#00f5a0'
  on-primary-container: '#006b43'
  inverse-primary: '#006c44'
  secondary: '#a5e7ff'
  on-secondary: '#003543'
  secondary-container: '#00d2ff'
  on-secondary-container: '#00566a'
  tertiary: '#fff0e7'
  on-tertiary: '#4c2700'
  tertiary-container: '#ffcda5'
  on-tertiary-container: '#8d4d00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#50ffaf'
  primary-fixed-dim: '#00e293'
  on-primary-fixed: '#002111'
  on-primary-fixed-variant: '#005232'
  secondary-fixed: '#b6ebff'
  secondary-fixed-dim: '#47d6ff'
  on-secondary-fixed: '#001f28'
  on-secondary-fixed-variant: '#004e60'
  tertiary-fixed: '#ffdcc2'
  tertiary-fixed-dim: '#ffb77a'
  on-tertiary-fixed: '#2e1500'
  on-tertiary-fixed-variant: '#6d3a00'
  background: '#101418'
  on-background: '#e1e2e9'
  surface-variant: '#32353a'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system is tailored for an intelligent, performance-driven nutrition and diet ecosystem. It balances clinical data accuracy with energetic lifestyle aesthetics. The tone is motivating, crisp, intuitive, and modern, blending deep slate dark-mode utility with vibrant, bio-luminescent accents.

The design movement combines modern minimalist utility with targeted neon glassmorphism:
- **High-contrast surfaces:** Deep charcoal/slate containers paired with pure neon cyan and fresh mint callouts to guide visual attention.
- **Intelligent telemetry:** Clean, luminous progress rings, biometric HUD scanning brackets, and pill markers evoke cutting-edge computer vision.
- **Warm culinary balance:** Warm amber and coral tones counterbalance cool neon hues to highlight appetizing meal photography and macro-nutrient distributions.

## Colors

The color palette centers on a dark substrate optimized for high contrast, glanceability, and visual energy:

- **Primary (`#00F5A0` - Vibrant Mint):** Drives primary goal completions, active nutrition thresholds, positive state feedback, and caloric budget confirmations.
- **Secondary (`#00D2FF` - Neon Cyan):** Highlights AI computer vision frames, real-time scanning targets, hydration tracking, and interactive data filters.
- **Tertiary (`#FF9F43` - Warm Amber):** Highlights meal slots (e.g., breakfast/lunch calories), elevated fat/carb indicators, and streak markers.
- **Neutral Dark (`#12151A` - Deep Obsidian Slate):** Acts as the canvas base. Paired with elevated container tiers (`#1A1F26` for surface-low, `#222933` for surface-card, and `#2E3744` for interactive stroke outlines).
- **Text & Foreground:** `#F8FAFC` (Pure/Near White) for primary titles; `#94A3B8` (Muted Slate) for unit metrics, metadata labels, and timestamps.

## Typography

The type system blends the energetic curves of **Plus Jakarta Sans** for headlines, numerical caloric summaries, and micro-labels with the neutral legibility of **Inter** for dense nutritional lists, ingredients, and logging records.

- Numeric figures for calories, grams, and percentages should consistently leverage tabular figures (`font-variant-numeric: tabular-nums`) to prevent layout shifts during animated counting cycles.
- Micro-labels and macronutrient headers utilize uppercase or title-case styling with widened tracking (`0.02em` to `0.04em`) to maintain sharp legibility against dark slate card backgrounds.

## Layout & Spacing

This design system uses an adaptive grid model tailored for high-density dashboard layouts and single-handed mobile scanning gestures:

- **Mobile Viewports (< 640px):** Single-column layout with a fixed base margin of `1rem` (16px) and component gap spacing of `0.75rem` (12px). Sticky bottom floating docks host the camera shutter and instant AI food logger.
- **Tablet / Split Viewports (640px - 1024px):** 6-column fluid grid, allocating space between the visual food scanner preview and nutritional macro breakdowns.
- **Desktop / Large Dashboard (> 1024px):** 12-column fixed grid (max content width 1240px) with `1.5rem` gutters, segregating meal logs, circular telemetry charts, and historical trends into modular cards.
- **Vertical Rhythm:** Strict 4px/8px incremental rhythm for all inner paddings and stack gaps.

## Elevation & Depth

Visual hierarchy is constructed through luminous tonal surface layering, low-contrast inner borders, and ambient neon back-glows:

- **Base Layer:** Canvas sits at pure `#12151A`.
- **Card Surfaces (Surface Level 1):** `#1A1F26` background, bordered with a subtle 1px border of `rgba(255, 255, 255, 0.08)`.
- **Raised & Floating Modals (Surface Level 2):** `#222933` background with dual-stage ambient drop shadows: `0 8px 32px rgba(0, 0, 0, 0.45)`, overlaid with an ultra-thin 1px highlight line along the top edge (`rgba(255, 255, 255, 0.12)`).
- **Scanner Reticle & AI Badging:** Computer-vision overlays use a subtle cyan/mint glass backdrop: `background: rgba(0, 210, 255, 0.08)`, `backdrop-filter: blur(12px)`, accented by glowing borders `box-shadow: 0 0 16px rgba(0, 245, 160, 0.35)`.
- **Macro Rings:** Caloric progress tracks sit inside recessed track layers (`rgba(255, 255, 255, 0.06)`) with luminous fill arcs casting ambient color halos.

## Shapes

The design system embraces a high-radius, pill-driven aesthetic that makes tracking feel organic, friendly, and tactile:

- **Containers & Nutrition Cards:** Large, sweeping rounded corners (`1.5rem` to `2rem`) to soften high-density data.
- **Tags, Pills, & Action Triggers:** Complete capsule / pill geometry (`9999px` border-radius) for meal tags, macro chips, and standard buttons.
- **AI Viewfinder Overlay:** Outer scan brackets retain generous `1.5rem` corner curves with interrupted perimeter lines framing the meal dish.

## Components

### Buttons
- **Primary Action (Log Food / Scan):** Pill-shaped (`rounded-full`), filled with Mint Green (`#00F5A0`), label in dark obsidian (`#12151A`, Plus Jakarta Sans Bold). Emits a subtle mint glow on hover/active states.
- **Secondary Action:** Pill-shaped translucent dark button (`#222933`), 1px stroke of `rgba(255, 255, 255, 0.12)`, text in `#F8FAFC`.
- **AI Shutter Floating Action:** Prominent 64px circular action button housing an animated aperture or sparkle icon with dual ring cyan/mint pulse gradients.

### Nutrition & Macro Progress Rings
- SVG-based circular meters with smooth geometric end-caps (`stroke-linecap: round`).
- Recessed slate background track (`#1A1F26`) with primary active strokes in Mint Green (Calories), Neon Cyan (Water/Carbs), and Warm Amber (Protein/Fats).
- Center text embeds large bold caloric figures with muted subtext labels underneath.

### AI Scanner Brackets & HUD
- Camera viewfinder bounded by rounded neon corners (`#00F5A0` or `#00D2FF`) with dynamic target tracking dots.
- Semi-transparent detection pills float over identified items (e.g., "Avocado • 160 kcal") using glassmorphism (`backdrop-filter: blur(12px)`).
- AI identification indicator: Soft purple-violet pill (`#8A2BE2` to `#A855F7`) labeled "AI" with micro sparkle glyphs.

### Chips & Pill Tags
- Compact 28px height, capsule curvature, padded `0.75rem` horizontally.
- Active states: `#00F5A0` background with dark contrast typography.
- Inactive / Filtering states: `#1A1F26` background, 1px subtle outline, muted slate text.

### Cards & Meal Tiles
- Deep slate surface (`#1A1F26`), `1.25rem` padding, `1.5rem` border radius.
- Left-aligned meal category icons (e.g., coffee cup for breakfast, bowl for lunch) wrapped in circular high-contrast accent backgrounds.
- Right-aligned caloric ratio indicators (`316 / 488 kcal`) featuring bold current intake and muted max targets.

### Input Fields & Search Bars
- Recessed pill or high-radius container (`#161A20`) with interior inset shadows.
- Prefix search/barcode/camera glyphs in neon cyan. Placeholder text in `#64748B`. Focused state introduces a 1px solid `#00D2FF` border with a subtle 4px diffused glow.