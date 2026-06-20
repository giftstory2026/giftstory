# README.md

# Gift Story

**Gift Story / قفت ستوري** is a premium Saudi gifting brand based in Jeddah.

Slogan:

```text
WHERE EVERY GIFT TELLS A STORY
```

Gift Story is not a normal product shop.

It is a curated gifting experience built around:

* Premium presentation.
* Elegant packaging.
* Limited drops.
* Gift stories.
* Ready-to-gift boxes.
* Soft, refined visual identity.
* Organized commerce and operations.

---

## 1. Project Purpose

This repository contains the clean source system for Gift Story.

It organizes:

* Brand decisions.
* Website structure.
* Packaging rules.
* Pricing model.
* Commerce setup.
* Inventory and costing.
* Special request forms.
* Visual assets.
* Launch planning.

The purpose is to keep Gift Story clear, consistent, and easy to build without returning to scattered files.

---

## 2. Current Business Direction

Gift Story should be built as a premium brand system, not a rushed online store.

The current direction is:

* Official website for brand trust and storytelling.
* Commerce platform for products, prices, checkout, and payment.
* Special request form for custom gift requests.
* Limited drops for product focus.
* Organized inventory and costing.
* Controlled launch with one main category first.

---

## 3. First Launch Focus

The first active launch category is:

```text
Little Stories — Baby & Kids Gifts
هدايا الصغار
```

Customer-facing line:

```text
قصص ناعمة للمولود والطفل، منسقة بعناية لتصل كهدية كاملة.
```

This category is the first focus because it fits the current Gift Story visual direction, available product direction, and soft premium gifting style.

Other categories should appear as Coming Soon until they are ready.

---

## 4. Category System

Approved category structure:

| Category                           | Arabic Name       | Status                |
| ---------------------------------- | ----------------- | --------------------- |
| Little Stories — Baby & Kids Gifts | هدايا الصغار      | Active / First Launch |
| Care Stories                       | قصص العناية       | Coming Soon           |
| Graduation Stories                 | قصص التخرج        | Coming Soon           |
| Birthday Stories                   | قصص أعياد الميلاد | Coming Soon           |
| Travel Stories                     | قصص من السفر      | Coming Soon           |
| Special Stories                    | قصص خاصة          | Request-Based         |

Coming Soon categories should not be sold before products, pricing, photos, and operations are ready.

---

## 5. Official Website Role

The official website is the brand home.

Recommended domain:

```text
gift-story.com
```

The website should show:

* Brand story.
* Gift categories.
* Little Stories.
* Packaging experience.
* Previous stories.
* Coming Soon stories.
* Special Gift Story Request.
* Policies.
* Contact.
* Shop redirect.

The website should not be the main checkout system.

The website builds trust.
The commerce platform completes the order.

---

## 6. Main Website CTA

Main CTA:

```text
تسوّقي القصة الحالية
Shop The Current Story
```

This CTA should direct customers to the active commerce platform.

Possible commerce destination:

```text
shop.gift-story.com
```

or the approved Salla / Zid store link.

---

## 7. Commerce Direction

Preferred starting commerce platform:

```text
Salla
```

Zid may be considered later if it becomes more suitable operationally.

The commerce platform should handle:

* Active products.
* Prices.
* Inventory.
* Checkout.
* Payment.
* Orders.
* Invoices.
* Delivery settings.
* Customer purchase flow.

---

## 8. Pricing Direction

Gift Story does not use one fixed price for all boxes.

Pricing is based on:

* Landed product cost.
* Packaging cost.
* Preparation cost.
* Payment fees.
* Platform fees.
* Delivery app commission if applicable.
* Target profit.
* Brand perception.
* Channel-specific pricing.

Minimum target profit:

```text
50% above total cost
```

Formula:

```text
Minimum Net Revenue Needed = Total Cost × 1.5
```

The 299 SAR price remains a possible price tier, but it is not the fixed price for every box.

---

## 9. Packaging System

Gift Story packaging structure:

1. Branded outer gift bag.
2. Branded inner box.
3. Tissue paper.
4. Sticker.
5. Gift card.
6. Product arrangement inside the box.
7. Protective nylon or shipping carton when needed.

Approved sizes:

| Item           | Size            |
| -------------- | --------------- |
| Inner box      | 40 × 30 × 10 cm |
| Outer gift bag | 45 × 33 × 15 cm |

Protective nylon or shipping carton is logistics protection only.
It is not part of the premium unboxing identity.

---

## 10. Visual Identity

Approved visual direction:

* Off-white.
* Creamy beige.
* Nude.
* Muted / satin gold.
* Soft digital pink only when needed.
* Elegant castle.
* Stars and moon.
* Soft tissue paper.
* Premium gift card.
* Minimal luxury presentation.

Avoid:

* Dark navy as the main identity.
* Loud colors.
* Heavy glitter.
* Cartoon visuals.
* Crowded layouts.
* Discount banners.
* Cheap commercial design.

---

## 11. Print Rule

Physical packaging print should use:

```text
Single-color muted / satin gold print
```

This applies to:

* Outer gift bag.
* Inner box.
* Sticker.
* Gift card.
* Tissue pattern if printed.
* Packaging elements.

Digital assets may include soft pink details, but physical packaging should stay aligned with the one-color gold print rule.

---

## 12. WhatsApp Role

WhatsApp is not the main public sales channel.

Official WhatsApp number:

```text
+966576362810
```

WhatsApp may be used only when needed for:

* Selected support cases.
* Manual clarification.
* Complex special requests.
* Delivery coordination.
* Direct follow-up after form or email.

Standard orders should go through the commerce platform.

Special requests should go through the form.

---

## 13. Logistics Number

Internal logistics number:

```text
0576239046
```

This number is for internal coordination only.

It should not appear as the main customer-facing contact.

---

## 14. Recommended Project Structure

```text
giftstory/
  README.md

  docs/
    00_MASTER_SOURCE.md
    01_FOUNDATION_DECISIONS.md
    02_BRAND_POSITIONING.md
    03_CATEGORIES_AND_DROPS.md
    04_PACKAGING_SYSTEM.md
    05_PRICING_MODEL.md
    06_COMMERCE_CHANNELS.md
    07_WEBSITE_STRUCTURE.md
    08_ASSETS_INDEX.md
    09_OPERATIONS_AND_POLICIES.md
    10_LAUNCH_PLAN.md

  assets/
    ASSETS_README.md
    logo/
    castle/
    pattern/
    sticker/
    cards/
    packaging/
    product-photos/
    mockups/
    social/
    video/
    references/

  website/
    official-site/
      README.md
      pages-map.md
      copy/
        home.md
        our-story.md
        little-stories.md
        packaging.md
        previous-stories.md
        special-request.md
        policies.md
        contact.md
        shop.md
      wireframes/
        home-wireframe.md
        little-stories-wireframe.md
        packaging-wireframe.md
        special-request-wireframe.md
      references/

  commerce/
    salla-or-zid/
      README.md
      product-upload-rules.md
      channel-pricing-rules.md
      product-pricing-template.md

  forms/
    special-gift-story-request/
      form-questions.md
      form-logic.md
      customer-message.md

  inventory/
    INVENTORY_AND_COSTING_README.md
    GiftStory_Inventory_and_Costing_Template.xlsx

  archive/
    old-docs/
    old-html/
    original-pdfs/
    old-assets/
```

---

## 15. Documentation Source Order

## Active Source Rule

The `docs/` folder is the active source of truth for Gift Story.

Any files inside `archive/`, old uploaded references, or previous project versions are treated as historical reference only.

If any archived or older file conflicts with the active files inside `docs/`, the decision inside `docs/` must be followed.


Use the files in this order:

```text
00_MASTER_SOURCE.md
01_FOUNDATION_DECISIONS.md
02_BRAND_POSITIONING.md
03_CATEGORIES_AND_DROPS.md
04_PACKAGING_SYSTEM.md
05_PRICING_MODEL.md
06_COMMERCE_CHANNELS.md
07_WEBSITE_STRUCTURE.md
08_ASSETS_INDEX.md
09_OPERATIONS_AND_POLICIES.md
10_LAUNCH_PLAN.md
```

The master source is the top-level reference.

If old files conflict with the new source files, use the new files.

---

## 16. Asset Rule

Every important visual asset should have:

* Source file.
* Preview file.
* Clear English filename.
* Usage note.
* Status label.

Example:

```text
GS_Logo_Primary_Gold_Print.ai
GS_Logo_Primary_Gold_Print_Preview.png
```

No important asset should exist only as an unclear AI, PDF, or image file without a preview.

---

## 17. Product Photo Rule

Customer-facing product photos must not show:

* Price tags.
* Store labels.
* Discount labels.
* Ross.
* MSRP.
* Dollar signs.
* Purchase source.
* Messy backgrounds.
* Supplier screenshots.
* Personal information.

Customer-facing photos should be clean, soft, premium, and suitable for website or commerce use.

---

## 18. Inventory Rule

Every product should be recorded before use.

Every box should be costed before sale.

Every channel price should be calculated before publishing.

No product should go live without:

* Landed cost.
* Packaging cost.
* Total cost.
* Target profit.
* Final approved price.
* Clean photos.
* Correct inventory.
* Product description.
* Policy notes.

---

## 19. Special Request Rule

Special requests should be handled through:

```text
Special Gift Story Request
طلب قصة خاصة
```

A form submission is not an approved order.

Each request must be reviewed based on:

* Occasion.
* Recipient.
* Timeline.
* Budget.
* Product availability.
* Brand fit.
* Packaging fit.
* Operational capacity.
* Profit potential.

---

## 20. Policies Summary

Core policy direction:

* No return or exchange after the order leaves preparation, except before preparation/dispatch, clear fulfillment error, or any case required by regulation.
* Product details may vary depending on availability while maintaining the same level of presentation.
* Digital colors may differ from physical print.
* Special requests require extra time and review.
* Protective packaging is used when needed for delivery or shipping.
* Shipping labels should not be placed on branded Gift Story packaging.

---

## 21. Website Launch Scope

The first official website should include:

```text
Home
Our Story
Little Stories
Packaging
Previous Stories
Special Request
Policies
Contact
Shop Redirect
```

The first version should be clean, mobile-friendly, and premium.

Do not overbuild the website before the core journey works.

---

## 22. Launch Priorities

Launch priorities:

1. Final source files.
2. Organized assets.
3. Website copy and wireframes.
4. Clean product photos.
5. Inventory and costing sheet.
6. Commerce platform setup.
7. Little Stories product listings.
8. Packaging photos or mockups.
9. Special request form.
10. Soft launch content.

---

## 23. What to Delay

Delay:

* Full multi-category store.
* Heavy influencer campaigns.
* Large packaging production.
* Too many active drops.
* Public WhatsApp ordering.
* Showing prices on official website.
* Large paid ads.
* Advanced backend development.
* Complex loyalty or discount systems.
* Too many delivery app products.
* Corporate gifting pages.

---

## 24. Development Notes

The website may start as:

* Static website.
* Lightweight custom website.
* Cloudflare Pages deployment.
* GitHub repository.

The website should be:

* Arabic-first.
* RTL-friendly.
* Mobile-first.
* Fast.
* SEO-friendly.
* Easy to update.
* Connected to the commerce platform.

## Source Rules

* `docs/` contains the active project decisions.
* `assets/` contains the active visual assets used by the project.
* `archive/` is old reference only and must not override active source files.
* When there is any conflict, active source files are the final reference.

---

## 25. Final Rule

Gift Story should not be built as a random store.

It should be built as a premium gift experience with:

* Clear brand world.
* Organized website.
* Controlled commerce platform.
* Cost-based pricing.
* Clean product photography.
* Elegant packaging.
* Limited drops.
* Special request system.
* Strong operational discipline.

Gift Story’s long-term value is not in having many products.

It is in making every gift feel like a story.
