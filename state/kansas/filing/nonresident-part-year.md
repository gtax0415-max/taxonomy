---
type: filing
category: filing
jurisdiction: KS
tax_year: 2026
source_doc: Federal Form 1040 as filed for 2026 / Form W-2 (state wage boxes 15–17 by state) / Forms 1099 and Schedule K-1 showing Kansas-source income / move-in or move-out dates (lease, closing disclosure) / other state's return as filed
form: Form K-40
line: "9, 10"
via:
  - Schedule S, Part B, lines B1–B21 (Kansas-source income) ÷ line B22 (Kansas AGI) → line B23 → Form K-40, line 9 → line 10
---
# Nonresident and Part-year Resident Allocation
## Description
Nonresidents with Kansas-source income, and part-year residents, compute tax as if a full-year resident, then multiply by the share of income from Kansas sources.

## How the allocation works
- Kansas-source income: all income while a Kansas resident; wages for work in Kansas; Kansas lottery, gambling and pari-mutuel winnings; Kansas real or tangible property; Kansas business income; Kansas unemployment
- NOT Kansas-source for nonresidents: interest, dividends and gains on intangibles (unless from a Kansas business); pensions and retirement distributions
- Nonresident percentage = modified Kansas-source income ÷ Kansas AGI, rounded to four decimals, not over 100%
- Line 10 tax = line 8 tax × line 9 percentage

## Notes
- SCOPE: OUT OF SCOPE for this taxonomy (team decision 2026-09-30: full-year residents with Kansas income only). This file stays in the index so the tool can recognize and route the situation.
- A nonresident must file if they had ANY Kansas-source income
- A joint federal return where one spouse is a Kansas resident and the other is not must be a joint Kansas return filed as nonresidents
- Nonresident military pay and certain military spouse income are subtracted

## Required Information
- Dates of Kansas residency during 2026
- Federal return and income by state (W-2 state wage boxes, 1099s, K-1s)
- Other state returns as filed

## Questions
- Did you live in Kansas for only part of 2026, or not at all?
- Did you have income from work or property in Kansas?

## Common Errors
- Including pensions or investment income as Kansas source for a nonresident
- Rounding the percentage incorrectly

## Prompt
- I moved to Kansas in June 2026.
- I live in Missouri but work in Kansas.
