---
type: payment
category: tabor-refund
jurisdiction: CO
tax_year: 2026
source_doc: Federal Form 1040 as filed (line 11a AGI; lines 6a and 6b Social Security) / Form SSA-1099 / Forms 1099-INT (box 8) and 1099-DIV (box 12) showing tax-exempt state and local bond interest
form: Form DR 0104
line: "38"
via:
  - Line 34 federal AGI + Line 35 nontaxable Social Security + Line 36 tax-exempt bond interest = Line 37 modified AGI → TABOR table → Line 38 ($0 for 2026) → Line 39
routing:
  - "Tax year 2026 → line 38 is $0 for every return"
  - "Lines 34 to 37 are still completed; other lines rely on line 34"
see_also:
  - income/subtractions/social-security-subtraction.md
  - income/additions/other-state-bond-interest.md
  - payments/overpayment-and-refund.md
---
# Modified AGI and TABOR State Sales Tax Refund
## Description
In years with a TABOR revenue surplus, Colorado refunds the excess through a sales tax refund on the income tax return, scaled by modified AGI. There is no surplus for the year that funds tax year 2026, so the refund is $0.

## Status for 2026 — no TABOR refund
- Legislative Council's September 2026 forecast shows FY 2025-26 revenue $175.9 million BELOW the TABOR limit, so there is nothing to refund on 2026 returns
- No temporary income tax rate cut for 2026; the rate stays at 4.4%
- Modified AGI (lines 34 – 37) is still computed and used elsewhere

## Amount
- Line 34: federal AGI (negative if negative)
- Line 35: nontaxable Social Security (Form 1040 line 6a minus 6b)
- Line 36: tax-exempt interest from state and local bonds
- Line 37: modified AGI
- Line 38: $0

## Notes
- For reference, the 2025 refund ranged from about $20 to $62 (single) and $40 to $124 (joint)
- Example: joint filers, AGI $96,000, Social Security $30,000 of which $18,000 taxable, no bond interest → line 37 $108,000; line 38 $0

## Required Information
- Federal AGI
- Social Security benefits
- Tax-exempt bond interest

## Questions
- Not asked for line 38 in 2026; lines 34 – 36 come from the federal return

## Common Errors
- Entering a 2025 TABOR amount on a 2026 return
- Leaving line 34 blank

## Prompt
- Will I get a TABOR refund on my 2026 Colorado return?
