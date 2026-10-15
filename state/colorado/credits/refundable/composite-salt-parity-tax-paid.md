---
type: credit
category: business-refundable
jurisdiction: CO
tax_year: 2026
source_doc: Colorado K-1 statement (DR 0106K) received from each partnership or S corporation, showing composite tax paid and SALT Parity tax paid on the owner's behalf
form: Form DR 0104
line: "31"
refundable: yes
via:
  - Colorado K-1 → DR 0104CR, Line 11 → Line 26 → Form DR 0104, Line 31
routing:
  - "Any K-1 shows a SALT Parity election → also add back the full federal QBI deduction on DR 0104, line 3"
  - "No SALT Parity election → QBI addback applies only if AGI exceeds $500,000 ($1,000,000 joint)"
see_also:
  - credits/refundable/refundable-credits-total.md
  - income/additions/qbi-deduction-addback.md
---
# Composite or SALT Parity Tax Paid by a Pass-Through Entity
## Description
Credit for Colorado income tax that a partnership or S corporation paid on an owner's behalf, either through a composite nonresident return or through a SALT Parity Act (pass-through entity tax) election. The owner claims their share as a refundable payment.

## Amount
- Sum of composite tax and SALT Parity tax shown on every Colorado K-1 received (DR 0106K lines 16 and 25)

## Eligibility
- Partner or S corporation shareholder
- Entity filed a composite return or made the SALT Parity election for 2026

## Notes
- The SALT Parity Act continues for 2026 with no change in response to the federal SALT cap changes
- A SALT Parity election requires adding back the full federal QBI deduction, regardless of income
- Attach every Colorado K-1
- Example: K-1 shows $3,400 of SALT Parity tax → $3,400 credit, plus QBI addback on DR 0104 line 3

## Required Information
- Colorado K-1 from each entity
- Entity name and Colorado account number
- Federal QBI deduction (Form 8995 or 8995-A)

## Questions
- Did a partnership or S corporation pay Colorado tax for you?
- Did any entity make a SALT Parity election?
- Did you take a federal QBI deduction?

## Common Errors
- Missing the QBI addback when a SALT Parity election was made
- Leaving out a K-1 from a second entity
- Not attaching the K-1s

## Prompt
- How do I claim SALT Parity tax paid by my partnership?
- My S corporation elected to pay Colorado tax at the entity level.
