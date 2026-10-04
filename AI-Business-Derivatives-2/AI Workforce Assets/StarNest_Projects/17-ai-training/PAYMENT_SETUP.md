# Stripe payment path — prepared, activation pending

Prepared October 4, 2026. **Provider selected: Stripe Payment Links. Live checkout: NOT CREATED. Proposed pilot prices: $200 USD Workday Tune-Up and $125 USD Inquiry Reply Sprint, BOTH UNAPPROVED.** No account was created, terms accepted, payment charged, or live payment link published during this setup.

## Why this provider

Stripe Payment Links provides a hosted checkout without building a website. Standard US domestic-card pricing is listed as 2.9% + $0.30 per successful transaction, with Payment Links included in standard payments pricing. Account-specific, international, currency-conversion, tax-product, and other charges may differ. See [Stripe pricing](https://stripe.com/pricing) and [Payment Links](https://stripe.com/payments/payment-links).

This fits the first sprint because it avoids a website, custom checkout code, monthly custom-domain add-on, and a subscription billing setup. It is a one-time training purchase. Provider selection is an implementation recommendation; onboarding and account eligibility have not been verified.

## Two products, one payment provider

Create distinct one-time products and links only after approval. Workday Tune-Up: 90-minute remote workshop, one property-management business, up to eight attendees, three prompts, safe-use guide, practice exercise, and recap; proposed $200 USD. Inquiry Reply Sprint: 75-minute private session, one home-service owner; proposed $125 USD. Do not combine these prices or use one product link for both offers. The optional $300 Workday audit and $95 Inquiry audit are separate unapproved follow-ons; do not create their links yet.

## Prepared Inquiry Reply checkout specification

| Field | Ready-to-enter value |
| --- | --- |
| Product name | StarNest AI Inquiry Reply Sprint — 75 minutes |
| Description | One private 75-minute remote session for one home-service business owner. Includes a business fact card, reusable inquiry-reply prompt, three practice cases, review checklist, one-page instructions, and a recap within one business day. No automatic sending, integrations, website, lead generation, or guaranteed results. |
| Price | **$125.00 USD — proposal, awaiting founder approval** |
| Billing | One time, no subscription |
| Quantity | One session; do not allow buyer quantity changes for the first pilot |
| Scheduling | Appointment agreed manually before sending checkout link |
| Customer information | Contact email and name; business name if available; no inquiry/customer records in checkout |
| Checkout success text | Thank you. Your payment has been received. This checkout does not schedule an appointment. We will confirm the session time already agreed with you through our existing conversation. |
| Receipt | Enable successful-payment receipts using the account's verified support details |
| Add-ons | No custom domain, automatic post-payment invoice add-on, subscription, coupon campaign, or new paid integration |
| Tax | Resolve applicability and account settings before activation; do not assume the service is tax-exempt |
| Refund/reschedule terms | Use the founder-approved version of OFFER.md; current terms are proposals |
| Support identity | Founder to confirm the correct seller name and public support contact in Stripe |

## Customer journey

**Fit confirmed → approved offer and terms → appointment agreed → live Stripe link → payment verified in Dashboard → manual confirmation → 75-minute delivery → recap and sales-log update.**

Share the link only after agreeing a session time and scope; the checkout is not a scheduling system. Do not create a new calendar subscription for this pilot.

## Remaining activation steps

1. Founder approves or revises each pilot price and its corresponding OFFER.md terms. Approval of one package does not approve the other.
2. Sign in to the correct [Stripe Dashboard](https://dashboard.stripe.com/payment_links), or complete Stripe's account setup if no suitable account exists. Enter identity, bank, and verification details directly in Stripe, not in chat or these files. The accessible page during this task was the Stripe sign-in screen.
3. Verify the business and permitted service. Stripe's [account setup guidance](https://docs.stripe.com/get-started/account/set-up) describes live activation. A qualifying existing business/social profile may satisfy the public URL requirement; do not invent a business website. See [Stripe's website/profile guidance](https://support.stripe.com/questions/do-i-have-to-have-a-business-website-to-sign-up-for-stripe).
4. In the account's sandbox, create the product and one-time Payment Link using the specification above. Follow [Create a payment link](https://docs.stripe.com/payment-links/create).
5. Preview and test in the sandbox with Stripe's documented [testing tools](https://docs.stripe.com/testing). Verify product, price, quantity, customer contact collection, success message, and test payment record. Never use a real card for a test and never count sandbox payments as revenue.
6. Once commercial approval and account setup are complete, create the live equivalent. Recheck the actual live checkout and record its returned URL below; do not synthesize a URL from a product name.
7. Share with a qualified buyer only under authorized outreach. Confirm actual payment success in Stripe before recording cash and confirming fulfillment. Payout to the bank is separate from a successful customer payment.

## Current readiness register

| Item | Status |
| --- | --- |
| Provider choice and official documentation | Complete |
| Product description and checkout field specification | Complete |
| Founder price/terms approval | Pending |
| Correct authenticated Stripe account | Pending sign-in |
| Business verification / live eligibility / payout setup | Not inspected |
| Sandbox product and payment test | Not created / not run |
| Live Payment Link | Not created |
| Live checkout verification | Not performed |

**Workday live URL:** pending.
**Inquiry Reply live URL:** pending. No usable checkout URL exists from this task yet.  
**Stripe product/price/link IDs:** pending.  
**Owner:** StarNest founder.  
**Next action:** approve the commercial draft and sign in to the correct Stripe account.

## Sales-log rules

Record agreed/proposed deal value under Amount. Record successful customer payments less refunds under Cash collected, before processing fees; include the payment reference in Proposal alongside the scope/version. Keep cash received separate from proposals and bank payout timing. Do not count sandbox transactions or earlier DJ earnings in the new training sprint.

## Integration decision record

Status: **selected for proposed manual checkout**, not installed as an API dependency. No API key required for Dashboard setup. Review date: 2026-10-04. Expected volume: initially one pilot transaction; actual demand unknown. Fallback: pause collection while account access/approval is unresolved; preserve the written offer and scheduling conversation. Do not collect card details manually or substitute an unverified personal transfer route.
