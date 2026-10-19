---
type: income
category: government-benefits
jurisdiction: CA
tax_year: 2026
source_doc: Form SSA-1099 (Social Security benefit statement) / Form RRB-1099 (railroad retirement equivalent benefits) / federal Form 1040, Line 6b as filed (taxable amount)
form: Form 540
line: "14"
via:
  - Form SSA-1099 → federal Form 1040, Line 6b → federal AGI → Form 540, Line 13
  - Schedule CA (540), Part I, Section A, Line 6, column B (subtraction) → Line 27, column B → Form 540, Line 14
---
# Social Security Benefits
## Description
Part of Social Security benefits may be taxable federally, but California does NOT tax Social Security. Whatever amount was included in federal AGI is subtracted on Schedule CA.

## Amount
- Subtract the TAXABLE amount included in federal AGI (federal Form 1040, line 6b), not the gross benefit

## Notes
- Line numbers follow the 2025 Form 540 and schedules; confirm them on the 2026 forms (expected December 2026)
- Equivalent TIER 1 railroad retirement benefits are also excluded (same line 6, column B); Tier 2 railroad retirement is excluded on line 5 (see income/retirement/pensions-annuities.md)
- If none of the benefit was taxable federally, no California adjustment is needed
- Applies to equivalent railroad retirement benefits on RRB-1099
- A federal deduction for repaying Social Security benefits is reversed for California in Schedule CA, Part II, line 16, column B

## Required Information
- SSA-1099 or RRB-1099
- Taxable amount on federal Form 1040, line 6b

## Questions
- Did you receive Social Security benefits in 2026?
- How much was taxable on your federal return?
- Did you repay any benefits?

## Common Errors
- Paying California tax on Social Security by missing the subtraction
- Subtracting the gross benefit instead of the federally taxable amount

## Prompt
- I'm retired and receive Social Security.
- Does California tax my Social Security?
