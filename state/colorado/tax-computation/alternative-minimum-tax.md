---
type: tax-computation
category: alternative-minimum-tax
jurisdiction: CO
tax_year: 2026
source_doc: Federal Form 6251 as filed (alternative minimum taxable income, lines 4 – 6) / federal Form 1040 as filed
form: Form DR 0104
line: "14"
via:
  - Form 6251 AMTI + Colorado additions − Colorado subtractions (except the state tax refund) → × 3.47% − regular Colorado tax → Line 14
routing:
  - "Owed federal AMT → usually owes Colorado AMT as well; complete the Colorado AMT schedule"
  - "Exclude the state income tax refund subtraction and Colorado bond interest already in federal AMTI"
  - "Part-year or nonresident → apportion"
see_also:
  - tax-computation/colorado-tax-rate-and-tax-table.md
  - credits/nonrefundable/colorado-minimum-tax-credit.md
---
# Colorado Alternative Minimum Tax
## Description
Colorado AMT is the amount by which 3.47% of Colorado alternative minimum taxable income exceeds the regular Colorado tax. Prior-year Colorado AMT can generate the Colorado minimum tax credit.

## Amount
- Colorado AMTI = federal AMTI (Form 6251) + Colorado additions − Colorado subtractions other than the state tax refund
- Tentative tax = Colorado AMTI × 3.47% (unchanged for 2026)
- AMT = tentative tax − regular Colorado tax (if positive)

## Notes
- Do not duplicate items already in federal AMTI
- Example: ISO exercise; federal AMTI $180,000; no Colorado adjustments → $6,246; regular Colorado tax $5,500 (taxable income $125,000) → AMT $746

## Required Information
- Federal Form 6251
- Colorado additions and subtractions

## Questions
- Did you owe federal alternative minimum tax for 2026?

## Common Errors
- Using the wrong Form 6251 line
- Including the state tax refund in the subtractions

## Prompt
- Does Colorado have an alternative minimum tax?
