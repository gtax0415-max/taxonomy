---
type: income
category: retirement
jurisdiction: CA
tax_year: 2026
source_doc: Form 1099-R (IRA and Roth IRA distributions and conversions) / Form 5498 records of contributions / records of prior-year IRA contributions that were deductible federally but not in California (basis records) / federal Form 8606 as filed
form: Form 540
line: "13, 14, 16"
via:
  - Form 1099-R → federal Form 1040, Line 4b → federal AGI → Form 540, Line 13
  - "California taxable amount smaller: Schedule CA (540), Part I, Section A, Line 4, column B → Line 14"
  - "California taxable amount larger: Schedule CA (540), Part I, Section A, Line 4, column C → Line 16"
---
# IRA Distributions
## Description
IRA distributions are generally taxed the same way in both systems, but the taxable amount can differ when California and federal BASIS differ.

## When an adjustment is needed
- California IRA deductions differed from federal deductions in earlier years (for example, because of different self-employment income), so California basis differs
- A conversion from a traditional IRA to a Roth IRA where California basis differs
- A filer who was a nonresident in earlier years may need to restate California IRA basis (FTB Publication 1100)
- Use FTB Publication 1005 worksheets to compute the difference

## Coverdell education savings accounts
- A taxable Coverdell distribution may trigger California's additional tax on FTB 3805P (see other-taxes/retirement-account-penalties.md)

## Notes
- Line numbers follow the 2025 Form 540 and schedules; confirm them on the 2026 forms (expected December 2026)
- Early distributions before 59½ also trigger the California 2.5% additional tax

## Required Information
- 1099-R amounts and codes
- California basis history

## Questions
- Did you take an IRA distribution or convert to a Roth IRA?
- Were your IRA deductions ever different on your California return?
- Did you live outside California when you made contributions?

## Common Errors
- Using federal basis when California basis differs
- Ignoring basis from years as a nonresident

## Prompt
- I converted my traditional IRA to a Roth this year.
