---
type: computation
category: tax-computation
jurisdiction: KS
tax_year: 2026
source_doc: Federal Form 1040 as filed for 2026 (filing status) / the Kansas taxable income figured from the filer's documents (no separate source document)
form: Form K-40
line: "8"
via:
  - Form K-40, line 7 (taxable income) → Tax Table (≤ $100,000) or Tax Computation Worksheet (> $100,000) → line 8 → line 12
---
# Tax Computation Worksheet
## Description
Kansas has two rates for 2026: 5.20% and 5.58%. Taxable income of $100,000 or less uses the Tax Table; above $100,000 uses this worksheet. There was NO 2026 rate cut — the revenue trigger in 2025 SB 269 was not met (KDOR Notice 25-06).

## 2026 rates
- Married filing joint: 5.20% on taxable income up to $46,000; 5.58% on the amount above
- Single, head of household, married filing separate: 5.20% up to $23,000; 5.58% on the amount above

## Worksheet (taxable income over $100,000)
- Single, head of household, married filing separate: tax = taxable income × 5.58% − $87
- Married filing joint: tax = taxable income × 5.58% − $175

The subtraction is the rate difference (0.38%) on the lower bracket: $23,000 × 0.38% ≈ $87; $46,000 × 0.38% ≈ $175.

## Example
Married filing joint, Kansas taxable income $150,000: $150,000 × 5.58% = $8,370 − $175 = $8,195.

## Notes
- Brackets are not indexed for inflation
- The former zero-tax rule for very low taxable income was repealed starting in 2024
- Nonresidents and part-year residents multiply this tax by the nonresident percentage (line 9 → line 10)
- Under $100,000 the Tax Table figures tax on income ranges, so results can differ by a few dollars from the formula

## Required Information
- Kansas taxable income (line 7)
- Filing status

## Questions
- What is your filing status?
- Is your Kansas taxable income over $100,000?

## Common Errors
- Using the formula instead of the Tax Table for $100,000 or less
- Using the joint subtraction ($175) for head of household
- Applying a 2026 rate cut that did not happen

## Prompt
- How is Kansas income tax calculated for 2026?
- What are the Kansas tax brackets for 2026?
