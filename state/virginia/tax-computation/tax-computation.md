---
type: index
category: index
jurisdiction: VA
tax_year: 2026
form: Form 760
line: "15-18"
---
# Tax Computation (Form 760, Lines 15-18)
## Description
This folder turns Virginia taxable income (Form 760, Line 15) into the net amount of tax on Line 18. Virginia uses a graduated rate schedule (2%, 3%, 5% and 5.75%) with a Spouse Tax Adjustment of up to $259 for joint filers.
## How the lines flow
```
Line 15  Virginia taxable income (Line 9 - Line 14)
Line 16  Tax from tax table or Tax Rate Schedule (whole dollars; $0 if VAGI is below the filing threshold)
Line 17  Spouse Tax Adjustment (Filing Status 2 only; spouse's VAGI entered in the box)
Line 18  Net amount of tax = Line 16 - Line 17
         → nonrefundable credits (Lines 23-25) are limited to Line 18
         → Line 18 is compared with total payments and credits (Line 26)
```
## Files in this folder
- tax-computation.md - this index (Form 760, Lines 15-18)
- tax-rate-schedule.md - Form 760, Line 16; Tax Rate Schedule and tax table
- spouse-tax-adjustment.md - Form 760, Line 17; Spouse Tax Adjustment Worksheet and separate VAGI worksheet
## Related
- Line 18 is the ceiling for all nonrefundable credits: see credits/credits.md
- Payments, the addition to tax, penalties and interest (Line 32) and the balance due or refund: see payments/payments.md
- Consumer's use tax (Line 33): see other-taxes/consumer-use-tax.md
## Questions
- What is your Virginia taxable income on Line 15?
- Are you married filing jointly, and do both of you have income?
## Prompt
- How is Virginia income tax calculated?
- What is the spouse tax adjustment?
- What tax rate applies to my Virginia income?
