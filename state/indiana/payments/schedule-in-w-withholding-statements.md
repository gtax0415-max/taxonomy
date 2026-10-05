---
type: filing
category: schedule-in-w
jurisdiction: IN
tax_year: 2026
source_doc: Forms W-2, W-2C, W-2G, 1099-R, 1099-G, 1099-MISC, 1099-NEC, IN-MSID-A and Schedule IN K-1 showing Indiana state or county tax withheld
form: Schedule IN-W
line: "1-25, 26, 27"
via:
  - Each withholding statement → Schedule IN-W, one row (columns A-H)
  - Column E total → Line 26 → Schedule 5, Line 1 (Indiana state tax withheld) → Form IT-40, Line 12
  - Column G total → Line 27 → Schedule 5, Line 2 (Indiana county tax withheld) → Form IT-40, Line 12
routing:
  - "Reporting any Indiana withholding on a paper return → complete and enclose Schedule IN-W plus the statements"
  - "One statement withholding for several Indiana counties → enter state income and state tax once only"
  - "More than 25 statements → additional IN-W pages; totals of all pages on lines 26 and 27 of the first page only"
  - "IN-MSID-A or IN K-1, or form type not on the chart → leave column B blank"
see_also:
  - filing/filing.md
  - payments/indiana-withholding.md
  - payments/payments.md
---
# Schedule IN-W: Indiana Withholding Statements
## Description
Schedule IN-W lists each statement on which Indiana state or county (local) tax was withheld for you or your spouse. Complete and enclose it when reporting any tax withheld and filing Form IT-40 by paper. Enclose the W-2s, 1099s, IN-MSID-As, IN K-1s and other statements as well. The column totals become Schedule 5, lines 1 and 2.
## Columns
| Column | Entry |
|---|---|
| A | Your or your spouse's SSN from the statement |
| B | Form code from the reference chart: W-2/W-2C = W; W-2G = G; 1099R = R; 1099M = M; 1099G = U; 1099NEC = N. Leave blank for IN-MSID-A, IN K-1 or a form type not listed |
| C | Employer or payer ID number (generally the employer's FEIN) |
| D | Indiana state income |
| E | Indiana state tax withheld |
| F | Indiana local income (only if there is Indiana local withholding) |
| G | Indiana county tax withheld (only if there is Indiana local withholding) |
| H | Indiana 2-digit county code from the Schedule CT-40 chart (only if there is Indiana local withholding) |
## Totals
- Line 26: add column E, lines 1-25 → Schedule 5, line 1.
- Line 27: add column G, lines 1-25 → Schedule 5, line 2.
- More than 25 statements: use additional Schedule IN-W pages without completing lines 26 and 27 on them; enter the all-page totals on lines 26 and 27 of the first page.
## Multiple counties on one statement
If one statement shows withholding for several Indiana counties, enter the state income and state tax withheld only once for that statement; list each county's local income, local tax and code without repeating the state amounts.
## Example
W-2 from Employer A: state wages $52,000, state tax $1,534, county wages $52,000, county tax $884, Marion County (49). 1099-R: state income $6,000, state tax $177, no county tax. Rows: W / FEIN / 52000 / 1534 / 52000 / 884 / 49 and R / payer ID / 6000 / 177. Line 26 = $1,711; line 27 = $884.
## Questions
- Which forms show Indiana state or county tax withheld for you and your spouse?
- Does any W-2 show withholding for more than one Indiana county?
- Do you have more than 25 withholding statements?
## Common Errors
- Claiming tax withheld for other states or non-Indiana localities
- Repeating the state income and state tax on each county line of a multi-county W-2
- Using the wrong form code or putting a code for IN K-1s
- Not enclosing the statements themselves
## Prompt
- How do I fill out Schedule IN-W?
- My W-2 shows two Indiana counties. How do I list it?
