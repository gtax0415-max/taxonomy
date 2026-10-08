---
type: payment
category: withholding
jurisdiction: IN
tax_year: 2026
source_doc: Forms W-2 (Box 17 state tax, Box 19 local tax), W-2G, 1099-R, 1099-G, 1099-MISC and 1099-NEC
form: Schedule 5
line: "1, 2"
via:
  - Indiana state tax withheld (Schedule IN-W, column E → line 26) → Schedule 5, Line 1 → Line 13 → Form IT-40, Line 12
  - Indiana county tax withheld (Schedule IN-W, column G → line 27) → Schedule 5, Line 2 → Line 13 → Form IT-40, Line 12
routing:
  - "Indiana state withholding on any statement → line 1"
  - "Indiana county withholding → line 2 (report separately from state)"
  - "Tax withheld for other states or non-Indiana localities → not claimed here"
  - "Joint return → include spouse's statements"
  - "PTET credited on an IN K-1 → Schedule 5, line 3, not withholding"
see_also:
  - payments/payments.md
  - payments/schedule-in-w-withholding-statements.md
  - payments/pass-through-entity-tax-credit.md
  - payments/underpayment-penalty.md
---
# Indiana State and County Tax Withheld (Schedule 5, Lines 1-2)
## Description
Report Indiana state tax withheld on line 1 and Indiana county tax withheld on line 2, separately. State withholding is usually in W-2 box 17 and county withholding in box 19, but Indiana withholding can also appear on W-2Gs, 1099s, Form IN-MSID-A and Schedule IN K-1. The amounts come from Schedule IN-W, lines 26 and 27.
## Enclosures
Enclose the withholding statements (W-2s, W-2Gs, 1099s, IN-MSID-As, IN K-1s) and Schedule IN-W. Failure to enclose them results in a reduced refund or larger amount owed. Make sure statements are readable. Substitute W-2s delay processing and may affect the refund. Verification may also be delayed if the payer files withholding statements late.
## What does not belong here
| Item | Where it goes |
|---|---|
| Tax withheld for other states or for localities outside Indiana | Not claimed (other-state credit is a separate Schedule 6 item) |
| Indiana pass through entity tax | Schedule 5, line 3 |
| Estimated or extension payments | Schedule 5, line 4 |
## Household employers
If you paid cash wages of $2,200 or more to a household employee, or $1,000 or more in any calendar quarter to all household employees (2025 amounts; confirm against the 2026 form), you may have withheld Indiana state and county income tax. Pay those taxes using Schedule IN-H with your return.
## Example
Lynn's W-2: box 17 $1,620, box 19 $918. Her spouse's 1099-R shows Indiana tax withheld $240. Schedule IN-W line 26 = $1,860 → Schedule 5, line 1; line 27 = $918 → Schedule 5, line 2.
## Questions
- Do you have W-2s, 1099s, W-2Gs, IN-MSID-As or IN K-1s showing Indiana state or county tax withheld?
- On a joint return, what was withheld for your spouse?
## Common Errors
- Combining state and county withholding on one line
- Claiming Illinois, Ohio or other state withholding
- Reporting PTET as withholding
- Omitting the statements or Schedule IN-W
## Prompt
- Where do I put the county tax from my W-2?
- Can I claim the Ohio tax withheld on my Indiana return?
