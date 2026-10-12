# Materials routing — ALTAR' redesign v2

Source of truth = Google Drive folder `ALTAR’`. The repo is **public and holds no originals**: only this doc, `materials/manifest.yaml` (index: Drive id, hash, category, usage) and web-optimized assets the site actually ships (`public/assets/…`). Local working copies live in `materials/` (git-ignored). Stitch board and Jules receive derived copies only when the routing table says so.

## Folders (mapped from Drive)
| Local folder | Drive source | What it is |
|---|---|---|
| `materials/brand/` | Лого,элементы,брендбук | logo, brand elements, brandbook |
| `materials/references/` | loose images in Drive root | moodboard / inspiration (typography, posters, identities) — NOT product |
| `materials/product/` | Предметка и пнг, ПНГ первая коллекция, Altar' каталог новые | cut-out product PNGs, catalog shots |
| `materials/photo/` | Сьемка, Первая сьемка, Пленка | photoshoots, film: editorial/hero imagery |
| `materials/content/` | Контент | texts, copy, catalogue data |
| `materials/_inbox/` | — | unsorted; nothing is used from here |

## Routing: material → site part → tool/agent
| Category | Site parts | Stitch board | Tool / agent | Jules |
|---|---|---|---|---|
| brand | tokens, logo, footer, packaging section | logo + 2–3 key elements | art-director (`design-dna` extract → `design-tokens.md`) | optimize/export SVG, favicon set |
| references | visual direction only | yes (moodboard) | art-director (`design-dna`, `design-taste-frontend`) | never |
| product | catalog, product cards, product pages | 5–8 representative pieces, not all | component-researcher → frontend-developer | resize/webp/srcset batch, catalog data → JSON |
| photo | hero, editorial, about/workshop | 3–6 best frames | art-director picks → motion-3d-engineer (parallax/reveal) | image optimization batch |
| content | all copy, catalog data, SEO | no | ux-architect (brief/page-map), research-librarian (facts) | SEO metadata, JSON-LD |

Rules: every file gets one row in `materials/manifest.yaml`; `use:` names the page/section; `stitch:` true only for files uploaded to the board; agents receive **manifest rows/paths**, never pasted images.
