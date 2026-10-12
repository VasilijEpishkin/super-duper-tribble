# Materials routing — ALTAR' redesign v2

Source of truth = Google Drive folder `ALTAR’`. The single local mirror is `materials/ALTAR’/` with 1,699 files. The repository is **public**: the full local `materials/manifest.yaml`, original filenames and source files stay outside Git. Stitch board and Jules receive only approved derived copies or short, task-specific manifest slices.

## Folders (mapped from Drive)
| Local folder | Drive source | What it is |
|---|---|---|
| `materials/ALTAR’/Лого,элементы,брендбук/` | same | logo, brand elements, brandbook |
| `materials/ALTAR’/` (19 images in root) | loose images in Drive root | moodboard / inspiration (typography, posters, identities) — NOT product |
| `materials/ALTAR’/Предметка и пнг /`, `ПНГ первая коллекция/`, `Altar' каталог новые/`, `Контент/` | same | cut-out product PNGs, catalog shots and source video |
| `materials/ALTAR’/Сьемка/`, `Первая сьемка/`, `Пленка/` | same | photoshoots, film: editorial/hero imagery |
| `materials/ALTAR’/Контент/` | same | 212 original MOV/MP4 videos, nine instories cards, promotional PNG and product stills |
| `materials/ALTAR’/Обзор папок и файлов Drive.docx` | Google Docs file in Drive root | exported overview and secondary copy source |

## Routing: material → site part → tool/agent
| Category | Site parts | Stitch board | Tool / agent | Jules |
|---|---|---|---|---|
| brand | tokens, logo, footer, packaging section | logo + 2–3 key elements | art-director (`design-dna` extract → `design-tokens.md`) | optimize/export SVG, favicon set |
| references | visual direction only | yes (moodboard) | art-director (`design-dna`, `design-taste-frontend`) | never |
| product | catalog, product cards, product pages | 5–8 representative pieces, not all | component-researcher → frontend-developer | resize/webp/srcset batch, catalog data → JSON |
| photo | hero, editorial, about/workshop | 3–6 best frames | art-director picks → motion-3d-engineer (parallax/reveal) | image optimization batch |
| video (.MOV/.MP4) | hero loop, workshop/story section | no (Stitch is static) | motion-3d-engineer: select, compress/trim with ffmpeg → `public/assets/video/*.mp4/webm` | never (large binaries) |
| content (instories PNG, texts) | all copy, catalog data, SEO | no | ux-architect (brief/page-map), research-librarian (facts) | SEO metadata, JSON-LD |

Rules: every source file has one row in local `materials/manifest.yaml`; `use:` names the page/section; `stitch:` true only for files uploaded to the board. Agents receive **short relevant slices**, never the entire manifest. Product-image matching should begin with perceptual hashes against images from the live product cards; manual review resolves ambiguous matches. For video, generate contact sheets first, then review a shortlist. The old `_inbox/`, ZIP exports and category-copy folders were removed after SHA-256 verification; the only local copy is now `materials/ALTAR’/`.

Notes: `instories_*.PNG` are Instagram cards → used as copy/price source, not as imagery. Third-party moodboard images are `references` only and must never ship on the site.
