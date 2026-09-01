# Anjali Pal — Product Designer Portfolio

Personal portfolio — a premium single-page bento grid.

Live at: https://ianjalipal.github.io/anjali-portfolio/

## Contents

No build step — plain HTML/CSS/JS, one file per page.

- `index.html` — the homepage: a premium 7-card bento grid (Apple / Linear / Notion feel).
  Glass pill nav (avatar + name), a hero with a mesh-gradient blob portrait and 4 icon stats,
  a category-row Tools & Stack card, an Experience timeline, a dark Featured Case Study card
  (Wizlo / SmarterEMR) with an angled dashboard mockup, a warm "Beyond Design" card with
  pastel hobby stickers, Selected Projects (Wizlo, MediFlow, Polystox), and a Contact card
  with a line-art desk illustration.
- `index-bento.html` — identical source of the homepage, kept as a named copy.
- `index-minimal.html` — the earlier minimal / editorial landing (full scroll, Fraunces italic).
- `index-moxa.html` — the earlier brutalist-editorial landing.
- `resume.html` — web résumé, printable to PDF.
- `verified-beauty-providers.html`, `ability-amore.html`, `mostly-events.html` — case studies.
- `anjali.jpg` — the headshot used by the hero portrait and nav avatar.

## Design tokens (homepage)

White `--bg #FAFAFA`, accent blue `--accent #4F7CFF` with a violet secondary for the hero blob,
light borders `--line #ECECEC`, 32px card radius, soft blur shadows. Body **Inter**, handwritten
card labels **Caveat**. Scroll-reveal, hover lift, mobile hamburger — all
`prefers-reduced-motion`-aware. Tool logos and UI icons are inlined SVGs (no runtime fetches).

## Sharing / SEO

Every page has `<title>`, `<meta name="description">`, canonical URL, an inline SVG favicon,
and Open Graph / Twitter Card tags. For a link-preview image, add a 1200×630 `og-cover.png`
to the repo root and add an `og:image` meta to each page's `<head>`.
