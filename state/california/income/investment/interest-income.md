---
type: income
category: investment
jurisdiction: CA
tax_year: 2026
source_doc: Form 1099-INT (box 1 interest, box 3 U.S. savings bond and Treasury interest, box 8 tax-exempt interest) / Form 1099-OID / brokerage consolidated statement showing state of issue for municipal bonds
form: Form 540
line: "13"
via:
  - Form 1099-INT → federal Form 1040, Line 2b → federal AGI → Form 540, Line 13
  - "U.S. obligation interest: Schedule CA (540), Part I, Section A, Line 2, column B → Form 540, Line 14"
  - "Non-California municipal bond interest: Schedule CA (540), Part I, Section A, Line 2, column C → Form 540, Line 16"
---
# Interest Income
## Description
Interest from savings, money market and escrow accounts, refunds and similar sources. It flows to California through federal AGI, but two common items differ between federal and California law.

## Sources
- Savings accounts
- Mortgage escrow accounts
- Money market accounts
- Interest on refunds, offsets and credits
- Out-of-state municipal bonds

## California differences
- OUT-OF-STATE municipal bond interest is tax-exempt federally but TAXABLE in California: add it in column C
- U.S. Treasury and savings bond interest is taxable federally but EXEMPT in California: subtract it in column B
- California municipal bond interest is exempt in both

## Notes
- Line numbers follow the 2025 Form 540 and schedules; confirm them on the 2026 forms (expected December 2026)
- Also subtract (column B): interest on Ottoman Turkish Empire settlement payments; a child's interest reported by the parent under FTB 3803
- Also add (column C): HSA interest and earnings (taxable annually in California); interest on American Samoa obligations; obligations of the District of Columbia issued after December 27, 1973; non-California bond interest passed through from S corporations, trusts, partnerships or LLCs
- EXEMPT-INTEREST DIVIDENDS: exempt for California only if the fund has at least 50% of its assets in U.S. obligations and/or California municipal obligations
- No adjustment for Fannie Mae, Ginnie Mae or FHLMC securities interest
- A 1099-INT is not a bill or a notice of an extra refund; it reports interest received
- FTB Publication 1001 covers federal and California differences

## Required Information
- All 1099-INT and 1099-OID forms
- Tax-exempt interest by issuing state
- U.S. obligation interest

## Questions
- Do you own municipal bonds from states other than California?
- Did you earn interest on U.S. Treasury bills, notes or savings bonds?
- Did you receive interest on a tax refund?

## Common Errors
- Leaving non-California municipal bond interest off the California return
- Paying California tax on U.S. Treasury interest

## Prompt
- I have interest from my savings account and some municipal bonds.
- I own Treasury bills. Does California tax that interest?
