---
type: credit
category: family-dependent
jurisdiction: NYS, NYC
source_doc: NO EXTERNAL SOURCE DOCUMENT — computed from instruction tables using figures already on the return — federal AGI (Form IT-201, line 19, itself from federal Form 1040 line 11), dependent status (Item C), and the count of dependents at Item H. For married filing separately, the federal AGI from BOTH returns is required
form: Form IT-201
line: "40, 48"
refundable: no
via:
  - New York State household credit tables 1-3 → Form IT-201, Line 40
  - New York City household credit tables 4-6 → Form IT-201, Line 48
---
# Household Credit
## Description
Small nonrefundable credit for low-income filers, computed directly from tables in the Form IT-201 instructions. THERE IS NO CLAIM FORM. Two separate versions exist, one for New York State and one for New York City, each with its own tables and income limits.
## The disqualifier that catches most people
If you marked YES at Item C on Form IT-201 — meaning you CAN be claimed as a dependent on someone else's federal return — you do not qualify for either version. You must mark Yes even if the other taxpayer chose not to claim you.
## New York State credit (Line 40)
Income limits by filing status, using federal AGI from line 19:
- Single: no credit above $28,000
- All other statuses: no credit above $32,000
Amounts, single filers: $75 at the bottom of the range, stepping down to $20 between $25,000 and $28,000.
Amounts, joint and head of household filers: start at $90 for one exemption and rise by $15 for each additional dependent, then step down as income rises. Count yourself, your spouse if filing jointly, and each dependent listed at Item H.
Married filing separately uses a third table with amounts roughly half the joint figures, and the income test applies to the COMBINED income from both returns.
## New York City credit (Line 48)
Much tighter income limits:
- Single: no credit above $12,500
- All other statuses: no credit above $22,500
Amounts, single: $15, dropping to $10 between $10,000 and $12,500.
Amounts, joint and head of household: $30 per exemption at the lowest incomes, scaling down in four income bands.
## Interaction with the earned income credit
The New York State household credit REDUCES the New York State EIC. Form IT-215 Worksheet B subtracts it. Because the EIC is refundable and the household credit is not, a filer with no tax liability can find the household credit worth nothing on its own while still shrinking a refundable credit. Do not treat the two as additive.
## Notes
- Build America Bond interest is backed out of federal AGI for this test if you entered special condition code A6
- Credit amounts in the married-filing-separately and NYC tables are rounded
- For more than seven exemptions, add the per-person column amount to the seven-person figure
## Required Information
- Federal AGI from Form IT-201, line 19
- Whether you can be claimed as a dependent (Item C)
- Number of dependents listed at Item H
- Filing status
- For married filing separately, the federal AGI from both returns
## Questions
- Can anyone claim you as a dependent on their federal return?
- What is your federal AGI?
- How many dependents did you list at Item H?
- Did you live in New York City during the year?
## Common Errors
- Claiming it while marked as a dependent at Item C
- Forgetting to count yourself and your spouse as exemptions alongside the dependents
- Using only your own AGI on a married-filing-separately return when the test uses both returns combined
- Treating the household credit and the EIC as stacking when the household credit reduces the EIC
- Overlooking the NYC version, which has separate and much lower income limits
## Prompt
- Do I qualify for the New York household credit?
- My income was under $20,000 last year.
- What is the difference between the state and city household credit?
