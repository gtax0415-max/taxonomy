---
type: payment
category: payments
source_doc: Bank routing and account numbers for direct deposit / prior-year Form 1040 for the identity verification AGI / IRS notices if a refund was offset
form: Form 1040
line: "34, 35a, 36, 37, 38"
via:
  - Total payments (Line 33) minus total tax (Line 24) → Line 34 overpaid, or Line 37 amount owed
---
# Refund or Balance Due
## Description
The last lines of the return. Total tax on Line 24 is compared with total payments on Line 33, and the difference is either money back or money owed.
## The lines
- Line 34 — AMOUNT OVERPAID, when Line 33 exceeds Line 24
- Line 35a — the portion you want REFUNDED, with routing and account numbers on 35b through 35d for direct deposit
- Line 36 — the portion APPLIED to next year's estimated tax. See estimated-tax.md
- Line 37 — AMOUNT YOU OWE, when Line 24 exceeds Line 33
- Line 38 — ESTIMATED TAX PENALTY from Form 2210, which can appear even on a return showing a refund
## Refund choices
- DIRECT DEPOSIT is fastest and can be split across up to three accounts using Form 8888
- APPLYING IT FORWARD (Line 36) credits the amount as paid on the FIRST estimated tax installment date, which is often better than receiving a refund and then writing a check in April
- A paper check is the slowest option and the one most often lost or stolen
## Why a refund can be delayed
- Returns claiming the EARNED INCOME CREDIT or the ADDITIONAL CHILD TAX CREDIT cannot be issued before mid-February by law, regardless of when you file
- A mismatch between reported income and the information returns the IRS already holds triggers review
- REFUND OFFSET: the Treasury Offset Program can seize a refund for past-due federal tax, state tax, child support, or defaulted federal student loans. If the debt belongs only to your spouse, Form 8379 (injured spouse allocation) can protect your share
- Identity verification holds
## If you owe
- The balance is due on the FILING DEADLINE regardless of any extension. An extension extends the time to FILE, not the time to PAY
- FAILURE TO PAY penalty: 0.5% of the unpaid balance per month, plus interest
- FAILURE TO FILE penalty: 5% per month, ten times larger. If you cannot pay, file anyway — the cheapest mistake is owing money, not failing to file
- Payment options include IRS Direct Pay from a bank account, card payments with a processing fee, an installment agreement on Form 9465, and for genuine hardship an offer in compromise
## Notes
- A large refund means you lent money to the government interest-free all year. Adjusting Form W-4 converts it into take-home pay
- A large balance due usually points to under-withholding or missed estimated payments, and often carries a Form 2210 penalty on top
- Getting a refund does NOT prove your quarterly timing was correct. See estimated-tax.md
## Required Information
- Bank routing and account numbers, if using direct deposit
- Prior-year AGI, used to verify identity when e-filing
- Any IRS or agency notices about offsets
## Questions
- Are you getting a refund or do you owe?
- Do you want the refund deposited, or applied to next year's estimated tax?
- Do you or your spouse have past-due obligations that could offset the refund?
- If you owe, can you pay in full by the deadline, or do you need an installment agreement?
- Should you adjust your Form W-4 for next year?
## Common Errors
- Assuming an extension extends the time to pay
- Not filing because you cannot pay, which triggers the 5% penalty instead of the 0.5% one
- Entering incorrect bank details and losing a direct deposit
- Treating a large refund as a windfall rather than over-withholding
- Missing Form 8379 when a joint refund is offset for a spouse's separate debt
## Prompt
- When will I get my refund?
- I owe money and cannot pay it all right now.
- My refund was taken for my spouse's student loans.
- Should I apply my refund to next year?
