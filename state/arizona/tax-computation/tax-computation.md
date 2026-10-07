---
type: index
category: index
jurisdiction: AZ
tax_year: 2026
form: Form 140
refundable: no
line: "45-52, 76-77"
see_also:
  - deductions/deductions.md
  - credits/credits.md
  - payments/payments.md
---
# Tax Computation (Form 140, Lines 45 to 52 and 76 to 77)
## Description
Arizona taxes all taxable income at a single rate of 2.5% for every filing status (the 2026 rate, confirmed by the 2026 Form 140ES); the optional tax tables and X and Y tables are obsolete. Recaptured credits are added, then the Dependent Tax Credit, Family Income Tax Credit and Form 301 nonrefundable credits reduce the tax to the balance of tax on line 52, which is never below 0. Penalties for estimated tax underpayment are figured on Form 221 and entered on line 76.
## How the lines flow
```
Line 45  Arizona taxable income = line 42 - lines 43 and 44 (not less than 0)
Line 46  Tax = line 45 x 2.5%
Line 47  Tax from recapture of credits (Form 301, Part 2, line 30)
Line 48  Subtotal = line 46 + line 47
Line 49  Dependent Tax Credit
Line 50  Family Income Tax Credit
Line 51  Nonrefundable credits (Form 301, Part 2, line 60)
Line 52  Balance of tax = line 48 - lines 49, 50, 51 (0 if the credits are larger)
Line 76  Estimated payment penalty (Form 221, box 30c)
Line 77  Boxes 771 annualized/other, 772 farmer or fisherman, 773 Form 221 included
```
## What changed for 2026
- Rate unchanged at 2.5%
- Dependent Tax Credit (line 49) rises to $125 per dependent under 17 (Laws 2026, Chapter 140)
- Form 301 credits on line 51: New Employment credit repealed; refundable R&D no longer available
## Tax computation topics in this folder
- tax-computation.md - this index
- arizona-taxable-income-and-tax.md - lines 45, 46
- credit-recapture.md - line 47; Form 301, lines 27 to 30
- balance-of-tax.md - lines 48, 52
- underpayment-of-estimated-tax-form-221.md - lines 76, 77 (boxes 771 to 773); Form 221
- penalties-and-interest.md - late filing, late payment, extension underpayment penalties, interest, returned payments
## Related
- Credits on lines 49 to 51 are in credits/
- Payments and the amount owed are in payments/
## Notes
- Form 140 line and box numbers follow the 2025 Form 140; ADOR had not released the 2026 Form 140 when this was revised, so confirm them against it
## Required Information
- Arizona taxable income
- Credit forms and recapture computations
- Estimated payment records
## Questions
- What is your Arizona taxable income?
- Are you recapturing any credits (motion picture, qualified facilities, affordable housing)?
- Did you make required estimated payments on time?
## Prompt
- What is the Arizona income tax rate for 2026?
