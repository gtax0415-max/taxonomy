---
type: credit
category: earned-income
jurisdiction: CO
tax_year: 2026
source_doc: Federal Form 1040 as filed (line 27a EIC) / Schedule EIC / federal EIC worksheet (earned income) / Forms W-2 and 1099-NEC
form: Form DR 0104
line: "31"
refundable: yes
via:
  - Form 1040, Line 27a → DR 0104CR, Lines 3–5 (part-year Line 6) → Line 26 → Form DR 0104, Line 31
routing:
  - "Claimed the federal EITC → lines 3 to 5"
  - "Part-year resident → line 6 = line 5 × Colorado income percentage (not over 100%)"
  - "No federal EITC because of an ITIN, or under 25 with no children, or some dependents have ITINs → DR 0104TN (coeitc-itin-under-25)"
see_also:
  - credits/refundable/coeitc-itin-under-25.md
  - credits/refundable/refundable-credits-total.md
---
# Colorado Earned Income Tax Credit
## Description
Refundable Colorado credit equal to a percentage of the federal earned income credit, for full-year and part-year residents who claim the federal EITC.

## Amount
- 2026: 25% of the federal EITC (down from 50% for 2025)
- 25% is the statutory floor under HB24-1134; the higher tiers (up to 50%) depend on a TABOR revenue trigger that did not fire for 2026
- Part-year residents multiply by the Colorado income percentage
- 2026 federal maximum EITC (Rev. Proc. 2025-32): $664 / $4,427 / $7,316 / $8,231 for 0 / 1 / 2 / 3+ children

## Eligibility
- Claimed the federal EITC for 2026
- Full-year or part-year Colorado resident
- Each qualifying child listed on the Colorado dependents table

## Notes
- Example: single parent, federal EITC $3,996 → Colorado credit $3,996 × 25% = $999

## Required Information
- Federal EITC amount
- Earned income from the federal EIC worksheet
- Qualifying children's names, birth dates and SSNs
- Residency status

## Questions
- Did you claim the federal earned income credit for 2026? How much?
- Were you a Colorado resident all year?

## Common Errors
- Using the 2025 50% rate for 2026
- Entering the Colorado credit on both line 5 and line 6
- Using this credit instead of DR 0104TN when an ITIN blocked the federal EITC

## Prompt
- What is the Colorado earned income credit for 2026?
- I got the federal EITC. Does Colorado give one too?
