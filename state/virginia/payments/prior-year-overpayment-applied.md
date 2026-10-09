---
type: payment
category: estimated-tax
jurisdiction: VA
tax_year: 2026
source_doc: Virginia Tax Individual Online Services record of the overpayment carried forward from 2025 / any Virginia Tax notice adjusting the amount carried forward
form: Form 760
line: "21"
via:
  - 2025 Form 760, Line 29 (overpayment credited to next year) → 2026 Form 760, Line 21 → Line 26
routing:
  - "2026 estimated payments actually paid → Line 20, not Line 21"
see_also:
  - payments/overpayment-credited-to-next-year.md
  - payments/estimated-tax-payments.md
  - payments/addition-to-tax-underpayment.md
---
# 2025 Overpayment Applied to 2026 Estimated Tax (Form 760, Line 21)
## Description
Line 21 reports the amount of your 2025 overpayment that you chose to apply toward 2026 estimated tax instead of receiving it as a refund. It is the other end of last year's Line 29 ("Amount of overpayment you want credited to" the next year's estimated tax). It counts as a payment toward the 2026 tax on Line 26, alongside withholding and estimated payments.
## What to enter
- The amount of the 2025 overpayment actually applied to 2026 estimated tax.
- Use the amount shown in Individual Online Services, which reflects any change the Department made when it processed the 2025 return (for example an offset or a correction). If the Department adjusted the 2025 return, the amount carried forward may differ from what was requested.
## Interaction with other lines
- Line 21 is separate from Line 20 (2026 estimated payments made during the year) and Line 22 (extension payments).
- On Form 760C, the overpayment credit from the prior year return is entered as a timely payment toward the installments.
- The mirror image for next year is Line 29 of this return (see overpayment-credited-to-next-year.md).
## Required Information
- Amount of the 2025 overpayment actually carried forward to 2026, per the Department's records
## Questions
- Did you ask for part of your 2025 Virginia refund to be applied to 2026?
- How much was applied, according to your online account or any Department notice?
## Common Errors
- Adding the prior year overpayment into Line 20 with estimated payments
- Claiming a credit forward when the 2025 overpayment was refunded instead
- Using the amount requested instead of the amount the Department actually carried forward
- Forgetting the credit forward entirely and overpaying 2026
## Prompt
- I applied last year's Virginia refund to this year; where does that go?
- How do I find how much of my overpayment carried forward?
- My 2025 return credited part of my overpayment to 2026 estimated tax.
