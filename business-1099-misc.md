---
type: income
category: business
source_doc: Form 1099-MISC Box 3 (other income)
form: Form 1040
line: "8"
see_also: federal/income/rental/1099-misc.md
via:
  - Schedule C, Line 1 or Line 6 → Schedule C, Line 31 (net profit) → Schedule 1, Line 3 → Schedule 1, Line 10 → Form 1040, Line 8
routing:
  - "Form 1099-MISC Box 3, when the amount is from a business you operate → Schedule C → Schedule 1, Line 3 → Form 1040, Line 8 (self-employment tax applies)"
  - "Form 1099-MISC Box 3, when the amount is a prize or award → Schedule 1, Line 8i → Schedule 1, Line 9 → Form 1040, Line 8 (no self-employment tax)"
  - "Form 1099-MISC Box 3, any other case → Schedule 1, Line 8z → Schedule 1, Line 9 → Form 1040, Line 8 (no self-employment tax)"
  - "Form 1099-MISC Box 1 (rents) or Box 2 (royalties) → federal/income/rental/1099-misc.md → Schedule E → Schedule 1, Line 5 → Form 1040, Line 8"
---
# Form 1099-MISC — Box 3 as business income
## Description
Form 1099-MISC usually reports RENTS (Box 1) and ROYALTIES (Box 2), which are documented at federal/income/rental/1099-misc.md. This file covers only Form 1099-MISC BOX 3 (other income) and where that amount goes.
## Box 3 has three possible destinations
The form does not tell you which one applies. Box 3 is a catch-all, so the routing depends on what the payment was for:
- It came from a BUSINESS YOU OPERATE → Schedule C → Schedule 1 Line 3. Net profit is subject to SELF-EMPLOYMENT TAX (15.3%) and may qualify for the QBI deduction
- It was a PRIZE OR AWARD → Schedule 1 Line 8i (prizes and awards). No self-employment tax
- ANYTHING ELSE (a one-time settlement, a research payment, a rebate) → Schedule 1 Line 8z (other income), with a description entered on the line
All three total on Schedule 1 Line 10 and land on Form 1040 Line 8.
## Why the distinction matters
Self-employment tax. The same dollar amount costs an extra 15.3% if it goes on Schedule C, and nothing extra if it goes on Schedule 1 Line 8i or 8z. Going the wrong way costs money in either direction: a one-off prize on Schedule C overpays, while genuine business income on Line 8z gives up both the expense deductions and the QBI deduction.
## Notes
- Nonemployee compensation for SERVICES now comes on Form 1099-NEC, not Form 1099-MISC — see 1099-nec.md
- Form 1099-MISC Box 1 (rents) and Box 2 (royalties) are not covered here; see federal/income/rental/1099-misc.md
- Schedule 1 Line 8j is a separate line for income from an activity NOT engaged in for profit (a hobby). Hobby income goes there, and hobby expenses are not deductible at all
## Required Information
- Form 1099-MISC Box 3 amount
- Payer name and TIN
- What the payment was for (this is what determines the routing)
- Related expenses, if it is business income
## Questions
- What was the Form 1099-MISC Box 3 payment for?
- Does it come from an ongoing business you operate, or was it a one-time event?
- Was it a prize, award, or settlement?
- Do you have related expenses (deductible only if it is business income)?
## Common Errors
- Putting a one-off prize on Schedule C and paying unnecessary self-employment tax
- Putting genuine business income on Schedule 1 Line 8z and losing both the expense deductions and the QBI deduction
- Treating hobby income as a business
- Looking here for rents or royalties, which are documented under rental/
## Prompt
- I received a 1099-MISC with an amount in Box 3.
- I got a 1099-MISC that is actually from my business.
- I won a prize and received a 1099-MISC.
