---
type: computation
category: tax-computation
jurisdiction: NM
tax_year: 2026
source_doc: Computed on the return from federal Form 1040 (AGI and standard or itemized deduction) and the New Mexico additions and deductions
form: Form PIT-1
line: "17"
via:
  - Lines 9 + 10 + 11 − 12 − 13 − 14 − 15 → PIT-1, Line 17 → Line 18 (tax from the rate table)
---
# New Mexico Taxable Income (Line 17)
## Description
The income New Mexico taxes: federal AGI with New Mexico's own additions, deductions, and exemptions. It feeds the tax rate table on line 18.

## Formula
- Line 9: federal AGI
- + Line 10: state and local tax addback
- + Line 11: PIT-ADJ additions
- − Line 12: federal standard or itemized deduction
- − Line 13: deduction for certain dependents
- − Line 14: low- and middle-income exemption
- − Line 15: PIT-ADJ deductions and exemptions
- = Line 17, not less than zero

## Then (line 18)
Tax from the 2026 rate table or schedule for the filing status (see tax-computation/tax-rate-table.md): 1.5% to 5.9%, top rate starting above $210,000 single, $315,000 joint/HOH/surviving spouse, $157,500 separate.

## Notes
- Line 16 is reserved
- New Mexico taxable income is often HIGHER than federal taxable income in 2026, because the federal tips, overtime, senior, car loan interest, and QBI deductions do not carry over

## Status for 2026
No change from the 2026 legislative session.

## Required Information
- Federal AGI and the federal standard or itemized deduction
- New Mexico additions, deductions, and exemptions

## Questions
- Do the New Mexico additions and deductions reconcile to the federal return?

## Common Errors
- Starting from federal taxable income
- Allowing a negative result

## Prompt
- How does New Mexico figure taxable income?
