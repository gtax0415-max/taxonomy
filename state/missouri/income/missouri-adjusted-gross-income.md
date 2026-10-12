---
type: income
category: income
jurisdiction: MO
tax_year: 2026
statute: RSMo 143.091 (federal conformity), 143.121 (modifications)
source_doc: Federal Form 1040 as filed (line 11, adjusted gross income) / each spouse's W-2s, 1099s, and schedules used to split federal AGI between spouses
form: Form MO-1040
line: "1–7"
line_basis: 2025 form numbering (2026 Missouri forms expected December 2026); amounts are 2026
via:
  - Federal AGI → line 1Y/1S
  - Form MO-A Part 1, line 7 → line 2 additions
  - Form MO-A Part 1, line 19 → line 4 subtractions
  - Line 1 + line 2 − line 4 → line 5Y/5S → line 6 total → line 7 each spouse's percentage
---
# Missouri Adjusted Gross Income
## Description
Missouri starts from federal AGI, adds Missouri additions, and subtracts Missouri subtractions, separately for each spouse on a combined return.

## Amounts for 2026
- Line 3 = line 1 + line 2; line 5 = line 3 − line 4 (per spouse); line 6 = 5Y + 5S; line 7 = each spouse's share of line 6 (totals 100%)
- Missouri follows the federal Code as currently in effect, so 2025 federal law changes that affect federal AGI flow through
- The federal deductions for tips, overtime, car-loan interest, and the senior deduction are below AGI and are NOT allowed on the Missouri return

## Eligibility
- Every return

## Notes
- Married filing combined: split federal AGI between spouses using the worksheet in the instructions; the two shares must equal total federal AGI
- Negative federal AGI on a non-combined return → enter $0
- If one spouse's Missouri AGI is negative, line 7 is 0% for that spouse and 100% for the other
- Example: line 1Y $60,000, additions $500, subtractions $2,000 → line 5Y $58,500

## Required Information
- Federal AGI and each spouse's share
- Total additions and subtractions from MO-A

## Questions
- Are you filing a combined Missouri return with your spouse?
- How much of the federal AGI belongs to each spouse?

## Common Errors
- Using total AGI instead of each spouse's share
- Taking the federal tips or overtime deduction on the Missouri return

## Prompt
- What is Missouri adjusted gross income?
