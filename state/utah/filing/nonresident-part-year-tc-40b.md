---
type: filing
category: filing
jurisdiction: UT
tax_year: 2026
source_doc: 2026 federal Form 1040 and Schedule 1 as filed (total income and adjustments by line) / Forms W-2 (box 16 Utah wages) and 1099 / Utah Schedules K-1 / move-in or move-out dates
form: Form TC-40
line: "22"
via:
  - Federal Form 1040 lines → TC-40_B lines 1–38 (Column A Utah, Column B total) → line 39 ratio → line 41 = (TC-40 line 20 − line 21) × ratio → Form TC-40, line 22
---
# Non or Part-year Resident Schedule (TC-40_B)
## Description
Nonresidents and part-year residents figure tax as if they were full-year residents, then multiply by the ratio of Utah income to total income.

## Status for 2026 — out of scope
OUT OF SCOPE — team decision 2026-09-30: the product covers full-year residents with Utah income only. Kept for routing: a "No" in a full-year resident box should stop the flow and flag the return.

## Method
- Column A: Utah-source income while a nonresident + all income while a resident
- Column B: total income from the federal return
- Line 15: additions (TC-40_A Part 5), Utah portion only in A
- Lines 19–37: federal adjustments; Column A only the Utah part (moving expenses only for moves INTO Utah)
- Line 38 Column B must equal TC-40, line 7
- Line 39: A ÷ B, 4 decimals, between 0.0000 and 1.0000
- Line 41: (TC-40 line 20 − line 21) × line 39 → TC-40, line 22

## Notes
- Nonresident active-duty military pay is excluded from Column A
- Nonresident military spouse income: subtraction SU011PT
- A Utah loss in Column A can make the Utah tax zero but is not carried to other years

## Required Information
- Federal return line detail
- Utah-source amounts and residency dates

## Questions
- Were you or your spouse a Utah resident for only part of 2026, or not at all?

## Common Errors
- Line 38 Column B not matching TC-40 line 7
- Putting all income in Column A for a part-year resident

## Prompt
- I moved to Utah in June 2026.
