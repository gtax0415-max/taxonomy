---
type: computation
category: taxes
jurisdiction: MS
tax_year: 2026
source_doc: Each spouse's Forms W-2, 1099, and federal Schedules C, E, F (income or loss by spouse) / no separate source document for the rule itself
form: Form 80-105
line: "17"
via:
  - Form 80-105, Line 16, Columns A and B → combine if one is negative → Schedule of Tax Computation, Column A only → Line 17
---
# One Column Negative on a Combined Return
## Description
Applies to married joint/combined returns and the "spouse died" status. When one spouse's column has positive taxable income and the other's is negative, the two are netted and the net is taxed in Column A only.
## Rules
- Both columns positive: tax each column, each with its own $10,000 at 0%
- One positive, one negative: add them together. If the net is positive, tax it in Column A using ONE $10,000 zero-rate band. If the net is zero or negative, no tax
- Both negative: no tax
## Example (2026)
- Column A $40,000; Column B −$6,000 → net $34,000 in Column A → ($34,000 − $10,000) × 4% = $960
## Notes
- A negative column usually comes from a business, farm, or rental loss, or from putting too much of the deduction and exemption in a low-income spouse's column. Reallocating deductions (see deduction-division.md) can keep both columns at or above zero and preserve two zero-rate bands
## Required Information
- Taxable income by column on line 16
## Questions
- Does either spouse have a business, farm, or rental loss?
- Can deductions and exemptions be reallocated to avoid a negative column?
## Common Errors
- Taxing the positive column alone and ignoring the other spouse's loss
- Giving the netted amount two $10,000 zero-rate bands
- Creating a negative column through poor allocation of deductions
## Prompt
- My spouse had a business loss. How does that work on our Mississippi combined return?
