---
type: deduction
category: itemized
source_doc: Form W-2 Box 17 (state income tax withheld) / Form 1098 Box 10 (real estate taxes) / property tax bills / estimated payment records
form: Form 1040
line: "12"
via:
  - Schedule A, Lines 5a-5e → Form 1040 Line 12
---
# State and Local Taxes (SALT)
## Description
Itemized deduction for state and local taxes paid. Includes state and local income taxes (or, alternatively, sales taxes), real estate taxes, and personal property taxes — all subject to a single combined cap.
## What counts toward SALT
- Schedule A Line 5a: state and local income taxes OR general sales taxes (choose one, not both)
- Schedule A Line 5b: state and local real estate taxes (see real-estate-taxes.md)
- Schedule A Line 5c: state and local personal property taxes (e.g., value-based vehicle registration)
- Schedule A Line 5d: the total of 5a + 5b + 5c
- Schedule A Line 5e: the total AFTER applying the cap — this is what is actually deductible
## The cap (changed by OBBBA)
- 2024 and earlier: $10,000 ($5,000 married filing separately)
- 2025: $40,000 ($20,000 married filing separately)
- 2026: $40,400, then increasing 1% per year through 2029
- 2030: reverts to $10,000
## Income phase-down
- The increased cap is reduced by 30% of the amount by which MAGI exceeds $500,000 (2025) or $505,000 (2026)
- The deduction never falls below $10,000 regardless of income
- For 2025, taxpayers with MAGI of $600,000 or more are limited to $10,000
- Example (2025, joint): MAGI $530,000, SALT paid $48,000. Cap starts at $40,000; MAGI exceeds the threshold by $30,000; reduction is 30% x $30,000 = $9,000; deductible SALT = $31,000
## Notes
- Only available if you itemize
- Choosing sales tax instead of income tax can help taxpayers in states with no income tax
- The pass-through entity tax (PTET) workaround remains available and was not restricted by OBBBA
## Questions
- How much did you pay in state and local income taxes (Form W-2 Box 17, estimated payments)?
- How much did you pay in real estate and personal property taxes?
- Do you live in a state with no income tax (making the sales tax election better)?
- Is your MAGI above $500,000 (triggering the phase-down)?
## Common Errors
- Treating real estate taxes as deductible separately from the SALT cap
- Deducting both income taxes and sales taxes (only one is allowed)
- Missing the MAGI phase-down for high earners
- Using the old $10,000 cap for 2025 and later
## Prompt
- I paid a lot of state income tax and property tax this year.
- I want to know how much of my state and local taxes I can deduct.
