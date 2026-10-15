---
type: payment
category: withholding
jurisdiction: CO
tax_year: 2026
source_doc: Forms W-2 (Colorado withholding, box 17) / Forms W-2G / Forms 1099 (1099-R, 1099-NEC, 1099-MISC, 1099-G) showing Colorado tax withheld / final pay stub, if no W-2 was issued
form: Form DR 0104
line: "24"
via:
  - W-2, W-2G and 1099 Colorado withholding → Form DR 0104, Line 24 → Line 33
routing:
  - "Colorado state withholding only; not federal, other-state or local withholding"
  - "Real estate sale withholding or nonresident beneficiary withholding → line 28 instead"
  - "Employer did not issue a W-2 → substitute W-2 using the final pay stub"
see_also:
  - payments/other-prepayments.md
  - tax-computation/estimated-tax-penalty-dr0204.md
---
# Colorado Income Tax Withheld
## Description
Colorado income tax withheld from wages, gambling winnings, pensions and other payments during 2026.

## Amount
- Total Colorado withholding shown on all W-2s, W-2Gs and 1099s

## Notes
- E-filed returns must include each payer's FEIN and the Colorado withholding; missing information causes the amount to be adjusted
- Paper returns must attach the W-2s and 1099s
- If no W-2 was received, file a substitute W-2 (DR 0084) with the final pay stub
- Example: two W-2s with Colorado withholding of $1,820 and $640 → line 24 $2,460

## Required Information
- Each W-2, W-2G and 1099 with Colorado withholding
- Payer FEIN

## Questions
- How much Colorado tax was withheld on your 2026 W-2s, W-2Gs and 1099s?
- Did any employer fail to send a W-2?

## Common Errors
- Including federal or other-state withholding
- Putting real estate withholding on line 24

## Prompt
- Where do I enter Colorado withholding?
