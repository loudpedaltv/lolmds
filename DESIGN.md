---
version: alpha
name: FloSports
description: >-
  The FloSports design system. One look. One brand. One Flo. Bold, gritty,
  high-contrast visual identity built for underserved sports — momentum-driven,
  sharp, and unmistakably Flo. Derived from the FloSports 2026 Brand Style
  Guide (v7.0) and aligned with the Ignite Design System.

colors:
  # ---- Primary palette ----
  primary: "#FF140F"            # Ignite Red — master brand red (digital)
  primary-on-light: "#ED2925"   # Dark Red — substitute for Ignite Red when placed on white surfaces
  on-primary: "#FFFFFF"
  secondary: "#121212"          # Flo Black — foundation surface, headlines
  on-secondary: "#FFFFFF"
  tertiary: "#939396"           # Cool Grey — borders, captions, metadata
  neutral: "#F5F5F5"            # Neutral Light Grey — soft light surface

  # ---- Surfaces ----
  surface: "#121212"            # Default surface (dark mode is the default)
  surface-light: "#FFFFFF"      # Light surface
  on-surface: "#FFFFFF"
  on-surface-light: "#121212"

  # ---- Greys ----
  dark-grey: "#222222"          # Tonal-elevation layer above Flo Black
  medium-grey: "#6F6F73"        # Mid grey for inactive states / secondary text

typography:
  # NOTE — Source of truth: Ignite Design System (Figma), node 3050-649
  # https://www.figma.com/design/bbwUvSkRtLat32WN2Pnht7/Ignite-Design-System?node-id=3050-649
  # Values below are placeholders inferred from the FloSports 2026 Style Guide
  # and the character of Uni Neue / Indivisible / Rubik. To be reconciled with
  # the Ignite DS scale on the next pass — paste the Figma values and v3 will
  # match them exactly.
  headline-display:
    fontFamily: Indivisible
    fontSize: 64px
    fontWeight: 900
    lineHeight: 1.0
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Indivisible
    fontSize: 48px
    fontWeight: 900
    lineHeight: 1.05
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Uni Neue
    fontSize: 32px
    fontWeight: 900
    lineHeight: 1.1
    letterSpacing: 0em
  headline-sm:
    fontFamily: Uni Neue
    fontSize: 24px
    fontWeight: 700
    lineHeight: 1.2
  body-lg:
    fontFamily: Uni Neue
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.5
  body-md:
    fontFamily: Uni Neue
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
  body-sm:
    fontFamily: Uni Neue
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.45
  label-lg:
    fontFamily: Uni Neue
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0.04em
  label-md:
    fontFamily: Uni Neue
    fontSize: 12px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Uni Neue
    fontSize: 11px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0.1em
  presentation:
    fontFamily: Rubik
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.5

rounded:
  # Shape language is sharp / near-square — matches the engineered, 10°-lean
  # character of the brand. Confirmed by design team.
  none: 0px
  sm: 2px
  md: 4px
  lg: 8px
  xl: 12px
  full: 9999px
---

# FloSports Design System

## Overview

FloSports is the leading digital platform for underserved sports — bold, gritty, and built for momentum. Our visual identity should feel like the sports we cover: sharp, kinetic, hard-won, and uncompromising. Every screen the agent generates should feel like it belongs to a single brand — *one look, one brand, one Flo* — and should reflect the personality of underdog sports: the worn playbook, the dusty gym, the burnt rubber on asphalt.

The brand is built as a **Branded House**: `FloSports` is the corporate identity, `Flo` is the consumer-facing voice, and sport-specific sub-brands (`FloRacing`, `FloWrestling`, `FloHockey`, `FloTrack`, `FloCheer`, etc.) sit beneath. The unified Flo identity is always primary — sub-brand expression is layered on top, never substituted for it.

Mission line (North Star): *"Grow our sports every day."* FloSports does not rely on a single external slogan. Core values to express through design are Accountability, Collaboration, Curiosity, Positivity, Grit, and Excellence.

Approved consumer CTAs (closed list — do not invent variants): **LIVE ON FLO**, **WATCH ON FLO**, **ONLY ON FLO**.

A recurring motif throughout the brand — and one the agent should preserve — is the **10° forward lean** seen in the Flo Hawk icon, the sub-brand brush strikes, and partnership "X" multipliers. It signals motion and momentum.

The product defaults to **dark mode**.

## Colors

The palette is anchored in high-contrast neutrals with a single high-energy accent. Dark-first by default; light surfaces are supported but secondary.

- **Ignite Red (`#FF140F`)** — Master brand red. Primary accent for actions, key links, important callouts, and brand moments. The fuse has been lit; use sparingly so it stays urgent. **Substitute with Dark Red `#ED2925` whenever the red sits on a white surface** — Ignite Red is calibrated for dark surfaces, not white.
- **Flo Black (`#121212`)** — Foundation. Strength, authority, the highest standard. Primary surface in dark mode, headline text on light backgrounds, and body copy.
- **White (`#FFFFFF`)** — Clarity, visibility, focus. Backgrounds and text on dark surfaces; lets performance speak for itself.
- **Cool Grey (`#939396`)** — Balance, precision, data. Borders, dividers, captions, and metadata.
- **Neutral Light Grey (`#F5F5F5`)** — Soft light surface and section-dividing background.
- **Dark Grey (`#222222`)** — Tonal layer immediately above Flo Black; use to separate cards, surfaces, and modules without resorting to shadows.
- **Medium Grey (`#6F6F73`)** — Mid grey for inactive states and secondary supporting text.

Ignite Red also drives the brand **gradient** used for hero panels and texture overlays.

## Typography

Three typefaces, each with a job. Don't mix more than two on one screen.

- **Uni Neue** — *Main brand font.* Rounded edges, warm but professional. The default for headlines, body copy, and UI labels across product surfaces. Weights used: Heavy Italic, Bold, Regular.
- **Indivisible** — *Social and scroll-stopping headline font.* Constructed to stop the scroll. Reserve for big editorial headlines, marquee event titles, and social. Weights used: Black, Semi-Bold, Black Italic.
- **Rubik** — *Presentation font.* Easy to share, easy to build with, no formatting surprises. Use for slides, internal decks, and pitch material — not for product UI. Weights used: Black, Bold, Regular.

Web fallback stack: `Uni Neue, Inter, "Helvetica Neue", Arial, sans-serif`.

**Source of truth for type scale:** [Ignite Design System (Figma) — node 3050-649](https://www.figma.com/design/bbwUvSkRtLat32WN2Pnht7/Ignite-Design-System?node-id=3050-649). The token values in the YAML front matter are placeholders; they will be reconciled to the Ignite DS values on the next revision.

## Layout

The shape language is sharp and engineered (see *Shapes*). A formal spacing scale is owned by the Ignite Design System and is intentionally out of scope for this file at this version. Layout direction: **fluid on mobile, fixed-max-width on desktop** (1200–1440px content max recommended).

Composition rule for video and broadcast surfaces: the Flo watermark holds the **upper-right** of the frame at a fixed size; co-branded or league watermarks sit immediately to its left at consistent scale.

## Elevation & Depth

FloSports is a flat, gritty, high-contrast brand — depth is conveyed through **tonal contrast and texture**, not through ambient drop-shadows. Where separation is needed in UI, prefer:

1. A 1px Cool Grey (`#939396`) border at 30–50% opacity, or
2. A switch between Flo Black surface (`#121212`) and the elevated Dark Grey tonal layer (`#222222`), or
3. Texture overlays drawn from the approved set (Dark Paper, Glued Poster, Glitched Print, Halftone, Film Dust, Dust Particles).

**Drop shadows are permitted in one situation only:** when applied over photography to help text or marks read against a busy image. Outside that use case, do not use drop shadows, glassmorphism, or soft ambient depth. If a shadow is required over a photo, keep it short and hard rather than soft and diffuse.

## Shapes

The shape language is **sharp and engineered**. The Flo Hawk and brush strikes are imperfect and hand-cut, but UI containers default to **near-square corners**:

- `rounded.sm` (2px) for inputs, chips, and dense data UI.
- `rounded.md` (4px) for buttons and cards — modern but rigid.
- `rounded.lg` (8px) only for hero modules, premium cards, and partner lockups.
- `rounded.full` (9999px) reserved for avatars, status pills, and live indicators.

The 10° forward lean is a **graphic accent**, not a UI primitive — apply it to brand marks, decorative strokes, and section dividers, never to functional containers.

## Imagery

Photography is **bold, high-contrast, intentional**. Edits should enhance color and amplify the intensity, emotion, and energy of competition. Two treatments:

- **Hero photography.** Sharp, full-bleed, minimal cropping interference. Subject-forward.
- **Treated photography.** Background-layer use only. Reduced saturation, blended with texture overlays, layered under headlines.

Approved background textures and effects: Dark Paper, Glued Poster, Glitched Print, Diet Vector (Sour Chew), Halftones, Film Dust, Dust Particles, and KolorMarc-True Grit Photoshop brushes. Lead with texture on every canvas — let the grit show through.

## Voice & Tone

The Flo voice is **confident, kinetic, and direct**. We talk like the athletes and the communities we cover — never like a corporate press release. Lean into momentum verbs (run, drop, stick, ignite, win), keep sentences short, and respect the reader's time. Mission anchor: *Grow our sports every day.* Avoid hype that the result on the field doesn't back up.

## Do's and Don'ts

- **Do** lead with the Flo Hawk and let it own the upper-right of any video frame.
- **Do** reserve Ignite Red for the single most important action on a screen — it should feel urgent, not ambient.
- **Do** swap Ignite Red `#FF140F` for Dark Red `#ED2925` whenever the red sits on a white background.
- **Do** lead every canvas with texture — paper, halftone, dust, grit.
- **Do** preserve the 10° forward-lean motif in brand marks, strokes, and decorative accents.
- **Don't** stretch, distort, tilt, recolor, or outline the Flo Hawk or any logo lockup.
- **Don't** mix more than two font weights on a single screen.
- **Don't** revert to outdated logo treatments or invent new lockups like "FloKids" or "Flodium."
- **Don't** use Ignite Red for body text or large fills — it loses urgency.
- **Don't** apply drop shadows except over photography for contrast. No glassmorphism, no soft ambient depth.
- **Don't** mix rounded and sharp corners in the same view.
- **Don't** combine the Flo Hawk graphic-element treatment with the FloSports wordmark.

---

*Source: FloSports 2026 Brand Style Guide v7.0 + Ignite Design System (Figma). Maintained by the FloSports Brand Team — brand@flosports.tv. Resolution log for v2 is in `DESIGN.questions.md`.*
