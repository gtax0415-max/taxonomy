---
type: payment
category: payments
jurisdiction: IA
tax_year: 2026
source_doc: Entity's Iowa pass-through statement (delivered as the Iowa Schedule K-1) showing PTET or composite tax paid on the owner's behalf / federal Schedule K-1 (Form 1065 or 1120-S) for the same entity
form: Form IA 1040
line: "27"
refundable: yes
via:
  - Entity's statement of PTET paid (owner's share) → IA Schedule CC, Part III → Form IA 1040, line 27
  - Entity's statement of composite tax paid (nonresident owner) → IA Schedule CC, Part III → Form IA 1040, line 27
---
# Composite and PTET Credit (IA Schedule CC)
## Description
Refundable credit for Iowa income tax that a partnership or S corporation paid on the owner's behalf, either through the elective pass-through entity tax (PTET) or a composite return.

## PTET credit (Iowa Code 422.16C) — in scope for residents
- The entity elected to pay Iowa tax at the entity level
- The owner claims a credit for their share of the tax, in the year the related income must be reported
- Refundable: any excess over the owner's Iowa tax is paid out

## Composite credit (Iowa Code 422.16B) — nonresidents
- A nonresident member whose Iowa tax was paid on the entity's IA PTE-C composite return
- OUT OF SCOPE for the team's full-year-resident scope; keep as a review row

## Rules for 2026
- Enter the total from IA Schedule CC Part III on line 27 and attach Schedule CC
- Do NOT report these credits on IA 148
- Interaction with federal SALT: the entity's PTET payment is deductible federally at the entity level, reducing the owner's federal K-1 income. Any Iowa add-back of that deduction comes through the entity's Iowa modification (Schedule 1 line 3), not this line

## Source note
- The credit amount appears only on the entity's Iowa statement (the Iowa Schedule K-1). No federal form carries it, so for this item a state-format entity statement is unavoidable. It is a third-party document the owner receives, not a state instruction

## Required Information
- PTET or composite tax paid for the owner's share, by entity
- Entity name and FEIN

## Questions
- Do you own part of a partnership or S corporation that elected to pay Iowa tax at the entity level?
- Did the entity send you an Iowa K-1 showing tax paid for you?

## Common Errors
- Reporting the credit on IA 148
- Claiming PTET credit in the wrong tax year
- Missing the related Iowa add-back on line 3

## Prompt
- My S corporation paid Iowa PTET. How do I get credit for it?
