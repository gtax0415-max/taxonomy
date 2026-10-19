---
type: deduction
category: federal-deduction
jurisdiction: NM
tax_year: 2026
source_doc: Form 1099-G box 2 (state or local income tax refund) / Form 1040 Schedule 1, line 1 as filed / prior-year federal Schedule A showing the income tax deduction
form: Form PIT-1
line: "15"
via:
  - Schedule 1, Line 1 → PIT-ADJ, Line 21 → PIT-ADJ, Line 28 → PIT-1, Line 15
---
# Taxable Refunds of State and Local Income Taxes
## Description
If you itemized last year, your state income tax refund may be taxable federally this year (Schedule 1 line 1). New Mexico subtracts it, because New Mexico already made you add that tax back when you deducted it (PIT-1 line 10).

## Amount
- Exactly the amount on the current-year federal Schedule 1, line 1
- No cap

## Eligibility
- You itemized on a prior-year federal Schedule A and deducted state and local income taxes
- The refund is included in this year's federal AGI

## Notes
- This is the mirror image of the state and local tax addback (PIT-1 line 10)
- With the federal SALT cap raised to $40,000 for 2025 and $40,400 for 2026, more 2025 refunds will be federally taxable in 2026, so this line will appear more often
- A refund that was not taxable federally (for example, you took the standard deduction last year) is not entered

## Status for 2026
No change from the 2026 legislative session. Confirm line numbers on the 2026 PIT-ADJ.

## Required Information
- 1099-G box 2
- Schedule 1, line 1 amount
- Prior-year itemized deduction details

## Questions
- Did you get a state or local income tax refund this year?
- Did you itemize on last year's federal return?
- Did any of the refund show up on Schedule 1, line 1?

## Common Errors
- Using the full 1099-G amount instead of the taxable amount on Schedule 1, line 1
- Subtracting a refund that was not taxable federally
- Including real estate tax refunds

## Prompt
- I got a New Mexico refund last year and it is taxable on my federal return.
- What is the state tax refund line on PIT-ADJ?
