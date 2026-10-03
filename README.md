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

Open `index.html` in a static web host. Routes use `?page=` (for example, `?page=catalog` or `?page=workshop`). Cart contents live in browser local storage. The catalog names and prices come from the reviewed source catalog; checkout, inventory, contact details, and order submission need confirmation before a real store launch. The 12 product photos are now paired with the corresponding product cards in the live ALTAR’ catalog.

## Stitch → website

Stitch screens are design drafts and HTML exports, not a connected storefront. The previous site was coded separately and was not a pixel-accurate transfer. The saved design screens cover home, catalog, product and contacts; their exports also contain invented product names, terms and contact facts. See [the content and asset audit](stitch-content-audit.md): all 12 real product images are already uploaded to Stitch, but the generated cards did not use the correct associations. The current code uses the verified product catalog and a corrected interpretation of the proposed design, with restrained scroll reveals and page transitions that respect reduced-motion preferences. A screen-by-screen fidelity pass and remaining page designs are still required before claiming that the site is assembled from Stitch.
