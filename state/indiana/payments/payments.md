---
type: payment
category: payments
jurisdiction: IN
tax_year: 2026
form: Form IT-40
line: "12, 14-26; Schedule 5, lines 1-4"
---
# Payments, Refund and Amount Due (Form IT-40, Lines 12-26; Schedule 5, Lines 1-4)
## Description
Indiana treats withholding, pass through entity tax and estimated payments as credits. They are reported on Schedule 5, lines 1-4, together with the refundable credits on lines 5-11, and the Schedule 5, line 13 total goes to Form IT-40, line 12. Line 14 (credits plus Schedule 6 offset credits) is compared with line 15 (Indiana taxes from line 11) to produce an overpayment (lines 16-22) or an amount due (lines 23-26).
## How the lines flow
```
Schedule 5
 Line 1   Indiana state tax withheld (Schedule IN-W, line 26)
 Line 2   Indiana county tax withheld (Schedule IN-W, line 27)
 Line 3   Pass Through Entity Tax Credit (Schedule IN K-1)
 Line 4   Estimated tax paid for the year, including any IT-9 extension payment
 Lines 5-11  Refundable credits (outside this folder)
 Line 13  Total → Form IT-40, line 12
Form IT-40
 Line 12  Credits (Schedule 5, line 13)
 Line 13  Offset credits (Schedule 6, line 8)
 Line 14  Line 12 + line 13
 Line 15  Indiana taxes (line 11)
 Line 16  If line 14 >= line 15: line 14 - line 15 (else skip to line 23)
 Line 17  Donations (Schedule IN-DONATE, line 2); not more than line 16
 Line 18  Overpayment = line 16 - line 17
 Line 19a County tax to apply to next year's estimates (your county code)
 Line 19b Spouse's county tax to apply (spouse's county code)
 Line 19c State adjusted gross income tax to apply
 Line 19d Total applied (a + b + c), not more than line 18
 Line 20  Penalty for underpayment of estimated tax (IT-2210 or IT-2210A); 20a code A or F
 Line 21  Refund = line 18 - lines 19d and 20
 Line 22  Direct deposit (routing, account, type, outside-U.S. box)
 Line 23  Amount due: line 15 - line 14, plus line 20
 Line 24  Late filing/payment penalty
 Line 25  Interest
 Line 26  Amount you owe = lines 23 + 24 + 25
```
## Files in this folder
- payments.md - this index
- indiana-withholding.md - Schedule 5, lines 1 and 2
- schedule-in-w-withholding-statements.md - Schedule IN-W columns A-H, lines 26 and 27
- pass-through-entity-tax-credit.md - Schedule 5, line 3
- estimated-payments.md - Schedule 5, line 4 (including extension payments)
- schedule-in-donate-donations.md - Form IT-40, line 17 (Schedule IN-DONATE, funds 200, 201, 202)
- overpayment-applied-to-estimated-tax.md - Form IT-40, lines 19a-19d
- underpayment-penalty.md - Form IT-40, lines 20 and 20a (Schedules IT-2210 and IT-2210A)
- refund-and-direct-deposit.md - Form IT-40, lines 21 and 22
- amount-due-and-payment.md - Form IT-40, lines 23 and 26
- late-penalty-and-interest.md - Form IT-40, lines 24 and 25
## Related
- credits/schedule-5/schedule-5.md - Schedule 5, lines 5-11 (refundable credits)
- filing/due-dates-and-extensions.md - extensions and Schedule 7, line 3
## Questions
- How much Indiana state and county tax was withheld for you and your spouse?
- Did any pass-through entity pay Indiana PTET for you?
- What estimated or extension payments did you make for 2026?
- Do you want to donate part of any overpayment, apply it to next year's estimated tax, or have it refunded by direct deposit?
## Prompt
- Where do I enter my Indiana withholding?
- How do I pay what I owe Indiana?
