---
type: tax-computation
category: estimated-tax-penalty
jurisdiction: CO
tax_year: 2026
source_doc: Prior-year (2025) federal and Colorado returns as filed (2025 tax and federal AGI) / Forms W-2 and 1099 showing 2026 Colorado withholding / payment confirmations showing the date and amount of each 2026 estimated payment
form: Form DR 0104
line: "46"
via:
  - Exceptions → required annual payment → four installments compared with payments and withholding → penalty → Line 46
routing:
  - "2026 tax after credits minus $1,000 and withholding is zero or less → no penalty"
  - "Required payment = smaller of 70% of 2026 tax, or 100% of 2025 tax (110% if 2025 federal AGI was over $150,000; $75,000 separate)"
  - "Due dates April 15, June 15, September 15, 2026 and January 15, 2027"
  - "Return filed and tax paid by January 31, 2027 → no penalty for the fourth installment"
  - "Farmers and fishermen → farmer exception; uneven income → annualized method"
see_also:
  - tax-computation/farmers-fishermen-estimated-tax.md
  - tax-computation/annualized-installment-method.md
  - payments/estimated-tax-payments.md
---
# Underpayment of Estimated Tax Penalty
## Description
Penalty, figured like interest, when 2026 estimated payments and withholding were too low or too late.

## Amount
- $1,000 statutory exemption
- Required annual payment: smaller of 70% of 2026 tax or 100% / 110% of 2025 tax, in four equal installments
- Penalty per installment = underpayment × rate × days / 365
- Rate: 11% (2026 regular rate) for days in 2026; 10% (2027 regular rate) for days from January 1 to April 15, 2027. The 2025 schedule used 12%

## Notes
- Payments apply to the earliest unpaid installment first
- Example: 2026 tax $6,000, withholding $1,000; 2025 tax $4,000, AGI $90,000 → required payment $4,000 ($1,000 per quarter). Withholding counts $250 per quarter and no estimates were paid → April 15 shortfall $750 × 11% × 260 / 365 = $58.77, and so on for each installment

## Required Information
- 2026 tax and withholding
- 2025 tax and federal AGI
- Dates and amounts of payments

## Questions
- Did you make 2026 Colorado estimated payments, and on what dates?
- What was your 2025 Colorado tax and federal AGI?

## Common Errors
- Using the 2025 12% rate for 2026 days, or 11% for 2027 days
- Ignoring the $1,000 exemption
- Applying a later payment to the latest installment instead of the earliest

## Prompt
- Do I owe a Colorado underpayment penalty?
