---
type: income
category: colorado-taxable-income
jurisdiction: CO
tax_year: 2026
source_doc: None — computed from the return (federal taxable income plus Colorado additions minus Colorado subtractions)
form: Form DR 0104
line: "12"
via:
  - Line 1 + Lines 2–7 and 9 → Line 10 → − Line 11 (DR 0104AD subtotal) → Line 12 → tax (Line 13)
routing:
  - "Line 8 is reserved on the 2025 form and is not added; the 2026 form may use it for the overtime addback"
  - "Line 11 must equal the DR 0104AD subtotal; no negative amounts"
  - "Part-year residents and nonresidents → apportion on DR 0104PN after line 12"
see_also:
  - income/additions/other-additions.md
  - income/subtractions/other-subtractions.md
  - tax-computation/colorado-tax-rate-and-tax-table.md
---
# Colorado Taxable Income
## Description
Colorado taxable income is federal taxable income plus Colorado additions, minus Colorado subtractions. The tax rate for 2026 is 4.4% (no TABOR temporary rate cut for 2026).

## Amount
- Line 10: federal taxable income + additions
- Line 11: total subtractions
- Line 12: line 10 − line 11

## Notes
- Attach the subtractions schedule when any subtraction is claimed
- Example: line 1 $95,000; other-state bond interest $1,500 → line 10 $96,500; Social Security subtraction $14,000 → line 11 $14,000; line 12 $82,500; tax at 4.4% = $3,630

## Required Information
- Federal taxable income
- Additions and subtractions

## Questions
- Do you have any Colorado additions or subtractions?

## Common Errors
- Including reserved line 8 on the 2025 layout
- Line 11 not matching the subtractions schedule

## Prompt
- How is Colorado taxable income figured?
