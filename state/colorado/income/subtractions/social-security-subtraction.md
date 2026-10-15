---
type: subtraction
category: social-security
jurisdiction: CO
tax_year: 2026
source_doc: Form SSA-1099 for each person / federal Form 1040 as filed (line 6b taxable Social Security; line 11a AGI)
form: Form DR 0104
line: "11"
via:
  - Taxable Social Security by person → DR 0104AD, Line 3 (primary) and Line 5 (spouse) → DR 0104AD subtotal → Form DR 0104, Line 11
  - Each person's Social Security subtraction reduces that person's pension limit (lines 4 and 6)
routing:
  - "65 or older on December 31, 2026 (born 1961 or earlier) → all taxable benefits"
  - "55 to 64 (born 1962 – 1971) → all if federal AGI is $75,000 or less single / $95,000 or less joint; otherwise up to $20,000"
  - "Under 55 → only benefits received because of the death of the person entitled to them, up to $20,000"
  - "Lines 3 + 5 cannot exceed Form 1040 line 6b"
see_also:
  - income/subtractions/pension-annuity-subtraction.md
  - payments/tabor-sales-tax-refund.md
---
# Social Security Benefits Subtraction
## Description
Colorado subtracts taxable Social Security benefits (including SSDI), with limits by age. HB24-1142 extended the full subtraction to ages 55 – 64 below an income limit starting in 2025.

## Amount
- Age 65+: all taxable benefits
- Age 55 – 64: all taxable benefits if federal AGI ≤ $75,000 (single) / $95,000 (joint); otherwise up to $20,000
- Under 55: survivor benefits only, up to $20,000
- The $75,000 / $95,000 limits are NOT indexed

## Notes
- On a joint return each spouse's age is tested separately; the primary uses line 3, the spouse line 5
- Attach all SSA-1099s
- Example: joint, AGI $88,000. Primary age 62 with $16,000 taxable benefits; spouse age 66 with $9,000 → $16,000 (AGI under $95,000) and $9,000

## Required Information
- Each person's SSA-1099 and age
- Taxable portion
- Federal AGI

## Questions
- What were your and your spouse's ages on December 31, 2026?
- How much of each person's Social Security was taxable?
- What is your federal AGI?

## Common Errors
- Using total benefits (SSA-1099 box 5) instead of the taxable part
- Applying the $75,000 single limit on a joint return

## Prompt
- Is Social Security taxed in Colorado?
