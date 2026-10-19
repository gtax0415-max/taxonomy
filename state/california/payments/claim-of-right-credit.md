---
type: payment
category: payments
jurisdiction: CA
tax_year: 2026
source_doc: Records of the repayment (canceled check, employer or payer statement) / prior-year federal return as filed showing the amount was included in income / records showing the filer was a California resident (or the income was California-source) in the year the amount was received
form: Form 540
line: "78"
via:
  - "Credit option: computed credit added to Form 540, Line 78 (write \"IRC 1341\" and the amount to the left)"
  - "Deduction option: Schedule CA (540), Part II, Line 16 (over $3,000) or Line 21 (2% floor, $3,000 or less)"
---
# Claim of Right Credit (IRC 1341)
## Description
When a filer repays more than $3,000 of income that was taxed in an earlier year (because they then thought they had an unrestricted right to it), they may take EITHER a deduction this year OR a credit for the tax paid on it earlier, whichever results in less tax.

## Rules
- Compute the credit using CALIFORNIA tax rates
- The credit is treated as a payment: add it to Form 540, line 78 and write "IRC 1341" with the amount
- Repayments of $3,000 or less: deduction only, as a miscellaneous itemized deduction subject to the 2% floor (line 21)
- If California never taxed the amount, no deduction or credit is allowed (for example, Social Security repayments)
- The choice can differ from the federal return; adjust Schedule CA, Part II, line 16 accordingly

## Notes
- Line numbers follow the 2025 Form 540 and schedules; confirm them on the 2026 forms (expected December 2026)

## Required Information
- Amount repaid and year originally taxed
- Prior-year California tax on that amount

## Questions
- Did you repay income you reported in an earlier year?
- Was it more than $3,000?
- Was it taxed by California when received?

## Common Errors
- Claiming a credit for income California never taxed
- Using federal rates to compute the California credit

## Prompt
- I repaid a $10,000 signing bonus I reported last year.
