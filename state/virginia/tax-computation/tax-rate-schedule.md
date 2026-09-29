---
type: tax
category: tax-rate
jurisdiction: VA
tax_year: 2026
source_doc: Form 760, Line 15 Virginia taxable income / the Tax Rate Schedule (instructions page 38) or the detailed tax table and Tax Calculator at www.tax.virginia.gov
form: Form 760
line: "16"
via:
  - Form 760, Line 15 → Tax Rate Schedule or tax table → Form 760, Line 16 → Line 18 (after the Spouse Tax Adjustment)
routing:
  - "VAGI (Line 9) below the filing threshold → enter $0 on Line 16; do not use the schedule or table"
  - "Otherwise → tax on Line 15 from the table or schedule, rounded to whole dollars"
see_also:
  - tax-computation/tax-computation.md
  - tax-computation/spouse-tax-adjustment.md
  - filing/filing-requirements.md
---
# Tax Rate Schedule (Form 760, Line 16)
## Description
Virginia taxes Virginia taxable income (Line 15) at graduated rates: 2% up to $3,000, 3% from $3,001 to $5,000, 5% from $5,001 to $17,000, and 5.75% over $17,000. The same brackets apply to every filing status; joint filers get relief through the Spouse Tax Adjustment on Line 17 instead of wider brackets. The tax can be taken from the Tax Rate Schedule, the detailed tax table on the Department's website, or the online Tax Calculator.
## 2026 Tax Rate Schedule
| Virginia taxable income over | but not over | tax is | of excess over |
|---|---|---|---|
| $0 | $3,000 | 2% | $0 |
| $3,000 | $5,000 | $60 + 3% | $3,000 |
| $5,000 | $17,000 | $120 + 5% | $5,000 |
| $17,000 | no limit | $720 + 5.75% | $17,000 |
Example from the instructions: taxable income of $90,000 gives $720 + (0.0575 x $73,000) = $720 + $4,197.50 = $4,917.50, rounded to $4,918.
A quick equivalent for income over $17,000: 5.75% of taxable income minus $257.50.
## How to compute Line 16
1. Confirm Line 9 (VAGI) is at or above the filing threshold ($11,950 for Filing Status 1 or 3; $23,900 for Filing Status 2). If not, enter $0.
2. Apply the schedule (or table) to Line 15.
3. Round to whole dollars and enter on Line 16.
4. Filing Status 2: compute the Spouse Tax Adjustment on Line 17; Line 18 = Line 16 - Line 17.
## Where else the schedule is used
- Spouse Tax Adjustment Worksheet, Lines 8 and 9 (tax on each spouse's share)
- Form 760C Exceptions 2, 3 and 4 and Form 760F Exception 2 (tax recomputed on prior year or annualized income)
## Questions
- What is your Virginia taxable income on Line 15?
- Is your VAGI above the filing threshold for your filing status?
- Are you filing jointly (so the Spouse Tax Adjustment may apply)?
## Common Errors
- Applying the rate to VAGI (Line 9) instead of taxable income (Line 15)
- Computing tax when VAGI is below the filing threshold; the tax is $0
- Applying 5.75% to all income instead of using the bracket amounts
- Not rounding Line 16 to whole dollars
- Expecting wider brackets for joint filers instead of claiming the Spouse Tax Adjustment
## Prompt
- What are Virginia's income tax rates for 2026?
- How much Virginia tax do I owe on $60,000 of taxable income?
- Is Virginia's tax rate different for married couples?
