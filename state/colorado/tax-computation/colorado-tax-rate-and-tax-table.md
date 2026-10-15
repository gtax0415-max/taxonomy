---
type: tax-computation
category: tax-rate
jurisdiction: CO
tax_year: 2026
source_doc: None — computed from Colorado taxable income (line 12)
form: Form DR 0104
line: "13"
via:
  - Line 12 → tax table (up to $50,000) or × 4.4% (over $50,000) → Line 13 → Line 16
routing:
  - "Full-year resident, Colorado taxable income $50,000 or less → read the tax table row"
  - "Over $50,000 → Colorado taxable income × 4.4%, rounded to the dollar"
  - "Part-year or nonresident → apportioned tax from the apportionment schedule"
see_also:
  - income/colorado-taxable-income.md
  - tax-computation/alternative-minimum-tax.md
  - tax-computation/net-income-tax.md
---
# Colorado Tax Rate and Tax Table
## Description
Colorado has one flat income tax rate. For 2026 it is 4.4%: FY 2025-26 revenue was $175.9 million below the TABOR limit, so no temporary rate cut applies.

## Amount
- Rate: 4.4%
- Tax table (up to $50,000): first rows $0 – $10 tax $0; $10 – $30 $1; $30 – $50 $2; $50 – $75 $3; $75 – $100 $4; then $100 rows, tax = 4.4% of the row midpoint, rounded, through the row over $49,900 but not over $50,000 ($2,198)
- An income exactly on a row boundary belongs to the lower row
- Over $50,000: Colorado taxable income × 0.044

## Notes
- The 2025 booklet worksheet labels the input "line 11"; Colorado taxable income is line 12
- Example: $45,250 → row over $45,200 but not over $45,300 → $1,991. $82,500 → $82,500 × 0.044 = $3,630

## Required Information
- Colorado taxable income

## Questions
- What is your Colorado taxable income?

## Common Errors
- Multiplying a table-range income by 4.4% instead of using the row
- Placing a boundary income in the higher row
- Using the worksheet's line 11 label instead of line 12

## Prompt
- What is the Colorado income tax rate for 2026?
