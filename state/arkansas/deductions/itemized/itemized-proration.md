---
type: tax
category: itemized
jurisdiction: AR
tax_year: 2026
source_doc: Computed from each spouse's Arkansas AGI and the AR3 total (no separate source document); Status 5: the spouse's AGI from the spouse's own records
form: Form AR1000F
line: "27"
via:
  - AR3, lines 31–33 (AGI ratio) → line 34 → Form AR1000F, line 27, column A
  - AR3, line 35 → Form AR1000F, line 27, column B (Status 4) or the spouse's return (Status 5)
---
# Itemized Deductions on Status 4 and 5
## Description
Married couples filing separately (on the same or different returns) split the itemized total in proportion to each spouse's AGI.

## Notes
- If either spouse itemizes, both must
- Line 31: each spouse's AGI; line 32: total
- Line 33: primary's AGI ÷ total (to the whole percent)
- Line 34: AR3 total × line 33 → primary's line 27
- Line 35: remainder → spouse (column B on Status 4; the spouse's own return on Status 5)
- Attach a copy of AR3 on Status 5

## Required Information
- Both spouses' Arkansas AGI
- AR3 total itemized deductions

## Questions
- Is either of you itemizing?
- (Status 5) What is your spouse's AGI?
- Are you filing Status 4 or 5?

## Common Errors
- Assigning deductions to whoever paid them instead of prorating
- One spouse itemizing and the other taking the standard deduction
- Not attaching AR3 on Status 5

## Prompt
- We file separately on the same return. How are our itemized deductions split?
- My spouse and I file separate returns and itemize.
