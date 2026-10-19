---
type: computation
category: tax-computation
jurisdiction: NM
tax_year: 2026
source_doc: Computed on the return / for line 20, the other state's return as filed; for line 21, the certificates behind each PIT-CR credit
form: Form PIT-1
line: "22"
via:
  - Lines 18 + 19 − 20 − 21 → PIT-1, Line 22 → Line 23 → Lines 32–39
---
# Net New Mexico Income Tax (Line 22)
## Description
The New Mexico tax after nonrefundable credits, before payments. Refundable credits are counted later, as payments.

## Formula
- Line 18: tax on New Mexico taxable income
- + Line 19: additional tax on lump-sum distributions
- − Line 20: credit for taxes paid to another state (attach the other state's return)
- − Line 21: nonrefundable business-related credits applied (PIT-CR line A)
- = Line 22, not less than zero

## Notes
- PIT-CR line A cannot exceed lines 18 + 19 minus line 20
- Refundable credits (PIT-RC, working families tax credit, refundable PIT-CR) are NOT subtracted here; they are payments on lines 24–26
- Line 20 is covered in credits/other-state/tax-paid-another-state.md (out of scope for full-year residents with New Mexico income only)

## Status for 2026
No change from the 2026 legislative session.

## Required Information
- Tax from the rate table (line 18) and any lump-sum tax (line 19)
- Nonrefundable PIT-CR credits applied

## Questions
- Did you pay income tax to another state on income also taxed by New Mexico?
- Do you have any PIT-CR credit certificates?

## Common Errors
- Subtracting refundable credits here
- Allowing line 22 to go below zero

## Prompt
- How is my net New Mexico tax figured?
