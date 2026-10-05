---
type: tax
category: tax-computation
jurisdiction: IN
tax_year: 2026
form: Form IT-40
line: "8-11"
---
# Tax Computation (Form IT-40, Lines 8-11)
## Description
Indiana income tax has two parts, both computed on Indiana adjusted gross income (Form IT-40, line 7): the flat state adjusted gross income tax (line 8, 2.95% for 2026) and the county tax (line 9, from Schedule CT-40, at the rate of the county where you lived on January 1). Other taxes from Schedule 4 (use tax, household employment taxes, credit recapture) are added on line 10; they are in other-taxes/. Line 11 totals the Indiana taxes and carries to line 15, where credits (lines 12-14) are applied. The penalty for underpayment of estimated tax (line 20) is in payments/underpayment-penalty.md.
## Rates for 2026
| Tax | Rate | Line |
|---|---|---|
| State adjusted gross income tax | 2.95% (the 2025 form prints 3%) | 8 |
| County tax | county of residence on Jan. 1, 2026 (Schedule CT-40 chart; for example Marion .0202, Hamilton .011, Lake .015) | 9 |
## How the lines flow
```
Line 7   Indiana adjusted gross income (line 5 - line 6)
Line 8   State adjusted gross income tax = line 7 x 2.95% (leave blank if less than zero)
Line 9   County tax from Schedule CT-40, line 7 (leave blank if less than zero)
Line 10  Other taxes from Schedule 4, line 4 → other-taxes/
Line 11  Indiana taxes = lines 8 + 9 + 10 → line 15
Lines 12-14  Credits (Schedule 5) and offset credits (Schedule 6) → credits/
```
## Files in this folder
- tax-computation.md - this index (Form IT-40, lines 8-11)
- state-adjusted-gross-income-tax.md - line 8
- county-tax.md - line 9, Schedule CT-40 lines 1-7, county rules
- county-tax-rates-2026.md - 2026 county rates and codes, January and October 2026 changes
## Related
- other-taxes/other-taxes.md - line 10 (Schedule 4)
- payments/underpayment-penalty.md - line 20
- deductions/deductions.md - lines 4-7
- credits/credits.md - lines 12-14
- payments/payments.md - lines 15-26
## Questions
- What is your Indiana adjusted gross income (line 7)?
- In which Indiana county did you (and your spouse) live and work on January 1, 2026?
## Prompt
- What is the Indiana income tax rate for 2026?
- How is Indiana county tax calculated?
