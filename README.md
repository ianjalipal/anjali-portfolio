# Anjali Pal — Product Designer Portfolio

Personal portfolio: UI/UX and product design case studies in healthcare, SaaS and B2B workflow design.

Live at: https://ianjalipal.github.io/anjali-portfolio/ (once GitHub Pages is enabled on this repo)

## Contents

No build step — plain HTML/CSS/JS, one file per page.

- `index.html` — main portfolio (minimal / editorial, full scroll).
- `index-bento.html` — **premium 7-card bento landing** (Apple / Linear / Notion feel): glass
  pill nav with avatar + name, hero with blue-circle portrait, category-row Tools & Stack,
  Experience timeline, dark Featured Case Study card (Wizlo / SmarterEMR) with an angled
  dashboard mockup, warm "Beyond Design" card, Selected Projects (Wizlo, MediFlow, Polystox),
  and a Contact card with a line-art desk illustration. White `#FAFAFA`, accent `#4F7CFF`,
  Inter + Caveat labels, scroll-reveal + hover lifts, `prefers-reduced-motion`-aware.
- `index-moxa.html` — alternate landing in a brutalist-editorial style.
- `resume.html` — web résumé, printable to PDF.
- `verified-beauty-providers.html`, `ability-amore.html`, `mostly-events.html` — case studies.

## Add a photo

`index-bento.html` (and index / index-moxa) reference **`anjali.jpg`** at the repo root —
a square-ish B&W headshot. The About card, hero portrait and nav avatar use it and fall back
to a placeholder silhouette until the file is added.

## Design tokens (index-bento)

Warm-neutral white (`--bg #FAFAFA`), accent blue (`--accent #4F7CFF`) with a violet secondary
for the hero circle, light borders (`--line #ECECEC`), 32px card radius, soft blur shadows.
Body **Inter**, handwritten card labels **Caveat**.

## Sharing / SEO

Every page has `<title>`, `<meta name="description">`, canonical URL, an inline SVG favicon,
and Open Graph / Twitter Card tags.
