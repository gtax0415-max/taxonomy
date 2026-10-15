---
type: deduction
category: subtractions
jurisdiction: UT
tax_year: 2026
source_doc: Form 1099-G for the state income tax refund received in 2026 / 2026 federal Schedule 1, line 1 / 2025 federal return showing whether deductions were itemized (Schedule A)
form: Form TC-40
line: "5"
via:
  - Federal Schedule 1, line 1 → Form TC-40, line 5 → subtracted in line 7
---
# State Tax Refund Included on the Federal Return
## Description
A state income tax refund is taxable federally if the tax was deducted on the prior-year federal Schedule A. Utah removes it so the refund is not taxed in Utah (UCA §59-10-114(2)(c)).

## Amount
- If you ITEMIZED on your 2025 federal return: line 5 = the amount on 2026 federal Schedule 1, line 1
- Otherwise leave line 5 blank (nothing was included in federal AGI)

## Notes
- Line 5 is a separate subtraction line on the 2026 return, not part of the TC-40_A Part 6 subtractions
- Schedule 1 line 1 may include refunds from any state, not just Utah, and Utah removes the full amount reported there
- Part-year and nonresidents: TC-40_B line 32 Column A takes only the part related to Utah tax
- Refunds a trust distributed to a beneficiary use subtraction SU008PT instead

## Required Information
- 1099-G amount
- Schedule 1, line 1 amount
- Whether 2025 deductions were itemized

## Questions
- Did you get a state income tax refund in 2026?
- Did you itemize deductions on your 2025 federal return?

## Common Errors
- Subtracting a refund that was never in federal AGI (2025 standard deduction)
- Entering the 1099-G amount instead of the taxable amount on Schedule 1, line 1

## Prompt
- I got a Utah refund last year and it shows on my federal return. Is it taxed in Utah?
