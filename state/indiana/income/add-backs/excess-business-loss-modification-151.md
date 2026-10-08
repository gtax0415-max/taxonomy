---
type: income
category: add-back
jurisdiction: IN
tax_year: 2026
source_doc: Federal Form 461 / federal Schedule 1 (Form 1040), excess business loss line
form: Schedule 1
line: "6 (code 151)"
via:
  - Indiana add-backs inside a loss disallowed under IRC 461(l) → full add-backs on their own lines, then the lesser of those add-backs or the 461(l) disallowance → Schedule 1, Line 6, code 151 (negative) and Schedule NOL-MOD, Part 2 → reduces the Indiana NOL carryforward
routing:
  - "Current-year excess business loss under IRC 461(l) and Indiana add-backs (bonus depreciation, Section 179, state taxes) within the disallowed deductions → code 151 deduction"
  - "Add-backs larger than the 461(l) disallowance → code 151 limited to the disallowance"
  - "Prior-year Indiana modifications (for example bonus catch-up) → not code 151"
see_also:
  - income/add-backs/add-backs.md
  - income/add-backs/bonus-depreciation-add-back.md
  - income/add-backs/section-179-add-back.md
  - income/add-backs/tax-add-back.md
  - income/add-backs/net-operating-loss-add-back.md
---
# Modifications for Excess Business Losses (Schedule 1, Line 6, Code 151)
## Description
Use code 151 if you have a current-year excess business loss under IRC 461(l) that is not deducted in federal AGI, and current-year federal deductions disallowed in federal AGI for which Indiana requires an add-back. The most common are bonus depreciation, IRC 179 expensing, and state and local taxes deducted in figuring federal AGI. Do not report modifications arising from prior-year Indiana modifications such as bonus depreciation catch-up.
## How to report
1. Report the add-backs normally, as if no 461(l) limit applied.
2. Report the lesser of those add-backs or the 461(l) disallowance (federal Schedule 1, line 8p on the 2025 form) as a code 151 deduction (negative).
3. Report the same amount on Schedule NOL-MOD, Part 2. The code 151 deduction reduces the Indiana NOL carryforward.
## Examples (2025 booklet)
- Bob: federal AGI $100,000 ($370,000 salary, $270,000 allowable partnership loss); $300,000 excess business loss disallowed; bonus depreciation add-back $80,000. Report $80,000 on line 4 and -80,000 with code 151. The current-year NOL is reduced to $220,000.
- Same facts but the bonus add-back is $320,000: report $320,000 on line 4; code 151 is limited to the $300,000 excess business loss. The current-year NOL is zero.
## Questions
- Did you file Form 461 with a disallowed excess business loss?
- Which Indiana add-backs (bonus depreciation, Section 179, state taxes) are inside the disallowed loss?
## Common Errors
- Netting the add-back and code 151 into one entry
- Exceeding the 461(l) disallowance
- Omitting Schedule NOL-MOD, Part 2
## Prompt
- I have an excess business loss and a bonus depreciation add-back. How does Indiana handle it?
