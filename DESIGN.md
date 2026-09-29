---
name: Assistência Segura Design System
colors:
  surface: '#f6f9ff'
  surface-dim: '#d6dae0'
  surface-bright: '#f6f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f4fa'
  surface-container: '#eaeef4'
  surface-container-high: '#e4e8ee'
  surface-container-highest: '#dfe3e9'
  on-surface: '#171c20'
  on-surface-variant: '#434750'
  inverse-surface: '#2c3136'
  inverse-on-surface: '#edf1f7'
  outline: '#737781'
  outline-variant: '#c3c6d2'
  surface-tint: '#325f9e'
  primary: '#00366d'
  on-primary: '#ffffff'
  primary-container: '#1c4d8b'
  on-primary-container: '#9abfff'
  inverse-primary: '#a8c8ff'
  secondary: '#3e6280'
  on-secondary: '#ffffff'
  secondary-container: '#b7dbff'
  on-secondary-container: '#3d607f'
  tertiary: '#003e3d'
  on-tertiary: '#ffffff'
  tertiary-container: '#205554'
  on-tertiary-container: '#94c8c7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#a8c8ff'
  on-primary-fixed: '#001b3d'
  on-primary-fixed-variant: '#124684'
  secondary-fixed: '#cde5ff'
  secondary-fixed-dim: '#a7caed'
  on-secondary-fixed: '#001d32'
  on-secondary-fixed-variant: '#254a67'
  tertiary-fixed: '#b7eceb'
  tertiary-fixed-dim: '#9cd0cf'
  on-tertiary-fixed: '#002020'
  on-tertiary-fixed-variant: '#184e4e'
  background: '#f6f9ff'
  on-background: '#171c20'
  surface-variant: '#dfe3e9'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 3rem
    fontWeight: '800'
    lineHeight: 3.5rem
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '800'
    lineHeight: 2.75rem
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '700'
    lineHeight: 2rem
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
  label-lg:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
  label-md:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
  label-sm:
    fontFamily: Inter
    fontSize: 0.6875rem
    fontWeight: '700'
    lineHeight: 0.875rem
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2.5rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses stability, immediate readiness, operational clarity, and human warmth. Designed for 24/7 mission-critical assistance operations, it balances corporate rigor with reassuring hospitality. The primary audience spans insurance claim managers, emergency dispatch operators, fleet directors, and end-beneficiaries experiencing urgent roadside, health, or home incidents.

The visual direction follows **Corporate / Modern** precision infused with **Human-Centered Soft Modernism**. Interfaces prioritize frictionless cognitive processing during high-stress scenarios. Clean layouts, gentle tonal layering, generous tap targets, and crisp information grouping replace high-intensity visual clutter. 

Key attributes:
- **Resilient & Dependable**: Solid architecture anchored by deep, trustworthy oceanic blues.
- **Calming & Human**: Softer teal accents and gentle surface contrasts that de-escalate anxiety.
- **Immediate Legibility**: Uncompromised typographic contrast meeting strict WCAG 2.1 AAA/AA standards across day and night operational conditions.

## Colors

The palette is engineered around deep corporate trust, operational balance, and subtle natural empathy.

### Core Swatches
- **Primary (`#1C4D8B` - Deep Blue)**: The commanding anchor. Used for primary CTAs, main interactive states, active navigation elements, and primary branding landmarks.
- **Secondary (`#2F5371` - Slate Blue)**: The stabilizing balance. Used for sub-headers, segmented controls, secondary badges, and auxiliary control bars.
- **Tertiary / Accent (`#699C9B` - Sage Teal)**: The calming reassuring touchpoint. Applied to positive feedback, active tracking states, resolution metrics, and gentle confirmation highlights.
- **Soft Accent (`#A3CFF0` - Sky Mist)**: Subtle functional highlight used for interactive focus rings, tag surfaces, hover tinting, and selected card perimeters.
- **Neutral Light (`#E0E4EA` - Slate Cool Gray)**: The baseline canvas background and border structure that softens the starkness of pure white while maintaining clean separation.
- **Text & Surface Extremes**:
  - `Surface White` (`#FFFFFF`): Primary elevated cards, data modals, and input fields.
  - `Dark Graphite` (`#111E2E`): Ultimate high-contrast neutral for headlines, critical data, and high-priority alerts.

### Functional Application Rules
1. Never place pure saturated blue text over muted teal containers; maintain a minimum 4.5:1 contrast ratio.
2. Background canvases default to `#F4F6F9` or `#E0E4EA` with `#FFFFFF` reserved for elevated cards and functional interactive containers.
3. For emergency dispatch or alert triggers, reserved semantic tokens (`#D32F2F` for critical, `#F57C00` for warning, `#2E7D32` for success) harmoniously balance with `#111E2E` without colliding with the primary slate tones.

## Typography

The type system blends the human, welcoming geometry of **Plus Jakarta Sans** with the analytical clarity and tabular performance of **Inter**.

- **Plus Jakarta Sans** governs branding headings, section introductions, conversational titles, and main interactive calls to action. Its open apertures and subtle geometric curves communicate empathy and contemporary agility.
- **Inter** handles data tables, incident metrics, KPI indicators, status tags, form microcopy, and operational telemetry. Its neutral glyph construction and superior optical hinting prevent fatigue during intensive dispatch monitoring.

### Typographic Hierarchy
- Use `headline-xl` sparingly for landing heroes and key operational dashboard greetings.
- Ensure all interactive microcopy and system badges use uppercase tracking (`+0.04em`) via `label-sm` or `label-md` to ensure instantaneous readability at a glance.
- Numeric metrics (incident response times, vehicle coordinates, policy numbers) must employ `Inter` with tabular figures (`font-variant-numeric: tabular-nums`).

## Layout & Spacing

This design system is anchored on an 8pt architectural rhythm, calibrated for dense operational tools as well as uncluttered customer-facing flows.

### Grid Framework
- **Desktop (>= 1200px)**: 12-column responsive fluid grid with `margin: 2.5rem` and `gutter: 1.5rem`. Maximum container width is capped at 1360px for administrative views and 1140px for customer intake forms.
- **Tablet (768px – 1199px)**: 8-column layout with `margin: 2rem` and `gutter: 1.25rem`. Complex dual-column tables collapse into single stacked modules.
- **Mobile (< 768px)**: 4-column responsive grid with `margin: 1.25rem` and `gutter: 1rem`. Sticky contextual action bars stay affixed to bottom safe areas.

### Component Spacing Principles
- `space-xs` (4px): Micro-spacing between paired icons and adjacent labels.
- `space-sm` (8px): Internal compact button padding, pill-tags, and form field helper text gaps.
- `space-md` (16px): Standard padding inside card bodies, lists, and fieldset gaps.
- `space-lg` (24px): Card block separations and modular dashboard widget insets.
- `space-xl` (40px): Section divisions and major dashboard column groupings.

## Elevation & Depth

Visual hierarchy is maintained through deliberate tonal layering supported by low-opacity, blue-tinted ambient shadows. By incorporating cool ambient tones rather than neutral grays into shadow values, elevations preserve clean chromatic cohesion.

### Tonal Tiers
1. **Base Floor (`#E0E4EA` / `#F5F7FA`)**: The primary desktop backdrop.
2. **Surface Container 1 (`#FFFFFF`)**: Standard cards, table rows, and unselected modules. Elevated by a crisp 1px hairline border (`#D0D7E2`) and an ambient glow: `0px 2px 6px rgba(17, 30, 46, 0.04)`.
3. **Surface Container 2 (Elevated State / Hover)**: Active or hovered cards: `0px 10px 24px -4px rgba(28, 77, 139, 0.08), 0px 4px 8px -2px rgba(17, 30, 46, 0.03)`.
4. **Surface Container 3 (Overlays & Modals)**: Critical incident popups, floating emergency action menus, and dropdown controls: `0px 20px 40px -8px rgba(17, 30, 46, 0.16)`. Accompanied by a 24% deep-navy frosted backdrop blur (`rgba(17, 30, 46, 0.35)` with `backdrop-filter: blur(6px)`).

Crisp border treatments (`1px solid rgba(47, 83, 113, 0.12)`) act in tandem with subtle shadows, eliminating the need for aggressive drop-shadow styling.

## Shapes

The design uses a roundedness index of `2` (Moderate Rounded), striking an optimal balance between corporate authority and friendly human ergonomics.

- **Base Radius (`0.5rem` / 8px)**: Applied to text fields, input selectors, buttons, badge containers, and incident preview thumbnails.
- **Card & Modal Radius (`1rem` / 16px)**: Applied to self-contained module panels, primary summary tiles, and dashboard summary widgets.
- **Overlay & Sheet Radius (`1.5rem` / 24px)**: Applied to bottom sheets, emergency callout cards, and modal window perimeters.
- **Pill Badges (`9999px`)**: Reserved exclusively for real-time status indicators (e.g., "Em Deslocamento", "Ativo", "Aguardando Vistoria") and avatar frames.

## Components

### Buttons
- **Primary**: Solid background in Deep Blue (`#1C4D8B`) with crisp White (`#FFFFFF`) text, subtle 8px border radius, and bold label font (`Inter`, 600 weight). Hover state transitions to slate `#153C6E` with a slight 1px elevation lift. Focus ring applies `0 0 0 3px rgba(163, 207, 240, 0.6)`.
- **Secondary**: Slate Blue tint (`#EBF1F7`) with Deep Blue (`#1C4D8B`) text and border `1px solid rgba(28, 77, 139, 0.2)`. On hover, shifts to `#DFE9F3`.
- **Accent (Emergency / Immediate Action)**: Tertiary Sage Teal (`#699C9B`) or Deep Blue with high-contrast text for decisive customer reassurances.
- **Ghost / Tertiary**: Transparent surface, secondary slate text (`#2F5371`), gaining `#F0F4F8` on hover.

### Cards
- Constructed on a pure white surface (`#FFFFFF`) bordered with `1px solid rgba(47, 83, 113, 0.12)` and wrapped in 16px border-radius.
- Cards maintain a 24px interior padding (`space-lg`), separating header actions from payload metrics with a light 1px divider in `#E0E4EA`.

### Input Fields & Selectors
- Background: `#FFFFFF` encased in a 1.5px border (`#CFD6E0`).
- Padding: 12px 16px. Height: 44px (touch-compliant 48px on mobile viewports).
- Text color: `#111E2E` with placeholder in `#73869C`.
- Focused state: Border changes to `#1C4D8B` paired with an accessible outer ring in Sky Mist (`#A3CFF0`).

### Chips & Status Badges
- **Status Pills**: Height 24px, 12px padding, font size 11px uppercase (`Inter`).
  - *Active / On Route*: Background `#EAF4F3`, text `#3A6B6A`, with a 6px tertiary teal pulsating dot.
  - *In Review*: Background `#EBF3FB`, text `#1C4D8B`.
  - *Urgent Alert*: Background `#FDF0EE`, text `#C53030`.

### Checkboxes & Radio Buttons
- 20x20px dimension with a 4px radius for checkboxes and 50% circular for radio buttons.
- Unchecked: 1.5px border in `#73869C` on `#FFFFFF`.
- Checked: Deep Blue fill (`#1C4D8B`) displaying an unmistakable white check or centered white bullet, accompanied by the signature `#A3CFF0` focus outline.

### Lists & Activity Feeds
- Structured as separated rows or connected timeline nodes.
- Incident trackers utilize a vertical timeline rail in `#A3CFF0` anchored with `#1C4D8B` progress pips to provide continuous clarity to dispatchers and distressed customers.