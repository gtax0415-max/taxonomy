---
type: credit
category: family-dependent
jurisdiction: CO
tax_year: 2026
source_doc: Federal Form 1040 as filed (line 11a AGI, dependents section with Child Tax Credit box) / Schedule 8812 / each child's date of birth and SSN or ITIN
form: Form DR 0104
line: "31"
refundable: yes
via:
  - DR 0104CN → DR 0104CR, Line 1 → Line 26 → Form DR 0104, Line 31
routing:
  - "Federal AGI over $77,000 single, head of household or separate / $87,000 joint (2025 bands; 2026 bands indexed, not yet published) → $0"
  - "Child under 6 at the end of 2026 (born 2021 or later) → counts"
  - "Child 6 to 16 → no regular credit for 2026 (the Family Affordability part is off)"
  - "Full-year nonresident → not eligible; part-year resident → prorate"
see_also:
  - credits/refundable/refundable-credits-total.md
  - credits/refundable/family-affordability-tax-credit.md
---
# Colorado Child Tax Credit
## Description
Refundable per-child credit for Colorado residents with a child under age 6 who qualifies the filer for the federal child tax credit. ITIN filers may claim it, and the child does not need an SSN.

## Amounts
Regular Child Tax Credit table (C.R.S. 39-22-129):

| Federal AGI: single, HOH, MFS | Federal AGI: joint | Per child under 6 |
|---|---|---|
| $26,000 or less | $36,000 or less | $1,200 |
| $26,001 – $51,000 | $36,001 – $61,000 | $600 |
| $51,001 – $77,000 | $61,001 – $87,000 | $200 |
| Over $77,000 | Over $87,000 | $0 |

- The dollar amounts ($1,200 / $600 / $200) are fixed in statute and are NOT indexed
- The AGI bands ARE indexed (Denver-Aurora-Lakewood CPI-U, rounded to $1,000). The figures above are the 2025 bands; DOR has not yet published the 2026 bands, which may rise by $1,000 steps
- Family Affordability Tax Credit amounts are $0 for 2026, so this regular credit is the only child credit on DR 0104CN for 2026
- Part-year residents multiply by the Colorado income percentage

## Eligibility
- Child under 6 on December 31, 2026 and under 17 for the federal test
- Child meets the federal relationship, residency, support and joint return tests, with the Child Tax Credit box checked on the federal return
- Filer is a full-year or part-year Colorado resident

## Notes
- The federal OBBBA SSN requirement for the federal credit does not change the Colorado credit (DOR, February 2026)
- Example: joint filers, AGI $48,000, children born 2022 and 2016. One child under 6 × $600 = $600

## Required Information
- Federal AGI
- Each child's name, date of birth, and SSN or ITIN
- Whether the child has the federal Child Tax Credit box checked
- Residency status and Colorado income percentage if part-year

## Questions
- How many of your children were under 6 at the end of 2026?
- What is your federal AGI and filing status?
- Were you a Colorado resident all year?

## Common Errors
- Counting a child born in 2020 for 2026
- Treating the $1,200 / $600 / $200 amounts as inflation adjusted
- Claiming Family Affordability amounts for 2026
- Claiming as a full-year nonresident

## Prompt
- How much is the Colorado child tax credit for 2026?
- I have a 3-year-old and live in Colorado.
