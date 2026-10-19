---
type: deduction
category: itemized
jurisdiction: CA
tax_year: 2026
source_doc: Federal Form 1040 as filed (federal AGI) / federal Schedule A as filed (medical, investment interest, casualty and gambling loss amounts)
form: Form 540
line: "18"
via:
  - Schedule CA (540), Part II, Line 28 → Itemized Deductions Worksheet → Line 29 → Line 30 → Form 540, Line 18
---
# Itemized Deduction Limitation (High Income)
## Description
California keeps the older "Pease" limitation that federal law repealed: high-income filers lose part of their itemized deductions.

## Thresholds (federal AGI, Form 540 line 13)
- 2026: pending FTB release (expected late December 2026)
- 2025: $252,203 single or MFS; $378,310 head of household; $504,411 MFJ or QSS

## Computation (Itemized Deductions Worksheet)
1. Start with Schedule CA, Part II, line 28
2. Subtract medical expenses (line 4), investment interest (line 9), casualty and theft losses (line 15) and gambling losses; if zero, no reduction
3. Multiply the remainder by 80%
4. Multiply federal AGI over the threshold by 6%
5. Reduce itemized deductions by the SMALLER of step 3 or step 4

## Notes
- Line numbers follow the 2025 Form 540 and schedules; confirm them on the 2026 forms (expected December 2026)
- RDPs use recalculated federal AGI
- The exemption credits phase out at the same AGI thresholds
- MFS: if one spouse itemizes, the other must itemize (line 30)

## Required Information
- Federal AGI
- Itemized deductions by category

## Questions
- Is your federal AGI above the threshold for your filing status?
- How much of your itemized deductions are medical, investment interest, casualty or gambling losses?

## Common Errors
- Skipping the worksheet at high income
- Including medical or investment interest in the reducible amount

## Prompt
- My AGI is $600,000. Are my California itemized deductions limited?
