---
type: filing
category: filing-status-residency
subtype: residency
jurisdiction: GA
tax_year: "2026"
source_doc: Dates of Georgia residency during the year / income by source (Georgia vs everywhere) split into Columns A/B/C / the Schedule 3 ratio computation
form: Form 500
line: "Schedule 3 (Lines 9-14)"
refundable: n/a
via:
  - Form 500 Schedule 3 → Georgia taxable income for part-year residents and nonresidents
---
# Residency and Schedule 3 (Georgia)
## Description
Residency type determines the computation path. Full-year residents use the Form 500 main lines; part-year residents and nonresidents SKIP Lines 9–14 and use Schedule 3 to prorate income, deductions, and exemptions to the Georgia portion.
## The three residency types
- Full-year resident: taxed on all income regardless of source; uses Form 500 Lines 9–14
- Part-year resident: resident for part of the year; uses Schedule 3
- Nonresident: not a resident but with Georgia-source income; uses Schedule 3
## How Schedule 3 works
- Columns A/B/C split income: Column A = income as if a full-year Georgia resident; Column B = income not taxable to Georgia; Column C = Georgia taxable income (A must equal B + C)
- Line 9 ratio = Column C ÷ Column A (Georgia income as a share of total)
- The ratio cannot be negative and cannot exceed 100%; it is 100% if both adjusted federal and Georgia AGI are zero or negative, and 100% if adjusted federal AGI is zero/negative (full exemption and deductions apply)
- Standard/itemized deductions and the dependent exemption are prorated by the Line 9 ratio (Lines 10–14)
## What gets prorated
The retirement income exclusion (earned and unearned portions separately), itemized deductions, the other-state credit for part-year residents, and the dependent exemption all prorate through this ratio. Most items across this taxonomy carry a matching "part-year/nonresident must prorate" note.
## Required Information
- Dates of Georgia residency
- Income by source split into Columns A/B/C
- The Schedule 3 ratio
## Questions
- Were you a Georgia resident for the whole year, part of it, or none?
- What portion of your income is from Georgia sources?
- Did you move into or out of Georgia during the year?
## Common Errors
- A part-year/nonresident using Form 500 Lines 9–14 instead of Schedule 3
- Column A not equaling Column B plus Column C
- Entering a negative or over-100% ratio
- Failing to prorate the retirement exclusion's earned and unearned portions separately
## Prompt
- I moved to Georgia in the middle of the year.
- I live in another state but work in Georgia.
- How do I figure my Georgia income as a part-year resident?
## Related
- Retirement exclusion proration — see income/subtractions/retirement-income-exclusion.md
- Itemized deduction proration — see deductions/items/itemized-deductions.md
