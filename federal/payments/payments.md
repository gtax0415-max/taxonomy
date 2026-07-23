---
type: payment
category: payments
form: Form 1040
line: "25, 26, 32, 33, 34, 37"
---
# Payments and Refundable Credits
## Description
What you already paid toward the year's tax, and how it settles into a refund or a balance due. This is where the return finally resolves: total tax on Form 1040 Line 24 minus total payments on Line 33 produces either an overpayment on Line 34 or an amount owed on Line 37.
## The payments section, line by line
- Line 25a — federal income tax withheld from Form(s) W-2 (Box 2)
- Line 25b — federal income tax withheld from Form(s) 1099 (the Box 4 on most 1099s)
- Line 25c — federal income tax withheld from other forms
- Line 25d — total withholding. See withholding.md
- Line 26 — estimated tax payments for the year, PLUS any prior-year overpayment you applied forward. See estimated-tax.md
- Line 27 — earned income credit. See federal/credits/income-based/earned-income-credit.md
- Line 28 — additional child tax credit, the refundable part. See federal/credits/family-dependent/child-tax-credit.md
- Line 29 — American opportunity credit, the refundable 40%. See federal/credits/education/education-credits.md
- Line 31 — total from Schedule 3, Part II
- Line 32 — total other payments and refundable credits (27 + 28 + 29 + 31)
- Line 33 — TOTAL PAYMENTS (25d + 26 + 32)
## Schedule 3, Part II — refundable credits and other payments
- Line 9 — net premium tax credit (Form 8962). See federal/credits/health-insurance/premium-tax-credit.md
- Line 10 — amount paid with a request for an extension to file (Form 4868)
- Line 11 — EXCESS SOCIAL SECURITY tax withheld by two or more employers. See excess-social-security.md
- Line 12 — credit for federal tax on fuels (Form 4136)
- Line 13 — other payments and refundable credits
## How it resolves
- Line 34 — if Line 33 exceeds Line 24, you OVERPAID
- Line 35a — the part of the overpayment you want refunded
- Line 36 — the part you want APPLIED to next year's estimated tax
- Line 37 — if Line 24 exceeds Line 33, the AMOUNT YOU OWE
- Line 38 — estimated tax penalty from Form 2210, which can apply even when you are getting a refund
See refund-or-balance-due.md
## Why a refund does not prove you were compliant
Line 38 is the reason. The underpayment penalty is computed QUARTER BY QUARTER. Someone who paid nothing for three quarters and then made one large payment in January can still owe a penalty while receiving a refund. The refund only reports the year-end net; it says nothing about timing.
## Files in this folder
- withholding.md — Form W-2 Box 2, Form 1099 Box 4, Form W-4, backup withholding
- estimated-tax.md — Form 1040-ES, the safe harbors, quarterly due dates, Form 2210
- excess-social-security.md — recovering over-withheld Social Security tax from multiple jobs
- refund-or-balance-due.md — the final lines, refund choices, and payment options
## Questions
- How much was withheld from wages and other payments?
- Did you make estimated tax payments during the year?
- Did you apply an overpayment from last year's return?
- Did you work for more than one employer this year?
- Do you expect a refund or a balance due?
## Prompt
- Am I getting a refund?
- How much did I already pay in taxes this year?
- I owe money at filing. Why?
