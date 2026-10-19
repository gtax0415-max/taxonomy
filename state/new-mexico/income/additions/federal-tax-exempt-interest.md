---
type: addition
category: additions
jurisdiction: NM
tax_year: 2026
source_doc: Form 1099-INT box 8 and Form 1099-DIV box 12, with the payer's state-by-state breakdown / Form 1040, line 2a as filed
form: Form PIT-1
line: "11"
via:
  - Form 1040, Line 2a → PIT-ADJ, Line 1 → PIT-ADJ, Line 6 → PIT-1, Line 11
---
# Interest and Dividends from Federal Tax-Exempt Bonds
## Description
New Mexico starts from federal AGI, which leaves out municipal bond interest. New Mexico adds ALL of that federally tax-exempt interest and exempt-interest dividends back in, from every state including New Mexico, and then lets you take the New Mexico portion back out as a separate deduction (PIT-ADJ line 7).

## Amount
- No dollar limit. The addition equals the total state and municipal bond interest and exempt-interest dividends excluded from federal AGI
- Normally the same figure as Form 1040, line 2a
- The New Mexico-exempt part (New Mexico state and local bonds, Puerto Rico, Guam, U.S. Virgin Islands, American Samoa, Northern Mariana Islands, and qualifying funds holding them) is subtracted on PIT-ADJ line 7

## Notes
- This is a gross-up-then-subtract design: add 100% here, deduct the New Mexico-exempt share on line 7. Netting the two on one line is wrong
- Exempt-interest dividends from a municipal bond mutual fund (1099-DIV box 12) count; the fund's year-end statement shows the percentage from each state
- Interest earned inside an IRA is not reported here and is not deductible on line 7
- If PIT-ADJ line 7 is larger than line 1, New Mexico requires an explanation with the return
- U.S. Treasury interest is the opposite case: it is taxable federally and deducted for New Mexico (PIT-ADJ line 9), so it never belongs on this line

## Status for 2026
No change to this addition from the 2026 legislative session (SB 151, HB 154, HB 291 reviewed). Line numbers are from the 2025 PIT-ADJ; confirm against the 2026 form when released.

## Required Information
- Total tax-exempt interest (Form 1040, line 2a)
- Each 1099-INT box 8 and 1099-DIV box 12 amount
- Payer or fund statement splitting the amount by issuing state

## Questions
- Did you receive tax-exempt interest from municipal bonds or a muni bond fund?
- How much of it came from New Mexico or U.S. territory obligations?
- Was any of it earned inside an IRA?

## Common Errors
- Adding back only the non-New Mexico portion instead of the full amount
- Forgetting exempt-interest dividends from mutual funds (1099-DIV box 12)
- Claiming the New Mexico deduction on line 7 without the matching addition on line 1
- Including IRA interest

## Prompt
- I have municipal bond interest on my federal return.
- I own a New Mexico muni bond fund.
- Do I pay New Mexico tax on tax-exempt interest?
