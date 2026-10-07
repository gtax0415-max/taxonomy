---
type: tax
category: tax-computation
jurisdiction: new-jersey
tax_year: 2026
source_doc: No external source document — computed from New Jersey taxable income
form: Form NJ-1040
line: "42, 43, 45, 49, 50, 54"
via:
  - Line 39 − Line 41 → Line 42 (NJ taxable income)
  - Line 42 → Tax Table (under $100,000) or Tax Rate Schedule (A or B) → Line 43
routing:
  - "Line 42 under $100,000 → Tax Table"
  - "Line 42 $100,000 or more → Tax Rate Schedules"
  - "Single or married/CU partner filing separately → Table A"
  - "Joint, head of household, qualifying widow(er) → Table B"
---
# Tax Computation (Lines 42–54)
## Description
New Jersey tax is a graduated tax on NJ taxable income (Line 42). The brackets are set by statute, are NOT indexed for inflation, and are UNCHANGED for 2026 (the FY2027 budget did not change the rates).
## 2026 Tax Rate Schedule A — Single; Married/CU partner filing separately
| NJ taxable income over | But not over | Multiply by | Subtract |
|---|---|---|---|
| $0 | $20,000 | 1.4% | $0 |
| $20,000 | $35,000 | 1.75% | $70.00 |
| $35,000 | $40,000 | 3.5% | $682.50 |
| $40,000 | $75,000 | 5.525% | $1,492.50 |
| $75,000 | $500,000 | 6.37% | $2,126.25 |
| $500,000 | $1,000,000 | 8.97% | $15,126.25 |
| $1,000,000 | — | 10.75% | $32,926.25 |
## 2026 Tax Rate Schedule B — Married/CU couple filing jointly; Head of household; Qualifying widow(er)/surviving CU partner
| NJ taxable income over | But not over | Multiply by | Subtract |
|---|---|---|---|
| $0 | $20,000 | 1.4% | $0 |
| $20,000 | $50,000 | 1.75% | $70.00 |
| $50,000 | $70,000 | 2.45% | $420.00 |
| $70,000 | $80,000 | 3.5% | $1,154.50 |
| $80,000 | $150,000 | 5.525% | $2,775.00 |
| $150,000 | $500,000 | 6.37% | $4,042.50 |
| $500,000 | $1,000,000 | 8.97% | $17,042.50 |
| $1,000,000 | — | 10.75% | $34,842.50 |
Tax = Line 42 × rate − subtraction amount. Example: single, Line 42 = $90,000 → $90,000 × 6.37% − $2,126.25 = $3,606.75.
## Lines after Line 43
- LINE 45 Balance of tax = Line 43 − Line 44 (credit for taxes paid to other jurisdictions)
- LINE 49 Total nonrefundable credits = Lines 46 + 47 + 48
- LINE 50 Balance of tax after credits = Line 45 − Line 49; if zero or less, no entry
- LINE 54 Total tax due = Line 50 + Line 51 + Line 52 + Line 53c
## Notes
- New Jersey has no separate capital gains rate, no alternative minimum tax, and no standard deduction
- The top rate (10.75%) applies to all NJ taxable income over $1 million; the 8.97% bracket applies from $500,000
- Line 42 is also the income test for the NJ Child Tax Credit and the NJ Child and Dependent Care Credit
- Line 45 is the tax base for the extension 80% test and for the Sheltered Workshop credit limit
## Questions
- What is your filing status?
- What is your NJ taxable income on Line 42?
## Common Errors
- Using the wrong schedule for the filing status (head of household uses Table B)
- Using the Tax Table when Line 42 is $100,000 or more
- Applying the rate to Line 39 instead of Line 42 (after the property tax deduction)
## Prompt
- What are New Jersey's income tax brackets for 2026?
- How much New Jersey tax do I owe on $120,000?
