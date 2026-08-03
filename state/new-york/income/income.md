---
type: income
category: index
jurisdiction: NYS
form: Form IT-201
line: "1-19, 20-24, 33"
---
# New York Income
## Description
New York starts from FEDERAL ADJUSTED GROSS INCOME and adjusts it. Lines 1 through 19 of Form IT-201 restate the federal return; lines 20 through 32 apply New York modifications; line 33 is New York adjusted gross income, the number the state actually taxes.
## The starting point
| Federal | New York |
|---|---|
| Form 1040, Line 1z (wages) | Form IT-201, Line 1 |
| Form 1040, Line 11 (federal AGI) | Form IT-201, Line 19 |
Line 19 must not be left blank. If you did not file a federal return, report the same income and adjustments you WOULD have reported.
## Folders
- additions/ — lines 20 through 23. Income New York taxes that the federal government does not
## Subtractions live under deductions/
New York SUBTRACTIONS (lines 25 through 31) are filed at state/new-york/deductions/subtractions/. They function as deductions — they reduce the tax base and must be affirmatively claimed — so they are documented there. Additions are here because they increase income.
```
Line 19   Federal AGI
Lines 20-23   ADDITIONS        → income/additions/
Line 24   Total
Lines 25-31   SUBTRACTIONS     → deductions/subtractions/
Line 32   Total subtractions
Line 33   New York AGI
```
## What New York taxes differently
New York does not restate the federal income rules. It departs in a bounded set of places, and each departure appears as a modification rather than as a different income line:
| Item | Federal | New York |
|---|---|---|
| Interest on OTHER states' municipal bonds | Exempt | TAXED, line 20 |
| Interest on New York municipal bonds | Exempt | Exempt |
| Public employee 414(h) contributions | Excluded from wages | TAXED, line 21 |
| U.S. Treasury interest | Taxed | EXEMPT, line 28 |
| Social Security benefits | Partly taxed | EXEMPT, line 27 |
| Government pensions | Taxed | EXEMPT, line 26 |
| Private pensions | Taxed | Up to $20,000 exempt, line 29 |
| Tips (2026) | Deduction | Deduction, newly conformed |
| Overtime premium | Deduction | NOT conformed, fully taxed |
## Conformity
New York is a STATIC conformity state. New federal provisions do not flow through automatically. See state/new-york/deductions/conformity.md for the full treatment, including why QBI never reaches a New York return.
## Related
- Federal income — see federal/income/
- New York subtractions — see state/new-york/deductions/subtractions/
- Form IT-225 carries both additions and subtractions by code
## Questions
- What is your federal AGI?
- Do you hold municipal bonds issued outside New York?
- Are you a New York public employee with 414(h) contributions on your W-2?
- Did you receive a Schedule K-1 with New York modification codes?
## Prompt
- How does New York calculate my income?
- Does New York tax my municipal bond interest?
- What is New York adjusted gross income?
