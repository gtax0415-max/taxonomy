---
type: exclusion
category: taxable-social-security
jurisdiction: LA
tax_year: 2026
source_doc: Form SSA-1099 or RRB-1099 / federal Form 1040, Line 6b (taxable Social Security)
form: Form IT-540, Schedule E
line: "Schedule E, Lines 4A to 4G, code 07E"
via:
  - Federal Form 1040, Line 6b → Schedule E code 07E → Line 4H → Line 5 → Form IT-540, Line 7
---
# Taxable Social Security (Code 07E)
## Description
Social Security benefits are fully exempt in Louisiana, so the amount taxed on the federal return is subtracted.

## Rules
- Subtract the federally taxable amount (Form 1040 Line 6b)
- No limit; no age or income test

Example: taxable Social Security of $7,020 → $7,020 exempt.

## Notes
- Authority: R.S. 47:44.2. Unchanged for 2026
- The new federal senior deduction for 2025–2028 is taken after federal AGI and doesn't affect this line

## Required Information
- Federal taxable Social Security

## Questions
- Did you receive Social Security benefits?

## Common Errors
- Subtracting total benefits instead of the taxable amount
- Forgetting the subtraction entirely

## Prompt
- Is Social Security taxed in Louisiana?
