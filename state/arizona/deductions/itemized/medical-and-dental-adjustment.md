---
type: deduction
category: itemized-medical
jurisdiction: AZ
tax_year: 2026
source_doc: Medical and dental receipts and insurance explanation-of-benefits statements (net of reimbursements) / Form W-2 box 1 and employer cafeteria plan statements (premiums paid pre-tax)
form: Schedule A
line: "1, 2, 3, 4"
via:
  - Line 1 total medical and dental expenses; line 2 federal allowed medical deduction; line 3 = line 1 - line 2 if line 1 is the same or more; line 4 = line 2 - line 1 if line 2 is more → line 9 (line 3) or line 10 (line 4)
routing:
  - "Expenses not allowed federally because of the AGI floor → added back through line 3"
  - "Cafeteria plan premiums and expenses not in W-2 box 1 → excluded from line 1"
  - "Self-employed health insurance deducted in federal AGI → excluded from line 1"
see_also:
  - deductions/itemized/itemized.md
  - deductions/itemized/arizona-itemized-deductions-total.md
---
# Medical and Dental Expenses Adjustment (Schedule A, Lines 1 to 4)
## Description
Arizona does not reduce medical expenses by a percentage of federal AGI, so in most cases the Arizona deduction is larger than the federal one. Lines 1 to 4 add back expenses not allowed federally because of the limitation. Skip them if you are not deducting medical expenses.
## Lines
| Line | Entry |
|---|---|
| 1 | Total medical and dental expenses, excluding amounts paid by insurance or other sources; excluding premiums and other expenses paid through an employer cafeteria plan unless included in W-2 box 1; excluding self-employed health insurance deducted in federal AGI |
| 2 | Medical expenses allowed as a federal itemized deduction |
| 3 | If line 1 is the same as or more than line 2, line 1 - line 2 (→ line 9) |
| 4 | If line 2 is more than line 1, line 2 - line 1 (→ line 10) |
## Example
Unreimbursed medical expenses $9,000; federal AGI $80,000, so the federal deduction is $9,000 - (7.5% x $80,000 = $6,000) = $3,000. Line 1 $9,000, line 2 $3,000, line 3 $6,000.
## Notes
- A.R.S. 43-1042 still allows the full amount of medical expenses for 2026, with no AGI floor
- Arizona Schedule A, Form 140 and page 3 line numbers follow the 2025 forms; ADOR had not released the 2026 forms when this was revised, so confirm them against them
## Required Information
- Medical and dental receipts, net of insurance and reimbursements
- Federal Schedule A medical lines
- Form W-2 box 1 (to identify cafeteria plan amounts)
## Questions
- What were your total unreimbursed medical and dental costs?
- Were any premiums paid pre-tax through an employer plan?
## Common Errors
- Including cafeteria plan premiums on line 1
- Entering only the federal deduction on line 1
## Prompt
- Can I deduct medical expenses in Arizona that didn't count federally?
