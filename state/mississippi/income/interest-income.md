---
type: income
category: income
jurisdiction: MS
tax_year: 2026
source_doc: Forms 1099-INT and 1099-OID (box 1, box 3 U.S. obligations, box 8 tax-exempt) / brokerage year-end statements showing interest by issuer state / federal Schedule B as filed
form: Form 80-105
line: "43"
via:
  - Form 80-108, Part II (Schedule B), Line 1 (all interest) − Line 2 (U.S. and Mississippi obligations) → Line 3 → Form 80-105, Line 43 → Line 49
---
# Interest Income
## Description
Interest from all sources, including federally tax-exempt bonds of OTHER states, minus interest on U.S. and Mississippi obligations.
## How it is built
- Line 1: total interest, including federally exempt municipal interest (1099-INT box 8)
- Line 2: subtract U.S. obligation interest (box 3) and Mississippi state and local bond interest
- Line 3: taxable Mississippi interest → line 43
## Notes
- Federal and Mississippi taxability differ in BOTH directions (see us-and-mississippi-obligations-interest.md and other-state-obligations-interest.md)
- Early withdrawal penalties are an adjustment on line 52, not netted here
## Example (2026)
- Bank interest $500, Treasury bills $1,200, Mississippi municipal bond $300, Texas municipal bond $400 → line 1 $2,400, line 2 $1,500, line 3 $900
## Required Information
- All Forms 1099-INT and 1099-OID
- Issuer state of each municipal bond
## Questions
- Do you own Treasury bills, savings bonds, or other U.S. government bonds?
- Do you own municipal bonds? Which state issued them?
## Common Errors
- Taxing U.S. Treasury interest
- Leaving out other states' municipal bond interest because it is federally exempt
- Starting from federal taxable interest only (Form 1040 line 2b)
## Prompt
- Is my savings bond interest taxable in Mississippi?
- Do I pay Mississippi tax on municipal bond interest?
