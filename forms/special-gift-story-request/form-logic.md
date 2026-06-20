# form-logic.md

# Gift Story — Special Gift Story Request Form Logic

## 1. Purpose

This file defines the internal review logic for Special Gift Story Request submissions.

Its purpose is to help Gift Story decide what happens after a customer submits a custom request form.

A form submission is not an approved order.

Every request must be reviewed before acceptance, pricing, payment, preparation, or sourcing.

---

## 2. Core Rule

Every special request has four possible outcomes:

```text
Accepted for Quote
Needs Clarification
Not Suitable / Declined
Waitlist / Future Review
```

Gift Story should not accept a custom request automatically.

The request should be reviewed based on:

* Occasion.
* Recipient.
* Timeline.
* Budget.
* Product availability.
* Brand fit.
* Packaging fit.
* Operational capacity.
* Delivery feasibility.
* Profit potential.

---

## 3. Review Flow Overview

Recommended internal flow:

```text
1. Receive form submission
2. Check required fields
3. Review occasion and recipient
4. Review timeline
5. Review budget
6. Review brand fit
7. Review product availability
8. Review packaging feasibility
9. Estimate cost and price range
10. Decide outcome
11. Reply to customer
12. If accepted, prepare quote
13. If approved by customer, collect payment
14. Prepare order
```

---

## 4. Request Status Labels

Use the following internal status labels:

```text
New Request
Under Review
Needs Clarification
Accepted for Quote
Quote Sent
Awaiting Customer Approval
Awaiting Payment
Confirmed
In Preparation
Ready for Delivery
Completed
Declined
Paused
Archived
```

---

## 5. Status Definitions

### New Request

The form has been submitted but not reviewed yet.

### Under Review

Gift Story is checking the request details, availability, timing, and feasibility.

### Needs Clarification

The request is missing important information or needs customer confirmation.

### Accepted for Quote

The request is suitable enough to prepare a concept or price range.

### Quote Sent

Gift Story has sent the proposed direction, price, and timeline to the customer.

### Awaiting Customer Approval

The customer has not yet accepted or declined the quote.

### Awaiting Payment

The customer approved the quote, but payment has not been completed.

### Confirmed

Payment and details are confirmed.

### In Preparation

Gift Story has started preparing the custom order.

### Ready for Delivery

The order is ready to leave preparation.

### Completed

The order has been delivered or closed.

### Declined

The request cannot be accepted.

### Paused

The request is held for later review due to capacity or availability.

### Archived

The request is closed and kept only as reference.

---

## 6. First Review Checklist

When a new request arrives, check:

```text
Customer name is provided
Email is provided
Phone number is provided
City is provided
Occasion is clear
Recipient type is clear
Timeline is provided
Budget range is provided
Customer accepted review terms
Customer accepted contact terms
```

If any critical information is missing, mark the request as:

```text
Needs Clarification
```

---

## 7. Critical Missing Information

A request should not move to quotation if any of the following is missing:

* Occasion.
* Recipient type.
* Delivery city.
* Desired delivery date.
* Budget range.
* Contact information.
* Customer consent to be contacted.
* Confirmation that request requires review.

If missing, ask for clarification before continuing.

---

## 8. Brand Fit Review

Before accepting a request, ask:

```text
Does this request fit Gift Story's premium gifting style?
Can it be presented in a soft, elegant way?
Does it match the brand's visual direction?
Can it be arranged as a complete gift story?
Will the final result feel curated, not random?
```

Acceptable fit:

* Soft baby/kids gifts.
* Elegant care gifts.
* Refined graduation gifts.
* Calm birthday gifts.
* Travel-inspired gift stories.
* Thoughtful personal gifts.
* Premium, simple, curated ideas.

Poor fit:

* Loud party supplies.
* Cheap bundle requests.
* Cartoon-heavy themes.
* Strong discount-driven requests.
* Requests that require messy packaging.
* Products that do not fit Gift Story’s quality.
* Items that could damage the brand perception.

---

## 9. Occasion Review

Classify the occasion:

```text
Baby / Kids
Care
Graduation
Birthday
Travel
Thank You
Family Occasion
Other
```

Then decide if it belongs to:

```text
Active Category
Coming Soon Category
Special Request Only
Not Suitable
```

Current priority:

```text
Little Stories — Baby & Kids Gifts
هدايا الصغار
```

Requests outside Baby/Kids may still be reviewed, but they should not distract from the first launch focus.

---

## 10. Timeline Review

Check the requested delivery date.

### Green Timeline

Good to review and possibly accept.

```text
7+ days available
Products already in stock
Packaging available
Delivery city is manageable
```

### Yellow Timeline

Needs caution.

```text
3-6 days available
Some products need sourcing
Customer expects specific details
Delivery is outside Jeddah
```

### Red Timeline

Usually not suitable for special request.

```text
Same-day request
Next-day request
Complex sourcing needed
Unclear delivery address
Major customization needed
Packaging not available
```

Important:

Urgent custom requests should not be accepted unless execution is clearly possible.

---

## 11. Budget Review

Budget should be treated as a guide, not a promise.

Review budget against:

* Product cost.
* Packaging cost.
* Preparation effort.
* Payment fees.
* Delivery or shipping.
* Profit target.
* Customer expectations.
* Visual value.

If the budget is too low for the requested idea, mark as:

```text
Needs Clarification
```

or

```text
Declined
```

depending on the situation.

---

## 12. Budget Range Logic

### 250 - 350 SAR

Suitable for:

* Simple Little Stories request.
* Small curated gift.
* Minimal sourcing.
* In-stock products.
* Standard packaging.

Needs caution if:

* Customer expects many items.
* Customer requests special sourcing.
* Delivery fees are high.
* Platform fees make margin weak.

### 350 - 500 SAR

Suitable for:

* Stronger curated box.
* More flexible product mix.
* Better visual value.
* Baby/Kids or care-style gifts.
* More premium presentation.

### 500 - 750 SAR

Suitable for:

* Larger gift story.
* More premium items.
* Stronger styling.
* Custom concept with more flexibility.

### 750 SAR+

Suitable for:

* High-value custom gifts.
* Travel-inspired sourcing.
* Premium limited items.
* Larger or more detailed concepts.

### غير محدد

Needs clarification.

Ask the customer to provide a comfortable budget range before preparing a quote.

---

## 13. Costing Rule

No special request should be quoted without estimated costing.

Minimum costing fields:

```text
Estimated Product Cost
Estimated Packaging Cost
Estimated Preparation Cost
Estimated Delivery / Shipping Cost
Payment Fee Assumption
Platform Fee Assumption
Total Estimated Cost
Target Profit
Suggested Quote
```

Minimum profit target:

```text
50% above total cost
```

Formula:

```text
Minimum Net Revenue Needed = Total Cost × 1.5
```

---

## 14. Packaging Feasibility Review

Check if the request fits the approved packaging system.

Approved packaging:

```text
Inner box: 40 × 30 × 10 cm
Outer gift bag: 45 × 33 × 15 cm
```

Ask:

```text
Will the products fit inside the inner box?
Will the gift look balanced inside the box?
Will the outer gift bag protect the presentation?
Is additional shipping protection needed?
Will the final presentation still feel premium?
```

If the request requires products that do not fit the box, either:

* Adjust product selection.
* Offer another concept.
* Decline the request.
* Treat it as a future special project.

---

## 15. Product Availability Review

Classify products needed:

```text
Already in stock
Can be sourced quickly
Needs special sourcing
Not available
Unsuitable for Gift Story
```

Preferred for first launch:

```text
Already in stock
```

Accept with caution:

```text
Can be sourced quickly
```

Avoid unless planned:

```text
Needs special sourcing
```

Decline:

```text
Not available
Unsuitable for Gift Story
```

---

## 16. Decision: Accepted for Quote

A request can be marked as:

```text
Accepted for Quote
```

when:

* Occasion is clear.
* Recipient is clear.
* Timeline is realistic.
* Budget is suitable.
* Concept fits Gift Story.
* Products are available or feasible.
* Packaging can support the request.
* Profit target can likely be protected.
* Operational capacity is available.

Next step:

Prepare a concept and quote.

---

## 17. Decision: Needs Clarification

Mark as:

```text
Needs Clarification
```

when:

* Budget is unclear.
* Delivery date is unclear.
* Occasion is vague.
* Recipient details are missing.
* Customer expects a previous story exactly.
* Desired products are unclear.
* Timeline may be too short.
* Request may exceed budget.
* Gift direction is too broad.

Do not prepare a quote until clarification is received.

---

## 18. Decision: Declined

Mark as:

```text
Declined
```

when:

* Request does not fit Gift Story.
* Timeline is impossible.
* Budget is too low for the expectation.
* Required products are unavailable.
* Packaging cannot support the idea.
* Request would weaken brand quality.
* Operational capacity is unavailable.
* Customer expects something outside the brand’s scope.
* Request involves unsuitable, unsafe, or inappropriate products.

Decline politely and offer the current story if relevant.

---

## 19. Decision: Waitlist / Future Review

Mark as:

```text
Waitlist / Future Review
```

when:

* The request fits Gift Story but timing is not suitable.
* Products may be available later.
* It belongs to a future category.
* The idea is good but not possible now.
* The customer is flexible on timing.

Use this status carefully.

Do not create false expectations.

---

## 20. Quote Preparation Logic

If accepted for quote, prepare:

```text
Gift direction
Suggested content type
Packaging note
Estimated preparation time
Final quote price
Payment method
Validity period
Important notes
```

A quote should include:

* What type of gift story is being proposed.
* What the customer can expect generally.
* Whether exact contents may vary.
* Estimated delivery or readiness date.
* Final price or approved price range.
* Confirmation requirements.
* Payment instruction through official method.

---

## 21. Quote Validity

Custom request quotes should have a validity period.

Recommended:

```text
24 to 48 hours
```

Reason:

* Product availability may change.
* Inventory may be reserved for other orders.
* Costs may change.
* Preparation schedule may fill.

Suggested customer-facing note:

```text
العرض صالح لمدة 48 ساعة، ويعتمد تأكيد الطلب على توفر القطع وقت اعتماد الطلب والدفع.
```

---

## 22. Payment Confirmation Logic

Do not begin preparation before:

```text
Customer approves the quote
Final gift direction is confirmed
Gift card message is confirmed or scheduled
Delivery date is confirmed
Payment is completed through an approved method
```

Once payment is complete, update status to:

```text
Confirmed
```

Then:

```text
In Preparation
```

---

## 23. Product Reservation Logic

Products should only be reserved after:

* Quote is accepted by customer.
* Payment is completed.
* Final direction is confirmed.

Before payment, do not guarantee product reservation unless the business intentionally approves a temporary hold.

If temporary hold is used, define a clear time limit.

Suggested:

```text
Temporary hold: maximum 24 hours
```

---

## 24. Preparation Logic

Once confirmed:

1. Reserve selected products.
2. Prepare product list.
3. Confirm gift card message.
4. Prepare packaging.
5. Arrange box.
6. Photograph order for internal record if needed.
7. Add protective packaging.
8. Prepare delivery or shipping.
9. Update status.

---

## 25. Quality Review Before Dispatch

Before dispatch, check:

```text
Correct customer request
Correct recipient direction
Products match approved concept
Gift card message is correct
Products are clean
No price tags visible
No purchase source visible
Packaging is clean
Tissue paper is neat
Sticker is placed correctly
Gift card is included
Outer gift bag is clean
Protective packaging is used if needed
Shipping label is not on branded packaging
Final presentation feels premium
```

---

## 26. Customer Reply Timing

Recommended response timing:

```text
New Request: reply within 24-48 hours if possible
Needs Clarification: reply as soon as review identifies missing info
Accepted for Quote: send quote after costing and availability check
Declined: reply politely once decision is clear
```

Do not promise a specific response time publicly unless operationally approved.

---

## 27. Customer Reply Templates

Detailed customer reply messages should live in:

```text
customer-message.md
```

This file only defines internal logic.

Use warm, formal, and clear replies.

---

## 28. Internal Scoring System

Gift Story may use a simple scoring system before accepting a request.

Score each item from 1 to 5:

```text
Brand Fit
Timeline Feasibility
Budget Suitability
Product Availability
Packaging Fit
Profit Potential
Operational Capacity
```

Maximum score:

```text
35
```

Suggested interpretation:

```text
30 - 35: Strong request, likely acceptable
24 - 29: Accept with caution or clarify
18 - 23: Needs clarification or adjustment
Below 18: Usually decline
```

This scoring is internal only and should not be shown to customers.

---

## 29. Red Flags

Review carefully or decline if:

* Customer wants many products for a low budget.
* Request requires same-day custom sourcing.
* Customer wants exact old box replication.
* Requested style is loud or unsuitable.
* Products do not fit the box.
* Timeline is unrealistic.
* Customer refuses review process.
* Customer wants to skip payment confirmation.
* Customer expects WhatsApp-only informal handling.
* Products may be unsafe or inappropriate.
* Margins are too weak.
* The request would hurt the premium image.

---

## 30. Green Flags

Good request signs:

* Customer understands the request is reviewed.
* Occasion is clear.
* Recipient details are clear.
* Budget is realistic.
* Timeline allows preparation.
* Customer likes Gift Story style.
* Products can be sourced or are in stock.
* Packaging can support the idea.
* Customer is flexible.
* Request protects profit and quality.

---

## 31. When to Offer the Current Story Instead

Offer the current ready story when:

* Customer needs a quick gift.
* Budget is limited.
* Timeline is too short.
* Request is close to Baby/Kids.
* Custom execution is not possible.
* Customer wants a gift without many special details.

Suggested direction:

```text
يمكنكِ استكشاف القصة الحالية المتاحة الآن عبر منصة البيع الرسمية، فهي الخيار الأنسب إذا كانت الهدية مطلوبة خلال وقت قصير.
```

---

## 32. When to Suggest a Future Category

Suggest future categories only when relevant.

Examples:

* Graduation request → Graduation Stories.
* Care request → Care Stories.
* Birthday request → Birthday Stories.
* Travel-inspired request → Travel Stories.

Do not promise exact launch dates unless confirmed.

Suggested direction:

```text
هذه الفكرة قريبة من إحدى القصص القادمة من Gift Story، وقد نتمكن من مراجعتها لاحقًا عند فتح هذا النوع من الطلبات.
```

---

## 33. Final Internal Rule

Special requests should help Gift Story grow carefully.

They should not create chaos.

Accept only requests that can be:

* Beautifully prepared.
* Properly costed.
* Protected in delivery.
* Presented in Gift Story style.
* Delivered within a realistic timeline.
* Profitable enough.
* Managed without harming the main launch focus.

The goal is not to accept every request.

The goal is to create gift stories that truly fit Gift Story.
