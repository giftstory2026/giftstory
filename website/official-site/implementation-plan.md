# implementation-plan.md

# Gift Story — Official Website Implementation Plan

## 1. Purpose

This file explains how to turn the approved Gift Story website copy and wireframes into a real official website.

The goal is to build a clean, premium, Arabic-first website that introduces Gift Story and sends customers to the active shop platform.

The website should not become a complicated store.

The website should remain the official brand home.

---

## 2. Website Role

The official website should do three things clearly:

```text id="fou9qk"
1. Explain Gift Story as a premium gifting brand.
2. Show the current active direction: Little Stories.
3. Send customers to the official shop or special request form.
```

The website should not handle:

```text id="8i4o75"
Checkout
Inventory
Payment
Order management
Product pricing by channel
Manual WhatsApp ordering as the main flow
```

These belong to Salla, Zid, or the approved commerce platform.

---

## 3. First Implementation Decision

Start with a simple official website.

Recommended first version:

```text id="s1ywmw"
Static HTML website
Arabic-first
RTL layout
Mobile-first
Hosted on Cloudflare Pages
Connected to GitHub
Shop button redirects to commerce platform
```

Do not build a full custom store in the first version.

---

## 4. Recommended First Website Scope

The first live website should include:

```text id="9hkgo7"
Home page
Our Story section
Little Stories section
Packaging section
Previous Stories preview
Special Request section
Policies summary
Contact section
Shop redirect CTA
Footer
```

This can be implemented as one strong landing page first.

Later, the same content can become separate pages.

---

## 5. Version 1 Structure

For the first release, use:

```text id="tudkj2"
index.html
```

Optional supporting files:

```text id="xggj5r"
assets/
styles.css
script.js
```

Recommended simple structure:

```text id="brx5qa"
giftstory/
  index.html
  README.md
  FINAL_PROJECT_STRUCTURE.md
  docs/
  website/
  commerce/
  forms/
  inventory/
  assets/
  archive/
```

For a cleaner web build later:

```text id="gx0blc"
website/
  official-site/
    index.html
    styles.css
    script.js
    assets/
```

But for Cloudflare Pages root deployment, `index.html` in the repository root is the easiest first step.

---

## 6. Content Source Mapping

Use the approved files as content sources.

| Website Section  | Source File                                      |
| ---------------- | ------------------------------------------------ |
| Hero             | `website/official-site/copy/home.md`             |
| Brand promise    | `website/official-site/copy/home.md`             |
| Our Story        | `website/official-site/copy/our-story.md`        |
| Little Stories   | `website/official-site/copy/little-stories.md`   |
| Packaging        | `website/official-site/copy/packaging.md`        |
| Previous Stories | `website/official-site/copy/previous-stories.md` |
| Special Request  | `website/official-site/copy/special-request.md`  |
| Policies         | `website/official-site/copy/policies.md`         |
| Contact          | `website/official-site/copy/contact.md`          |
| Shop Redirect    | `website/official-site/copy/shop.md`             |

---

## 7. Layout Source Mapping

Use the wireframes as layout references.

| Page / Section         | Wireframe Source               |
| ---------------------- | ------------------------------ |
| Homepage layout        | `home-wireframe.md`            |
| Little Stories layout  | `little-stories-wireframe.md`  |
| Packaging layout       | `packaging-wireframe.md`       |
| Special Request layout | `special-request-wireframe.md` |

For Version 1, do not implement every wireframe as a separate page.

Use the most important parts inside one elegant landing page.

---

## 8. First Homepage Section Order

Recommended section order for `index.html`:

```text id="fpr1f5"
1. Header
2. Hero
3. Brand Promise
4. Current Story / Little Stories
5. Why Gift Story
6. Packaging Experience
7. Previous Stories Preview
8. Coming Soon Stories
9. Special Request
10. Policies Summary
11. Contact
12. Footer
```

This order supports the customer journey:

```text id="ai2hr4"
Brand feeling → Current story → Trust → Packaging → Shop or Special Request
```

---

## 9. Header Requirements

Header should include:

```text id="w2fb0f"
Gift Story logo text
الرئيسية
هدايا الصغار
تجربة التغليف
طلب قصة خاصة
السياسات
تواصل
تسوّقي القصة الحالية
```

The main CTA should be:

```text id="d6wg1f"
تسوّقي القصة الحالية
```

Link target:

```text id="il8lfw"
shop.gift-story.com
```

or the approved Salla / Zid shop link once ready.

Do not use WhatsApp as the main header CTA.

---

## 10. Hero Section

Hero should communicate the brand quickly.

Recommended content:

```text id="v70fqa"
Gift Story
WHERE EVERY GIFT TELLS A STORY

هدايا منسقة بعناية، حيث كل هدية تحكي قصة.

تسوّقي القصة الحالية
اكتشفي طلب القصة الخاصة
```

Hero visual should show:

```text id="dtgudb"
Gift Story packaging
Soft neutral background
Outer gift bag
Inner box
Gift card
Muted gold details
```

Avoid using raw product inventory as the hero image.

---

## 11. Little Stories Section

Purpose:

Show the first active launch category.

Section title:

```text id="n2o8qt"
هدايا الصغار
```

Subtitle:

```text id="3rhy93"
قصص ناعمة للمولود والطفل، منسقة بعناية لتصل كهدية كاملة.
```

CTA:

```text id="b65571"
تسوّقي القصة الحالية
```

Do not show many categories as active products.

Little Stories should remain the main active direction.

---

## 12. Packaging Section

Purpose:

Make packaging part of the perceived value.

Must mention:

```text id="gpmq93"
Outer gift bag: 45 × 33 × 15 cm
Inner gift box: 40 × 30 × 10 cm
Gift card
Tissue paper
Sticker
Protective packaging when needed
```

Important clarification:

```text id="d4jqhc"
Protective nylon or shipping carton is logistics protection only, not part of the premium unboxing identity.
```

Include color/print note:

```text id="l69xl4"
قد تختلف بعض التفاصيل اللونية بين العروض الرقمية والتغليف المطبوع، حيث تعتمد Gift Story في التغليف الفعلي على طباعة فاخرة بلون ذهبي موحد حسب مواصفات الإنتاج.
```

---

## 13. Previous Stories Section

Purpose:

Show inspiration and premium history without making old products look available.

Use wording like:

```text id="aoxrdt"
قصص سابقة من Gift Story، تُعرض كإلهام فقط وقد لا تتكرر بنفس التفاصيل.
```

Avoid:

```text id="w0mti4"
Adding sold-out products as available
Showing exact prices
Promising the same box can be recreated
```

CTA:

```text id="j0aei3"
اطلبي قصة خاصة مستوحاة من قصة سابقة
```

---

## 14. Coming Soon Section

Show categories as coming soon only:

```text id="47kp40"
قصص العناية
قصص التخرج
قصص أعياد الميلاد
قصص من السفر
```

Do not add product prices.

Do not make them purchasable before ready.

---

## 15. Special Request Section

Purpose:

Offer custom requests in a controlled way.

CTA:

```text id="id590l"
طلب قصة خاصة
```

The CTA should lead to:

```text id="8b7a42"
Special request form
```

or a page section with the form.

Important wording:

```text id="q0xdil"
إرسال الطلب لا يعني تأكيده مباشرة. تتم مراجعة الطلب أولًا حسب التوفر وإمكانية التنفيذ.
```

---

## 16. Policies Summary Section

Include only a short summary on the homepage.

Must include:

```text id="hkucm9"
لا يمكن الاسترجاع أو الاستبدال بعد خروج الطلب من مقر التجهيز، إلا في حال وجود خطأ واضح من Gift Story أو حسب ما تقتضيه الأنظمة.
```

Also mention:

```text id="8biz17"
الطلبات الخاصة تحتاج مراجعة قبل القبول.
قد تختلف بعض تفاصيل المحتوى حسب التوفر.
تستخدم Gift Story تغليف حماية خارجي عند الحاجة للتوصيل أو الشحن.
```

Detailed policies can live in a separate section or page later.

---

## 17. Contact Section

Contact should be professional and not WhatsApp-first.

Include:

```text id="1qarsy"
Email contact placeholder
Shop link
Special request link
Instagram placeholder
```

Official WhatsApp can appear as secondary support only:

```text id="2j3flv"
+966576362810
```

Do not show the logistics number publicly.

Internal logistics number:

```text id="w8px4a"
0576239046
```

This should remain internal.

---

## 18. Visual Direction

Website visual style:

```text id="jc2kzz"
Off-white background
Creamy beige sections
Nude accents
Muted / satin gold details
Dark warm text
Soft borders
Large spacing
Minimal layout
```

Avoid:

```text id="9af9o0"
Dark navy as main identity
Bright colors
Crowded product grids
Discount banners
Cartoon graphics
Heavy shadows
Harsh black sections
Cheap commercial style
```

---

## 19. Image Requirements for Version 1

Minimum images needed:

```text id="dn3t7j"
Hero packaging image
Little Stories product or box image
Packaging detail image
Gift card detail image
Previous Stories placeholder image
Special Request soft visual
```

If real images are not ready, use clean placeholders or approved mockups.

Do not use:

```text id="u7s1uc"
Raw inventory photos
Images with price tags
Images with Ross
Images with MSRP
Dollar price tags
Supplier screenshots
Messy backgrounds
Personal customer information
```

---

## 20. Technical Requirements

The first website should be:

```text id="dpae84"
Arabic-first
RTL
Responsive
Mobile-first
Fast loading
SEO-friendly
Easy to edit in VS Code
Deployable on Cloudflare Pages
```

HTML requirements:

```text id="fxpdrx"
Use semantic sections
Use clear IDs for navigation
Keep code readable
Avoid unnecessary libraries
Avoid heavy animations
Keep CSS simple
Use accessible buttons and links
```

---

## 21. SEO Basics

Minimum SEO metadata:

```text id="dh4me7"
Page title
Meta description
Arabic language
Open Graph title
Open Graph description
Open Graph image
Canonical URL later
```

Suggested page title:

```text id="dku1no"
Gift Story | هدايا فاخرة تحكي قصة
```

Suggested meta description:

```text id="abxv87"
Gift Story براند سعودي للهدايا المنسقة بعناية، يبدأ بهدايا الصغار وتجربة تغليف فاخرة حيث كل هدية تحكي قصة.
```

---

## 22. CTA Link Rules

Use these CTA targets:

| CTA                  | Target                            |
| -------------------- | --------------------------------- |
| تسوّقي القصة الحالية | Commerce platform / shop redirect |
| طلب قصة خاصة         | Special request form or section   |
| استكشفي هدايا الصغار | Little Stories section            |
| اقرئي السياسات       | Policies section                  |
| تواصلي معنا          | Contact section                   |

Do not use empty buttons.

If the real shop is not ready, point the CTA to a temporary shop-ready message section.

---

## 23. Version 1 Build Steps

Build in this order:

```text id="d8bjei"
1. Create or clean index.html
2. Add RTL Arabic HTML structure
3. Add header and navigation
4. Add hero section
5. Add Little Stories section
6. Add packaging section
7. Add previous stories and coming soon sections
8. Add special request section
9. Add policies and contact sections
10. Add footer
11. Add CSS styling
12. Add responsive mobile styling
13. Add real links or placeholders
14. Test buttons
15. Test mobile view
16. Prepare for GitHub upload
17. Connect to Cloudflare Pages
```

---

## 24. What Not to Build in Version 1

Do not build:

```text id="4n2l7n"
Custom checkout
Cart system
Payment system
Inventory backend
User accounts
Admin dashboard
Complex product filtering
Full multi-page website if not needed
Large animation system
Public WhatsApp order flow
```

These can be handled later or by the commerce platform.

---

## 25. Version 1 Success Criteria

Version 1 is successful if:

```text id="v4ga5c"
The brand feels premium
The website is clear on mobile
The current story CTA is visible
The customer understands Little Stories
The packaging value is clear
Special request path is clear
Policies are not hidden
There are no random prices on the website
There are no raw product photos
Shop link works
The website can be edited easily
```

---

## 26. Pre-Launch Website Checklist

Before publishing:

```text id="rx3mbx"
Logo/name is correct
Slogan is correct
Arabic copy is polished
No fixed wrong prices appear
No old WhatsApp-first flow remains
No logistics number appears publicly
Shop CTA works
Special request CTA works
Policies are visible
Packaging sizes are correct
Print/color note is included
Images are clean
Mobile view is clean
No broken links
No placeholder text remains
Footer is complete
```

---

## 27. Final Implementation Rule

The first Gift Story website should be simple, premium, and useful.

It should not try to do everything.

The correct first goal is:

```text id="1ztpnu"
Build trust, explain the story, show the gift experience, and direct customers to the right purchase or request path.
```

The website should feel like the entrance to Gift Story, while the commerce platform handles the transaction.
