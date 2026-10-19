---
type: computation
category: tax-computation
jurisdiction: NM
tax_year: 2026
source_doc: Computed on the return from New Mexico taxable income (PIT-1 line 17) and filing status (federal Form 1040 as filed)
form: Form PIT-1
line: "18, 18a"
via:
  - PIT-1 Line 17 + filing status → tax rate table (up to $100,000) or rate schedule (over $100,000) → PIT-1, Line 18 (18a = R) → Line 22
---
# Tax from the Tax Rate Table (Line 18)
## Description
New Mexico tax on taxable income, using six rates from 1.5% to 5.9% (2024 HB 252, effective 2025, unchanged for 2026). Mark 18a "R" when the tax comes from the rate table.

## Two methods
- Taxable income $100,000 or less: use the printed TABLE. It is in $100 rows ("more than / but not over"); read the amount in the filing-status column. The table figures the tax at the middle of each row, so it can differ slightly from straight bracket arithmetic
- Over $100,000: use the printed SCHEDULE below

## 2026 rate schedule over $100,000
- Single, taxable income $100,000–210,000: $4,356 + 4.9% of excess over $100,000
- Single, taxable income over $210,000: $9,746 + 5.9% of excess over $210,000
- Joint, head of household, surviving spouse, taxable income $100,000–315,000: $4,087 + 4.9% of excess over $100,000
- Joint, head of household, surviving spouse, taxable income over $315,000: $14,622 + 5.9% of excess over $315,000
- Married filing separately, taxable income $100,000–157,500: $4,492 + 4.9% of excess over $100,000
- Married filing separately, taxable income over $157,500: $7,310 + 5.9% of excess over $157,500

- The brackets and rates are fixed in statute and are not indexed, so the 2026 schedule carries the same figures TRD printed for 2025
- The printed bases are about $2 below straight bracket arithmetic at $100,000 (for example, single: arithmetic gives $4,358; the schedule uses $4,356). Use the printed figures, not your own bracket math
- Brackets by filing status are in filing/filing-status.md

## Example (2026, single)
Taxable income $120,000 → $4,356 + 4.9% × $20,000 = $5,336

## Status for 2026
No rate or bracket change from the 2026 legislative session, and no inflation indexing, so the figures above apply to 2026. Confirm against the 2026 table when TRD releases it.

## Required Information
- New Mexico taxable income
- Filing status

## Questions
- What is your New Mexico taxable income and filing status?

## Common Errors
- Computing bracket arithmetic instead of using the printed table (off by a few dollars)
- Using the single column for head of household (HOH uses the joint column)
- Forgetting to mark 18a

## Prompt
- How do I find my New Mexico tax?
