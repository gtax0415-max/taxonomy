---
type: credit
jurisdiction: MA
tax_year: 2026
category: income-based
source_doc: Massachusetts Form 1 Line 27 Massachusetts AGI Worksheet (built from Form 1 Line 10, Schedule Y Lines 2-10, Schedule B Line 35, Schedule D Line 19) / Form 1 Line 2b (number of dependents)
form: Massachusetts Form 1
line: "29"
refundable: no
via:
  - Form 1, Line 27 Massachusetts AGI Worksheet → Form 1, Line 29 Worksheet → Form 1, Line 29
routing:
  - "Massachusetts AGI at or under the No Tax Status threshold → fill in Line 27 oval, enter 0 on Line 28, skip Lines 29-31 (No Tax Status)"
  - "Massachusetts AGI above No Tax Status but at or under the Limited Income Credit ceiling → Line 29 worksheet → Form 1, Line 29"
  - "Married filing separately → neither No Tax Status nor the Limited Income Credit is available"
---
# Limited Income Credit (and No Tax Status)
## Description
Nonrefundable Massachusetts credit that caps tax for low-income filers at 10% of the amount by which Massachusetts AGI exceeds the No Tax Status threshold. It is an alternative tax calculation, not a percentage of anything spent. Purely a state credit — there is no federal counterpart.
## Two tiers
1. NO TAX STATUS (Line 27): AGI at or under the threshold → tax is ZERO, no worksheet needed
2. LIMITED INCOME CREDIT (Line 29): AGI above the No Tax Status threshold but under the ceiling → tax is limited
## 2026 thresholds
These amounts are STATUTORY and NOT inflation-indexed; they are unchanged from 2025 and expected to carry into 2026. Confirm against the 2026 Form 1 instructions when released.
| Filing status | No Tax Status (at or under) | Limited Income Credit ceiling (at or under) |
|---|---|---|
| Single | $8,000 | $14,000 |
| Head of household | $14,400 + $1,000 per dependent | $25,200 + $1,750 per dependent |
| Married filing jointly | $16,400 + $1,000 per dependent | $28,700 + $1,750 per dependent |
| Married filing separately | NOT ELIGIBLE | NOT ELIGIBLE |
Single filers get NO dependent add-on.
## Calculation (Line 29 Worksheet)
1. Massachusetts AGI (Line 27 worksheet, Line 7)
2. No Tax Status threshold ($8,000 single; $14,400 + $1,000 × dependents HOH; $16,400 + $1,000 × dependents joint)
3. Line 1 minus Line 2
4. Form 1, Line 28 tax, LESS any credit recapture (Line 25) and installment-sale additional tax (Line 26)
5. Line 3 × 10%
6. If Line 4 is larger than Line 5, the credit is Line 4 minus Line 5. Otherwise 0
## Massachusetts AGI for this purpose
Not federal AGI. Built on the Line 27 worksheet:
- 5.0% income (Form 1, Line 10), adding back any Abandoned Building Renovation deduction
- minus Schedule Y Lines 2-9b and 10 (certain above-the-line deductions)
- plus interest, dividends and short-term gains (Schedule B, Line 35, or Form 1, Line 20)
- plus long-term capital gains (Schedule D, Line 19, not less than 0)
Personal exemptions are NOT subtracted.
## Notes
- Recapture tax (Line 25) and installment-sale tax (Line 26) are NOT eliminated by No Tax Status — enter them on Line 28 and complete Line 31
- The same AGI worksheet determines eligibility for the College Tuition Deduction (Schedule Y, Line 11)
- Applied BEFORE the other-jurisdiction credit; the Line 30 worksheet subtracts it
## Required Information
- Filing status and number of dependents (Form 1, Line 2b)
- Form 1, Line 10, Schedule Y, Schedule B and Schedule D amounts
- Form 1, Line 28 tax, Line 25 and Line 26
## Questions
- What is your filing status, and how many dependents do you claim?
- What was your total Massachusetts income, including interest, dividends and capital gains?
- Do you owe any credit recapture or installment-sale tax?
## Common Errors
- Using federal AGI instead of the Line 27 Massachusetts AGI worksheet
- Applying the dependent add-on to a single filer
- Claiming it while married filing separately
- Wiping out credit recapture or installment-sale tax under No Tax Status
## Prompt
- I made very little this year. Do I still owe Massachusetts tax?
- What is Massachusetts No Tax Status?
