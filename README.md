# Dakyung Lee — Product Portfolio

A single-page portfolio built to show how I think about product: find the audience insight, launch fast, measure, iterate.

## What's Here

This site walks through three cases from my time at Google Korea and a student startup:

- **Android at G-STAR 2024** — Redesigned Google's booth at Korea's largest gaming expo around gamer-first use cases. +17pp purchase intent, 2× foot traffic vs. prior year.
- **Android × LE SSERAFIM** — Led product strategy for a fan merchandise line across Korea, Japan, Brazil, and Indonesia. 4.58M+ engagements, #1 on Coupang in the Galaxy category.
- **SARABOME** — Built a student housing review platform from zero. Grew to 3.6× monthly active users in one semester with a trust-first verification model.

## How It's Built

Static HTML + CSS, hosted on GitHub Pages. No framework, no build step — one `index.html` and an `images/` folder.

| Decision | Why |
|---|---|
| Single HTML file | Fast load, zero dependencies, easy to maintain |
| CSS custom properties | Light/dark mode without JS framework overhead |
| Native HTML/CSS for data viz | Charts and diagrams stay crisp at any resolution, no library needed |
| Real photos for product shots | Authenticity over polish — these are actual prototypes, booths, and packaging |
| Image optimization (Pillow) | 22 images compressed from 5.8MB → 2.5MB without visible quality loss |

## Design Principles

- **Apple HIG** for layout restraint and typographic hierarchy
- **Google/Android** brightness and color energy
- Fonts: Bricolage Grotesque (display), Instrument Sans (body), JetBrains Mono (mono)

## Run Locally

```bash
git clone https://github.com/dakyungl/dakyungl.github.io.git
open index.html
```

No install, no build. It's just a web page.

## License

© 2026 Dakyung Lee. All rights reserved.
