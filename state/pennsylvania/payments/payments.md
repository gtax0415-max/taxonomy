---
type: payment
category: index
jurisdiction: PA
form: PA-40
line: "13, 14, 15, 16, 17, 18, 24, 26, 27, 28, 29, 30, 31"
---
# Pennsylvania Payments, Refund, and Balance Due
## Description
Everything already paid toward the PA liability, and the arithmetic that turns it into a refund or a balance due.
## Files in this folder
- withholding.md — line 13
- estimated-payments.md — lines 14, 15, 16, and 18
- nonresident-withholding.md — line 17
- penalties-and-interest.md — line 27
- refund-or-balance-due.md — lines 24, 26, 28, 29, 30, and 31
## The full payment block
```
Line 12   PA TAX LIABILITY, line 11 x 3.07%
Line 13   Total PA tax WITHHELD
Line 14   CREDIT FROM YOUR 2024 PA RETURN
Line 15   2025 ESTIMATED INSTALLMENT PAYMENTS, oval if including REV-459B
Line 16   2025 EXTENSION PAYMENT
Line 17   NONRESIDENT TAX WITHHELD from PA Schedule NRK-1 (nonresidents only)
Line 18   Total estimated payments and credits: 14 + 15 + 16 + 17
Line 21   Tax Forgiveness Credit
Line 22   Resident Credit
Line 23   Total Other Credits
Line 24   TOTAL PAYMENTS AND CREDITS: 13 + 18 + 21 + 22 + 23
Line 25   USE TAX
Line 26   TAX DUE, if 12 + 25 exceeds 24
Line 27   PENALTIES AND INTEREST
Line 28   TOTAL PAYMENT DUE
Line 29   OVERPAYMENT, if 24 exceeds 12 + 25 + 27
Line 30   REFUND
Line 31   CREDIT to the 2026 estimated account
Lines 32-36  Refund donations
```
## Two things that are easy to get backwards
USE TAX IS ADDED, NOT SUBTRACTED. Line 26 compares line 24 against LINE 12 PLUS LINE 25. A taxpayer with a small overpayment can be pushed into a balance due by use tax.
CREDITS SIT INSIDE THE PAYMENTS TOTAL. Tax Forgiveness, the resident credit, and Schedule OC credits are all part of LINE 24, not a separate reduction of line 12. The ordering rules that cap those credits happen on their own schedules before they arrive here.
## The federal contrast
| | Federal | Pennsylvania |
|---|---|---|
| Withholding | Form 1040 line 25 | LINE 13 |
| Estimated payments | Line 26 | LINE 15 |
| Prior-year overpayment applied | Included in estimated | SEPARATE LINE 14 |
| Extension payment | Schedule 3 | SEPARATE LINE 16 |
| Refundable credits | Lines 27 to 31 | Inside LINE 24 |
| Use tax | NO FEDERAL EQUIVALENT | LINE 25 |
PA breaks the prepayment categories onto separate lines where the federal return groups them.
## Related
- Use tax, which is added at line 25 — see state/pennsylvania/taxes/use-tax.md
- Refund donations, which subdivide line 29 — see state/pennsylvania/donations/
- Credits that feed line 24 — see state/pennsylvania/credits/
## Questions
- Was PA tax withheld from your pay?
- Did you apply a 2024 overpayment forward?
- Did you make quarterly estimated payments or an extension payment?
- Do you owe use tax, which is added to the liability?
## Prompt
- How do I figure my PA refund?
- I made estimated payments to Pennsylvania.
- Why do I owe when I had a refund coming?
