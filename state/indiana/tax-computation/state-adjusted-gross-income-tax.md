---
type: tax
category: state-tax
jurisdiction: IN
tax_year: 2026
source_doc: Completed Form IT-40, lines 1-7
form: Form IT-40
line: "8"
via:
  - Form IT-40, Line 7 (Indiana AGI) x 2.95% → Line 8 → Line 11 → Line 15
routing:
  - "Line 7 less than zero → leave line 8 blank"
see_also:
  - tax-computation/tax-computation.md
  - tax-computation/county-tax.md
  - deductions/deductions.md
---
# State Adjusted Gross Income Tax (Form IT-40, Line 8)
## Description
The state adjusted gross income tax is a flat rate applied to Indiana adjusted gross income (Form IT-40, line 7). For 2026 the rate is 2.95% (.0295). The 2025 Form IT-40 prints "multiply line 7 by 3% (.03)"; the 2026 form should print 2.95%. Departmental Notice #1 (effective October 1, 2026) confirms: "For 2026, the state adjusted gross income tax rate for individuals is 2.95%." If the answer is less than zero, leave line 8 blank.
## Computation
```
Line 1  Federal AGI
Line 2  + Indiana add-backs (Schedule 1)
Line 4  - Indiana deductions (Schedule 2)
Line 6  - Indiana exemptions (Schedule 3)
Line 7  = Indiana AGI
Line 8  = Line 7 x .0295, rounded to whole dollars
```
## Rate schedule (SEA 451-2025)
The 2025 Legislative Synopsis describes further possible reductions of 0.05 percentage point for taxable years after 2029, subject to revenue tests. They do not affect 2026.
## Related computations that use the 2025 rate
Schedules IT-2210A (line 6) and the IT-2210 part-year example print 3% for 2025; for the 2026 versions use 2.95%. Credits for taxes paid to other states figure the Indiana tax at the same rate (Income Tax Information Bulletin #128, Example 11: $50,000 x .0295 = $1,475).
## Example
Federal AGI $62,000; no add-backs; renter's deduction $3,000 (2025 amount; confirm against the 2026 form); exemptions $1,000. Line 7 = $58,000. Line 8 = $58,000 x .0295 = $1,711.
## Questions
- What is your Indiana adjusted gross income on line 7?
## Common Errors
- Using the 3% rate printed on the 2025 form for 2026
- Entering a negative amount instead of leaving line 8 blank
## Prompt
- What is Indiana's state income tax rate for 2026?
