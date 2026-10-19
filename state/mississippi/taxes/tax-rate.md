---
type: computation
category: taxes
jurisdiction: MS
tax_year: 2026
source_doc: Forms W-2, 1099, and federal Form 1040 with schedules (income that builds Mississippi taxable income) / no separate source document for the rate itself
form: Form 80-105
line: "17"
via:
  - Form 80-105, Line 16 (by column) → Schedule of Tax Computation, Lines 1–4 → Form 80-105, Line 17
  - "Nonresident/part-year: Form 80-205, Line 19 → Schedule of Tax Computation → Line 20"
---
# Mississippi Income Tax (0% and 4%)
## Description
Two-tier flat tax: the first $10,000 of taxable income is taxed at 0% and the rest at a single rate. On a combined return, each spouse's column gets its own $10,000 at 0%.
## Rates
- 2026: 0% on the first $10,000; 4.0% on taxable income over $10,000 (down from 4.4% for 2025) — Miss. Code Ann. §27-7-5 as amended by HB 531 (2022) and HB 1 (2025)
- Scheduled under HB 1 (2025): 3.75% for 2027, 3.5% for 2028, 3.25% for 2029, 3.0% for 2030; further cuts from 2031 only if revenue triggers are met
- No separate capital gains rate
## Computation
- Line 1: first $10,000 of each column × 0%
- Line 2: remaining taxable income of each column × 4%
- Line 4: total tax → Form 80-105, line 17
## Example (2026)
- Single, taxable income $50,000: ($50,000 − $10,000) × 4% = $1,600
- Combined return, Column A $30,000 and Column B $25,000: ($20,000 + $15,000) × 4% = $1,400 (one combined column of $55,000 would owe $1,800)
## Notes
- The 2025 booklet still prints 4.4%; use 4.0% for 2026
- If one column is negative, see negative-column.md
## Required Information
- Mississippi taxable income by column (Form 80-105, line 16)
- Filing method (joint, combined, separate)
## Questions
- Is this a combined return with income in both columns?
- Is either column negative?
## Common Errors
- Using the 2025 rate of 4.4% for 2026
- Applying only one $10,000 zero-rate band to a combined return with two earners
- Applying 4% to the first $10,000
## Prompt
- What is the Mississippi income tax rate for 2026?
- How much Mississippi tax do I owe on $50,000 of taxable income?
