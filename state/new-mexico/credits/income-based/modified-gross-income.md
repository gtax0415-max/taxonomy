---
type: credit
category: income-based
jurisdiction: NM
tax_year: 2026
source_doc: Forms W-2, SSA-1099, RRB-1099, 1099-R, 1099-G, 1099-INT, 1099-DIV, 1099-B / federal Schedules C, E, F / award letters for SSI, TANF, VA benefits, workers' compensation / records of child support, alimony, cash gifts, and settlements — for the filer, spouse, and dependents
form: Form PIT-1
line: "24"
refundable: yes
via:
  - All household income → PIT-RC Lines 4–11 → Line 12 (modified gross income) → income tests for PIT-RC rebates and credits
---
# Modified Gross Income (PIT-RC Lines 4–12)
## Description
The income measure for the PIT-RC rebates. It is MUCH broader than AGI: all income of the filer, spouse, and dependents, taxable or not, with no reduction for losses or deductions.

## Included
- Wages, salaries, tips (line 4)
- GROSS Social Security, pensions, annuities, Railroad Retirement (line 5), not just the taxable part
- Unemployment and workers' compensation (line 6)
- Public assistance: TANF, general assistance, SSI (line 7)
- Net business, farm, or rental profit; a loss counts as ZERO and cannot offset other income (line 8)
- Gross capital gains, not reduced by losses (line 9)
- Cash gifts and marketable gifts (line 10)
- Everything else: interest (including tax-exempt), dividends, gross gambling winnings, settlements, scholarships, VA benefits, alimony, child support (line 11)
- Income exempted on PIT-ADJ lines 11 and 12 (tribal and age-100 income) must be included

## Excluded
- Loans that must be repaid
- SNAP and WIC
- Medicare, Medicaid, and similar medical payments
- New Mexico low-income and property tax rebates, and child day care credit money
- Rent subsidies, weatherization, and energy assistance
- Foster grandparent stipends
- Free room and board that is not compensation

## Income limits that use MGI (2026)
- Low income comprehensive tax rebate: $36,000
- Child day care credit: $30,160
- Additional county property tax rebate: $24,000
- Property tax rebate 65 or older: $16,000

## Status for 2026
No change from the 2026 legislative session. The income limits are fixed; they are not indexed.

## Required Information
- Every income source for the filer, spouse, and dependents, including nontaxable income

## Questions
- Did anyone in the household receive Social Security, SSI, TANF, VA benefits, child support, or gifts?
- Did any business or rental lose money? (It counts as zero, not a negative.)

## Common Errors
- Using federal AGI instead of MGI
- Netting a business loss against wages
- Using taxable instead of gross Social Security
- Leaving out dependents' income or nontaxable benefits

## Prompt
- What counts as income for the New Mexico low-income rebate?
