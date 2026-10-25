---
name: Canadian Crimson Academic
colors:
  surface: '#f8f9ff'
  surface-dim: '#cddbef'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eef4ff'
  surface-container: '#e4efff'
  surface-container-high: '#dbe9fe'
  surface-container-highest: '#d5e4f8'
  on-surface: '#0e1d2b'
  on-surface-variant: '#5c403e'
  inverse-surface: '#243241'
  inverse-on-surface: '#e9f1ff'
  outline: '#906f6d'
  outline-variant: '#e4bdbb'
  surface-tint: '#bd0f26'
  primary: '#b20120'
  on-primary: '#ffffff'
  primary-container: '#d62835'
  on-primary-container: '#fff2f0'
  inverse-primary: '#ffb3af'
  secondary: '#505f78'
  on-secondary: '#ffffff'
  secondary-container: '#d0e0fe'
  on-secondary-container: '#54637c'
  tertiary: '#004dcc'
  on-tertiary: '#ffffff'
  tertiary-container: '#2a66ee'
  on-tertiary-container: '#f4f4ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad7'
  primary-fixed-dim: '#ffb3af'
  on-primary-fixed: '#410006'
  on-primary-fixed-variant: '#930018'
  secondary-fixed: '#d4e3ff'
  secondary-fixed-dim: '#b7c7e4'
  on-secondary-fixed: '#0b1c32'
  on-secondary-fixed-variant: '#38475f'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#003ea8'
  background: '#f8f9ff'
  on-background: '#0e1d2b'
  surface-variant: '#d5e4f8'
  crimson-hover: '#B71C28'
  surface-light: '#F5F7FA'
  border-subtle: '#DCE2E9'
  success: '#10B981'
  warning: '#F59E0B'
typography:
  display-lg:
    fontFamily: Lexend
    fontSize: 3.5rem
    fontWeight: '700'
    lineHeight: 4rem
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Lexend
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Lexend
    fontSize: 2rem
    fontWeight: '600'
    lineHeight: 2.5rem
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Lexend
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
  headline-sm:
    fontFamily: Lexend
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
  body-lg:
    fontFamily: Lexend
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Lexend
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-sm:
    fontFamily: Lexend
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
  label-lg:
    fontFamily: Lexend
    fontSize: 1rem
    fontWeight: '500'
    lineHeight: 1.5rem
  label-md:
    fontFamily: Lexend
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: 1.25rem
  label-sm:
    fontFamily: Lexend
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.04em
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
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an accessible, student-centric academic interface for language training and global education pathways. Balancing the welcoming warmth of educational mentorship with institutional authority, the visual posture draws upon Canadian crimson and midnight navy to communicate trust, prestige, and clear progress. 

The aesthetic is Modern Corporate with an empathetic, human-focused tilt. Interfaces prioritize instant scannability, generous whitespace, and crisp, distinct card boundaries to reduce cognitive load for non-native English speakers. Visual accents incorporate quiet geometric motifs inspired by Canadian iconography—restrained, precise, and distinctly non-governmental—reinforcing a world-class training environment.

## Colors

The palette balances energetic engagement with academic discipline:

- **Primary Crimson (`#D62835`)**: The core interactive driver. Applied to critical actions, active tabs, progress callouts, and key conversion points.
- **Deep Navy (`#14243A`)**: The anchor of institutional authority. Serves as high-contrast body typography, primary headers, and structural background frames for hero areas.
- **Surface & Backgrounds**: Surfaces leverage stark white (`#FFFFFF`) for elevated interactive cards against a soft, glare-reducing canvas of `#F5F7FA`.
- **Secondary Slate (`#526071`)**: Governs secondary labels, metadata, captions, and structural borders when paired with `#DCE2E9`.
- **Functional Semantics**: Information states draw on `#2563EB`, verification and milestones rely on `#10B981`, and review alerts use `#F59E0B`.

All foreground-background combinations meet or exceed WCAG 2.1 AA standards (4.5:1 for body copy; 3:1 for large display elements).

## Typography

Typography is powered uniformly by Lexend, chosen specifically for its proven ability to improve reading fluency, character separation, and comprehension across diverse student literacy levels. 

Headings command attention using semi-bold and bold weights with subtle negative tracking, preventing optical sprawl in large viewports. Body copy relies on strict line-height ratios (minimum 1.5x) to maintain a stress-free reading cadence through intensive grammar explanations and study guides. Monospace variations are restricted purely to scores, reference codes, and timestamps.

## Layout & Spacing

The layout is grounded in a responsive 12-column fluid grid on desktop (max width 1280px) with 24px (`1.5rem`) gutters and section margins. Tablet breakpoints reflow into an 8-column grid with 16px gutters, while mobile devices collapse down to a single-column stack with 16px gutters and outer margin gutters.

Vertical rhythm adheres rigidly to an 8px grid foundation. Content containers, learning modules, and side panels use deliberate proportional breathing room (`space-lg` to `space-xl`) to prevent visual crowding during assessments and document review workflows.

## Elevation & Depth

Visual depth is achieved through quiet, layered containment rather than dramatic drop shadows. The design system uses three structured elevation tiers:

1. **Flat / Low-Tier Containers (Cards, List Groups)**: Grounded by a 1px solid border (`#DCE2E9`) against `#FFFFFF` with no elevation blur.
2. **Interactive Hover & Mid-Tier Overlays (Dropdowns, Active Cards)**: A diffused, ambient shadow tinted with Deep Navy: `0 4px 12px -2px rgba(20, 36, 58, 0.08)`.
3. **High-Tier Modals & Floating Concierge**: Elevated prominently over a 40% `#14243A` backdrop blur with an expanded soft shadow: `0 16px 32px -4px rgba(20, 36, 58, 0.16)`.

Surfaces retain clear, crisp boundaries to ensure high usability under direct sunlight or sub-optimal monitor calibrations.

## Shapes

The design system standardizes on Level 2 roundedness (`0.5rem` / `8px` base border-radius). This geometric softness balances approachable modern design with academic seriousness. 

Interactive controls (buttons, inputs, notification pills) use standard `0.5rem` rounding. Larger surface boundaries such as educational modules, modal dialogs, and hero feature containers scale up to `rounded-lg` (`1rem`) and `rounded-xl` (`1.5rem`). Circular radius is reserved strictly for student avatars, status dots, and icon action hubs.

## Components

### Buttons
- **Primary**: Solid Crimson (`#D62835`) background, `#FFFFFF` text, `0.5rem` radius. On hover: shifts smoothly to `#B71C28`.
- **Secondary**: Deep Navy outline (`2px solid #14243A`), `#14243A` text, transparent background. Hover fills surface with light navy tint (`rgba(20, 36, 58, 0.04)`).
- **Ghost**: Text-only using `#526071` with hover transition to `#14243A` and faint neutral background pill.

### Form Inputs & Selectors
- Text fields use a solid `#FFFFFF` fill with a `1px solid #DCE2E9` border and `0.5rem` corner radius.
- Active focus state transitions border to `#D62835` accompanied by a `2px` focus ring in `rgba(214, 40, 53, 0.15)`.

### Checkboxes & Radios
- Box size: `20px x 20px` with `4px` rounding for checkboxes, fully circular for radios.
- Unchecked states use `#DCE2E9` borders. Checked states fill with `#D62835` displaying a crisp white indicator mark.

### Course & Module Cards
- White surface base, `1px` border (`#DCE2E9`), and `1rem` radius.
- Contain a structured metadata header, progress bar (Crimson fill over `#F5F7FA` track), and an integrated badge slot.

### Status Badges & Chips
- Rounded tag format (`0.25rem` radius, uppercase tracking).
- Verified status tags render in `#10B981` (10% tint fill with solid text). Specialized Canadian academic marker badges incorporate a minimalist stylized geometric leaf icon beside text.

### AI Student Concierge Widget
- Fixed floating action launcher (`56px` circle in Deep Navy with Crimson badge marker).
- Expands into a `rounded-lg` window (`380px` desktop width) elevated at Tier 3 with an ultra-clean, conversation-centric feed.