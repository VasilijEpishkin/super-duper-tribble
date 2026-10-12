# ALTAR’ — page map v0.2

Observed on 12.10.2026 from the sitemap and both pages of the JavaScript catalog: six navigation pages, one additional blank page and eighteen catalog positions. Detailed URLs: [`docs/SITE_INVENTORY.md`](docs/SITE_INVENTORY.md). This is a proposal for the redesign, not a claim that current checkout was tested. [Source site](https://altarishere.com/).

| Page | Current URL | Proposed job | Primary action |
|---|---|---|---|
| Home | `/` | Brand introduction, selected pieces and paths to shop/custom | Browse jewelry |
| Catalog | `/ykrashenia` | Browse 18 listed positions, including the gift certificate | Open product |
| Product detail ×18 | Mixed `/tproduct/...` and `/ykrashenia/tproduct/...` | Show image, story, price, size/availability and order terms where relevant | Order / inquire |
| Custom order | `/individualnyzakaz` | Explain brief → sketch → making → delivery | Start in Telegram |
| Workshop | `/masterskaya` | Show craft, people and making process | Browse pieces / custom order |
| Care and warranty | `/recomendazii` | Care instructions and verified warranty terms | Browse pieces / contact |
| Contact | `/contact` | Real contact channels, location and support | Telegram / phone / email |

## Home sequence

1. Hero: single strong ALTAR image, concise brand line and clear catalog/custom-order actions.
2. Selected artifacts: 3–4 products with current prices and direct detail links.
3. Brand story: handmade individuality, with restrained symbol graphics.
4. Catalog gateway: rings and pendants, with a clear path to cuffs, earrings, bracelets and the gift certificate; final grouping follows the verified product map.
5. Editorial film/photo chapter: short vertical clips or stills showing jewelry in use and packaging.
6. Custom order: process in three steps, expected response route and Telegram CTA.
7. Workshop/care proof: making process and brief care/warranty summary.
8. Footer: accurate contacts, policy links and navigation.

## Core flow

Home or catalog → product detail → size/availability when relevant → chosen order action → confirmation/next step. The product action, order page/form/cart, confirmation state and any policy/checkout pages depend on the owner’s order decision; this map remains a draft until that decision and the platform/hosting choice are recorded. Custom order currently leads to Telegram; confirm whether to retain it before approval.

## Navigation and states

- Main: Jewelry, Custom order, Workshop, Care, Contacts. Logo returns home. Mobile navigation mirrors this order.
- Footer: contacts, care, delivery/payment/returns and privacy/terms once confirmed. Preserve/redirect existing product URLs at launch.
- Product states to design: available, made to order, unavailable; size required/unknown; image loading/failure; order success/error.
- Do not add account, search or advanced filters for the 18-position initial catalog without a demonstrated need.
