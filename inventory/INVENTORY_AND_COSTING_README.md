# INVENTORY_AND_COSTING_README.md

# Gift Story — Inventory and Costing README

## 1. Purpose

This folder is used to track Gift Story products, costs, box combinations, pricing, and stock movement.

The goal is to make sure every gift story is priced correctly before being sold.

No product should be added to a Gift Story box without knowing its real cost.

No box should be launched without a costing sheet.

---

## 2. Core Rule

Gift Story pricing must be based on real cost.

Each box price should be calculated using:

* Landed product cost.
* Packaging cost.
* Preparation cost if applicable.
* Payment fee.
* Platform fee.
* Delivery app commission if applicable.
* Target profit.
* Final channel price.

The minimum target profit is:

```text
50% above total cost
```

Formula:

```text
Minimum Net Revenue Needed = Total Cost × 1.5
```

---

## 3. Product Cost Rule

Each product should be recorded using landed cost.

Landed cost means the real cost of the product after considering shipping, customs, travel, or sourcing cost if already included.

Do not count the same shipping or customs cost twice.

Example:

```text
Correct:
Product landed cost = full real product cost

Wrong:
Product cost + shipping/customs again when already included
```

---

## 4. Packaging Cost Rule

Current working packaging cost assumption:

```text
18 SAR per full gift presentation
```

This includes the basic packaging assumption for:

* Inner box.
* Outer gift bag.
* Tissue paper.
* Sticker.
* Gift card.
* Basic finishing material.

This number must be updated if supplier prices change.

---

## 5. Product Inventory Fields

Each product should have these fields:

```text
Product ID
Product Name
Category
Drop
Brand
Product Type
Audience
Age / Size
Color
Source
Landed Cost
Quantity Purchased
Quantity Available
Condition
Storage Location
Raw Image Filename
Client Display Image Filename
Suggested Box Use
Customer-Facing Description
Internal Notes
Status
Date Added
Date Used
```

---

## 6. Product Status Labels

Use clear status labels:

```text
Available
Reserved
Used
Needs Photo
Needs Cleaning
Needs Review
Archived
```

Definitions:

```text
Available = Ready to use in a box
Reserved = Selected for a box but not sold yet
Used = Already sold or included in a completed order
Needs Photo = Needs clean customer-facing image
Needs Cleaning = Needs preparation before use
Needs Review = Not approved yet
Archived = Old or unsuitable reference
```

---

## 7. Product Image Rule

Every product should have two image types:

### 1. Raw Image

Used internally for reference.

May include:

* Tags.
* Source labels.
* Size labels.
* Cost reference.
* Original condition.

### 2. Client Display Image

Used publicly.

Must not show:

* Price tags.
* Store tags.
* Ross.
* MSRP.
* Dollar signs.
* Purchase source.
* Discount labels.
* Messy background.

---

## 8. Product Naming Rule

Use clear English filenames for product images.

Example:

```text
GS_LittleStories_BabySet_Pink_6M_Raw_v1.jpg
GS_LittleStories_BabySet_Pink_6M_ClientDisplay_v1.png
```

Avoid:

```text
IMG_1234.jpg
baby thing.png
new photo final.png
```

---

## 9. Box Costing Fields

Each gift box should have its own costing sheet.

Required fields:

```text
Box ID
Box Name
Category
Drop Name
Product 1 Name
Product 1 Cost
Product 2 Name
Product 2 Cost
Product 3 Name
Product 3 Cost
Total Product Cost
Packaging Cost
Preparation Cost
Total Cost
Target Profit
Minimum Net Revenue Needed
Payment Fee Assumption
Platform Fee Assumption
Delivery App Commission Assumption
Minimum Direct Price
Suggested Direct Price
Minimum App Price
Suggested App Price
Final Approved Price
Channel
Quantity Available
Status
Approval Date
Notes
```

---

## 10. Total Cost Formula

Use this formula:

```text
Total Cost = Total Product Cost + Packaging Cost + Preparation Cost
```

If there are extra direct costs, include them.

Examples:

* Special ribbon.
* Printed card.
* Custom sourcing.
* Additional protection.
* Special delivery material.

---

## 11. Profit Formula

Gift Story minimum profit target:

```text
Target Profit = Total Cost × 50%
```

Minimum net revenue needed:

```text
Minimum Net Revenue Needed = Total Cost × 1.5
```

Example:

```text
Total Cost = 180 SAR
Target Profit = 90 SAR
Minimum Net Revenue Needed = 270 SAR
```

---

## 12. Direct Platform Price Formula

For Salla, Zid, or any direct commerce platform:

Working assumption:

```text
Payment Fee = 7% + 1 SAR
```

Formula:

```text
Minimum Direct Selling Price = (Total Cost × 1.5 + Fixed Payment Fee) ÷ (1 - Payment Fee Percentage)
```

Using the current assumption:

```text
Minimum Direct Selling Price = (Total Cost × 1.5 + 1) ÷ 0.93
```

---

## 13. Delivery App Price Formula

For HungerStation, ToYou, The Chefz, or similar apps:

Working assumption:

```text
Delivery App Commission = 22.5%
```

Formula:

```text
Minimum App Selling Price = (Total Cost × 1.5) ÷ 0.775
```

Important:

If the platform deducts commission from the selling price, use division.

Do not simply add 22.5% on top of the direct price.

---

## 14. Price Tier Rule

After calculating the minimum price, choose a clean premium price tier.

Recommended tiers:

```text
249
299
349
399
449
499
549
599
649
699
```

Final price should be based on:

* Minimum financial price.
* Brand perception.
* Product value.
* Packaging quality.
* Sales channel.
* Customer expectation.

---

## 15. 299 SAR Rule

299 SAR is allowed only when the real cost supports it.

It is not the fixed price for all boxes.

Before approving 299 SAR, check:

* Total cost.
* Packaging cost.
* Payment fee.
* Platform fee.
* Target profit.
* Visual value.
* Customer perception.

A box should not be sold at 299 SAR if it does not protect the target profit.

---

## 16. Box Status Labels

Use these status labels:

```text
Draft
Costed
Ready for Photo
Ready to Sell
Live
Sold Out
Paused
Archived
```

Definitions:

```text
Draft = Idea not fully costed
Costed = Cost and minimum price calculated
Ready for Photo = Products selected and ready for image
Ready to Sell = Approved and ready for platform
Live = Active on sales channel
Sold Out = No longer available
Paused = Temporarily unavailable
Archived = Old reference only
```

---

## 17. Channel Price Separation

Each channel may have a different price.

Use separate final prices for:

```text
Salla / Zid
HungerStation
ToYou
The Chefz
Special Request
```

Reason:

Each channel may have different:

* Commission.
* Payment fee.
* Delivery rules.
* Customer expectations.
* Operational cost.

The official Gift Story website should not show detailed product prices by default.

---

## 18. Special Request Costing

Special requests should be costed manually.

Required fields:

```text
Request ID
Customer Name
Occasion
Recipient Details
Requested Style
Budget Range
Products Needed
Estimated Product Cost
Estimated Packaging Cost
Estimated Preparation Cost
Estimated Sourcing Cost
Total Estimated Cost
Target Profit
Quoted Price
Payment Status
Preparation Status
Delivery Date
Notes
```

Special request price should be confirmed before sourcing or preparation begins.

---

## 19. Inventory Movement Rule

Every product movement should be recorded.

Track:

```text
Date
Product ID
Action
Quantity
Box ID
Order ID
Notes
```

Actions:

```text
Added
Reserved
Used
Returned to Stock
Damaged
Archived
```

This prevents losing products or selling the same item twice.

---

## 20. Stock Control Rule

Gift Story should avoid launching products that are not physically available.

Before listing a box:

* Confirm all products are available.
* Reserve products for that box.
* Confirm packaging is available.
* Confirm photos are ready.
* Confirm price is approved.
* Confirm quantity is accurate.

---

## 21. Customer-Facing Product Description Rule

Customer-facing descriptions should not mention:

* Source store.
* Purchase price.
* Discount.
* Outlet.
* Internal cost.
* Ross.
* MSRP.
* Dollar signs.
* Supplier details.

Customer-facing descriptions should focus on:

* Gift feeling.
* Color.
* Style.
* Occasion.
* Softness.
* Presentation.
* Category fit.
* Premium appearance.

---

## 22. Internal Notes Rule

Internal notes may include:

* Purchase source.
* Cost reason.
* Condition details.
* Size confirmation.
* Missing information.
* Product risk.
* Suggested pairing.
* Platform notes.

Internal notes should never be copied into public product descriptions.

---

## 23. Recommended Files in This Folder

Recommended inventory folder structure:

```text
inventory/
  INVENTORY_AND_COSTING_README.md
  product-database-template.xlsx
  box-costing-template.xlsx
  special-request-costing-template.xlsx
  inventory-movement-log.xlsx
```

If using Google Sheets instead of Excel, keep the same structure and sheet names.

---

## 24. Recommended Sheet Names

For the main inventory workbook:

```text
Products
Boxes
Special Requests
Inventory Movement
Pricing Rules
Status Lists
```

---

## 25. Product Approval Checklist

Before a product becomes available:

```text
Product cost recorded
Product quantity recorded
Product category selected
Product condition checked
Product size confirmed
Raw image saved
Client display image created
Source details kept internal
Product status updated
Suggested box use added
```

---

## 26. Box Approval Checklist

Before a box goes live:

```text
All product costs recorded
Packaging cost added
Total cost calculated
Target profit calculated
Payment/platform fee included
Minimum price calculated
Final price approved
Products reserved
Photos ready
Description ready
Policy note ready
Platform listing ready
Quality checklist ready
```

---

## 27. Final Rule

Inventory is not only stock storage.

Inventory is the financial control system of Gift Story.

Every product should be traceable.
Every box should be costed.
Every price should be justified.
Every channel should protect profit.

Gift Story should never sell a gift story without knowing its real cost and expected profit.
