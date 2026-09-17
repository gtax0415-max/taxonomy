---
type: payment
category: refund-balance
jurisdiction: PA
source_doc: NO EXTERNAL SOURCE DOCUMENT — every figure is computed from other lines of the same return. The inputs are Line 12 tax liability, Line 24 total payments and credits, Line 25 use tax, and Line 27 penalties and interest. Bank routing and account details are needed only for direct deposit
form: PA-40
line: "24, 26, 28, 29, 30, 31"
refundable: no
via:
  - Lines 13, 18, 21, 22, 23 → Line 24 → compared against Lines 12, 25, 27 → Line 26 or Line 29
---
# Total Payments, Tax Due, and Overpayment (Lines 24 through 31)
## Description
The arithmetic that closes the return. Six lines, and the order matters because use tax and penalties both sit on the liability side.
## The computation
```
Line 24   TOTAL PAYMENTS AND CREDITS = 13 + 18 + 21 + 22 + 23
Line 25   USE TAX
Line 26   TAX DUE, if Line 12 PLUS Line 25 is more than Line 24
Line 27   PENALTIES AND INTEREST
Line 28   TOTAL PAYMENT DUE
Line 29   OVERPAYMENT, if Line 24 is more than Line 12 PLUS Line 25 PLUS Line 27
Line 30   REFUND, amount of Line 29 you want as a check
Line 31   CREDIT to your 2026 estimated account
Lines 32-36  Refund donations
THE TOTAL OF LINES 30 THROUGH 36 MUST EQUAL LINE 29
```
## Line 24 is the aggregation point for CREDITS
| Feeding line 24 | What it is |
|---|---|
| Line 13 | PA tax withheld |
| Line 18 | Estimated payments, prior-year credit, extension payment, NRK-1 withholding |
| Line 21 | TAX FORGIVENESS CREDIT |
| Line 22 | RESIDENT CREDIT |
| Line 23 | TOTAL OTHER CREDITS, Schedule OC and Schedule DC |
PA CREDITS ARE NOT SUBTRACTED FROM THE LINE 12 LIABILITY. They are added to the PAYMENTS side and compared against it. The ordering rules that cap them — resident credit first, then Tax Forgiveness, then Schedule OC — all happen on their own schedules BEFORE the amounts arrive at lines 21 through 23.
## Two things on the liability side that are easy to miss
USE TAX at line 25 is ADDED to line 12 in both the tax-due test and the overpayment test.
PENALTIES AND INTEREST at line 27 are subtracted in the OVERPAYMENT test at line 29, though they appear only in the payment total at line 28 on the other side.
So a taxpayer with modest withholding, a small use tax liability, and an estimated underpayment penalty can move from an expected refund to a balance due across these four lines.
## Line 29 must be fully allocated
THE TOTAL OF LINES 30 THROUGH 36 MUST EQUAL LINE 29. Refund, estimated-account credit, and any donations together must exhaust the overpayment exactly. An entry that breaks this identity stops processing.
## Line 31: crediting forward
An amount credited to the 2026 estimated account appears on the 2026 return at LINE 14, not line 15. See estimated-payments.md.
BECAUSE SPOUSES ARE SEPARATE TAXPAYERS FOR PA, a credit forward is posted to the SSN shown first on the return. Where the following year's estimated payments are made under a different SSN, FORM REV-459B is needed to move it.
## Payment deadline
Tax due must be paid IN FULL ON OR BEFORE APRIL 15, 2026. An extension of time to file does not extend the time to pay.
## Refund timing
The Department asks that taxpayers NOT CALL ABOUT A REFUND UNTIL TWELVE WEEKS AFTER FILING.
Where a refund depends on a PASS-THROUGH RESTRICTED CREDIT, expect the fall rather than the spring — the Department cannot allocate the credit until it holds the award, the pass-through form, and the entity's own return. It pays interest on the delay. See credits/business-incentive/restricted-tax-credits.md.
## The federal contrast
| | Federal | Pennsylvania |
|---|---|---|
| Refundable credits | Separate lines AFTER the tax | INSIDE the payments total at line 24 |
| Use tax | NO EQUIVALENT | Added at line 25 |
| Penalty placement | After the balance due | INSIDE the overpayment test |
| Refund allocation | Form 8888 for splitting | Lines 30 to 36 must total to line 29 |
## Required Information
- Lines 12, 13, 18, 21, 22, 23, 25, and 27
- Bank routing and account numbers, for direct deposit
- The allocation between refund, estimated credit, and donations
## Questions
- What is your total liability including use tax?
- Do you owe a penalty, which is subtracted before the overpayment is computed?
- Do you want the overpayment refunded, credited forward, or donated?
- Does the allocation total exactly to line 29?
## Common Errors
- Subtracting credits from line 12 rather than adding them at line 24
- Omitting use tax from the tax-due comparison
- Omitting line 27 from the overpayment test
- Failing to make lines 30 through 36 total exactly to line 29
- Reporting a credit forward on the following year's line 15 instead of line 14
- Calling about a refund before twelve weeks have passed
## Prompt
- Why do I owe when I expected a refund?
- Can I apply my PA refund to next year?
- How long does a PA refund take?
