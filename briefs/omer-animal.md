# Brief: Animal Services (buy/sell animals, vets, transport)

Read AGENT_BRIEF.md first: its tools, rules and final report all apply.
Only the account part changes: do NOT sign up (sign-up needs an OTP you cannot receive).
Log in with email + password (no OTP at login). Password for every account: {{TEST_PASSWORD}}

## Your account (by your persona name)

| Persona | Account | Role |
|---|---|---|
| Anna, Clara | buyer@test.com | buyer |
| Malik | buyer2@test.com | buyer |
| Layla, Jonas | seller@test.com | approved seller |
| Kenji | seller_pending@test.com | seller awaiting approval |
| Grace, Yuki | vet@test.com | approved veterinarian (doctor) |
| Ravi | vet_pending@test.com | veterinarian awaiting approval |
| Olga, Amira | transport@test.com | approved transport provider |
| Felipe | transport_pending@test.com | transport provider awaiting approval |
| Noah | suspended@test.com | suspended buyer |

If your persona is not in the table, use buyer@test.com.
Ignore the account part of your persona's goal. Keep its style (speed, care, language, accessibility).

## Your goal, by role

- **Buyer**: browse Home and Buy, search/filter, open a listing, add to cart, change quantity,
  go to checkout. Message a seller. Book a vet (doctor)
  appointment and request an animal transport. Open the Auction tab. Check profile, address,
  wallet, orders and notifications. Log out and log back in once.
- **Seller (approved)**: add a new listing with every field, edit it, look at incoming orders
  and messages, check the seller profile and earnings/wallet.
- **Veterinarian (approved)**: complete or check the vet profile (services, prices, schedule),
  look at appointment requests and accept or reply to one if any exist, check messages and earnings.
- **Transport provider (approved)**: complete or check the transport profile (vehicle, area,
  prices), look at transport requests and accept or reply to one if any exist, check earnings.
- **Any pending account**: check that the app clearly says the account awaits approval and that
  actions reserved for approved accounts are blocked. Report anything a pending user can still do.
- **Suspended account**: check the app clearly explains the suspension at login and blocks use.

For every role also try the Transport and Auction tabs and Settings, and report what each role
sees there.

## Payments (test card only)

Buyers: add money to the wallet with this test card, then pay for one order
(cart checkout) and one vet or transport booking if the app asks for payment:

- Card number 4111 1111 1111 1111 (Visa), CVC 123, any future expiry (for example 12/34), any name.
- If a 3-D Secure / OTP page appears, approve it (choose the success option or enter the test code shown).
- Top up a small amount (for example 100 SAR, or the smallest the app allows) before paying.
- Report: did the top-up reach the wallet balance, did the payment succeed, did the order or
  booking appear with the right status, and was the wallet charged the right amount.
- If the card is refused, report the exact message (the backend may be in live mode) and stop paying.

Never type any other card number.

## Never

Change an account's password, e-mail or phone, or delete an account or a listing you did not create.
