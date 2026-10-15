---
type: filing
category: filing
jurisdiction: UT
tax_year: 2026
source_doc: 2026 federal Form 1040 (standard deduction allowed, filing status) / federal Schedule 1-A, line 37 (enhanced senior deduction), if filed
form: Form TC-40
line: "19"
via:
  - TC-40 line 7 vs. federal standard deduction + Schedule 1-A line 37 → Qualified Exempt Taxpayer Worksheet → "X" on Form TC-40, line 19 → line 20 = 0
---
# Qualified Exempt Taxpayer
## Description
A taxpayer whose Utah taxable income is at or below their federal standard deduction (plus the federal senior deduction) owes no Utah income tax.

## 2026 Change
HB 60 (2025 General Session), first effective for 2026: the test now compares Utah TAXABLE income (line 7), not federal AGI.

## Worksheet
1. TC-40, line 7
2. Federal standard deduction WITHOUT the age/blindness additions:
   - Single $16,100
   - Head of household $24,150
   - Married filing jointly $32,200
   - Married filing separately $16,100 (or $0 if the spouse itemized)
   - Qualifying surviving spouse $32,200
   - If the standard deduction was limited (dependent filer), the amount allowed federally
   - 1040-NR filers: 0
3. Federal enhanced senior deduction from Schedule 1-A, line 37 (0 if none)
4. Line 2 + line 3
5. Line 1 − line 4, not less than zero
- If line 5 is zero: exempt → "X" on line 19, and line 20 = 0
- Otherwise leave line 19 blank

## Notes
- Exemption applies whether the filer itemized or not; the test uses the standard deduction amount
- Exempt filers still complete the rest of the return (refundable credits, withholding refunds)

## Required Information
- Line 7, filing status, standard deduction allowed, Schedule 1-A line 37

## Questions
- What filing status do you use?
- Can someone claim you as a dependent?
- Did you claim the federal senior deduction?

## Common Errors
- Using federal AGI instead of Utah taxable income (old rule)
- Adding the age/blindness additional standard deduction
- Using $16,100 for MFS when the spouse itemized

## Prompt
- My income is low — do I owe any Utah tax?
