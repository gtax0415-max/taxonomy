---
type: income
category: income
jurisdiction: AR
tax_year: 2026
source_doc: Form 1099-R for each pension and IRA (box 1 gross, box 2a taxable, box 7 code) / payee's date of birth / federal Simplified Method Worksheet if box 2a is blank / charity acknowledgment for a qualified charitable distribution
form: Form AR1000F
line: "18A, 18B"
via:
  - Form 1099-R → Form AR1000F, line 18A (primary) / 18B (spouse) → less $6,000 per person → line 23
---
# Employer Pension and Qualified IRA Distributions ($6,000 Exemption)
## Description
The first $6,000 of taxable employer-plan distributions and qualified traditional IRA distributions is exempt for each person. Lines 18A and 18B hold the gross and taxable amounts and the balance after the exemption.

## Notes
- Exemption: $6,000 per taxpayer, combined across employer plans and IRAs (unchanged for 2026)
- Qualifying IRA distributions: after age 59 1/2, or on death or disability
- Enter gross (1099-R box 1) and taxable (box 2a) amounts; subtract the $6,000 from the taxable amount
- Status 2: the spouse's amount goes on line 18B, column A. Status 4: line 18B, column B
- A surviving spouse is limited to one $6,000 exemption (not the deceased spouse's as well)
- Reduced by any military retirement exemption for the same person (line 17)
- 65 Special credit ($29) is available instead to a taxpayer 65 or over who does NOT claim this exemption
- Claiming the exemption bars the Low Income Tax Table; the taxpayer may elect not to use it
- Employer-plan distributions (pension, 401(k), 403(b)) qualify at any age; the 59 1/2 test applies only to IRAs
- A qualified charitable distribution (QCD) excluded on the federal return stays excluded; the exemption applies to the remaining taxable amount

## Required Information
- Each 1099-R by recipient
- Ages and any disability
- Military retirement for the same person

## Questions
- Do you or your spouse receive a pension, 401(k), or IRA distributions?
- Were you 59 1/2 or older when you took IRA money?
- Do you also receive military retirement?

## Common Errors
- Taking $6,000 for each 1099-R instead of each person
- Applying it to early IRA withdrawals (line 16)
- A surviving spouse taking two $6,000 exemptions
- Claiming both this exemption and the 65 Special credit

## Prompt
- I'm retired and get a pension and IRA distributions.
- My spouse and I both have pensions. How much is exempt?
