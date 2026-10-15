---
type: income
category: additions
jurisdiction: UT
tax_year: 2026
source_doc: Form 1099-INT (box 8 tax-exempt interest, box 9 issuer state) or Form 1099-DIV (box 12 exempt-interest dividends with state breakdown) / brokerage statement showing bond issuer and purchase date
form: Form TC-40
line: "3"
via:
  - Form 1099-INT / 1099-DIV → TC-40_A, Part 5 (code AD007PT) → Form TC-40, line 3
---
# Municipal Bond Interest
## Description
Interest on non-Utah state and local bonds is tax-exempt federally, so it is not in federal AGI. Utah adds it back when the bond was acquired after January 1, 2003, unless the issuing state does not tax Utah bonds or has no income tax.

## Amount
- Addition = tax-exempt interest from bonds issued by non-federal government entities OUTSIDE Utah, acquired after January 1, 2003
- Taxed at the 2026 Utah rate of 4.45%

## Eligibility
Add back only if ALL of these are true:
- The bond was issued by a state or local government other than Utah
- It was acquired after January 1, 2003
- The interest is not in federal AGI
- The issuer's state taxes Utah bond interest AND has an income tax

## Notes
- Utah's own municipal bond interest is NOT added back
- The AD007PT amount is reused: it is subtracted in the MAGI worksheets for the Child Tax Credit, Retirement Credit and Social Security Benefits Credit, so it must be reported correctly even when small
- Exempt-interest dividends from a multi-state fund need the fund's state-by-state breakdown

## Required Information
- 1099-INT box 8/box 9 or 1099-DIV box 12 with state detail
- Purchase date of each bond
- Issuer state

## Questions
- Do you have tax-exempt interest from bonds issued outside Utah?
- When were the bonds bought (before or after January 1, 2003)?
- Do you hold a municipal bond fund, and does it report a state breakdown?

## Common Errors
- Adding back Utah bond interest
- Adding back bonds acquired on or before January 1, 2003
- Adding back interest from a state with no income tax or that exempts Utah bonds
- Adding the whole fund dividend instead of only the non-Utah portion

## Prompt
- I have tax-exempt interest from California municipal bonds.
- My muni bond fund paid exempt-interest dividends.
