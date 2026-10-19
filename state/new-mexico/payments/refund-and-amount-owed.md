---
type: payment
category: payments
jurisdiction: NM
tax_year: 2026
source_doc: Computed on the return (net tax versus total payments and credits) / taxpayer's election of how to handle an overpayment (refund, apply to 2027, or contribute) / payment method for a balance due
form: Form PIT-1
line: "33, 38, 39, 41, 42"
via:
  - PIT-1, Line 22 (net tax) − Line 32 (total payments and credits) → Line 33 (tax due) → Line 38 (tax, penalty and interest due)
  - PIT-1, Line 32 − Line 23 → Line 39 (overpayment) − Line 40 (PIT-D contributions) − Line 41 (applied to 2027) → Line 42 (refund)
---
# Refund and Amount Owed
## Description
The bottom of the return. Net New Mexico tax (line 22) is compared with total payments and credits (line 32), which include withholding, estimated and other payments, and the refundable credits (PIT-RC rebates and credits, working families tax credit, refundable PIT-CR credits).

## Amount owed (lines 33 and 38)
- If net tax is more than payments and credits, the difference is tax due (line 33)
- Line 38 adds the underpayment penalty, late penalty, and interest (lines 34, 36, 37). Under firm policy (2026-10-06) those lines are left blank and billed, so as prepared line 38 equals line 33
- Due April 15, 2027, even with an extension

## Overpayment and refund (lines 39–42)
- If payments and credits exceed net tax, the difference is the overpayment (line 39)
- Line 40: refund contributions (see payments/pit-d-contributions.md), no more than line 39
- Line 41: part or all of the rest applied to 2027 estimated tax; report it next year as a 2027 estimated payment
- Line 42: the refund, by direct deposit or check (direct deposit is not allowed to an account outside the United States)
- A filer with no tax can still have an overpayment because the refundable credits are counted as payments
- Refunds can be reduced or intercepted for debts owed to the state or other agencies

## Status for 2026
No change from the 2026 legislative session.

## Required Information
- How the taxpayer wants an overpayment handled
- Payment method, if tax is owed

## Questions
- If you are due a refund, do you want it refunded, applied to 2027, or partly donated?
- If you owe, how and when will you pay?

## Common Errors
- Entering both an amount owed and an overpayment
- Applying to 2027 or donating more than the overpayment
- Forgetting to report the applied amount on the 2027 return
- Treating an extension as more time to pay

## Prompt
- How is my New Mexico refund figured?
- I owe New Mexico tax; when is it due?
- Can I apply my New Mexico refund to next year?
