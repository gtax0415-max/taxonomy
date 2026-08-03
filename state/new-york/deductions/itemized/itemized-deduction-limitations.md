---
type: deduction
category: itemized
jurisdiction: NYS
source_doc: NO EXTERNAL SOURCE DOCUMENT — both limitations are computed entirely from figures already on the return. The inputs are Form IT-201 line 19 (federal AGI) for the line 40 limitation, Form IT-201 line 33 (New York AGI) for the line 46 adjustment, and the Form IT-196 category subtotals at lines 4, 9, 14, 15, 16a, 19, 20, 28, 29, 30, 37, and 39. The underlying receipts sit with the individual category files
form: Form IT-201
line: "34"
refundable: no
via:
  - Form IT-196, Line 40 worksheet (2017 federal overall limitation) → Form IT-196, line 40
  - Form IT-196, Worksheets 3 through 6 (New York high-income adjustment) → Form IT-196, line 46
---
# Itemized Deduction Limitations
## Description
TWO SEPARATE LIMITATIONS apply in sequence on Form IT-196, and they use DIFFERENT INCOME MEASURES. Missing either one overstates the deduction. This is the most mechanically error-prone part of the New York return.
| Limitation | Line | Income measure | Origin |
|---|---|---|---|
| Overall limitation (Pease) | 40 | FEDERAL AGI, Form IT-201 line 19 | 2017 federal law, repealed federally |
| New York adjustment | 46 | NEW YORK AGI, Form IT-201 line 33 | New York Tax Law, no federal analogue |
## Limitation 1: line 40, the revived Pease limitation
Repealed federally by the TCJA, still alive for New York because Form IT-196 uses 2017 rules.
Applies when FEDERAL AGI exceeds:
| Filing status | 2025 threshold |
|---|---|
| Married filing jointly or qualifying surviving spouse | $408,850 |
| Head of household | $374,800 |
| Single | $340,700 |
| Married filing separately | $204,400 |
These are indexed; 2025 figures shown, use as a proxy for 2026 until the 2026 instructions publish.
The reduction is the SMALLER of:
- 80% of the deductions subject to the limitation, or
- 3% of federal AGI above the threshold
Protected from this limitation: medical and dental (line 4), investment interest (line 14), casualty and theft (line 20), gambling losses (line 29), casualty of income-producing property (line 30), qualified disaster loss (line 37), and qualified charitable contributions included on line 16a.
## Limitation 2: line 46, the New York adjustment
Keyed to NEW YORK AGI, not federal AGI. Six tiers:
| New York AGI | Line 46 treatment |
|---|---|
| $100,000 or less | No adjustment; leave blank |
| Over $100,000 to $475,000 | Worksheet 3 |
| Over $475,000 to $525,000 | Worksheet 4 |
| Over $525,000 to $1,000,000 | Enter 50% of line 45 |
| Over $1,000,000 to $10,000,000 | Worksheet 5 |
| Over $10,000,000 | Worksheet 6 |
The direction of travel: as income rises, New York progressively strips out NON-CHARITABLE deductions first, then cuts back charitable contributions themselves. At the top tiers only a fraction of charitable giving survives. Run the worksheet rather than estimating — the tiers interact and the transition bands at $475,000 and $1,000,000 do not behave linearly.
## Why the $100,000 threshold matters more than it looks
It is NOT indexed and it is NOT doubled for joint filers. A married couple with $110,000 of New York AGI is already in the limitation, which surprises people who associate deduction phase-outs with much higher incomes. In downstate New York, a large share of two-earner households sit above it.
## Order of operations
```
Lines 1-39   Individual categories
Line 40      Apply the 2017 Pease limitation, using FEDERAL AGI
Line 41      Subtract state, local, and foreign INCOME taxes
Line 42      Line 40 minus line 41
Line 43      College tuition deduction (IT-203 filers only)
Line 44      Add New York addition adjustments
Line 45      Add lines 42, 43, and 44
Line 46      Apply the New York adjustment, using NEW YORK AGI
Line 47      Line 45 minus line 46
Line 48      College tuition deduction (IT-201 filers)
Line 49      New York itemized deduction → Form IT-201, Line 34
```
The college tuition deduction enters AFTER the line 46 adjustment for IT-201 filers, which protects it from the high-income cutback. That placement is deliberate and easy to get wrong.
## Planning consequence
Anything that lowers NEW YORK AGI relieves the line 46 adjustment. New York subtractions therefore do double work: they reduce income directly, and they can restore itemized deductions that the adjustment would otherwise have taken. The pension and annuity exclusion, government pension exclusion, and 529 contribution subtraction all have this second-order effect. See state/new-york/deductions/subtractions/.
## Required Information
- Federal AGI from Form IT-201 line 19, for the line 40 test
- New York AGI from Form IT-201 line 33, for the line 46 test
- Category totals, split between limited and protected groups
- Charitable contributions, separated into qualified and non-qualified
## Questions
- Is your New York AGI over $100,000?
- Is your federal AGI over the line 40 threshold for your filing status?
- How much of your deduction is charitable, which survives longest?
- Are there subtractions that would drop New York AGI below a tier boundary?
## Common Errors
- Applying only one of the two limitations
- Using New York AGI for the line 40 test or federal AGI for the line 46 test
- Assuming the Pease limitation is dead because it was repealed federally
- Assuming the $100,000 threshold doubles for married filing jointly
- Placing the college tuition deduction before line 46 rather than after
- Failing to separate qualified charitable contributions on line 16a, losing protection at line 40
## Prompt
- Why is my New York itemized deduction smaller than my federal one?
- My income is over $500,000, can I still itemize in New York?
- Does New York limit itemized deductions?
