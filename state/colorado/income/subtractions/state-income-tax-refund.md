---
type: subtraction
category: state-tax-refund
jurisdiction: CO
tax_year: 2026
source_doc: Form 1099-G (state or local income tax refund) / federal Schedule 1 line 1 as filed
form: Form DR 0104
line: "11"
via:
  - Schedule 1, Line 1 → DR 0104AD, Line 1 → DR 0104AD subtotal → Form DR 0104, Line 11
  - Excluded from the Colorado alternative minimum tax subtraction
routing:
  - "State or local income tax refund reported on Schedule 1 line 1 → subtract the same amount"
  - "No refund in federal income → $0"
see_also:
  - income/additions/state-income-tax-addback.md
  - tax-computation/alternative-minimum-tax.md
---
# Taxable State Tax Refunds
## Description
A state or local income tax refund that is taxable federally (because the tax was itemized the year before) is removed for Colorado, since Colorado added back that state tax deduction in the earlier year.

## Amount
- The taxable refund reported on federal Schedule 1 line 1

## Notes
- Only a refund already on the federal return is subtracted
- Example: a 2025 itemizer reports a $640 Colorado refund on 2026 Schedule 1 line 1 → subtract $640

## Required Information
- Form 1099-G and Schedule 1 line 1

## Questions
- Did you report a state tax refund on your 2026 federal return?

## Common Errors
- Subtracting a refund that was not included in federal income

## Prompt
- Is my Colorado refund taxable in Colorado?
