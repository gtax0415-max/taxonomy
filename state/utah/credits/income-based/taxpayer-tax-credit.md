---
type: credit
category: income-based
jurisdiction: UT
tax_year: 2026
source_doc: 2026 federal Form 1040 (line 12e standard or itemized deduction; Dependents section) / 2026 federal Schedule A lines 5a–5e, if itemized
form: Form TC-40
line: "18"
refundable: no
via:
  - Line 9 (dependents × $2,167) + line 10 (federal 1040 line 12e) − line 12 (state income tax itemized) = line 13 → × 6% = line 14 → − 1.3% × (line 7 − line 15 base) = line 18 → line 20
---
# Taxpayer Tax Credit
## Description
Utah's substitute for exemptions and deductions. Every filer gets a credit of 6% of their federal deduction plus Utah personal exemptions, phased out by 1.3% of Utah taxable income above a base amount.

## Amount
1. Line 9: dependents × $2,167
2. Line 10: federal standard or itemized deduction (Form 1040 line 12e; 1040-NR line 12)
3. Line 12: state income tax included in federal itemized deductions (Schedule A line 5e − lines 5b and 5c, excluding any state tax lost to the federal SALT phase-down)
4. Line 13 = line 9 + line 10 − line 12
5. Line 14 = line 13 × 6%
6. Line 15 base phase-out amount for 2026:
   - Single / married filing separately: $18,696
   - Head of household: $28,045
   - Married filing jointly / qualifying surviving spouse: $37,392
7. Line 16 = line 7 − line 15 (not below zero)
8. Line 17 = line 16 × 1.3%
9. Line 18 credit = line 14 − line 17 (not below zero)

## 2026 Changes
- HB 77 (2026) modified this credit to align with federal tax changes, applying from January 1, 2026; the instructions now exclude state income tax phased out by the federal SALT limit
- Base amounts are indexed for inflation
- Personal exemption up from $2,111 (2025)

## Notes
- Federal deductions outside line 12e (Schedule 1-A tips/overtime/car loan/senior, non-itemizer charitable, QBI) do not enter
- Line 20 = line 8 − line 18

## Required Information
- Line 1 dependents; federal 1040 line 12e; Schedule A line 5 detail; line 7

## Questions
- Did you itemize, and did you deduct state income tax?

## Common Errors
- Using 2025 base amounts or exemption
- Leaving state income tax in line 13
- Adding Schedule 1-A deductions to line 10

## Prompt
- How does Utah's taxpayer tax credit work?
