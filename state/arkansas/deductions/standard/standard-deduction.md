---
type: tax
category: standard
jurisdiction: AR
tax_year: 2026
source_doc: Computed from filing status (no separate source document)
form: Form AR1000F
line: "27"
via:
  - Filing status → standard deduction → Form AR1000F, line 27 (larger of standard or AR3) → line 28
---
# Standard Deduction
## Description
A flat deduction per taxpayer, used when it is larger than itemized deductions. Not used with the Low Income Tax Tables, which build it in.

## Amounts
- 2025: $2,470 per taxpayer; $4,940 for Status 2; $2,470 in each column for Status 4
- 2026: NOT YET PUBLISHED. The amount is indexed annually (3% cap):
  - The template uses $2,540 per taxpayer ($5,080 Status 2), the indexed estimate
  - DFA's 2026 withholding formula (effective pay period 15, 2026) still uses $2,470
  - Use the template estimate until DFA publishes the 2026 figure, then update
- Cannot exceed AGI (line 25)

## Notes
- Use the larger of the standard deduction or AR3 itemized deductions
- Status 4 and 5: if one spouse itemizes, both must

## Required Information
- Filing status
- Itemized deduction total from AR3, to compare
- Status 4/5: whether the spouse itemizes

## Questions
- Are your itemized deductions more than the standard deduction?
- What is your filing status?
- Is your spouse itemizing (Status 4 or 5)?

## Common Errors
- Using the 2025 $2,470 without checking the 2026 figure
- Taking the standard deduction while the spouse itemizes (Status 4/5)
- Taking it with a Low Income Tax Table

## Prompt
- What is the Arkansas standard deduction for 2026?
- Should I take the standard deduction in Arkansas?
