---
type: income
category: add-back
jurisdiction: IN
tax_year: 2026
source_doc: Federal Schedule 1 (Form 1040), net operating loss line (line 8a on the 2025 form) / federal NOL carryover worksheet / Indiana Schedule IT-40NOL for each loss year
form: Schedule 1
line: "2"
via:
  - Federal NOL deduction (federal Schedule 1, "Other income" line, entered as a negative) → Schedule 1, Line 2 as a positive figure → Line 7 → Form IT-40, Line 2
  - Indiana NOL allowed → Schedule 2, Line 9 (Schedule IT-40NOL)
routing:
  - "Federal NOL deduction claimed → add back the full amount as a positive number"
  - "No federal NOL deduction → leave line 2 blank"
  - "Indiana NOL available → claim separately on Schedule 2, line 9"
see_also:
  - income/add-backs/add-backs.md
  - income/add-backs/debt-discharge-nol-reduction-155.md
  - income/add-backs/excess-business-loss-modification-151.md
  - income/add-backs/excess-inclusion-income-153.md
---
# Net Operating Loss Add-Back (Schedule 1, Line 2)
## Description
Any net operating loss (NOL) deduction reported on the federal return must be added back. Write the amount as a positive figure. Indiana computes its own NOL (Schedule IT-40NOL, one per loss year) and allows it as a deduction on Schedule 2, line 9.
## Line reference
The 2025 Schedule 1 form describes line 2 as the "Net operating loss carryforward from federal Form 1040, 'Other income' line." The booklet text says federal Schedule 1, line 8, and a note placed beside it says to leave the line blank if no NOL deduction was reported on line 8a of federal Schedule 1. Line 8a is the NOL line on the 2025 federal Schedule 1; confirm the line on the 2026 federal form.
## Indiana NOL rules (for context)
- Indiana NOLs may be carried forward up to 20 years after the loss year; no carryback claim may be filed after Dec. 31, 2011.
- For tax years 2021 and later, itemized deductions are not permitted in determining an Indiana NOL.
- Indiana modifications can create an Indiana NOL even when there is no federal NOL.
## Example
Federal Schedule 1, line 8a shows -18,000 (an NOL carryforward). Schedule 1, line 2 = 18000. If Schedule IT-40NOL shows an Indiana carryforward of $16,500 available, that amount goes on Schedule 2, line 9.
## Questions
- Did you deduct a net operating loss on your 2026 federal return? How much?
- Do you have Indiana NOL carryforwards and Schedule IT-40NOL for each loss year?
## Common Errors
- Entering the add-back as a negative number
- Assuming the federal NOL and Indiana NOL are the same amount
- Forgetting to claim the Indiana NOL on Schedule 2 after adding back the federal one
## Prompt
- I have a federal NOL carryforward. What does Indiana do with it?
