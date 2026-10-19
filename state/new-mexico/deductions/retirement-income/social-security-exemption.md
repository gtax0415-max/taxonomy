---
type: deduction
category: retirement-income
jurisdiction: NM
tax_year: 2026
source_doc: Form SSA-1099 / Form 1040 lines 6b (taxable Social Security) and 11 (AGI) as filed
form: Form PIT-1
line: "15"
via:
  - Form 1040, Line 6b (if Line 11 AGI is at or under the limit) → PIT-ADJ, Line 25 → PIT-ADJ, Line 28 → PIT-1, Line 15
---
# Social Security Income Exemption
## Description
Exempts ALL taxable Social Security benefits when federal AGI is at or below a limit for your filing status. Above the limit, NONE of it is exempt.

## AGI limits (unchanged for 2026)
- Single: $100,000
- Married filing jointly, head of household, surviving spouse: $150,000
- Married filing separately: $75,000

- This is a CLIFF: $1 over the limit loses the whole exemption
- Limits are fixed in statute and NOT indexed for inflation

## Amount
- The taxable Social Security included in federal AGI (Form 1040 line 6b), not the gross benefit

## Notes
- Railroad Retirement tier 1 benefits are exempted on their own line (PIT-ADJ line 10) with no income limit; do not count them here as well
- The new federal senior deduction (H.R.1) does not reduce federal AGI, so it does not help clear this cliff
- Bills to remove or phase out the AGI limits were introduced in the 2026 session (SB 156, HB 92) but were NOT enacted

## Status for 2026
No change; limits as above. Confirm line numbers on the 2026 PIT-ADJ.

## Required Information
- SSA-1099 for each spouse
- Taxable Social Security on Form 1040 line 6b
- Federal AGI and filing status

## Questions
- Do you receive Social Security benefits?
- Is your federal AGI at or under the limit for your filing status?
- Do you also receive Railroad Retirement benefits?

## Common Errors
- Exempting the gross benefit instead of the taxable amount
- Exempting a partial amount when AGI is over the limit
- Counting railroad tier 1 benefits here and on line 10
- Assuming the limits are inflation-adjusted

## Prompt
- I am retired with Social Security and an IRA; my AGI is $95,000.
- My wife and I have AGI of $160,000; is our Social Security taxed in New Mexico?
