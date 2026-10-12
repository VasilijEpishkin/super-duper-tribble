# ALTAR’ — brief v0.2

Status: discovery draft, 12.10.2026. Facts below come from the [live site](https://altarishere.com/), local brandbook, both Miro boards, the local content cards and the [brand source audit](docs/BRAND_SOURCE_AUDIT.md). The manifest indexes files; it does not substitute for reading their contents.

## Product and audience

- Handcrafted jewelry and one-off commissions. The brandbook describes women and men aged 22–45 who value individuality, fashion and objects with personal meaning. Miro develops a woman-centered muse. Confirm whether this is the intended current audience, a creative archetype, or one segment before final copy and casting.
- Brand promise: each piece is an artifact/sign with its own story. Miro asks for mystery, inner strength and subtle sacredness without literal occult imagery, aggressive sexuality or showy luxury. Preserve handmade variation and room for personal interpretation without making the shop hard to use.
- Geography observed: Moscow; Russian-language site; prices currently in RUB. Confirm shipping geography and whether a second language is needed.

## Goals

- Primary proposed goal: move a visitor from inspiration to a product inquiry/purchase with clear size, price and next step.
- Secondary goal: generate custom-order inquiries via Telegram.
- Working success measure: completed qualified orders/inquiries and conversion from product page to order. Baseline and measurement access are not yet known.

## Scope for first release

- Preserve and redesign the six existing navigation pages: home, catalog, custom order, workshop, care/recommendations, contacts; account for all 18 positions now visible across both catalog pages, including the gift certificate. See `docs/SITE_INVENTORY.md`.
- Organize the catalog by item type after mapping the 10 rings, 4 pendants, cuff, mono-earring, bracelet and gift certificate. Avoid a complex filter system without a demonstrated need.
- Product detail needs gallery, item story, current price, size/availability, care, delivery/payment information and a clear order action.
- Use original ALTAR photos, logo and brand symbols. Third-party reference images are moodboard only. Show only the current or approved packaging; its layered unboxing is part of the brand experience. Archive Stories are not proof that a product is currently for sale.
- Current Tilda site stays live until the replacement order flow is verified.

## Brand direction to review

- Editorial jewelry gallery: ivory `#FFFEF7`, deep red `#9C0000`, dark brown `#2C1900`, black `#000000` from the brandbook.
- Use the existing handwritten ALTAR wordmark and symbolic motifs sparingly; generous white space and close-up photography keep jewelry central.
- The brandbook lists Covered By Your Grace, TrueTypewriter PolyglOTT and Fira Code. Check Cyrillic coverage, font files/licensing and readability before fixing web typography.
- Primary proposal: a light gallery for browsing and dark/red chapter moments for brand storytelling. A fully dark immersive direction is an alternative for visual exploration, not the default for the catalog.

## Constraints and open decisions

1. Which of the 18 listed positions are current, and what are their confirmed photos, sizes and availability? The live catalog and asset folders are not yet mapped item by item.
2. Confirm shipping, returns, privacy policy and the visible lifetime-warranty claim before publishing copy.
3. Confirm final visual direction after reviewing page drafts; this brief is not design approval.
4. Before approving the page map and Jules implementation tasks: decide how ready-made items are ordered (Telegram, form, cart or online payment), who maintains product data, and the matching stack/hosting. This does not block the current source audit.

## Owner decisions (12.10.2026)

- **D1 · Order flow = as on the current site.** Ready-made pieces: «Оформить заказ» form on the product card (name, email, phone, Telegram, promo code, consent to policy). Custom pieces: Telegram (`t.me/altarishere`). No on-site cart/payment is introduced by this redesign. Still to confirm before build: where form submissions are delivered today (email/Telegram/CRM), what the visitor sees after sending, and how the promo code is honored; the new site must reproduce these, not just the fields.
- **D2 · Audience = all sources together, nothing excluded.** Brandbook: women and men 22–45; Miro: detailed woman-centred image and emotional tone (inner strength, freedom, softness, personal interpretation); site copy and Stories: range from quiet symbolism to irony. Design and copy stay inclusive (no gender-split catalog, no exclusion of men), keep the emotional core from Miro and avoid literal esotericism, aggression, showy luxury and over-sexualization. Re-check against the owner only if a conflict appears in copy.

