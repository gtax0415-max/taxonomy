---
type: payment
category: payments
jurisdiction: AL
tax_year: 2026
source_doc: W-2, 1099 and W-2G forms showing Alabama tax withheld / estimated and extension payment records / Schedule K-1 showing PTE tax paid / original return and refund records (amended returns only) / bank routing and account numbers for direct deposit
form: Form 40
line: "22–35"
refundable: yes
via:
  - Lines 22 + 23 + 24 + 25 + 26 → line 27 total payments → minus line 28 → line 29 adjusted total payments
  - Line 21 > line 29 → line 30 amount you owe (including line 31 penalties)
  - Line 29 > line 21 → line 32 overpaid → minus lines 31, 33, 34 → line 35 refund
---
# Payments, Overpayment and Refund
## Description
Totals the payments and refundable credits, compares them to the tax, and figures the balance due or the refund.

## Lines (2025 form numbering; confirm on the 2026 form)
- Line 22: Alabama income tax withheld
- Line 23: 2026 estimated and extension payments
- Line 24: amended returns only, payments already made
- Line 25: refundable credits from Schedule OC, Section F, line F6
- Line 26: payments from Schedule CP
- Line 27: total payments
- Line 28: amended returns only, refunds already received
- Line 29: adjusted total payments (27 minus 28)
- Line 30: amount you owe (21 minus 29, plus line 31)
- Line 31: penalties from Schedule ATP
- Line 32: amount overpaid (29 minus 21)
- Line 33: part of the overpayment applied to 2027 estimated tax
- Line 34: donation check-offs from Schedule DC
- Line 35: refund (32 minus 31, 33 and 34)

## Notes
- An amount applied to 2027 on line 33 cannot later be refunded
- Schedule DC donations come only from an overpayment and cannot be reversed
- Direct deposit: check the box on page 1 and complete Part V on page 2
- A refund can be offset for Alabama or IRS debts
- Late payment penalty: 1% a month, up to 25%; interest runs from April 15, 2027

## Example
Overpaid $500, $25 donated on Schedule DC: refund is $475.

## Required Information
- All withholding documents
- Payments and refundable credits
- Amount to apply to 2027 and any donations
- Bank details for direct deposit

## Questions
- Do you want your refund deposited directly?
- Do you want to apply any overpayment to 2027?
- Do you want to donate to any check-off fund?

## Common Errors
- Applying or donating more than the overpayment
- Forgetting line 28 on an amended return
- Entering a wrong routing or account number

## Prompt
- How is my Alabama refund figured?
