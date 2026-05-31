# Bugs Found

```
# BUG-001

Title:
Cart remains empty after adding product

Severity:
Critical

Steps:
1. Open product page
2. Add item to cart
3. Open cart

Expected:
Item should appear in cart

Actual:
Cart is empty

Impact:
User cannot purchase product
```

```
# BUG-002

Title:
Search returns irrelevant results

Severity:
High

Steps:
1. Search for a specific show or subscription
2. Review top results

Expected:
Relevant items matching query appear first

Actual:
Unrelated items appear; filters ignored

Impact:
Users struggle to discover content
```

```
# BUG-003

Title:
Wallet payment fails intermittently

Severity:
High

Steps:
1. Add paid item or subscription
2. Proceed to payment and select wallet
3. Confirm payment

Expected:
Payment completes and confirmation displays

Actual:
Payment errors or times out; balance unchanged

Impact:
Revenue loss and frustrated users
```

```
# BUG-004

Title:
Chat messages delayed or not delivered

Severity:
Medium

Steps:
1. Open group chat
2. Send a message
3. Observe delivery and receipt by other users

Expected:
Messages appear in near-real-time

Actual:
Messages delayed, duplicated, or missing

Impact:
Poor communication in shared subscriptions
```

```
# BUG-005

Title:
Subscription sharing join flow requires unexpected approvals

Severity:
Medium

Steps:
1. Search and open a shared subscription group
2. Attempt to join

Expected:
Smooth join flow or clear approval requirement

Actual:
Confusing approval steps; no clear messaging

Impact:
Reduced adoption of sharing features
```

```
# BUG-006

Title:
Gift card codes fail to redeem

Severity:
High

Steps:
1. Enter valid gift card code at checkout
2. Apply code

Expected:
Discount applied and code marked redeemed

Actual:
Error message or no effect; code still valid

Impact:
Customer dissatisfaction and support load
```

```
# BUG-007

Title:
Support responses are slow or missing context

Severity:
Low

Steps:
1. Submit support ticket or chat
2. Await response

Expected:
Timely, contextual support with ticket reference

Actual:
Long waits; generic replies lacking details

Impact:
Lower user satisfaction and retention
```

