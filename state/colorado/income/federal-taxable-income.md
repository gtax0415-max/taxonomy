---
type: income
category: federal-taxable-income
jurisdiction: CO
tax_year: 2026
source_doc: Federal Form 1040, 1040-SR or 1040-SP as filed (line 15, taxable income)
form: Form DR 0104
line: "1"
via:
  - Form 1040, Line 15 → Form DR 0104, Line 1 → Line 10 (with additions) → Line 12
routing:
  - "Negative federal taxable income → enter as a negative amount"
  - "Never enter total income, wages or AGI here"
see_also:
  - income/federal-deductions-flowing-through.md
  - income/colorado-taxable-income.md
  - filing/whole-dollar-rounding.md
---
# Federal Taxable Income
## Description
Colorado income tax starts from federal taxable income. It already reflects the federal standard or itemized deduction, the QBI deduction, and the new federal Schedule 1-A deductions (tips, overtime, car loan interest, seniors). Colorado then adds back or subtracts specific items.

## Amount
- Federal taxable income from Form 1040 line 15 (confirmed on the 2026 draft Form 1040): line 11b AGI minus line 14, where line 14 = line 12e (standard or itemized) + 12f (non-itemizer charitable) + 13a (Schedule 1-A) + 13b (QBI)
- 2026 federal standard deduction: $16,100 single and married filing separately; $32,200 joint; $24,150 head of household

## Notes
- DOR matches this line against the federal return filed with the IRS
- Example: single filer, wages $68,000, standard deduction $16,100 → federal taxable income $51,900 → line 1 $51,900

## Required Information
- Completed 2026 federal return

## Questions
- What is the taxable income on your 2026 federal return?

## Common Errors
- Entering wages or AGI instead of taxable income
- Entering a negative amount as zero

## Prompt
- Where does the Colorado return start?
