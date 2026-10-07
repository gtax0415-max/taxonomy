---
type: deduction
category: itemized-taxes
jurisdiction: AZ
tax_year: 2026
source_doc: Federal Schedule A state and local income tax amounts before and after the federal limit / Arizona credit forms for amounts paid as state income tax and used for a credit
form: Schedule A
line: "7; Schedule A 1A-7A"
via:
  - Worksheet: 1A state income taxes before the federal limit; 2A amount used for an Arizona credit; 3A = 1A - 2A; 4A federal limit; 5A = smaller of 3A or 4A; 6A state income taxes claimed after the limit; 7A = 6A - 5A → Schedule A, line 7 → line 10
routing:
  - "Deducted sales taxes instead of income taxes federally → no adjustment; go to line 8"
  - "Deducted income taxes, including amounts used for an Arizona credit → complete the worksheet"
  - "2026: Arizona's own $10,000 limit on state and local taxes also applies"
see_also:
  - deductions/itemized/salt-limit-2026.md
  - deductions/itemized/charitable-contributions-credit-adjustment.md
---
# Adjustment to State Income Taxes (Schedule A, Line 7; Worksheet 1A to 7A)
## Description
A.R.S. 43-1042 requires itemized deductions to be reduced for amounts used to claim an Arizona credit even if the amount was deducted federally as state income taxes paid rather than as a charitable contribution (for example, a credit contribution made by payroll withholding counted as tax). If you deducted sales taxes instead of income taxes on federal Schedule A, no adjustment is needed. Otherwise, use the page 2 worksheet:
| Line | Entry |
|---|---|
| 1A | Total state income taxes on federal Schedule A before applying the federal limitation |
| 2A | Amount included in line 1A for which you claimed an Arizona credit |
| 3A | Line 1A - line 2A |
| 4A | Limit from federal Schedule A: for 2026, $40,400 ($20,200 married filing separate), reduced by 30% of modified AGI over $505,000 ($252,500 separate) but not below $10,000 ($5,000 separate). The 2025 form printed $40,000 / $20,000 |
| 5A | Smaller of line 3A or line 4A |
| 6A | Total state income taxes claimed on federal Schedule A after the limitation |
| 7A | Line 6A - line 5A = Arizona adjustment → Schedule A, line 7 |

For 2026 the federal limit is $40,400 / $20,200, but Arizona separately limits the itemized deduction for state and local taxes to $10,000 (salt-limit-2026.md). Because the Arizona limit is lower, it is the one that binds for Arizona; how the 2026 form combines it with line 4A will be set by the 2026 form.
## Example (2026)
State income taxes $9,000 before the limit, of which $500 was used for an Arizona credit; 2026 federal limit $40,400 and Arizona limit $10,000; $9,000 claimed after the federal limit. 3A = $8,500, 4A = $10,000 (the lower Arizona limit), 5A = $8,500, 7A = $9,000 - $8,500 = $500 → line 7 = $500. Because total state and local taxes are under $10,000, the result is the same whichever limit the 2026 form uses on line 4A.
## Notes
- Statutory basis for the $10,000 limit: A.R.S. 43-1042: for taxable years beginning after December 31, 2025, the taxpayer may deduct up to $10,000 of the federal itemized deduction for state and local taxes allowed under IRC 164(b)(7), in lieu of the federal amount
- Arizona Schedule A, Form 140 and page 3 line numbers follow the 2025 forms; ADOR had not released the 2026 forms when this was revised, so confirm them against them
## Required Information
- Federal Schedule A state and local tax amounts, before and after the federal limit
- Arizona credit forms for amounts paid as state tax and used for a credit
## Questions
- Did you deduct state income taxes or sales taxes on federal Schedule A?
- Was any amount you counted as state tax also used for an Arizona credit?
## Common Errors
- Skipping line 7 when a credit amount was deducted as tax
- Completing the worksheet when sales tax was deducted
## Prompt
- Why does Arizona reduce my state tax deduction?
