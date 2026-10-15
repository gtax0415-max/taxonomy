---
type: income
category: income
jurisdiction: IA
tax_year: 2026
source_doc: Federal Form 1040 or 1040-SR as filed, line 15 (taxable income) / Forms W-2, 1099, and K-1 that support it
form: Form IA 1040
line: "2"
via:
  - Federal Form 1040, line 15 → Form IA 1040, line 2 → + IA Schedule 1 net modifications (line 3) → line 4 Iowa taxable income → × 3.8% → line 5
---
# Federal Taxable Income
## Description
For tax years beginning on or after January 1, 2023, Iowa's starting point is FEDERAL TAXABLE INCOME, not federal AGI. Every federal income item, adjustment, and deduction reaches Iowa through this one line, and Iowa differences are then made on Schedule 1.

## Rules for 2026
- Enter federal Form 1040 line 15
- Rolling conformity: Iowa automatically follows federal changes, including OBBBA, unless Iowa law says otherwise
- Iowa taxable income (line 4) = line 2 + Schedule 1 net modifications (line 3)
- Tax: flat 3.8% of line 4 for every filing status
- If federal taxable income is zero, a special computation applies and the result can be negative (see negative-federal-taxable-income.md)
- If no federal return is required, complete one anyway for Iowa purposes and use the amount that would be on line 15

## What flows in automatically
- The federal standard deduction (2026: $16,100 single and married filing separately, $32,200 married filing jointly, $24,150 head of household) or itemized deductions
- The federal QBI deduction
- OBBBA deductions for tips, overtime, car loan interest, seniors, and (new for 2026) the non-itemizer charitable deduction
- Federal personal exemption remains zero

## Notes
- Because the deductions are already in line 2, Iowa has no separate standard deduction or itemized schedule
- Complete the federal return first; Iowa lines 1a–1f and 2 come from it
- Federal line numbers checked against the 2026 draft Form 1040 (IRS e-file test scenarios, September 2026): line 15 (taxable income) and line 27a (EIC) are unchanged; confirm against the final form

## Required Information
- Completed 2026 federal Form 1040

## Questions
- Have you completed your 2026 federal return?
- Was your federal taxable income zero?

## Common Errors
- Starting from federal AGI (the pre-2023 method)
- Subtracting the standard deduction again on the Iowa return
- Leaving line 2 blank for a taxpayer with no federal filing requirement

## Prompt
- Where does my Iowa return start?
- Does Iowa use my federal AGI or taxable income?
