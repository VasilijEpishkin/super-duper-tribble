# QA evidence — ALTAR’ multi-page preview

## Completed

- `node --check site.js` passed; the packaged `dist/site.js` was checked during Site preparation.
- Sites saved and privately published the static build successfully. Deployment status: `succeeded`.
- The hosted URL resolves to its private sign-in screen in an unauthenticated browser.
- Source UI uses internal query routes for home, catalog, product, custom order, workshop, care, contacts, cart and checkout information.
- All 12 catalog images were paired with matching product cards from the live ALTAR’ catalog DOM. The homepage now uses distinct, catalog-backed product images.
- In local Chrome, the home and catalog pages rendered, source product images displayed, and the 390px catalog used a two-column grid with the mobile menu hidden. The private hosted version still needs authenticated review.
- Local Chrome confirmed 9 scroll-reveal targets on the home page, with 8 entering the visible state after scrolling. CSS page transitions are supported in that browser; reduced-motion styles disable the added effects. This checks behavior only, not design quality.
- The prior claim of Stitch fidelity was incorrect: the implementation was written separately. The current version remains a corrected interpretation, not an exact Stitch transfer.

## Pending authenticated review

- Rendered visual quality, responsive breakpoints, browser console, image loading and filter/cart interactions.
- The owner must complete ChatGPT sign-in before the private preview can be reviewed. This shares the account name and email with the Sites app; account selection was left to the owner.

## Scope limits

- Cart state is browser-local; no order, form, personal data or payment is submitted.
- Contact channels, stock, and policy claims need owner confirmation. The current Stitch exports contain invented facts and require correction before literal reuse.
