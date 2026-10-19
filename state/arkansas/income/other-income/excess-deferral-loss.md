---
type: subtraction
category: other-income
jurisdiction: AR
tax_year: 2026
source_doc: Form 1099-R (code 8 or P) for the corrective distribution of excess deferrals / plan administrator's letter showing the excess amount, earnings or loss, and withdrawal date / Form W-2 box 12 deferrals from all employers
form: Form AR1000F
line: "22"
via:
  - Form 1099-R (corrective distribution) → AR-OI, line 15 → line 19 → line 20 → Form AR1000F, line 22
---
# Loss on Excess Deferral Distribution
## Description
Subtracts a loss when excess 401(k)/403(b) deferrals are returned and the investment lost value before the corrective distribution.

## Notes
- 2026 elective deferral limit: $24,500 (catch-up $8,000 at 50+; $11,250 at 60–63) (IRS Notice 2025-67)
- Applies to excess deferrals for 2026 withdrawn before April 15, 2027 (the 2025 form used April 15, 2026)
- The line is labeled "loss on excess deferral distribution," but the 2025 instruction says to enter "the amount of distribution withdrawn" before the April deadline. This file treats it as the loss on the corrective distribution, following the federal rule; confirm the intended amount against the 2026 AR-OI instructions

## Required Information
- Total deferrals from all employers
- Corrective distribution amount, loss, and date

## Questions
- Did you contribute more than $24,500 to 401(k) or 403(b) plans across jobs in 2026?
- Was the excess returned by April 15, 2027, and at a loss?
- Do you have the plan administrator's letter?

## Common Errors
- Using the 2025 date or limit
- Subtracting the excess deferral itself
- Not counting deferrals from all employers

## Prompt
- I over-contributed to two 401(k)s and the excess was returned at a loss.
- My excess 401(k) money came back to me.
