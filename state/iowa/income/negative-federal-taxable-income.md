---
type: income
category: income
jurisdiction: IA
tax_year: 2026
source_doc: Federal Form 1040 as filed: line 11a (AGI), line 12e (standard or itemized deduction), line 12f (non-itemizer charitable deduction), line 13a (Schedule 1-A deductions), line 13b (QBI deduction), and line 15 (taxable income, zero)
form: Form IA 1040
line: "2"
via:
  - "If federal line 15 is zero: IA line 1c − IA line 1d − IA line 1e − federal line 12f − federal line 13a → Form IA 1040, line 2 (may be negative)"
---
# Line 2 When Federal Taxable Income Is Zero
## Description
Federal taxable income can never be below zero, but the deductions may exceed income. Iowa recomputes line 2 so the excess deductions are not lost, which lets Iowa additions on Schedule 1 be absorbed.

## Rule for 2026
- If federal Form 1040 line 15 is zero, line 2 = IA line 1c (federal AGI) − IA line 1d (standard or itemized deduction) − IA line 1e (QBI deduction, 2026 federal line 13b) − federal line 13a (Schedule 1-A deductions: tips, overtime, car loan interest, senior deduction) − federal line 12f (non-itemizer charitable deduction, new for 2026)
- The result may be NEGATIVE, for Iowa purposes only
- If no federal return is required and the would-be line 15 is zero, use the same computation
- 2026 federal line changes: on the 2026 draft Form 1040 the Schedule 1-A deductions moved to line 13a and QBI to line 13b (the 2025 Iowa instruction subtracts "line 13b," which meant Schedule 1-A on the 2025 form). The new line 12f non-itemizer charitable deduction (up to $1,000, $2,000 joint) also reduces federal taxable income, so it is subtracted here so line 2 matches federal taxable income before the zero floor. Confirm against the 2026 IA 1040 instructions

## Example
- AGI $14,000; standard deduction $16,100; no other deductions; Iowa Schedule 1 additions $3,000 of out-of-state municipal interest
- Federal line 15 = 0; Iowa line 2 = 14,000 − 16,100 = −$2,100
- Line 4 = −2,100 + 3,000 = $900 Iowa taxable income

## Required Information
- Federal Form 1040 lines 11a, 12e, 12f, 13a, 13b, and 15

## Questions
- Was your federal taxable income zero?
- Do you have any Iowa additions, such as municipal bond interest?

## Common Errors
- Entering zero on line 2 and losing the excess deduction
- Leaving out the Schedule 1-A deductions (2026 line 13a) or the line 12f charitable deduction
- Using the 2025 line numbers (13a/13b are swapped on the 2026 form)
- Carrying a negative line 2 to anything other than the Iowa computation

## Prompt
- My federal taxable income is zero. What goes on Iowa line 2?
- Can Iowa line 2 be negative?
