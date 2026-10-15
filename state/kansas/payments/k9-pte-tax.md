---
type: payment
category: payments
jurisdiction: KS
tax_year: 2026
source_doc: Statement of Partnership or S Corporation Tax Paid (Form K-9) received from each electing entity, Part C / Schedule K-1 (Form 1065 or 1120-S) from the same entity
form: Form K-40
line: "25"
via:
  - Kansas tax paid by electing entity on the owner's share → Form K-40, line 25 → line 27
---
# Credit for Tax Paid on the K-120S (K-9)
## Description
Refundable credit for Kansas tax that an electing partnership or S corporation paid on the owner's share of income under the Kansas SALT Parity Act (pass-through entity tax). The entity pays Kansas tax and deducts it federally, working around the federal SALT cap; the owner then claims the tax paid as a payment on the K-40.

## Amount
- The "Kansas tax at 5.58%" paid on the owner's behalf, shown on the entity's statement (Form K-9, Part C)
- Add amounts from every electing entity
- The rate matches the top Kansas individual rate, unchanged for 2026 (no rate cut: KDOR Notice 25-06)

## Notes
- Enclose every K-9 with the return
- The entity's federal deduction for the tax reduces the income on the owner's K-1, so the owner's federal AGI is already lower; the owner does not deduct the tax again
- The federal SALT cap for 2026 rises to $40,400 under OBBBA, but the entity-level deduction remains valuable for owners above the phase-down threshold and for amounts over the cap

## Required Information
- Each electing entity's name and EIN
- Kansas tax paid on the owner's share

## Questions
- Are you a partner or S corporation shareholder in a business that elected to pay Kansas tax at the entity level?
- Did you receive a K-9 statement?

## Common Errors
- Claiming the entity tax without the K-9 statement
- Entering it as a nonrefundable credit instead of a payment on line 25
- Also claiming it as an itemized deduction

## Prompt
- My S corporation paid Kansas tax for me under the SALT parity election.
- I received a Kansas K-9 from my partnership.
