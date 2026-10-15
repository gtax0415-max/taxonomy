---
type: tax-computation
category: net-income-tax
jurisdiction: CO
tax_year: 2026
source_doc: None — computed from the return (tax, AMT, recapture, nonrefundable credits and DR 0619 repayment)
form: Form DR 0104
line: "16, 21, 23"
via:
  - Line 16 = Lines 13 + 14 + 15 → − Lines 17–20 (not below zero) → Line 21 → + Line 22 → Line 23 → compared with Line 39
routing:
  - "Lines 17 + 18 + 19 + 20 cannot exceed line 16"
  - "Line 21 cannot be negative"
see_also:
  - credits/nonrefundable/nonrefundable-credit-limit.md
  - tax-computation/repayment-of-credit-dr0619.md
  - payments/overpayment-and-refund.md
---
# Subtotal, Net Income Tax and Net Tax
## Description
Tax plus alternative minimum tax and credit recapture, reduced by nonrefundable credits, plus any dealer / e-bike credit repayment, gives the net tax that is compared with payments.

## Amount
- Line 16: tax (13) + AMT (14) + recapture (15)
- Line 21: line 16 − nonrefundable credits (17), enterprise zone (18), CHIPS Zone (19), Strategic Capital (20); not below zero
- Line 23: line 21 + repayment (22)

## Notes
- Example: tax $3,630, no AMT or recapture → line 16 $3,630; long-term care credit $150 → line 21 $3,480; no repayment → line 23 $3,480

## Required Information
- Tax, AMT, recapture, nonrefundable credits, repayment

## Questions
- Do you have any Colorado nonrefundable credits or credit repayments?

## Common Errors
- Letting nonrefundable credits push line 21 below zero

## Prompt
- How is Colorado net tax figured?
