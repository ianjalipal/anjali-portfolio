# Anjali Pal — Product Designer Portfolio

Personal portfolio: UI/UX and product design case studies in healthcare, SaaS and B2B workflow design.

Live at: https://ianjalipal.github.io/anjali-portfolio/ (once GitHub Pages is enabled on this repo)

## Contents

No build step — plain HTML/CSS/JS, one file per page.

- `index.html` — main portfolio, minimal / editorial (hero, about, services, selected work, skills, process, contact).
- `index-bento.html` — a compact single-screen bento "intro" grid (à la Sanjay Billa / Evan Smith /
  Daniel Evans): profile card (avatar, availability, location + live time, quick buttons), a
  "Tools I use daily" chip grid, a "Selected work" link list, a small stats card, "Right now",
  and a "Let's work together" card. Warm light, one clay accent, handwritten (Caveat) card labels.
  No scroll on desktop. Swap the placeholder avatar for a photo.
- `index-moxa.html` — alternate landing in a brutalist-editorial "moxa" style: cream panel inside
  a black frame with orange geometric shapes, heavy Archivo Black display type, a sparkle/asterisk
  motif, a diagonal scrolling skills marquee, strikethrough joke in the hero, hard-edged split
  buttons, centered section headers, alternating portfolio rows, a 2×2 services grid.
  Swap the chosen variant over `index.html` once picked.
- `resume.html` — web résumé, printable to PDF.
- `verified-beauty-providers.html` — case study (three-sided marketplace design system, Figma-to-code).
- `ability-amore.html` — case study (accessible native iOS dating app).
- `mostly-events.html` — case study (events-industry gig marketplace, live at mostlyevents.com).

## Design — `index.html`

Minimal / editorial. Warm light palette (`--bg #FAF9F6`, `--ink #1C1B18`, one restrained
clay accent `--accent #B4603C`). Type: **Hanken Grotesk** (body + headings) with **Fraunces
italic** for the accent phrase, the stat figures and the pull-quote. Generous whitespace,
rounded soft cards, thin rules.

Interactions (all `prefers-reduced-motion`-aware): a refined CSS-3D isometric plate stack +
clay orb in the hero with gentle float and cursor parallax; an additive custom cursor
(dot + trailing ring that grows over links) on fine-pointer devices; magnetic pill buttons;
scroll-reveal on sections (scroll-driven, with load/timeout fallbacks so content is never
left hidden); nav hairline on scroll; back-to-top; live Bangalore time in the footer.

The case-study pages each keep their own bespoke palette (Ability Amore → violet,
Mostly Events → light blue, VBP → dark violet).

## Sharing / SEO

Every page has `<title>`, `<meta name="description">`, canonical URL, an inline SVG favicon,
and Open Graph / Twitter Card tags. For a link-preview image, add a 1200×630 `og-cover.png`
to the repo root and uncomment the `og:image` line in each page's `<head>`.
