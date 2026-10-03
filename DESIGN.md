---
version: alpha
name: ALTAR’ — Тихая сила артефакта
description: Редакционная витрина украшений, где личный смысл и фактура предмета важнее демонстративной роскоши.
colors:
  canvas: "#F7F4EE"
  surface: "#F3F1EC"
  stone: "#E8E5DF"
  ink: "#1C1B1A"
  muted: "#77736D"
  accent: "#8C2E24"
typography:
  display-xl:
    fontFamily: EB Garamond
    fontSize: 72px
    fontWeight: 500
    lineHeight: 0.98
    letterSpacing: "-0.035em"
  heading-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: 500
    lineHeight: 1.04
    letterSpacing: "-0.025em"
  heading-md:
    fontFamily: EB Garamond
    fontSize: 30px
    fontWeight: 500
    lineHeight: 1.1
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: 400
    lineHeight: 26px
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: 400
    lineHeight: 22px
    letterSpacing: "0.02em"
  label-md:
    fontFamily: Geist
    fontSize: 11px
    fontWeight: 400
    lineHeight: 14px
    letterSpacing: "0.16em"
rounded:
  sm: 0px
  md: 0px
  lg: 0px
spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 32px
  xl: 64px
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.canvas}"
    rounded: "{rounded.sm}"
    padding: 16px
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.sm}"
    padding: 16px
---

## Overview

ALTAR’ делает украшения для женщин, которые соединяют внешнюю красоту с самостоятельностью, опытом и внутренней опорой. Украшение может стать личным знаком или напоминанием, но бренд не диктует его значение: его определяет сама владелица. Интерфейс должен оставлять место для личной интерпретации и помогать увидеть реальный предмет.

## Colors

- **Mineral canvas (`#F7F4EE`):** основной фон сайта.
- **Stone (`#F3F1EC` / `#E8E5DF`):** поверхности и тонкие разделители.
- **Charcoal (`#1C1B1A`):** основной текст и контрастные действия.
- **Oxblood (`#8C2E24`):** сдержанный акцент для важных действий и деталей.

Maintain readable contrast. Long-form product and care copy uses warm light text, not dim metallic grey. Color never carries product status by itself.

## Typography

Use EB Garamond for editorial display and section headings. Use Geist for product names, prices, descriptive copy, navigation, and forms. Product facts remain comfortably readable and never inherit the smallest tracked label style. Russian copy is the default; keep the supplied ALTAR’ voice and edit only for clarity.

## Layout

Use an asymmetrical 12-column desktop composition and a clear 4-column mobile grid, with generous but purposeful breathing room. Photography leads the first viewport; product names, prices, size selection, and purchase actions remain easy to scan. Keep navigation and cart visible. Use spacious editorial sections for brand story and workshop content, then return to clear shopping structure in the catalog and product details.

## Elevation & Depth

Use pale mineral surfaces, physical photography, and occasional hairline rules. Avoid conventional cards with heavy shadows, glow, blur, or simulated glass. Prefer the lighting and texture already present in ALTAR’ photographs over generated decorative backgrounds.

## Shapes

Use sharp corners and simple rectangular image frames. Do not use pills or rounded cards. Preserve clear focus outlines and touch targets even when the visual system is angular.

## Components

- **Primary action:** high-contrast charcoal rectangular button with a direct Russian verb (e.g. «В каталог», «Добавить в корзину»).
- **Secondary action:** quiet charcoal text link with an arrow or underline.
- **Product presentation:** image first, then name, price, available size/availability only when verified.
- **Product detail:** image gallery paired with readable product story and explicit size/purchase controls.
- **Forms:** visible labels, clear consent text, inline errors, and a strong keyboard focus state.
- **Navigation:** concise menu, discoverable cart and separate route for individual orders.

## Do’s and Don’ts

**Do** use original jewelry and workshop photography from the Miro/Stitch source library; let real metal, stone, hands, fabric, and light carry the mood. Keep poetic copy paired with factual product information.

**Don’t** invent materials, stones, availability, prices, or delivery terms; use literal occult symbols, witch/goddess imagery, fake relic labels, or erotic language; imitate a generic luxury/SaaS template; or let oxblood overwhelm the product. The older dark Stitch theme is exploratory, not the approved storefront direction.
