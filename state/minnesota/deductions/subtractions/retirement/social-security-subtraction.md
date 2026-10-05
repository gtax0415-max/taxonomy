---
type: subtraction
jurisdiction: Minnesota
tax_year: 2026
category: subtractions-retirement
source_doc: Form SSA-1099 / Form RRB-1099 / Form 1040 Lines 6a, 6b, 2a, 9 / federal Schedule 1 Lines 21 and 26
form: Form M1
line: "7"
via:
  - Schedule M1M, Line 14 (Worksheet for Line 14 if AGI is over the threshold) → Schedule M1M, Line 43 → Form M1, Line 7
---
# Social Security Benefit Subtraction
## Description
Minnesota taxes Social Security only to the extent it is federally taxable, and then lets most filers subtract ALL of it. Higher-income filers get a partial subtraction.
## 2026 — MN Department of Revenue published figures
(TY2026 inflation-adjusted amounts; 2026 Schedule M1M instructions)
FULL SUBTRACTION if AGI is BELOW: $86,410 single and HOH / $110,780 MFJ and QSS / $55,390 MFS
SIMPLIFIED METHOD above the threshold: subtraction reduced 10% for each $4,000 ($2,000 MFS) of AGI over the threshold, rounded up; zero once AGI exceeds the threshold by more than $40,000 ($20,000 MFS)
ALTERNATIVE METHOD (not indexed): maximum $4,560 single and HOH / $5,840 MFJ and QSS / $2,920 MFS, reduced by 20% of provisional income over $69,250 / $88,630 / $44,315
SUBTRACTION = the GREATER of the two methods
## Indexing
The simplified-method thresholds are indexed (statutory base year 2023); the alternative-method amounts are not indexed.
## How to enter
- AGI below the threshold: enter the full Form 1040 line 6b amount (including federally taxable Tier 1 Railroad Retirement benefits) on Line 14
- AGI above: complete the 30-step Worksheet for Line 14 (step 28 alternative vs. step 29 simplified; step 30 the greater)
## Interaction
- Do not also subtract the same RRB benefits on Line 19
- Coordinated-member public pensions do not qualify for the public pension subtraction but their Social Security does qualify here
## Required Information
- Forms SSA-1099 and RRB-1099; Form 1040 lines 2a, 6a, 6b, 9; Schedule 1 lines 21 and 26
## Questions
- Do you receive Social Security, and what is your AGI?
## Common Errors
- Subtracting the gross benefit (Form 1040 line 6a) instead of the taxable amount (line 6b)
- Using only one method when AGI exceeds the threshold
## Prompt
- Does Minnesota tax Social Security in 2026?
