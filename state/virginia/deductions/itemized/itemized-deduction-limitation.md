---
type: deduction
category: itemized-deduction
jurisdiction: VA
tax_year: 2026
source_doc: Federal Form 1040 (federal filing status and adjusted gross income) / federal Schedule A (Form 1040) and the documents behind it (W-2 state withholding, Form 1098, real estate and personal property tax bills, charity acknowledgments, Form 4684, W-2G and gambling records) / Form 4952 for investment interest / records of income added back for modified adjusted gross income (Form 2555, Form 4563) for the SALT cap phase-down
form: Virginia Schedule A
line: "17-18"
via:
  - Limited Itemized Deduction Worksheet, Part A, Line 12a (or 12b) → Virginia Schedule A, Line 17
  - Limited Itemized Deduction Worksheet, Part B, Line 15 → Virginia Schedule A, Line 18
  - Virginia Schedule A, Line 17 - Line 18 → Line 19 → Form 760, Line 10
routing:
  - "Form 760 Line 1 (or Conformity FAGI) at or below the threshold → Line 17 = sum of Lines 4, 7, 10, 14, 15, 16c; Line 18 = Line 5a income tax + Line 6 foreign income tax"
  - "Over the threshold → enter no more than the SALT cap amount on Line 5a, complete the worksheet; Line 17 = Line 12a or 12b; Line 18 = Part B, Line 15"
see_also:
  - deductions/itemized/itemized.md
  - deductions/itemized/taxes-paid.md
  - deductions/itemized/medical-and-dental-expenses.md
---
# Itemized Deduction Limitation and Income Tax Reduction (Virginia Schedule A, Lines 17-18)
## Description
Virginia keeps the overall limitation on itemized deductions (the Pease limitation), which was suspended for federal purposes and has now been replaced federally. Virginia does not follow the federal replacement, the 2/37 reduction under the new IRC § 68 (HB 29, Chapter 7; Tax Bulletin 26-1; 2026 Legislative Summary). Higher-income taxpayers reduce their itemized deductions by the smaller of 3% of income over a threshold or 80% of the deductions subject to the limit. Line 18 then removes state, local and foreign income taxes, in proportion when the limitation applies. Taxpayers subject to the limitation must apply the federal SALT cap amount to Line 5a.
## Thresholds (use federal filing status)
| Federal filing status | 2025 (confirmed) | 2026 (estimated) |
|---|---|---|
| Married filing jointly or qualifying surviving spouse | $399,200 | $408,900 |
| Head of household | $365,950 | $374,800 |
| Single | $332,700 | $340,750 |
| Married filing separately | $199,600 | $204,450 |

The 2025 amounts are from the 2025 Virginia Schedule A instructions. The 2026 amounts are an inflation estimate; Virginia Tax has not published them. Confirm them against the 2026 Schedule A instructions.

Compare Form 760, Line 1 (or Line 5 of the Conformity Worksheet, if there are conformity adjustments) with the threshold.
## Limited Itemized Deduction Worksheet, Part A
Complete after Schedule A Lines 1-16. Lines 1-11 are completed as though a full-year Virginia resident.
1. Total of Schedule A Lines 4, 5a, 5b, 5c, 6, 10, 14, 15 and 16c (Line 5a already no more than the SALT cap amount)
2. Total of Lines 4, 9 and 15, plus gambling losses on Line 16a
3. Line 1 - Line 2 (if zero or less, the limitation does not apply)
4. Line 3 x 80%
5. Form 760, Line 1 (or Conformity Worksheet Line 5)
6. Threshold from the table
7. Line 5 - Line 6 (if zero or less, the limitation does not apply)
8. Line 7 x 3%
9. Smaller of Line 4 or Line 8
10. Line 3
11. Line 9 divided by Line 10, to 3 decimal places
12a. Residents and nonresidents: Line 1 - Line 9 → Schedule A, Line 17
12b. Part-year residents (Form 760PY): resident-period deductions only: (1) total of Lines 4, 5a, 5b, 5c, 6, 10, 14, 15, 16c; (2) Lines 5a, 5b, 5c, 6, 8e, 14 and 16c (minus gambling losses) x Line 11; (3) (1) - (2) → Line 17
## Part B: income tax modification
13. State and local income tax from Schedule A, Line 5a (the lesser of Line 5a or the SALT cap amount; part-year residents only the amount paid while a resident; include foreign income tax per the instructions)
14. Line 13 x Line 11
15. Line 13 - Line 14 → Schedule A, Line 18
## SALT cap amount
For 2026 the federal cap is $40,400 ($20,200 married filing separately). It is reduced by 30% of modified adjusted gross income over $505,000 ($252,500 married filing separately), but not below $10,000 ($5,000). Virginia Tax's May 28, 2026 guidance says to apply the cap to the amount entered on Schedule A, Line 5a, not downstream on this worksheet; otherwise the return may not process correctly. Lines 1, 12(b) and 13 then pick up the capped Line 5a.
## Starting amounts
Use the federal itemized deductions before the federal 2/37 reduction, which Virginia does not apply. The 2026 federal rules that change individual deductions do carry over: the 0.5% charitable floor, 90% gambling losses, mortgage insurance premiums and state-declared disaster losses.
## Different federal and Virginia filing status
Complete Lines 1-11 using the federal filing status as a full-year resident, skip 12a, and complete 12b with the itemized deductions that may be claimed on the Virginia Schedule A; then complete Lines 14-15.
## Example (single, no conformity adjustments, using the estimated 2026 threshold)
- **Inputs:** Form 760, Line 1 = $500,000. MAGI is below $505,000, so the full $40,400 cap applies.
- **Schedule A:** Line 5a income tax $30,000 (under the cap); Line 5b $10,000; Line 10 $20,000 (no investment interest); Line 14 $6,000. Total = $66,000.
- **Part A:**
  - Line 3 = $66,000
  - Line 4 = $52,800
  - Line 7 = $159,250
  - Line 8 = $4,777.50
  - Line 9 = $4,777.50
  - Line 11 = 0.072
  - Line 12a = $61,222.50 → Line 17
- **Part B:** $30,000 x 0.072 = $2,160; Line 15 = $27,840 → Line 18.
- **Result:** Line 19 = $33,382.50, rounded to whole dollars on the return.
## Required Information
- Federal filing status and federal adjusted gross income
- Any conformity adjustments, for Conformity FAGI
- Federal itemized deductions by category, before any federal 2/37 reduction
- Medical, investment interest, casualty and gambling loss amounts (not reduced)
- State and local income tax paid and modified adjusted gross income, for the SALT cap
- Residency dates, for part-year residents
## Questions
- What is your federal filing status and federal AGI?
- Do you have conformity adjustments?
- How much of your Schedule A is medical, investment interest, casualty or gambling losses?
- What is your MAGI for the SALT cap phase-down?
## Common Errors
- Using Virginia filing status instead of federal filing status for the threshold
- Using the 2025 thresholds, or treating the estimated 2026 thresholds as final
- Applying the SALT cap only inside the worksheet instead of on Line 5a
- Starting from federal itemized deductions after the federal 2/37 reduction
- Reducing medical, investment interest, casualty or gambling losses
- Entering full Line 5a on Line 18 when the worksheet applies (use Part B, Line 15)
- Rounding Line 11 to other than 3 decimal places
## Prompt
- Does Virginia still limit itemized deductions for high earners?
- My income is over $400,000. How do I figure my Virginia Schedule A?
- Does Virginia use the new federal 35% cap on itemized deductions?
