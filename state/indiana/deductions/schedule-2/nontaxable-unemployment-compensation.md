---
type: deduction
category: unemployment-compensation
jurisdiction: IN
tax_year: 2026
source_doc: Form 1099-G (enclose) / federal Form 1040, line 11 (federal AGI)
form: Schedule 2
line: "10"
via:
  - Unemployment Compensation Worksheet, line 7 → Schedule 2, Line 10 → Line 12 → Form IT-40, Line 4
routing:
  - "Single → worksheet line 3 = $12,000"
  - "Married filing jointly → worksheet line 3 = $18,000"
  - "Married filing separately and lived with spouse at any time during the year → worksheet line 3 = 0"
  - "Married filing separately and lived apart the entire year → worksheet line 3 = $12,000"
  - "Unemployment issued by the Railroad Retirement Board → code 624, not this worksheet"
see_also:
  - deductions/schedule-2/schedule-2.md
  - deductions/schedule-2/railroad-unemployment-sickness-benefits-deduction-624.md
  - deductions/schedule-2/repayment-of-previously-taxed-income-deduction-630.md
---
# Nontaxable Portion of Unemployment Compensation (Schedule 2, Line 10)
## Description
If you reported unemployment compensation on your federal return, part or all of it may be deductible in Indiana depending on federal AGI. Complete the Unemployment Compensation Worksheet; line 7 is the deduction. Enclose your Form(s) 1099-G.
## Unemployment Compensation Worksheet
```
1. Unemployment compensation included on IT-40, line 1 (exclude Railroad Retirement Board unemployment)
2. Federal adjusted gross income from federal Form 1040, line 11
3. Enter $12,000 if single, or $18,000 if married filing a joint return
4. Line 2 minus line 3; if zero or less, enter zero
5. One-half of line 4
6. Taxable unemployment compensation for Indiana: smaller of line 1 or line 5
7. Line 1 minus line 6 → Schedule 2, line 10
```
The $12,000 and $18,000 base amounts are 2025 amounts (2025 amount; confirm against the 2026 form).
## Married filing separately
- Lived with your spouse at any time during the year: enter zero on line 3.
- Lived apart from your spouse the entire year: enter $12,000 on line 3.
## Filing statuses not named
Line 3 names only "single" and "married filing a joint return" (plus the MFS note). The booklet does not separately address head of household or qualifying surviving spouse; confirm the treatment against the 2026 form.
## Examples
- Single, unemployment $6,000, federal AGI $20,000: line 4 = $8,000; line 5 = $4,000; line 6 = $4,000; line 7 = $2,000 deduction.
- Single, unemployment $8,000, federal AGI $30,000: line 4 = $18,000; line 5 = $9,000; line 6 = $8,000; line 7 = $0.
- Married filing jointly, unemployment $5,000, federal AGI $16,000: line 4 = $0; line 5 = $0; line 6 = $0; line 7 = $5,000, all deductible.
## Repayment interaction
If unemployment compensation deducted in an earlier year is later repaid, the earlier deduction is refigured and the repayment deduction (code 630) is reduced by the difference. See repayment-of-previously-taxed-income-deduction-630.md.
## Questions
- How much unemployment did you receive (Form 1099-G), and was any from the Railroad Retirement Board?
- What is your federal AGI?
- If married filing separately, did you live with your spouse at any time during the year?
## Common Errors
- Including Railroad Retirement Board unemployment on worksheet line 1 (use code 624)
- Using $12,000 on a separate return when the spouses lived together part of the year
- Entering the taxable amount (line 6) instead of the nontaxable amount (line 7)
- Not enclosing Form 1099-G
## Prompt
- Is my unemployment taxed in Indiana?
- How do I figure the Indiana unemployment deduction if I'm married filing separately?
