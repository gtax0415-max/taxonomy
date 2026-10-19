---
type: filing
category: filing
jurisdiction: MS
tax_year: 2026
source_doc: Federal Form 1040 as filed / each spouse's Forms W-2 (by SSN), 1099s, and federal Schedules C, E, F
form: Form 80-105
line: "1"
via:
  - Filing status Line 1 → each spouse's income in own column (Column A taxpayer, Column B spouse) → Lines 14–15 split → Line 16 by column → Schedule of Tax Computation
---
# Married Combined Return
## Description
One return on line 1 when BOTH spouses have income. Each spouse's income goes in that spouse's column, and each column gets its own first $10,000 at 0%. The exemption and deduction may be split between columns in any manner.
## Why it matters
- Two zero-rate bands instead of one: up to $400 less tax in 2026 than putting all income in one column
## Rules
- Income follows ownership: each spouse's W-2s, business, and investment income go in that spouse's column
- Deductions and exemptions: split freely (see deduction-division.md and exemption-division.md)
- If one column ends negative, the negative-column rule applies (see negative-column.md)
## Example (2026)
- Spouse A $50,000, Spouse B $30,000; total deduction and exemption $16,600 split $8,300 each → A $41,700, B $21,700 → ($31,700 + $11,700) × 4% = $1,736
- All in one column: ($80,000 − $16,600 − $10,000) × 4% = $2,136
## Required Information
- Each spouse's income
## Questions
- Do both you and your spouse have income?
- Whose name is on each W-2 or business?
## Common Errors
- Placing all income in Column A
- Splitting one spouse's income between columns
- Letting a column go negative through poor allocation
## Prompt
- We both work. How do we file in Mississippi?
