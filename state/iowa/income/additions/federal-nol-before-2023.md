---
type: income
category: additions
jurisdiction: IA
tax_year: 2026
source_doc: Federal Form 1040 Schedule 1, line 8a (net operating loss deduction) / federal NOL carryover worksheet from IRS Publication 536 showing the year each loss arose
form: Form IA 1040
line: "3"
via:
  - Federal NOL carryover worksheet (pre-2023 portion) → IA 124 → IA Schedule 1, line 10 column A → line 12 → line 13 → line 21 → Form IA 1040, line 3
---
# Federal Net Operating Loss Carried from Before 2023 (IA 124)
## Description
Addition that removes the part of the 2026 FEDERAL NOL deduction that came from a loss year beginning BEFORE January 1, 2023. Before 2023 Iowa computed its own NOLs from a different starting point, so the pre-2023 federal amount is added back and replaced with the separately tracked Iowa NOL on Schedule 1 line 17.

## Amount
- Add back the portion of the 2026 federal NOL deduction (Form 1040 Schedule 1 line 8a) attributable to losses arising in tax years beginning before January 1, 2023
- Federal NOLs from 2023 and later are NOT added back; Iowa follows them because the starting point is federal taxable income
- The pre-2023 Iowa NOL is then subtracted on Schedule 1 line 17 (see iowa-nol-before-2023.md)

## Notes
- Federal Schedule 1 line numbers cited here are from the 2025 form; the 2026 Schedule 1 was not available to verify, so confirm them when the final 2026 form is released
- This is a paired adjustment: line 10 (federal pre-2023 NOL, addition) and line 17 (Iowa pre-2023 NOL, subtraction). Filling only one side distorts Iowa taxable income
- Federal NOLs arising after 2017 are limited to 80% of taxable income; that federal limit is already reflected in the line 8a figure
- Include IA 124 with the return; it documents both the federal and Iowa carryforwards
- No 2026 Iowa law change. Line number follows the 2025 Schedule 1

## Required Information
- 2026 federal NOL deduction amount
- Federal NOL carryover schedule by loss year
- Remaining Iowa NOL carryforward from pre-2023 years

## Questions
- Did you claim a net operating loss deduction on your 2026 federal return?
- In what tax year did each loss arise?
- Do you also have an Iowa NOL carryforward from before 2023?

## Common Errors
- Adding back a 2023-or-later federal NOL
- Entering the line 10 addition without the matching line 17 Iowa NOL subtraction
- Using the original loss amount instead of the amount actually deducted in 2026

## Prompt
- I am carrying forward a business loss from 2021.
- How does Iowa handle my federal net operating loss deduction?
