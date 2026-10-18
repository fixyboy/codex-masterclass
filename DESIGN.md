---
name: Mastering Codex — withfouad
description: A minimal editorial companion for the next build.
colors:
  primary: "#D10F0F"
  primary-hover: "#b90d0d"
  background: "#030303"
  foreground: "#fff"
  muted: "rgba(255,255,255,.6)"
  rule: "rgba(255,255,255,.17)"
typography:
  display:
    fontFamily: "Inter Tight, sans-serif"
    fontSize: "clamp(62px,17vw,96px)"
    fontWeight: 650
    lineHeight: 0.98
    letterSpacing: "-.04em"
  editorial:
    fontFamily: "Instrument Serif, serif"
    fontWeight: 400
  body:
    fontFamily: "Inter Tight, sans-serif"
    fontSize: "17px"
    lineHeight: 1.55
  label:
    fontFamily: "Inter Tight, sans-serif"
    fontSize: "15px"
    fontWeight: 600
spacing:
  gutter-mobile: "24px"
  gutter-tablet: "40px"
  gutter-desktop: "64px"
  desktop-column-gap: "100px"
components:
  primary-download:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.foreground}"
    typography: "{typography.label}"
    padding: "15px 21px"
  primary-download-hover:
    backgroundColor: "{colors.primary-hover}"
---

# Design System: Mastering Codex — withfouad

## Overview

**Creative North Star: "The Editorial Video Companion"**

Confident, minimal, and useful. Oversized type establishes hierarchy; open space and fine horizontal rules organize dense takeaways. The lowercase withfouad identity, black ground, restrained red, and sans/serif pairing are durable brand commitments.

**Key Characteristics:**
- Strong typography with selective italic serif emphasis.
- Open chapter rows, rather than boxed card grids.
- One clear red download action, repeated at the close.

## Colors

### Primary

Red identifies the primary download action and text selection. Its darker sibling is the button hover state.

### Neutral

Black is the page ground; white carries headings and important text. Muted white supports descriptions and secondary labels. Low-opacity white rules separate sections without creating panels.

**The Single Accent Rule.** Preserve red as the only accent; use it sparingly.

## Typography

Inter Tight handles interface text, body copy, and primary headings. Instrument Serif supplies italic title emphasis, sequential chapter numbers, and short chapter summaries. Both load explicitly through Google Fonts with system fallbacks and `display=swap`.

The two-line hero pairs a tight sans heading with italic “Codex.” Chapter titles grow from (32px) to (40px) on desktop; serif numbers grow from (37px) to (48px). Takeaways use (15px), increasing to (16px) on desktop, with (1.65) line height and a (57ch) maximum. Closing type scales from (42px) to (70px), again pairing sans with italic serif. Small labels sit between (11px) and (15px).

## Layout

Mobile starts stacked within equal gutters. The centered container stops at (1200px). At (600px), chapter rows become two columns: heading and summary on the left, takeaways on the right. At (1000px), the hero and closing also split; the hero favors its title column (1.4fr / 1fr), while chapters and closing use (1.2fr / 1fr). Desktop column gaps and responsive gutters are recorded above.

The compact six-part contents index sits below the hero copy on mobile and beside it on desktop. Generous section spacing contrasts with compact navigation rows. Footer links wrap naturally.

## Elevation & Depth

The page is flat: no gradients, glows, or elevated content cards. Typography, whitespace, and rules provide separation. Only the temporary download status has a soft black shadow so it remains legible over page content.

## Shapes

Controls and content use square corners. Fine horizontal rules define open rows; small square bullets mark takeaways. Thin inline SVG arrows and a download icon reinforce link purpose.

## Components

- **Primary download:** square red anchor, white semibold label, download icon, minimum height (54px). Hover darkens the red and reveals a subtle border. The same action appears in the hero and closing.
- **Contents navigation:** six ruled rows, tabular two-digit counts, right-aligned arrows, and minimum row height (51px), increasing to (55px) on desktop. Hover shifts the arrow slightly.
- **Chapter row:** serif number, sans heading, serif summary, and three compact takeaways. White lead phrases distinguish the actions within muted explanatory text.
- **Text links:** white, restrained, with underlines on hover and comfortable targets of at least (44px).
- **Brand:** lowercase withfouad wordmark at (24px); the lighter “with” contrasts with the heavier name.

All links expose a white (2px) focus outline offset by (6px). Reduced-motion preferences disable smooth scrolling and transitions. The temporary download status uses a polite live region. Social destinations are explicitly marked placeholders in the current implementation; replace them before public sharing.

## Do's and Don'ts

### Do:
- **Do** preserve the lowercase withfouad identity and single red accent.
- **Do** use typography, whitespace, and open horizontal rules for hierarchy.
- **Do** keep serif emphasis selective and keyboard focus visible.
- **Do** retain stacked mobile layouts and readable fallback fonts.

### Don't:
- **Don't** add generic card grids, gradients, glows, or decorative animation.
- **Don't** introduce another accent color or make content depend on font loading.
- **Don't** present placeholder destinations as finished social links.
