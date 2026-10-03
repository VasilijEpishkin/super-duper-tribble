# ALTAR’ — super-duper-tribble

This repository is the implementation workspace for ALTAR’, a handcrafted jewelry brand. Product and brand research lives in Miro; the proposed visual direction is “Editorial Mineral” in Stitch. The new Russian-language site includes its own internal routes for the home page, catalog, product detail, custom order, workshop, care, contacts, cart, and checkout information. It is a static prototype with a browser-local demo cart; payment and form submission are not connected.

## Project sources

- [Miro — ALTAR’ brand philosophy and packaging](https://miro.com/app/board/uXjVHjFJ6Uc=/)
- [Stitch — Altar Redesign System](https://stitch.withgoogle.com/projects/15828773713461572210)
- [Proposed design system](DESIGN.md)
- [Project discovery artifacts](.)

## Jules workflow

Codex delegates bounded tasks through the already installed and authenticated official Jules CLI (`tools/jules`). The `super-duper-tribble` repository is connected to Jules. Each task needs acceptance criteria; review the resulting PR before merging. The former issue-label GitHub Action was removed because this repository has no `JULES_API_KEY` secret and that path would fail. Direct CLI delegation does not need that secret.

## Preview and limits

Open `index.html` in a static web host. Routes use `?page=` (for example, `?page=catalog` or `?page=workshop`). Cart contents live in browser local storage. The catalog contains 16 source-listed jewelry pieces and one gift certificate across the source site's two catalog pages; checkout, inventory and order submission need confirmation before a real store launch. See [the source site inventory](source-site-inventory.md) for page coverage and the product count.

## Stitch → website

Stitch screens are design drafts and HTML exports, not a connected storefront. The previous site was coded separately and was not a pixel-accurate transfer. The saved design screens contain invented product names, terms and contact facts. See [the content and asset audit](stitch-content-audit.md): all 16 jewelry hero photos and the gift certificate image are already uploaded to Stitch, but the generated cards did not use the correct associations. The uploaded Stitch content document still lists only the first 12; the local source has been corrected to 16+1 and awaits a new upload. The current code uses the verified catalog, with restrained scroll reveals and page transitions that respect reduced-motion preferences. A screen-by-screen fidelity pass and remaining page designs are still required before calling the site assembled from Stitch.
