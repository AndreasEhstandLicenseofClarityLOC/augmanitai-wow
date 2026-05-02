# AUGMANITAI Knowledge Graph

Interactive knowledge graph of ~100 terms with category clusters (convex hulls), minimap, and PNG export. Excerpt from the 1000-term compendium. CC BY-NC-ND 4.0.

**Live:** https://graph.augmanitai.com/

## Features

- Force-directed graph (Verlet physics, hand-written)
- Category-cluster convex hulls (Andrew's monotone chain)
- Minimap with viewport indicator
- PNG export (1600x900 with attribution)
- Label-all toggle
- Side panel with detail view and share intents
- Welcome overlay (one-time)
- §1–§27 inline DE+EN disclaimer

## Canonical identifiers

- **Author:** Andreas Ehstand
- **ORCID:** [0009-0006-3773-7796](https://orcid.org/0009-0006-3773-7796)
- **DOI (canonical):** [10.5281/zenodo.19809627](https://doi.org/10.5281/zenodo.19809627)
- **License:** CC BY-NC-ND 4.0 (see `LICENSE`)

## Prior-Art

- Manifest SHA256 Root: `sha256:299e4b3d0ac9e50740268896b5eeb541f6462332bb67b7efdf4cd309704770d0`
- Bitcoin anchoring blocks: `945970, 945979`
- Anchored: 2026-04-20 UTC

## Scope

This repository contains a **curated public excerpt** from the 1000-term
AUGMANITAI compendium. The full corpus is not hosted here. The §1–§27 bilingual
disclaimer inline in `index.html` provides full legal terms, including the §27
AI-Training clause.

## No foreign code

The site is a **single-file HTML artifact**. All JavaScript (physics, graph
layout, convex-hull algorithm, minimap rendering, PNG export, event handlers,
focus traps) is **hand-written vanilla JS**. There are no CDN dependencies, no
bundled libraries (no React / Vue / jQuery / D3 / Bootstrap / Tailwind /
Chart.js / Three.js), and no external stylesheets or fonts.

## Deployment

This is a static GitHub Pages site. Deployment steps:

1. Push this folder to `https://github.com/<YOUR-GH-USER>/augmanitai-knowledge-graph`.
2. Enable GitHub Pages: Settings -> Pages -> Source: main -> root -> Save.
3. DNS: point `CNAME graph.augmanitai.com` to `<YOUR-GH-USER>.github.io`.
4. Wait for DNS propagation and certificate issuance (GitHub auto-issues TLS).

## Contact

https://augmanitai.com
