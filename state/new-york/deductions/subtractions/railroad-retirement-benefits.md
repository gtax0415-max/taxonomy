---
type: deduction
category: subtractions
jurisdiction: NYS
source_doc: Form RRB-1099 (Social Security equivalent Tier 1 benefits) / Form RRB-1099-R (Tier 2 and supplemental annuity benefits) / Form 1099-G for railroad unemployment insurance benefits
form: Form IT-201
line: "27, 31"
refundable: no
via:
  - Social Security equivalent Tier 1 → Form IT-201, Line 27
  - Tier 2, supplemental annuity, and railroad unemployment → Form IT-225, code S-122 → Form IT-201, Line 31
routing:
  - "Social Security equivalent Tier 1 benefits → Form IT-201, Line 27, with Social Security"
  - "Tier 2 benefits, supplemental annuity, and railroad unemployment insurance → Form IT-225 code S-122 → Form IT-201, Line 31"
---
# Railroad Retirement Benefits
## Description
Railroad retirement is EXEMPT FROM STATE INCOME TAX under Title 45 of the U.S. Code, but New York removes it through TWO DIFFERENT LINES depending on which tier the benefit falls in. Splitting them correctly is the whole difficulty.
## The two routes
| Benefit | Reported on | New York route |
|---|---|---|
| Social Security equivalent TIER 1 | Form RRB-1099 | Line 27, alongside Social Security |
| TIER 2 benefits | Form RRB-1099-R | Form IT-225, code S-122 → Line 31 |
| SUPPLEMENTAL ANNUITY under the Railroad Retirement Act of 1974 | Form RRB-1099-R | Form IT-225, code S-122 → Line 31 |
| RAILROAD UNEMPLOYMENT INSURANCE benefits | Form 1099-G | Form IT-225, code S-122 → Line 31 |
For Form IT-203 filers the Tier 1 equivalent goes on line 26 rather than line 27.
## Why the split exists
Social Security equivalent Tier 1 is treated by federal law as though it were Social Security, so it flows through the same line New York uses for Social Security. Everything else is exempt under a separate federal statute and has no dedicated New York line, so it uses the modification code.
## The failure mode
A railroad retiree who enters only the Tier 1 amount at line 27 and stops has left the Tier 2 and supplemental annuity amounts fully taxed by New York. Those are often the larger figures.
Conversely, entering the whole RRB-1099-R at line 27 misstates the return in the other direction and produces a notice.
Check whether BOTH an RRB-1099 and an RRB-1099-R were received. Most career railroad retirees have both.
## Code S-122
The Form IT-225 code covers "certain railroad retirement income and railroad unemployment insurance benefits." The condition is that the benefits are EXEMPT FROM STATE INCOME TAXES under Title 45 of the United States Code. Nearly all Railroad Retirement Board benefits meet this.
## Not covered here
- A private railroad pension outside the Railroad Retirement system. That follows the ordinary pension rules — see pension-annuity-exclusion.md
- Long Island Railroad Company pensions, which qualify for the GOVERNMENT PENSION EXCLUSION at line 26 as a listed public authority. See government-pension-exclusion.md
- MTA and MABSTOA pensions, likewise line 26
## Required Information
- Form RRB-1099 and Form RRB-1099-R, both if received
- The taxable amount of each, as reported in federal AGI
- Form 1099-G for any railroad unemployment insurance benefits
## Questions
- Did you receive Form RRB-1099, Form RRB-1099-R, or both?
- Are the amounts Tier 1, Tier 2, or a supplemental annuity?
- Did you receive railroad unemployment insurance benefits?
- Is any of your railroad income from a private plan rather than the Railroad Retirement Board?
## Common Errors
- Subtracting only Tier 1 and leaving Tier 2 taxed
- Putting the entire RRB-1099-R amount on line 27
- Omitting Form IT-225, which invalidates the S-122 subtraction
- Missing railroad unemployment insurance benefits
- Routing an LIRR pension here instead of to the line 26 government pension exclusion
## Prompt
- I am a retired railroad worker.
- I got an RRB-1099 and an RRB-1099-R.
- Does New York tax railroad retirement?
