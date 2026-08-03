---
type: deduction
category: subtractions
jurisdiction: NYS
source_doc: Federal Form 1040, Schedule 1, line 1 (taxable refunds, credits, or offsets of state and local income taxes) / Form 1099-G from the Tax Department / records of any New York inflation refund check received in fall 2025
form: Form IT-201
line: "25"
refundable: no
via:
  - Federal Form 1040, Schedule 1, Line 1 → Form IT-201, Line 25
---
# Taxable Refunds, Credits, or Offsets of State and Local Income Taxes
## Description
New York does not tax the refund of its own income tax. Whatever amount of state and local income tax refund landed in your federal AGI comes back out at Form IT-201 line 25.
## Why the amount exists at all
If you itemized federally in a prior year and deducted state income taxes, a later refund of those taxes is federally taxable under the tax benefit rule. It appears on federal Schedule 1 line 1 and flows into federal AGI, and therefore into Form IT-201 line 19. Line 25 removes it.
Filers who took the federal standard deduction generally have nothing here, because there was no prior deduction to recapture.
## The 2025 inflation refund check
New York mailed INFLATION REFUND CHECKS in the fall of 2025. If you received one AND the amount was included in the federal AGI reported on line 19, enter that amount on line 25.
Whether it lands in federal AGI depends on how the payment was characterized and whether you itemized. Check federal Schedule 1 line 1 rather than assuming. If the check never reached federal AGI, there is nothing to subtract and entering it anyway understates New York income.
## What belongs here and what does not
| Item | Line 25? |
|---|---|
| Refund of New York State income tax | YES, if in federal AGI |
| Refund of New York City or Yonkers income tax | YES, if in federal AGI |
| Refund of ANOTHER state's income tax | YES, if in federal AGI |
| 2025 inflation refund check | YES, if in federal AGI |
| Refund of federal income tax | NO — never taxable, never in AGI |
| Property tax rebate or STAR check | NO — not an income tax refund. But it may reduce the property tax you deduct on Form IT-196 |
That last row is the confusion worth flagging. A STAR check is not subtracted here. It reduces the real estate taxes reported on Form IT-196 line 6 IF you itemize. Two different mechanisms, two different forms.
## Required Information
- Federal Schedule 1, line 1 amount
- Form 1099-G from the Tax Department, available online rather than mailed
- Whether an inflation refund check was received and whether it reached federal AGI
## Questions
- Does your federal Schedule 1 line 1 show a state or local tax refund?
- Did you itemize federally in the prior year?
- Did you receive a New York inflation refund check in fall 2025?
- Did you receive a STAR check, which is handled differently?
## Common Errors
- Subtracting a STAR or property tax rebate here instead of adjusting Form IT-196 line 6
- Subtracting an inflation refund check that never entered federal AGI
- Missing the subtraction entirely, leaving a New York refund taxed by New York
- Subtracting a federal refund, which was never taxable
## Prompt
- I got a refund from New York last year, is it taxable?
- I received an inflation refund check.
- My Schedule 1 shows a state tax refund.
