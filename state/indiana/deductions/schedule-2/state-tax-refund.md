---
type: deduction
category: state-tax-refund
jurisdiction: IN
tax_year: 2026
source_doc: Federal Schedule 1 (line 1 on the 2025 form) / Form 1099-G for the state refund
form: Schedule 2
line: "3"
via:
  - Federal Schedule 1, line 1 taxable state refund → Schedule 2, Line 3 → Line 12 → Form IT-40, Line 4
routing:
  - "Other recovered itemized deductions reported as federal other income → code 616, not line 3"
see_also:
  - deductions/schedule-2/schedule-2.md
  - deductions/schedule-2/recovery-of-deductions-616.md
  - deductions/federal-items-without-indiana-effect.md
---
# State Tax Refund Reported on Federal Return (Schedule 2, Line 3)
## Description
If you entered a state tax refund amount on federal Schedule 1, line 1 (2025 form line; confirm on the 2026 federal form), enter that amount here. The refund was included in federal AGI only because it was itemized federally in an earlier year; Indiana never allowed the deduction, so it removes the refund from Indiana income.
## What qualifies
- Only the amount actually included on federal Schedule 1, line 1.
- If none of the refund was taxable federally (for example, you took the standard deduction), there is nothing to deduct.
## Example
A refund of $640 of 2025 state income tax was received in 2026, and $640 is taxable on federal Schedule 1, line 1 (2025 amount; confirm against the 2026 form). Schedule 2, line 3 = $640.
## Questions
- Did you report a state or local tax refund on federal Schedule 1?
- How much of it was taxable federally?
## Common Errors
- Entering the full Form 1099-G amount when only part was taxable federally
- Putting other recovered itemized deductions on this line instead of code 616
## Prompt
- My state refund is taxable on my federal return. Is it taxed by Indiana?
