---
type: credit
category: new-york-city
jurisdiction: NYC
source_doc: NO EXTERNAL SOURCE DOCUMENT — computed from instruction tables. Inputs are federal AGI (Form IT-201, line 19) reduced by IRA and individual retirement annuity distributions (line 9), dependent status (Item C), months of NYC residence (Item F), and NYC taxable income (line 47) for the rate reduction amount. Records establishing city residency dates support Item F
form: Form IT-201
line: "69, 69a"
refundable: yes
via:
  - Instruction tables → Form IT-201, Line 69 (fixed amount)
  - Instruction rate schedules → Form IT-201, Line 69a (rate reduction amount)
  - Form NYC-210 filed ALONE, for people not otherwise required to file
routing:
  - "Fixed amount → Form IT-201, Line 69. Refundable, no return required"
  - "Rate reduction amount → Form IT-201, Line 69a. Refundable"
  - "Non-filers → Form NYC-210, standalone"
---
# New York City School Tax Credit
## Description
Two separate credits sharing one name, both for New York City residents, both refundable, neither requiring a claim form when filing Form IT-201. Despite the name they have nothing to do with paying school taxes or having children in school — every qualifying city resident gets them.
## Part 1: Fixed amount (Line 69)
A flat dollar credit:
| Filing status | Credit |
|---|---|
| Single, married filing separately, head of household | $63 |
| Married filing jointly, qualifying surviving spouse | $125 |
Eligibility:
- Full-year or part-year New York City resident
- You CANNOT be claimed as a dependent on another taxpayer's federal return
- INCOME of $250,000 or less
Income here has a special definition: federal AGI from line 19, MINUS IRA and individual retirement annuity distributions reported on line 9. A retiree with large IRA withdrawals may qualify when their AGI alone suggests otherwise.
Part-year residents prorate by month, from $5 up to $63 for a single filer and $10 up to $125 for a joint filer.
## Part 2: Rate reduction amount (Line 69a)
A percentage of NYC TAXABLE INCOME, functioning as a small rate cut delivered as a credit:
| Filing status | Calculation |
|---|---|
| Married filing jointly, QSS | 0.171% of taxable income up to $21,600, then $37 plus 0.228% of the excess, to $500,000 |
| Single, married filing separately | 0.171% up to $12,000, then $21 plus 0.228% of the excess, to $500,000 |
| Head of household | 0.171% up to $14,400, then $25 plus 0.228% of the excess, to $500,000 |
Income ceiling is $500,000 here, higher than the fixed amount's $250,000. Someone earning $300,000 gets the rate reduction amount and not the fixed amount.
## Claimable without filing a return
Form NYC-210 lets a city resident who is not required to file an income tax return claim the fixed amount by itself. Do NOT file Form NYC-210 if you are claiming the credit on Form IT-201 — that duplicates the claim.
## Married couples with split city residency
- BOTH full-year city residents: Table 1, joint amount
- BOTH part-year: Table 2, using the months of the spouse with the LONGER city residence
- One full-year resident, one full-year nonresident, computing NYC tax as married filing separately: Table 1 single amount for the resident only
- One full-year resident, one full-year nonresident, ELECTING to compute as if both were residents: Table 1 joint amount
- One full-year resident, one part-year resident: compute each separately and ADD them
## Notes
- The fixed amount is statutory and has been rounded in the tables
- Both credits are refundable and reach filers with no city tax liability
- Item F on Form IT-201, months of city residence, is what the Tax Department uses to verify these credits. Leaving it blank stalls the claim
## Required Information
- Months of New York City residence for each spouse (Item F)
- Federal AGI and any IRA distributions from line 9
- NYC taxable income from line 47, for the rate reduction amount
- Dependent status (Item C)
- Filing status
## Questions
- Were you a New York City resident, and for how many months?
- Can anyone claim you as a dependent?
- Is your income, less IRA distributions, at or below $250,000?
- Is your NYC taxable income at or below $500,000?
- Did you and your spouse have different periods of city residence?
## Common Errors
- Leaving Item F blank
- Using federal AGI without subtracting IRA distributions for the income test
- Missing the rate reduction amount because the fixed amount was phased out at $250,000
- Filing Form NYC-210 in addition to claiming the credit on Form IT-201
- Mishandling a couple with split city residency by using one table for both
- Assuming the credit requires school-age children
## Prompt
- I live in New York City, do I get a school tax credit?
- I moved to Queens in September.
- I do not have to file a return but I lived in NYC all year.
