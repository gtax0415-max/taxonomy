---
type: tax
category: new-york-city
jurisdiction: NYC
source_doc: Form IT-196, lines 16a and 16b (contributions to the New York Charitable Gifts Trust Fund) / Form IT-201, lines 33, 34, 36, and 38 / records of contributions to the Health Charitable Account or the Elementary and Secondary Education Account
form: Form IT-201
line: "47"
refundable: no
via:
  - Form IT-201, Line 38 → Form IT-201, Line 47 (no adjustment, the normal case)
  - Line 47 worksheet in the Form IT-201 instructions → Form IT-201, Line 47 (Charitable Gifts Trust Fund case)
---
# New York City Taxable Income Adjustment
## Description
THE ONLY INCOME ADJUSTMENT New York City makes to the state base. For nearly every filer, city taxable income at line 47 simply EQUALS state taxable income at line 38 and nothing needs to be computed.
## When no adjustment applies
If you did NOT contribute to the New York Charitable Gifts Trust Fund, or you did but did not claim an itemized deduction for it on Form IT-196, enter the LINE 38 AMOUNT on line 47. Done.
## When the adjustment applies
Both conditions must be met:
1. You contributed to the New York Charitable Gifts Trust Fund in the HEALTH CHARITABLE ACCOUNT or the ELEMENTARY AND SECONDARY EDUCATION ACCOUNT, and
2. You claimed an ITEMIZED DEDUCTION for that contribution on Form IT-196
Then complete the Line 47 worksheet:
```
1  New York adjusted gross income (Form IT-201, line 33)
2  Contributions to Charitable Gifts Trust Fund accounts
3  New York City AGI = line 1 plus line 2
4  Your itemized deduction amount (Form IT-201, line 34)
5  Line 3 minus line 4
6  Dependent exemptions (Form IT-201, line 36)
7  NYC taxable income = line 5 minus line 6 → Form IT-201, Line 47
```
The effect is to ADD THE CONTRIBUTION BACK for city purposes. The city does not recognize the deduction that the state allowed.
## Why this exists
The New York Charitable Gifts Trust Fund was created as a workaround to the federal SALT cap: contribute to a state charitable account, take a federal charitable deduction, and receive a New York credit. The city declined to follow the state in allowing an offsetting deduction, so the amount is restored to the city base.
The number of filers affected is small, but for those affected the amounts are usually large, because the structure only makes sense for high-income taxpayers with capped SALT deductions.
## Where the contribution shows up upstream
Form IT-196 line 16b captures contributions to these two accounts, drawn from the qualified contributions on line 16a. If line 16b has an entry, the Line 47 worksheet is in play. Treat any line 16b amount as a flag with downstream city consequences.
## What is NOT adjusted for the city
To be explicit, because the question comes up constantly:
| Item | City adjustment? |
|---|---|
| New York additions, lines 20-23 | NO. Already in the state base |
| New York subtractions, lines 25-31 | NO. Already removed from the state base |
| Standard deduction | NO. Same amount as the state |
| Itemized deductions | NO, except the Charitable Gifts Trust Fund add-back |
| Dependent exemption | NO. Same $1,000 per dependent |
| Pension and annuity exclusion | NO. The city honors the state exclusion |
| Social Security | NO. Exempt for the city as it is for the state |
A retiree exempt from state tax on their pension is equally exempt from city tax. There is no separate city inclusion.
## Required Information
- Form IT-201 line 38, the default line 47 amount
- Whether Form IT-196 line 16b has an entry
- Contribution amounts by account
- Lines 33, 34, and 36 if the worksheet is needed
## Questions
- Did you contribute to the New York Charitable Gifts Trust Fund?
- Did you claim an itemized deduction for that contribution on Form IT-196?
- Does Form IT-196 line 16b show an amount?
- Are you a full-year city resident, or part-year, which routes to Form IT-360.1 instead?
## Common Errors
- Recomputing city taxable income from scratch instead of carrying line 38 across
- Missing the add-back when Form IT-196 line 16b has an entry
- Applying the worksheet when the contribution was made but no itemized deduction was claimed
- Assuming the city has its own additions and subtractions
- Using line 47 for a part-year city resident, who uses Form IT-360.1 instead
## Prompt
- Is New York City taxable income the same as state taxable income?
- I contributed to the New York Charitable Gifts Trust Fund.
- What goes on line 47 of the IT-201?
