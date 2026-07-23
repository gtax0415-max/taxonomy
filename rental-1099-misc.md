---
type: income
category: rental
source_doc: Form 1099-MISC Box 1 (rents), Box 2 (royalties), Box 3 (other income), Box 4 (federal income tax withheld)
form: Form 1040
line: "8"
via:
  - Form 1099-MISC Box 1 and Box 2 → Schedule E → Schedule 1, Line 5 → Form 1040, Line 8
  - Form 1099-MISC Box 3 → Schedule 1, Line 8i or Line 8z → Schedule 1, Line 9 → Form 1040, Line 8
routing:
  - "Form 1099-MISC Box 1 (rents) → Schedule E, Line 3 → Schedule 1, Line 5 → Form 1040, Line 8"
  - "Form 1099-MISC Box 2 (royalties) → Schedule E, Line 4 → Schedule 1, Line 5 → Form 1040, Line 8"
  - "Form 1099-MISC Box 3 (other income), e.g. a prize → Schedule 1, Line 8i (prizes and awards) or Line 8z (other) → Schedule 1, Line 9 → Form 1040, Line 8. See federal/income/business/1099-misc.md"
  - "Form 1099-MISC Box 4 (federal income tax withheld) → Form 1040, Line 25b"
---
# Form 1099-MISC
## Description
Miscellaneous information return. Since nonemployee compensation moved to Form 1099-NEC in 2020, Form 1099-MISC now mainly reports rents, royalties, and other miscellaneous income.
## Box-to-line mapping
- Form 1099-MISC Box 1 (rents) → Schedule E, Line 3 → Schedule 1, Line 5 → Form 1040, Line 8
- Form 1099-MISC Box 2 (royalties) → Schedule E, Line 4 → Schedule 1, Line 5 → Form 1040, Line 8
- Form 1099-MISC Box 3 (other income) → Schedule 1, Line 8i (prizes and awards) or Line 8z (other income). If the amount is from a business you operate it goes on Schedule C instead — see federal/income/business/1099-misc.md
- Form 1099-MISC Box 4 (federal income tax withheld) → Form 1040, Line 25b (tax already paid; credited on your return)
- Form 1099-MISC Box 9 (crop insurance proceeds) → Schedule F — see federal/income/farming/farm-income.md
## Notes
- Most current Form 1099-MISC income is Box 1 rents and Box 2 royalties, which flow through Schedule E and are generally NOT subject to self-employment tax (passive income)
- Beginning with tax year 2026, the issuing threshold rises from $600 to $2,000 (One Big Beautiful Bill Act; inflation-adjusted from 2027)
- All income is taxable even if no Form 1099-MISC was received; the threshold only controls whether a form is issued
- If the payment is actually for SERVICES you performed as a business, it usually belongs on Form 1099-NEC and Schedule C instead — see federal/income/business/1099-nec.md
- Rental losses may be limited by the passive activity rules — see federal/income/rental/passive-activity-limits.md
## Required Information
- Payer name
- Payer TIN
- Form 1099-MISC Box 1 (rents)
- Form 1099-MISC Box 2 (royalties)
- Form 1099-MISC Box 3 (other income)
- Form 1099-MISC Box 4 (federal income tax withheld)
## Questions
- What type of payment did you receive (rent, royalty, prize, or other)?
- Do you own rental property or hold royalty interests?
- Do you have related expenses (for Schedule E rentals) to deduct?
- Was federal tax withheld (Form 1099-MISC Box 4)?
## Common Errors
- Putting rental or royalty income on Schedule C instead of Schedule E
- Treating passive rental or royalty income as self-employment income (it generally is not)
- Forgetting that prizes and awards in Box 3 are taxable other income
- Forgetting to claim Form 1099-MISC Box 4 withholding on Form 1040 Line 25b
## Prompt
- I received a 1099-MISC for rent paid to me.
- I got a 1099-MISC for royalties on my creative work.
- My 1099-MISC shows an amount in Box 3 for a prize I won.
