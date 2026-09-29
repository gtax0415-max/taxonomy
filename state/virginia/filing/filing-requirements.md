---
type: filing
category: filing-requirement
jurisdiction: VA
tax_year: 2026
source_doc: Completed federal return (adjusted gross income) / Forms W-2, W-2G, 1099 and VK-1 showing Virginia withholding / Form 760ES or online records of estimated payments
form: Form 760
line: "9"
via:
  - Form 760, Lines 1-8 → Form 760, Line 9 (VAGI) → compared with the filing threshold for the filing status
routing:
  - "VAGI at or above the threshold → file and compute tax on Lines 10-18"
  - "VAGI below the threshold → tax is $0; file only to get a refund: complete Lines 10-15, enter 0 on Lines 16 and 18, then complete Lines 19-36"
  - "Part-year resident → Form 760PY; nonresident with Virginia source income → Form 763 (see residency-status.md)"
see_also:
  - filing/residency-status.md
  - filing/filing-status.md
  - filing/dependent-on-anothers-return.md
  - tax-computation/tax-rate-schedule.md
  - income/income.md
---
# Who Must File (Form 760, Line 9)
## Description
Every Virginia resident whose Virginia adjusted gross income (VAGI) is at or above the minimum threshold for the filing status must file. The test uses VAGI from Form 760, Line 9, not federal gross income or federal AGI, so the Virginia subtractions (age deduction, Social Security, state refund, Schedule ADJ subtractions) are applied before the test. A resident below the threshold owes no Virginia tax but must still file to get back any Virginia withholding or estimated tax.
## 2026 filing thresholds
| Filing status | Must file if VAGI is |
|---|---|
| 1 Single | $11,950 or more |
| 2 Married filing jointly | combined VAGI of $23,900 or more |
| 3 Married filing separately | $11,950 or more |
The same figures are printed on Form 760, Line 9: "If less than $11,950 for Filing Status 1 or 3; or $23,900 for Filing Status 2, your tax is $0.00."
The filing threshold for a single individual also applies to dependent children (2025 Form 760F instructions; confirm against the 2026 form).
## How to test
1. Complete Form 760, Lines 1 through 9 to find VAGI.
2. Compare Line 9 with the threshold for the filing status.
3. At or above the threshold: complete the rest of the return normally.
4. Below the threshold: the tax is $0.00. Do not use the tax rate schedule or tax table. To claim a refund, complete Lines 10 through 15, enter "0" on Lines 16 and 18, then complete Lines 19 through 36.
## Filing to get a refund
A taxpayer below the threshold is entitled to a refund of any Virginia withholding or estimated tax paid, but only by filing a return. Common cases: a student or part-time worker with Virginia tax withheld from wages, or a retiree whose Social Security and age deduction bring VAGI below the threshold.
## Interaction with other lines
- VAGI drives the age deduction worksheet, the Credit for Low-Income Individuals (family VAGI) and the Spouse Tax Adjustment (separate VAGI for each spouse)
- A taxpayer who is not required to file is also not required to complete Form 760C or Form 760F (2025 forms)
## Questions
- What was your federal adjusted gross income, and do any Virginia subtractions apply?
- Did you have Virginia income tax withheld or make estimated payments, even though your income was low?
- Can someone else claim you as a dependent?
- Are you filing jointly or separately with your spouse?
## Common Errors
- Testing federal AGI or gross income instead of VAGI (Line 9)
- Not filing when below the threshold and losing a refund of withholding
- Computing tax from the rate schedule when VAGI is below the threshold; the tax is $0
- Using the joint $23,900 threshold on a Filing Status 3 return
## Prompt
- I only made about $10,000 last year; do I need to file in Virginia?
- My employer took Virginia tax out of my paycheck but I barely earned anything.
- I'm retired and live on Social Security; do I have to file a Virginia return?
