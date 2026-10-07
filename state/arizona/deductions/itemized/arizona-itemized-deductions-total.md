---
type: deduction
category: itemized-total
jurisdiction: AZ
tax_year: 2026
source_doc: Form 1098 (mortgage interest and real estate tax) / property tax bills / Form W-2 box 17 and state tax payment records / charitable receipts / medical and dental receipts / mortgage credit certificate
form: Schedule A, Form 140
line: "Schedule A 9-15; Form 140 43, 43I"
via:
  - Line 9 = lines 3 + 5; line 10 = lines 4 + 6 + 7 + 8; line 11 federal itemized deductions allowed; line 12 = line 9; line 13 = line 11 + line 12; line 14 = line 10; line 15 = line 13 - line 14 → Form 140, line 43 (box 43I)
routing:
  - "Line 15 below zero → enter 0 (a negative entry delays processing)"
  - "No Arizona Schedule A needed → federal Schedule A total → line 43"
  - "Include a copy of federal Schedule A whenever itemizing"
see_also:
  - deductions/itemized/itemized.md
  - deductions/standard-deduction.md
---
# Arizona Itemized Deductions Total (Schedule A, Lines 9 to 15; Form 140, Line 43)
## Description
Lines 9 to 15 combine the adjustments with the federal total.
| Line | Entry |
|---|---|
| 9 | Line 3 + line 5 (increases) |
| 10 | Line 4 + line 6 + line 7 + line 8 (decreases) |
| 11 | Total federal itemized deductions allowed on the federal return |
| 12 | Amount from line 9 |
| 13 | Line 11 + line 12 |
| 14 | Amount from line 10 |
| 15 | Line 13 - line 14 = Arizona itemized deductions → Form 140, line 43; if less than 0, enter 0 |

For 2026, also apply the $10,000 limit on state and local taxes (salt-limit-2026.md) as the 2026 form directs.
## Example
Federal itemized $24,000; line 3 medical increase $6,000; line 6 credit contributions $1,409. Line 9 $6,000, line 10 $1,409, line 13 $30,000, line 15 $28,591 → line 43 (compare with the standard deduction).
## Notes
- The example has no state and local tax over $10,000; when there is, apply the 2026 limit first
- Arizona Schedule A, Form 140 and page 3 line numbers follow the 2025 forms; ADOR had not released the 2026 forms when this was revised, so confirm them against them
## Required Information
- Federal Schedule A (copy included with the return)
- Arizona Schedule A lines 1 to 8
## Questions
- What is your federal Schedule A total?
## Common Errors
- Entering a negative amount on line 43
- Forgetting to include the federal Schedule A copy
## Prompt
- How do I get my Arizona itemized deduction total?
