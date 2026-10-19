---
type: payment
category: payments
jurisdiction: MS
tax_year: 2026
source_doc: Computed from the return; no separate source document (underlying Forms W-2, 1099, and payment records)
form: Form 80-105
line: "29, 31, 34"
via:
  - Line 28 (total payments) − Line 23 (total tax) → Line 29 overpayment
  - Line 29 − Line 30 (interest and FTHB penalty) → Line 31 adjusted overpayment
  - Line 31 − Line 32 (applied to 2027) − Line 33 (check-offs) → Line 34 refund
---
# Overpayment and Refund
## Description
When payments exceed total tax, the overpayment is reduced by any underestimate interest or first-time home buyer penalty, then by the amount applied to 2027 and any voluntary contributions. The rest is refunded.
## Rules
- No refund under $1.00
- The refund may be offset for debts owed to the Department, counties, cities, Medicaid, MDES, child support (MDHS), or education lenders
- The return must be signed for a refund to be issued
- The refund can be paid by check or direct deposit
## Example (2026)
- Total payments $2,400, total tax $1,800 → overpayment $600; $100 to 2027; $5 to a check-off → refund $495
## Required Information
- Lines 23 and 28
- Choices for line 32 and line 33
## Questions
- Do you want your refund paid out, or part applied to 2027?
- Would you like to donate any to a check-off fund?
## Common Errors
- Forgetting to subtract line 30
- Applying more to 2027 than the overpayment
## Prompt
- How much is my Mississippi refund?
