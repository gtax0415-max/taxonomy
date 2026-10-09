---
type: payment
category: estimated-tax
jurisdiction: VA
tax_year: 2026
source_doc: The taxpayer's instruction on how much of the overpayment to apply to 2027 / projection of 2027 income and Virginia withholding
form: Form 760
line: "29"
via:
  - Form 760, Line 28 (overpayment) → Line 29 (credited to 2027 estimated tax) → Line 34 → reduces Line 36 refund (or increases Line 35) → 2027 Form 760, Line 21
routing:
  - "Overpayment on Line 28 → any part may be credited to 2027 on Line 29"
  - "Tax owed on Line 27 → no overpayment to credit; Line 29 is blank"
see_also:
  - payments/prior-year-overpayment-applied.md
  - payments/refund-and-direct-deposit.md
  - payments/estimated-tax-payments.md
  - payments/payments.md
---
# Overpayment Credited to 2027 Estimated Tax (Form 760, Line 29)
## Description
If Form 760 shows an overpayment on Line 28, you can have some or all of it credited to your estimated tax for next year (2027) instead of refunded. Enter the amount on Line 29. It becomes a 2027 estimated payment and appears on next year's return as the prior year overpayment (2027 Form 760, Line 21).
## How it flows
- Line 28: overpayment (Line 26 minus Line 18).
- Line 29: the part credited to 2027 estimated tax.
- Line 34: Lines 29 + 30 + 31 + 32 + 33.
- Line 36 refund: Line 28 minus Line 34 when Line 28 is greater; if Line 34 is greater than Line 28, the difference is owed on Line 35.
Because Line 29 is added into Line 34 with contributions, penalties and use tax, a credit forward is only available out of what remains of the overpayment after those items; if Line 34 exceeds Line 28, the return becomes a balance due.
## When it helps
- Taxpayers who expect to owe more than the estimated tax threshold beyond withholding for 2027 and would otherwise make estimated payments.
- On Form 760C for 2027, the prior year overpayment credit is treated as a timely payment toward the installments.
## Required Information
- Amount of the overpayment the taxpayer wants credited to 2027
- Expected 2027 Virginia tax and withholding, if deciding how much to credit
## Questions
- Do you want your Virginia overpayment refunded, or applied to next year's estimated tax?
- Do you expect to owe Virginia tax beyond withholding in 2027?
- Are you also making contributions from your refund on Schedule VAC?
## Common Errors
- Entering a Line 29 amount on a return that shows tax owed on Line 27
- Crediting more than the overpayment remaining after contributions, penalties and use tax
- Forgetting next year to claim the credit on Line 21
## Prompt
- Can I apply my Virginia refund to next year's taxes?
- I want to put part of my refund toward my 2027 estimated tax.
- Is it better to get the refund or credit it forward?
