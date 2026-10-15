---
type: payment
category: payments
jurisdiction: KS
tax_year: 2026
source_doc: Payment records showing dates and amounts of withholding, estimated payments and the balance paid / proof of filing date / gross income by source (to test the two-thirds farming or fishing rule)
form: Form K-40
line: "29, 30, 31"
via:
  - Interest → Form K-40, line 29 → line 32
  - Late-payment penalty → Form K-40, line 30 → line 32
  - Underpayment of estimated tax penalty (Schedule K-210) → Form K-40, line 31 → line 32
---
# Interest and Penalties
## Description
Kansas charges interest, a late-payment penalty, and a penalty for underpaying estimated tax.

## Rules for a 2026 return
- INTEREST (line 29): on the unpaid balance from the original due date (April 15, 2027), at the annual rate KDOR sets for each calendar year. Because a 2026 balance is late only from April 15, 2027, the 2027 rate applies; KDOR has not yet published it (the 2026 rate is 8% per year, 0.6667% per month or part of a month)
- ESTIMATED TAX PENALTY RATE: periods during 2026 use the 2026 rate (8%); periods from January 1, 2027 use the 2027 rate
- LATE-PAYMENT PENALTY (line 30): 1% per month or part of a month from the original due date, up to 24%. No penalty if at least 90% of the tax was paid by the original due date on an extended return
- ESTIMATED TAX PENALTY (line 31): possible if tax due after withholding and credits is $500 or more. Exceptions: payments equal at least 100% of the 2025 tax, or 90% of the 2026 tax, or the annualized-income exception
- FARMERS AND FISHERS: if at least two-thirds of income is from farming or fishing, mark the box on line 31; no estimated penalty if the return is filed and paid by March 1, 2027

## Notes
- SCOPE: The template does NOT figure interest or penalties (firm policy). This file is for recognizing when they apply and routing the client.
- Paying the full tax and interest with an amended return avoids the late-payment penalty
- Interest runs even when the filing deadline is extended

## Required Information
- Date the return was filed and the tax paid
- Estimated and withholding payment history
- Prior-year tax liability

## Questions
- Will you pay the full balance by April 15, 2027?
- Did you pay at least 90% of this year's tax or 100% of last year's through withholding and estimates?
- Is at least two-thirds of your income from farming or fishing?

## Common Errors
- Assuming an extension stops interest
- Missing the farmer/fisher box
- Applying penalty when 90% was paid by the original due date

## Prompt
- I'm filing my Kansas return late. Will I owe a penalty?
- I didn't make estimated payments this year.
