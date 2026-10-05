---
type: income
category: add-back
jurisdiction: IN
tax_year: 2026
source_doc: Federal Form 8990 (limitation on business interest expense under IRC 163(j)) for the current and prior years / K-1s reporting excess business interest
form: Schedule 1
line: "6 (code 142)"
via:
  - Business interest disallowed federally under IRC 163(j) in the year first paid or accrued → Schedule 1, Line 6, code 142 (negative) → Line 7 → Form IT-40, Line 2
  - Federally carried-over business interest deducted this year → Schedule 1, Line 6, code 142 (positive)
routing:
  - "Business interest disallowed by 163(j) this year → subtract it (negative entry)"
  - "Deducting 163(j) carryover interest from a prior year federally → add it back (positive entry)"
see_also:
  - income/add-backs/add-backs.md
  - income/add-backs/excess-business-loss-modification-151.md
---
# Excess Federal Interest Deduction Modification (Schedule 1, Line 6, Code 142)
## Description
IRC Section 163(j) limits the federal deduction for most business interest (generally to 30% of adjusted taxable income plus business interest; 50% for 2019 and 2020 in certain cases). Indiana has decoupled from this limit. In the year the interest is first paid or accrued, subtract the amount of excess business interest disallowed under 163(j). In a later year when you deduct carried-over business interest federally, add that amount back. Both use code 142.
## Example
2026: Form 8990 disallows $12,000 of business interest → code 142 = -12000. 2027: $5,000 of that carryover is deducted federally → code 142 = 5000 on the 2027 return.
## Questions
- Did you or a pass-through entity file Form 8990 or report excess business interest?
- Did you deduct 163(j) carryover interest this year?
## Common Errors
- Entering the disallowed amount as positive
- Deducting the carryover again for Indiana in the later year
## Prompt
- Does Indiana follow the federal business interest limitation?
