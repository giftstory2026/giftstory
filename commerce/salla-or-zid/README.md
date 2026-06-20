# README.md

# Gift Story — Salla / Zid Commerce Setup

## 1. Purpose

This folder contains the commerce setup rules for Gift Story.

It defines how products should be priced, prepared, uploaded, reviewed, and managed inside Salla, Zid, or any approved commerce platform.

The goal is to keep Gift Story’s sales channel organized, premium, and financially controlled.

---

## 2. Commerce Platform Role

Salla or Zid should handle the operational selling layer.

The commerce platform is responsible for:

* Active product listings.
* Product prices.
* Inventory.
* Checkout.
* Payment.
* Orders.
* Invoices.
* Delivery settings.
* Customer purchase details.
* Order notifications.

The official Gift Story website should remain the brand home.

The website builds trust.
The commerce platform completes the sale.

---

## 3. Official Website vs Commerce Platform

## Official Website

Used for:

* Brand story.
* Packaging experience.
* Category introduction.
* Previous stories.
* Special Gift Story Request.
* Policies.
* Contact.
* Shop redirect.

The official website should not show detailed active product prices by default.

---

## Commerce Platform

Used for:

* Available products.
* Product prices.
* Stock.
* Checkout.
* Payment.
* Customer order details.
* Delivery options.

The commerce platform is where the customer completes the purchase.

---

## 4. Preferred Starting Platform

Preferred starting direction:

```text id="mp4x1a"
Salla
```

This may be changed later if Zid becomes more suitable.

Before final selection, compare:

```text id="q99swp"
Monthly cost
Payment fees
Checkout experience
Domain or subdomain support
Product options
Inventory management
Delivery integrations
Arabic interface
Customer notifications
Design flexibility
Ease of operation
```

---

## 5. Main Shop Link

Preferred commerce setup:

```text id="fy5biu"
shop.gift-story.com
```

Alternative if technically supported:

```text id="xlcjdo"
gift-story.com/orders
```

Important:

Do not force `/orders` if it creates platform or routing issues.

The official website can use:

```text id="l3fzpl"
gift-story.com/shop
```

as a redirect page to the active platform.

---

## 6. Active Launch Category

The first active commerce category is:

```text id="3etgz2"
هدايا الصغار
Little Stories — Baby & Kids Gifts
```

Other categories should not be listed for sale until ready.

Coming Soon categories should remain on the official website until products are ready.

---

## 7. Files in This Folder

This folder should contain:

```text id="ght2sz"
commerce/
  salla-or-zid/
    README.md
    product-upload-rules.md
    channel-pricing-rules.md
    product-pricing-template.md
```

---

## 8. File Roles

## product-upload-rules.md

Defines how to upload products to Salla / Zid.

Covers:

* Product names.
* Categories.
* Photos.
* Descriptions.
* Inventory.
* Gift card field.
* Packaging notes.
* Policy notes.
* What not to upload.

Use this file before creating any public product listing.

---

## channel-pricing-rules.md

Defines how pricing differs by channel.

Covers:

* Direct platform pricing.
* Delivery app pricing.
* Special request pricing.
* Payment fee assumptions.
* Delivery app commission assumptions.
* Price tier rules.
* 299 SAR rule.
* Profit protection.

Use this file before approving prices across different sales channels.

---

## product-pricing-template.md

A practical template for each box or gift story.

Use it to calculate:

* Product cost.
* Packaging cost.
* Preparation cost.
* Total cost.
* Minimum net revenue needed.
* Direct platform price.
* Delivery app price.
* Expected profit.
* Final approved price.

No product should go live before this template is completed.

---

## 9. Pricing Principle

Gift Story does not use one fixed price for all products or channels.

Each price must be based on:

```text id="plp62s"
Actual cost
Packaging cost
Preparation cost
Payment fee
Platform fee
Delivery app commission if applicable
Target profit
Brand perception
Channel positioning
```

Minimum target profit:

```text id="vshgdq"
50% above total cost
```

Formula:

```text id="d2o7t5"
Minimum Net Revenue Needed = Total Cost × 1.5
```

---

## 10. 299 SAR Rule

299 SAR is allowed as a price tier.

It is not the fixed price for all boxes.

Before pricing a box at 299 SAR, confirm:

```text id="yceyvp"
Total cost supports the target profit
Packaging cost is included
Payment fees are included
Photos support the price
Visual value feels premium
Channel fees do not weaken the margin
```

If the cost does not support 299 SAR, move to a higher tier such as:

```text id="08z0xl"
349
399
449
499
```

---

## 11. Product Must Be Ready Before Upload

A product can be uploaded only when it is:

```text id="gjjogz"
Physically available
Costed
Priced
Photographed
Described
Approved
Inventory-checked
Packaging-ready
Operationally ready
```

Do not upload:

```text id="u4whfg"
Draft products
Uncosted products
Weak-margin products
Raw inventory photos
Products with visible price tags
Products with store labels
Unavailable products
Products that do not fit Gift Story
```

---

## 12. Product Image Rule

Product images inside Salla / Zid must be customer-facing.

Images must not show:

```text id="2pfrp9"
Price tags
Store labels
Discount labels
Ross
MSRP
Dollar signs
Purchase source
Messy backgrounds
Supplier screenshots
Personal information
```

Images should show:

```text id="vss09m"
Clean product presentation
Gift Story packaging
Soft background
Premium arrangement
Clear product view
Gift-ready feeling
```

---

## 13. Product Description Rule

Descriptions should be:

* Arabic-first.
* Clear.
* Warm.
* Premium.
* Not too long.
* Focused on gifting experience.
* Free from internal cost or sourcing details.

Descriptions should mention:

```text id="3pj5l9"
Gift occasion
Gift experience
Packaging
Gift card
Limited availability if relevant
Product variation note if relevant
Preparation note
Policy note
```

Descriptions should not mention:

```text id="axw8pu"
Purchase source
Outlet
Discount
Ross
MSRP
Dollar price
Internal cost
Supplier details
```

---

## 14. Inventory Rule

Inventory must be accurate.

For unique boxes:

```text id="c8c7br"
Quantity = 1
```

After sale:

```text id="ltz4fu"
Mark as Sold Out
```

Do not oversell unique boxes.

Do not reuse the same products in more than one box.

---

## 15. Gift Card Field

If the platform allows custom fields, add:

```text id="u51mmk"
رسالة كرت الإهداء
```

Suggested field note:

```text id="ro4fo2"
اكتبي رسالة الإهداء هنا، وسيتم تجهيزها حسب النص المعتمد.
```

If the message can be confirmed later:

```text id="uj21ke"
يمكن إضافة رسالة كرت الإهداء الآن أو تأكيدها لاحقًا قبل التجهيز.
```

---

## 16. Required Product Notes

Each product page should include these notes when relevant.

## Packaging Note

```text id="em1oe7"
تصل الهدية بتغليف Gift Story، مع ترتيب داخلي أنيق وكرت إهداء، وحماية خارجية عند الحاجة للتوصيل أو الشحن.
```

## Limited Availability Note

```text id="e0le8b"
تتوفر هذه القصة بكميات محدودة، وقد لا تتكرر بنفس التفاصيل بعد نفاد القطع.
```

## Product Variation Note

```text id="lpjqgg"
قد تختلف بعض تفاصيل المحتوى حسب توفر القطع، مع الحفاظ على نفس مستوى التنسيق والفخامة في كل قصة.
```

## Return and Exchange Note

```text id="vr1e9n"
نظرًا لطبيعة الهدايا المجهزة ومنتجات الأطفال والتغليف المخصص، لا يمكن استرجاع أو استبدال الطلب بعد خروجه من مقر التجهيز، حفاظًا على جودة المنتجات وسلامة تجربة الإهداء.
```

---

## 17. Product Upload Workflow

Before uploading a product:

```text id="ydtk1w"
1. Select product / box concept
2. Confirm products are available
3. Record landed costs
4. Add packaging cost
5. Add preparation cost if needed
6. Calculate total cost
7. Calculate minimum price
8. Select final price tier
9. Prepare customer-facing photos
10. Prepare product description
11. Confirm inventory quantity
12. Add gift card field if available
13. Add policy and packaging notes
14. Review product page on mobile
15. Publish only after approval
```

---

## 18. Product Status Workflow

Use these statuses internally:

```text id="1fxsm2"
Draft
Costed
Ready for Photo
Ready to Sell
Live
Sold Out
Paused
Archived
```

Only products marked as:

```text id="kc7ffb"
Ready to Sell
```

should be uploaded publicly.

---

## 19. Channel Pricing Workflow

For each channel, calculate separately:

```text id="unwr5z"
Salla / Zid Price
HungerStation Price
ToYou Price
The Chefz Price
Special Request Quote
```

Each channel may have a different price because of:

```text id="wdawym"
Payment fees
Platform commissions
Delivery app commissions
Operational cost
Channel positioning
Customer expectations
```

The official website should not display conflicting prices.

---

## 20. Delivery App Rule

Do not list every product on delivery apps.

Delivery apps should only include:

```text id="ckff56"
Ready-to-go gifts
Simple products
Fast-preparation items
Products with strong margin
Products that can survive delivery handling
Products with clear photos
```

Avoid listing:

```text id="aeax7t"
Complex custom requests
Products needing long explanation
Fragile one-off boxes
Weak-margin products
Products that need long preparation
```

---

## 21. Special Request Rule

Special requests should not be uploaded as normal ready products.

They should be handled through:

```text id="ibk2xj"
Special Gift Story Request form
Manual review
Custom quote
Payment after approval
Preparation after confirmation
```

Do not create generic “custom box” product listings unless the process is operationally ready.

---

## 22. Product Review Before Launch

After uploading a product, review it as a customer.

Check:

```text id="uf6fsz"
Does the product feel premium?
Is the main photo strong?
Is the title clear?
Is the description readable?
Is the price correct?
Is the quantity correct?
Is the gift card field clear?
Are policy notes visible?
Is checkout working?
Does the page look good on mobile?
```

If it feels low-value, rushed, or unclear, revise before launch.

---

## 23. Sold Out Rule

When a product sells out:

```text id="p5n1ab"
Mark as Sold Out
```

If it will not return, move its visual record to:

```text id="ygq2pc"
Previous Stories
```

on the official website.

Do not leave sold-out one-of-one products looking available.

---

## 24. Commerce Launch Checklist

Before opening the shop publicly, confirm:

```text id="19wjix"
Store name is correct
Brand visuals are uploaded
Active category is created
Products are uploaded
Prices are approved
Inventory is accurate
Payment works
Delivery settings work
Gift card message field works if available
Policy notes are visible
Order confirmation works
Mobile checkout is tested
Shop link works from official website
Test order completed successfully
```

---

## 25. Final Rule

The commerce platform should protect Gift Story from random selling.

Every product must be:

```text id="fd4y4u"
Costed
Priced
Photographed
Described
Available
Policy-aligned
Brand-appropriate
Ready to fulfill
```

Gift Story should never publish a product just because it exists in inventory.

It should only publish a product when it is ready to become a complete gift story.
