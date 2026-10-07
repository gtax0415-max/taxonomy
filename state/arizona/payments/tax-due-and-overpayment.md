---
type: payment
category: balance-due
jurisdiction: AZ
tax_year: 2026
source_doc: Form W-2 box 17 and Forms 1099 showing Arizona tax withheld / estimated and extension payment confirmations / ACA certificates for refundable credits
form: Form 140
line: "59, 60, 61, 63"
via:
  - Lines 53 to 58 → line 59; line 52 vs line 59 → line 60 (tax due) or line 61 (overpayment) → line 62 → line 63
routing:
  - "Line 52 larger → line 60 tax due; skip lines 61 to 63"
  - "Line 59 larger → line 61 overpayment; complete lines 62 and 63"
see_also:
  - payments/overpayment-applied-to-next-year.md
  - payments/refund-and-direct-deposit.md
  - payments/amount-owed-and-payment.md
---
# Total Payments, Tax Due and Overpayment (Form 140, Lines 59, 60, 61 and 63)
## Description
- Line 59: lines 53 through 58.
- Line 60, Tax due: if line 52 is larger than line 59, line 52 - line 59; skip lines 61, 62 and 63.
- Line 61, Overpayment: if line 59 is larger than line 52, line 59 - line 52.
- Line 63, Balance of overpayment: line 61 - line 62, before voluntary gifts and any estimated payment penalty.
## Example
Line 52 $1,186; withholding $1,500; excise credit $0: line 59 $1,500; line 61 $314; nothing applied to 2027, so line 63 $314.
## Notes
- Line 56 to 58 refundable credits are included in line 59; for 2026, box 581 (refundable research credit) is always 0 because Laws 2026, Chapter 140 repealed it
- Form 140 line and box numbers follow the 2025 Form 140; ADOR had not released the 2026 Form 140 when this was revised, so confirm them against it
## Required Information
- Form 140, line 52 (balance of tax)
- Form 140, lines 53 to 58 (payments and refundable credits)
## Questions
- What is your balance of tax and total payments?
## Common Errors
- Completing lines 61 to 63 when tax is due
## Prompt
- How do I know if I owe Arizona or get a refund?
