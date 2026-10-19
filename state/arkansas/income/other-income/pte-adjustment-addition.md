---
type: addition
category: other-income
jurisdiction: AR
tax_year: 2026
source_doc: Federal Schedule K-1 from the entity / Arkansas AR K-1 or AR1099PT from the entity showing that it elected entity-level tax / federal Schedule E as filed
form: Form AR1000F
line: "22"
via:
  - AR K-1 / AR1099PT → AR-OI, line 7 → line 11 → line 20 → Form AR1000F, line 22
---
# Pass-Through Entity Adjustment (Addition)
## Description
When a partnership or S corporation ELECTED to pay Arkansas tax at the entity level, the owner's share is exempt to the owner. This line ADDS BACK the owner's share of exempt LOSSES (excluding capital gains) that were not already claimed on Schedule E, so the owner doesn't deduct a loss the entity already used.

## Notes
- Add exempt losses from electing entities, excluding capital losses, not claimed on Schedule E
- Attach AR K-1 and/or AR1099PT
- Capital gains and losses from electing entities are adjusted on AR1000D instead
- 2026: entity-level tax rate follows the individual top rate cut to 3.7% (Acts 1 and 2 of 2026), but the owner's adjustment is unchanged

## Required Information
- Each electing entity and the owner's share of income or loss
- AR K-1 or AR1099PT for each electing entity

## Questions
- Do you own part of a partnership or S corporation that elected to pay Arkansas tax itself?
- Did the entity have a loss for 2026?
- Did you claim the loss on Schedule E?

## Common Errors
- Using this line for income (exempt INCOME is subtracted on line 16)
- Including capital gains or losses
- Adding back a loss from an entity that did not elect

## Prompt
- My S corporation elected the Arkansas pass-through entity tax and had a loss.
- How does the Arkansas PTE election affect my K-1 loss?
