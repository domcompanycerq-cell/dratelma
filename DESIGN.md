---
name: Dra. Telma Costa · Otomodelação
description: Taupe satin, white ground and sand rules; the moment a patient pins her hair up and stops hiding.
colors:
  taupe: "#A99B8C"
  taupe-press: "#9E8F80"
  sand: "#B5A595"
  white: "#FFFFFF"
  ink: "#2E2620"
  ink-soft: "#6B5E52"
typography:
  display:
    fontFamily: "Gambetta, Georgia, serif"
    fontSize: "clamp(2.4rem, 4vw, 3.8rem)"
    fontWeight: 500
    lineHeight: 1.02
    letterSpacing: "-0.02em"
  title:
    fontFamily: "Gambetta, Georgia, serif"
    fontSize: "clamp(1.05rem, 1.4vw, 1.3rem)"
    fontWeight: 400
    lineHeight: 1.3
  body:
    fontFamily: "Montserrat, system-ui, sans-serif"
    fontSize: "15.5px"
    fontWeight: 400
    lineHeight: 1.75
  label:
    fontFamily: "Montserrat, system-ui, sans-serif"
    fontSize: "15.5px"
    fontWeight: 600
    lineHeight: 1.3
  caption:
    fontFamily: "Montserrat, system-ui, sans-serif"
    fontSize: "13.5px"
    fontWeight: 400
    lineHeight: 1.7
  figure:
    fontFamily: "Montserrat, system-ui, sans-serif"
    fontSize: "22px"
    fontWeight: 600
    lineHeight: 1.2
    fontFeature: "\"tnum\" 1, \"lnum\" 1"
  meta:
    fontFamily: "Montserrat, system-ui, sans-serif"
    fontSize: "12.5px"
    fontWeight: 400
    lineHeight: 1.7
    letterSpacing: "0.02em"
rounded:
  panel: "14px"
  arch-mirror: "999px 999px 18px 18px"
spacing:
  gutter: "clamp(20px, 5vw, 72px)"
  intro-stack: "clamp(24px, 3.4vh, 36px)"
  link-gap: "8px"
  rule-gap: "28px"
components:
  button-primary:
    backgroundColor: "{colors.taupe}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.panel}"
    padding: "10px 20px"
    height: "60px"
  button-primary-hover:
    backgroundColor: "{colors.taupe-press}"
    textColor: "{colors.ink}"
  link-row:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "0"
    padding: "10px 4px"
    height: "60px"
  mirror-frame:
    backgroundColor: "{colors.sand}"
    rounded: "{rounded.arch-mirror}"
    width: "min(100%, 400px, calc((100svh - 160px) * 9 / 16))"
  caption-button:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.caption}"
    padding: "0"
---

# Design System: Dra. Telma Costa · Otomodelação

## Overview

**Creative North Star: "The Dressing-Table Mirror"**

The system is a dressing table at the moment the hair goes up: a white ground where the facts sit, a taupe satin field that holds the moving image, and fine sand rules that do the work other sites give to borders and boxes. The palette is the client's own (taupe, white, sand), with two deep taupe-browns derived from it so every line of text stays legible.

Density is low and calm. The name with her specialty in italic beneath, a paragraph of her own words, one solid taupe action, quiet ruled rows beneath it, then numbers set as figures. Depth comes from material (the satin raster, the white-rimmed arch) rather than from stacked cards. Motion is small and answers the hand: the action lifts, the rows draw an ink underline and nudge right. The only unprompted motion is a single reveal of the mirror's image on first load.

Secondary links are single-line rows over a sand rule, never a stack of identical pills.

**Key Characteristics:**
- Two grounds only: white for reading and acting, taupe satin for the moving image.
- Sand is linework (row rules, rings, dividers), never a fill on the white ground.
- Text is always ink or soft ink, including on taupe; white never carries text on taupe.
- Type-only header (name and italic specialty), an arched mirror with nothing laid over it.
- Gambetta display with an italic subtitle, Montserrat for everything else; proof in tabular figures.
- Quiet response: hover and focus lift or underline; one entrance reveal; nothing moves under reduced motion.

## Colors

A warm, low-chroma palette of three client colors (taupe, white, sand) carried by two derived taupe-brown inks.

### Primary
- **Satin Taupe** (taupe): the client's lead color. Fills the one solid action (WhatsApp), sits under the satin raster plate on the mirror field, colors text selection and the theme color.
- **Pressed Taupe** (taupe-press): the action's hover and focus fill only.

### Secondary
- **Rule Sand** (sand): linework only. The bottom rule of each secondary row, the proof divider, the footer rule and underline color; the placeholder fill inside the mirror glass before video paints.

### Neutral
- **White** (white): the reading ground of the first viewport and footer; the rim and moat of the mirror.
- **Ink** (ink): derived from taupe for legibility. Headings, link labels, icons, figures, the caption and sound toggle on the satin field, text on the taupe action, the hover underline on rows, focus outline.
- **Soft Ink** (ink-soft): derived from taupe. Subtitle, bio, proof labels, footer.

### Named Rules
**The Dark-On-Taupe Rule.** Text and icons on taupe are ink, never white. Ink holds about 5.5:1 on taupe and 4.7:1 on pressed taupe; white on taupe falls under 3:1.

**The Sand-Is-Line Rule.** On the white ground sand is a 1px line or ring. It never fills a surface or carries text there.

**The Two Grounds Rule.** A surface is either white or taupe satin. No third ground, no tinted cards.

## Typography

**Display Font:** Gambetta (with Georgia, serif); self-hosted from Fontshare, 400, 400 italic and 500 used.
**Body Font:** Montserrat (with system-ui, sans-serif); self-hosted variable, 400-600.

**Character:** A warm transitional serif for her name and specialty, roman for the name with an italic subtitle beneath, against a clean geometric sans that carries her words, every instruction and every number. Both faces are client-named.

### Hierarchy
- **Display** (500, clamp(2.1rem, 3.3vw, 3.3rem), 1.02, -0.02em, balanced; mobile clamp(2.2rem, 11vw, 2.8rem)): the name only, "Dra. Telma Costa". Roman, the head of the white column.
- **Title** (400 italic, clamp(1.05rem, 1.4vw, 1.3rem), 1.3, soft ink, balanced): the subtitle "Otomodelação & Estética Avançada" directly under the name, with a non-breaking space binding its last two words.
- **Body** (400, 15.5px / 15px mobile, 1.75, max 52ch, soft ink, text-wrap: pretty): the bio. A non-breaking space before the last word prevents a widow. The page base is 16px / 1.7.
- **Label** (600, 15.5px, 1.3): link labels, one line each.
- **Caption** (400, 13.5px, ink): the video caption and its sound toggle.
- **Figure** (600, 22px, 1.2, tabular lining figures): proof numbers (+300, 27520).
- **Meta** (12.5px, +0.02em on proof labels): proof labels and footer.

### Named Rules
**The Italic Subtitle Rule.** Italic Gambetta belongs to the subtitle under the name. The name itself is roman.

**The Figures Rule.** Any credential or count is set in tabular lining figures in Montserrat, never in Gambetta.

**The No-Widow Rule.** Running text and headings end on at least two words: text-wrap pretty or balance, plus a non-breaking space before the last word where needed.

## Layout

Desktop is a full-height two-column stage at 50/50 (min-height 100svh). The left column is a vertically centered stack, pushed toward the center seam and capped at 680px; the link list and proof strip are capped at 460px and the bio at 52ch. The order is fixed: name and subtitle, bio, links, proof; everything left-aligned. The right column is the full-bleed satin field with the mirror centered and its caption beneath. The gutter is fluid (gutter); the intro stack breathes at intro-stack.

Below 860px the stage collapses to one column and the satin mirror field comes first (44px 20px 40px), followed by the white section (32px 20px 36px padding, 22px stack gap) and the footer. In the white section the name block, bio (centered with auto inline margins), proof strip and footer row are centered; the links stay full width and left-aligned. Separation is by grounds and sand rules, never by card boxes. The footer is a single row of meta text under a 1px sand rule, max 1280px.

## Elevation & Depth

Depth is material, not chrome. The satin field is a raster plate (assets/satin.jpg, regenerated in taupe) over taupe. The arch is lifted by concentric box-shadow spreads (a white rim, a translucent white moat, a white outer ring) plus one long soft ink drop beneath. On the white ground only the taupe action casts a shadow, and only on hover or focus.

### Shadow Vocabulary
- **Mirror ring** (`box-shadow: 0 0 0 1.5px #FFFFFF, 0 0 0 9px rgba(255,255,255,.2), 0 0 0 10px rgba(255,255,255,.6), 0 40px 70px -30px rgba(46,38,32,.55)`): the video arch on taupe.
- **Action lift** (`box-shadow: 0 14px 28px -14px rgba(46,38,32,.55)`): the taupe action on hover and focus.

### Named Rules
**The Ringed Frame Rule.** Framed media gets rings and a moat, not a card. Shadows are ink-tinted, never neutral black.

**The Answering Surface Rule.** Surfaces are flat at rest and respond only to hover and focus: the action lifts 2px and darkens, rows draw an ink underline from the left and shift their content 6px right (0.4-0.5s, cubic-bezier(.16, 1, .3, 1)). Transitions are removed under reduced motion.

## Shapes

One silhouette: the arch for the mirror (999px top, 18px foot). The taupe action is a soft panel (14px). Secondary links have no box; their shape is a full-width 1px sand bottom rule. The mirror's glass carries nothing on top of it: no buttons, badges or marks.

## Components

### Buttons
Singular and warm: one solid taupe action per page.
- **Shape:** soft panel (14px), 60px minimum height, two-part grid (24px icon, single-line label), 16px gap.
- **Primary:** taupe fill, ink icon and ink label, no border.
- **Hover / Focus:** rises 2px, fill moves to pressed taupe, action lift shadow appears (0.4s transform and shadow, 0.3s color); returns to rest on press. Focus adds the global 2px ink outline at 3px offset.

### Link Rows (secondary)
- **Style:** no box, transparent ground, ink line icon and ink 600 single-line label over a full-width 1px sand bottom rule; 8px between rows.
- **Hover / Focus:** an ink 1px underline scales in from the left over the sand rule (0.5s), and the icon and label shift 6px right (0.4s).

### Proof Strip
Two figure pairs (12.5px soft-ink label over a 22px tabular figure), divided by a 1px sand rule with 28px either side.

### Mirror (signature)
The clinic video (cut to start at 0:06.1) in a 9:16 white-rimmed arch on the taupe satin field, with nothing laid over the glass. Below it an ink caption, "Conheça o consultório", ends in a text button "ativar som" (underlined, 45% ink underline, 3px offset) that toggles sound and reads "desativar som" when sound is on. A second text button, "pausar" (reads "reproduzir" when paused), stops and restarts the loop. Clicking the video toggles sound as well. On the first visible load the image is revealed bottom-up (clip-path inset 100% to 0, brightness .8 to 1, 1.25s, .15s delay, cubic-bezier(.16, 1, .3, 1)); it runs only without reduced motion, and under reduced motion autoplay stops.

## Do's and Don'ts

### Do:
- **Do** keep exactly one solid taupe action per view; every other link is a single-line row over a 1px sand rule.
- **Do** set ink (#2E2620) on taupe and pressed taupe, for text and icons alike.
- **Do** draw sand as 1px lines and rings on the white ground.
- **Do** keep the video in the arch (999px top, 18px foot) with the white rim.
- **Do** put video controls in the caption as text, off the glass.
- **Do** set the bio as running text between the name and the links, with no widow.
- **Do** set counts and registrations in tabular lining figures in Montserrat.
- **Do** honour prefers-reduced-motion: link transitions and the mirror reveal are skipped, and video autoplay stops.

### Don't:
- **Don't** put white text on taupe.
- **Don't** lay buttons, icons or badges over the video glass.
- **Don't** stack secondary links as identical filled pills.
- **Don't** introduce a third ground or wrap content in shadowed cards; separate with grounds and sand rules.
- **Don't** add uppercase tracked labels above headings.
