---
type: payment
category: payments
jurisdiction: NM
tax_year: 2026
source_doc: The entity's annual statement of New Mexico pass-through entity withholding to the owner (RPD-41359), boxes 2, 3 and 4, or Form 1099-MISC showing New Mexico withholding / federal Schedule K-1 from the same entity
form: Form PIT-1
line: "29"
via:
  - Entity statement box 2 (withholding) + box 3 (composite tax) + box 4 (entity-level tax credit) → PIT-1, Line 29 → PIT-1, Line 32
  - Box 2 only → also added back on PIT-ADJ, Line 5
---
# Pass-Through Entity Withholding, Entity-Level and Composite Tax
## Description
Tax paid to New Mexico by a partnership, S corporation, or LLC on the owner's behalf. The owner claims it as a payment on line 29 and attaches the entity's statement.

## The entity's statement (boxes)
- Box 1: owner's New Mexico net income (information only)
- Box 2: New Mexico tax withheld
- Box 3: composite income tax paid on the owner's behalf
- Box 4: owner's share of entity-level tax paid (credit)

## Amount
- Line 29 = box 2 + box 3 + box 4, for each entity
- Box 2 withholding is ALSO added to income on PIT-ADJ line 5 (see income/additions/pte-withholding-addback.md)

## Notes
- Oil and gas withholding is a different line (28)
- Attach every statement or 1099-MISC; claims without them are denied

## Status for 2026
No change from the 2026 legislative session.

## Required Information
- Each entity's statement, boxes 1–4
- Matching federal K-1

## Questions
- Do you own part of a partnership, S corporation, or LLC with New Mexico income?
- Did the entity withhold New Mexico tax, pay composite tax, or pay entity-level tax for you?

## Common Errors
- Claiming box 2 on line 29 without the PIT-ADJ line 5 addition
- Leaving out box 3 or box 4 amounts
- Entering box 1 (income) as a payment

## Prompt
- My S corporation paid New Mexico entity-level tax for me.
- I received a New Mexico pass-through withholding statement.
