---
type: credit
category: family-dependent
jurisdiction: OH
tax_year: 2026
source_doc: Federal Form 1040 dependent listing / Social Security cards, ITINs, or ATINs for each exemption claimed
form: Form IT 1040
line: "9"
refundable: no
via:
  - Ohio Schedule of Credits, line 9 → line 10 → line 40 → Form IT 1040, line 9
routing:
  - "$20 × number of exemptions on IT 1040 line 4, only if MAGI less exemptions is under $30,000 → Schedule of Credits, line 9"
---
# Exemption Credit
## Description
Flat $20 nonrefundable credit for each personal or dependent exemption claimed on the Ohio IT 1040. It is a low-income add-on to the exemption deduction, not a substitute for it.

## Amount
- $20 per exemption claimed on Form IT 1040, line 4
- Only if MAGI less exemptions is less than $30,000
- Per return, so a family of four under the ceiling gets $80

## Eligibility
- You claimed at least one Ohio exemption
- MAGI less exemptions is under $30,000
- A dependent who cannot claim an exemption on their own return also cannot claim this credit on that return

## The two MAGI uses people mix up
The exemption AMOUNT on IT 1040 line 4 phases by MAGI ($2,400 / $2,150 / $1,900 / $0). This CREDIT is a separate $30,000 cliff on MAGI less exemptions. You can have a reduced $1,900 exemption and still fail this credit, or have the full $2,400 exemption and claim $20 on top.

## Required Information
- Number of exemptions from IT 1040 line 4
- MAGI (Ohio AGI plus the business income deduction)
- Exemption amount used to compute MAGI less exemptions

## Questions
- How many exemptions are on line 4?
- Is MAGI less exemptions under $30,000?
- Did you add the business income deduction back when you computed MAGI?

## Common Errors
- Claiming $20 per exemption with MAGI less exemptions of $30,000 or more
- Using federal AGI instead of Ohio MAGI
- Forgetting that a child claimed as a dependent gets $0 exemption and $0 exemption credit on the child's own return

## Prompt
- I have two kids and my Ohio income is under $30,000.
- Is there an extra credit for exemptions in Ohio?
