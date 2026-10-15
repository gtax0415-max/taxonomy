---
type: income
category: additions
jurisdiction: UT
tax_year: 2026
source_doc: Schedule K-1 (Form 1065 or 1120-S) and the entity's statement of elective pass-through entity tax paid on your behalf to Utah and to any other state
form: Form TC-40
line: "3"
via:
  - Entity statement of tax paid → TC-40_A, Part 5 (code AD012PT) → Form TC-40, line 3
  - Same Utah amount → TC-40_A, Part 3 (credit code NN006PC) → Form TC-40, line 23
---
# Tax Paid on Behalf of a Pass-through Entity Taxpayer
## Description
When a partnership or S corporation elects to pay state income tax at the entity level (the SALT-cap workaround), that tax is deducted federally and lowers the owner's federal AGI. Utah adds it back, then gives a credit for the Utah portion.

## Amount
- Addition = total entity-level tax paid on your behalf during 2026 to:
  1. Utah under UCA §59-10-1403.2(2), AND
  2. any OTHER state with a similar elective entity tax
- The Utah portion is then claimed as a nonrefundable credit (NN006PC), with a 10-year carryforward (NN006PF)
- Utah tax rate for 2026: 4.45%

## 2026 Change
- HB 77 (2026 General Session, signed March 23, 2026) made the Utah elective pass-through entity tax permanent, applying from tax year 2026

## Eligibility
- You are a partner, member or shareholder of an entity that made the Utah (or another state's) elective entity-tax election for 2026
- The entity provides a statement of tax paid on your behalf

## Notes
- The addition includes OTHER states' elective taxes; the Utah credit covers only the Utah tax. For other-state tax, see the credit for income tax paid to another state (NN008PT)
- Do not confuse with ordinary pass-through WITHHOLDING (TC-40_W, Part 2 → line 30b), which is not added back

## Required Information
- Schedule K-1 and the entity's tax-paid statement for each entity
- Breakdown of Utah vs. other-state entity tax

## Questions
- Did any partnership or S corporation you own pay state tax for you at the entity level in 2026?
- Which states was it paid to?

## Common Errors
- Claiming the NN006PC credit without the matching addition
- Adding back only the Utah tax and missing other states' elective taxes
- Treating pass-through withholding as entity-level elective tax

## Prompt
- My S corporation elected to pay Utah tax at the entity level.
- My partnership K-1 shows state PTE tax paid on my behalf.
