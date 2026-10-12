---
type: income
category: federal-agi
jurisdiction: LA
tax_year: 2026
source_doc: 2026 federal Form 1040, Line 11b (adjusted gross income) as filed
form: Form IT-540
line: "7; Schedule E Line 1"
via:
  - Federal Form 1040, Line 11b → Form IT-540, Line 7 (no Schedule E)
  - Federal Form 1040, Line 11b → Schedule E, Line 1 → Schedule E, Line 5 → Form IT-540, Line 7 (Schedule E box marked)
---
# Federal Adjusted Gross Income (Starting Point)
## Description
The Louisiana return starts from federal AGI. With no Louisiana additions or exemptions it goes straight to IT-540 Line 7; otherwise it starts Schedule E and Louisiana AGI from Schedule E Line 5 goes on Line 7.

## Rules
- Use federal Form 1040 Line 11b (the 2025 form split AGI into Lines 11a and 11b; the IRS's draft 2026 form keeps that layout)
- On IT-540 Line 7, a negative amount is entered as 0
- On Schedule E Line 1, a negative AGI is entered without a minus sign and the loss box is marked
- When Schedule E is used, mark the Schedule E box on Line 7

Example: federal AGI $52,300, no Louisiana adjustments → $52,300 on Line 7.

## Notes
- Several 2026 federal changes (for example, new federal deductions taken after AGI) do not affect this line, because Louisiana starts from AGI, not taxable income
- Line numbers are from the 2025 forms; confirm on the 2026 forms

## Required Information
- Federal AGI as filed

## Questions
- What is your federal AGI on Form 1040?
- Do you have any Louisiana additions or exempt income?

## Common Errors
- Entering federal taxable income
- Entering a negative number on Line 7
- Using Schedule E without marking the box

## Prompt
- Where does the Louisiana return start?
