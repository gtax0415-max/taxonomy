---
type: subtraction
category: subtractions
jurisdiction: KS
tax_year: 2026
source_doc: Form 1099-G (box 2, state or local income tax refunds) / federal Schedule 1 as filed for 2026 (taxable refunds, line 1) and the federal state-refund worksheet
form: Form K-40
line: "2"
via:
  - Schedule S, line A13 → line A26 → line A27 → Form K-40, line 2
---
# State or Local Income Tax Refund
## Description
A state or local income tax refund is taxable federally when the tax was deducted as an itemized deduction in an earlier year. Kansas never allowed state income tax as a deduction, so it subtracts any such refund included in federal AGI.

## Amount
- The state or local income tax refund INCLUDED in 2026 federal AGI (federal Schedule 1, line 1)
- No entry if none of the refund was taxable federally (e.g., the filer took the federal standard deduction last year)
- Refunds from Kansas or any other state qualify. Unchanged for 2026

## Notes
- The higher federal SALT cap from 2025 ($40,000) means more 2025 itemizers deducted state income tax, so more 2026 refunds may be federally taxable and subtracted here
- Property tax refunds are not "income tax refunds" and do not belong here
- A refund received in 2026 from another state's prior-year return also qualifies if in federal AGI

## Required Information
- 1099-G box 2
- Taxable amount from the federal state-refund worksheet

## Questions
- Did you receive a state or local income tax refund in 2026?
- Did you itemize on your 2025 federal return?

## Common Errors
- Subtracting the full 1099-G amount when only part was federally taxable
- Subtracting a refund that was never included in federal AGI
- Including property tax refunds

## Prompt
- My Kansas refund from last year is on a 1099-G.
- Is my state tax refund taxed in Kansas?
