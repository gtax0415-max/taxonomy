---
type: credit
category: credits
jurisdiction: IA
tax_year: 2026
source_doc: Federal Form 1040 as filed (all-source income) / Forms W-2 (state boxes 15–17) and 1099s identifying Iowa-source income / federal Schedule K-1s with the entity's Iowa-source statement / records of move-in or move-out date
form: Form IA 1040
line: "13"
refundable: no
via:
  - Iowa-source net income ÷ all-source net income = Iowa percentage (IA 126 line 29)
  - (100% − Iowa percentage) × tax after credits → IA 126 line 34 → Form IA 1040, line 13
---
# Nonresident or Part-Year Resident Credit (IA 126)
## Description
Credit that removes Iowa tax on non-Iowa income for nonresidents and part-year residents, so only Iowa-source income is taxed, at the same rate as residents.

## Scope for this taxonomy
- OUT OF SCOPE (team decision 2026-09-30: full-year residents only). Keep line 13 as an entry with a review row so a nonresident or part-year return is flagged

## How it works (for reference)
- Iowa-source net income (IA 126 line 27) ÷ all-source net income (line 28) = Iowa percentage, between 0% and 100%
- Credit percentage = 100% − Iowa percentage
- Credit = tax after credits × credit percentage → line 13
- Nonresidents with Iowa-source net income under $1,000 (and no lump-sum tax) need not file
- Part-year residents report all income while a resident plus Iowa-source income while a nonresident
- Illinois residents' Iowa wages are not Iowa-source under reciprocity

## Required Information
- Residency dates and Iowa-source income by item

## Questions
- Were you an Iowa resident for all of 2026?

## Common Errors
- Preparing a part-year return as full-year resident

## Prompt
- I moved out of Iowa in June 2026.
