---
type: income
category: additions
jurisdiction: IA
tax_year: 2026
source_doc: Form 1099-INT, box 8 (tax-exempt interest) and box 9 (private activity bond interest) / brokerage year-end statement showing tax-exempt interest by issuing state / Form 1040, line 2a
form: Form IA 1040
line: "3"
via:
  - Form 1099-INT box 8 → Form 1040, line 2a → IA Schedule 1, line 1 column A → line 12 → line 13 → line 21 → Form IA 1040, line 3
---
# Interest from Other States' Municipal Securities
## Description
Addition for interest on state and municipal bonds that is exempt from federal tax but taxable in Iowa. Iowa starts from federal taxable income, so tax-exempt interest is missing from the starting point and must be added back unless Iowa law specifically exempts the bond.

## Amount
- Add the federally tax-exempt interest (Form 1040, line 2a) from bonds issued by states and municipalities, including other states and most Iowa issuers
- EXCLUDE interest on the Iowa bonds that Iowa law specifically exempts (for example Iowa Board of Regents bonds, Iowa Higher Education Loan Authority bonds, Vision Iowa, Iowa rural water district bonds, School Infrastructure Program bonds). An Iowa issuer is NOT automatically exempt; the bond must be on the statutory exempt list
- No dollar cap and no phase-out

## Notes
- The mirror-image subtraction is Schedule 1 line 1, column B: interest on direct U.S. obligations (Treasury bills, notes, bonds, Series EE/I savings bonds) included in federal taxable interest
- Ginnie Mae, Fannie Mae and Freddie Mac securities are NOT federal obligations for Iowa; their interest stays taxable and does not go in column B
- Report as a positive number. Do not use Schedule 1 merely to adjust for income taxed by another state; that is done on IA 126 / IA 130
- Married filing separately: split by ownership; jointly held accounts are split equally
- Unchanged for 2026: no Iowa legislation in the 2026 session changed this addition. Line number follows the 2025 IA 1040 Schedule 1; confirm against the 2026 form when released

## Required Information
- Form 1099-INT box 8 and box 9 amounts
- Issuer name or CUSIP for each bond, to identify Iowa-exempt issues
- Brokerage supplemental statement listing tax-exempt interest by state

## Questions
- Did you receive tax-exempt interest (Form 1099-INT box 8)?
- Which states or Iowa authorities issued the bonds?
- Did you also receive interest on U.S. Treasury bonds or savings bonds (a possible subtraction)?

## Common Errors
- Leaving out all Iowa bonds instead of only the specifically exempt ones
- Putting mutual fund exempt-interest dividends here instead of line 2
- Subtracting Ginnie Mae / Fannie Mae interest as if it were a federal obligation
- Missing private activity bond interest in box 9

## Prompt
- I have tax-exempt municipal bond interest on my 1099-INT.
- Is interest from Iowa bonds taxable on my Iowa return?
