---
type: payment
category: overpayment-refund
jurisdiction: CO
tax_year: 2026
source_doc: None — computed from the return (payments and refundable credits less net tax)
form: Form DR 0104
line: "42"
via:
  - Lines 24–32 → Line 33 → + Line 38 = Line 39 → Line 39 − Line 23 = Line 40 → − Line 41 carryforward → Line 42 refund
routing:
  - "Line 23 greater than line 39 → amount owed; see net-tax-due-and-amount-owed"
  - "Refund by direct deposit (bank or CollegeInvest) or by check"
  - "Refund taken for a Colorado or IRS debt and the joint filer is not responsible → injured spouse claim"
see_also:
  - payments/estimated-tax-carryforward.md
  - payments/direct-deposit.md
  - contributions-checkoffs/voluntary-contributions.md
---
# Subtotal, Overpayment and Refund
## Description
Payments and refundable credits are totaled and compared with net tax. Any excess is the overpayment, which can be refunded, applied to 2027 estimated tax, or partly donated.

## Amount
- Line 33: lines 24 – 32 (withholding, carryforward, estimates, extension payment, other prepayments, conservation easement, innovative vehicle, refundable credits, dealer / e-bike credit)
- Line 39: line 33 + line 38 (TABOR refund, $0 for 2026)
- Line 40: line 39 − line 23 (when positive)
- Line 42: line 40 − line 41

## Notes
- Voluntary contributions reduce the refund
- DOR intercepts refunds for debts to Colorado or the IRS
- Injured spouse claims go separately to the Injured Spouse Desk, PO Box 17087, Denver, CO 80217-0087, with federal Form 8379, the federal return and all W-2s and 1099s
- Example: line 23 $2,400; line 24 $2,460 and line 31 $600 → line 33 $3,060; line 40 $660; line 42 $660

## Required Information
- Payment and credit totals from the return
- Refund method

## Questions
- Do you want your refund by direct deposit or check?
- Do you owe any Colorado or IRS debts?

## Common Errors
- Including line 38 in line 33
- Sending the injured spouse claim with the return

## Prompt
- How is my Colorado refund figured?
