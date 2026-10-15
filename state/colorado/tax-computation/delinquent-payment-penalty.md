---
type: tax-computation
category: late-payment-penalty
jurisdiction: CO
tax_year: 2026
source_doc: Payment confirmations or canceled checks showing the date and amount of each payment / DOR billing notice, if received
form: Form DR 0104
line: "44"
via:
  - Net tax due (Line 43) paid after April 15, 2027 → penalty → Line 44 → Line 47
routing:
  - "Paid in full by April 15, 2027 → $0"
  - "Paid at least 90% by April 15, filed by the extended due date and paid the rest with the return → no penalty"
  - "Paid late → greater of $5 or 5% plus 0.5% for each additional full or partial month, up to 12%"
  - "Prefer not to compute → DOR will bill"
see_also:
  - tax-computation/delinquent-payment-interest.md
  - payments/net-tax-due-and-amount-owed.md
  - filing/filing-and-payment-due-dates.md
---
# Delinquent Payment Penalty
## Description
Penalty for tax not paid by the April 15 due date. The filing extension is not an extension to pay.

## Amount
- Greater of $5 or a percentage of the unpaid tax: 5% for the first month plus 0.5% for each additional full or partial month
- Maximum 12%
- Applies to the unpaid net tax, not the total tax

## Notes
- Example: net tax due $2,000 paid in the fourth month after April 15, 2027 → 5% + (3 × 0.5%) = 6.5% → $130

## Required Information
- Unpaid tax and payment dates

## Questions
- Will you pay the full balance by April 15, 2027?
- If not, when will you pay?

## Common Errors
- Applying the penalty to the whole tax instead of the unpaid amount
- Using less than the $5 minimum
- Assuming the filing extension also extends the payment date

## Prompt
- What is the Colorado late payment penalty?
