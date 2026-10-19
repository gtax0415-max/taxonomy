---
type: addition
category: additions
jurisdiction: NM
tax_year: 2026
source_doc: Federal Schedule K-1 (Form 1065 or 1120-S) from the entity / annual statement of New Mexico pass-through entity withholding issued to the owner (box 2), or Form 1099-MISC showing New Mexico withholding
form: Form PIT-1
line: "11"
via:
  - Entity withholding statement, box 2 → PIT-ADJ, Line 5 → PIT-ADJ, Line 6 → PIT-1, Line 11
  - Same amount claimed as a payment → PIT-1, Line 29
---
# Pass-Through Entity Withholding on Distributed Net Income
## Description
When a partnership, S corporation, or LLC withholds New Mexico tax on an owner's share of income, that tax is added to the owner's income and also claimed as a payment. Adding it back keeps the owner's New Mexico income at the full pre-withholding amount.

## Amount
- The tax withheld by the entity on your distributed net income, as reported in box 2 of the entity's annual withholding statement to you
- The same amount is then credited as tax paid on PIT-1 line 29

## Notes
- This is a two-step entry: addition on PIT-ADJ line 5 and payment on PIT-1 line 29. One without the other is wrong
- Withholding from oil and gas proceeds is a different line (PIT-1 line 28) and is not added back here
- If the entity elected to pay entity-level tax or composite tax instead, read the entity's statement carefully; those amounts are reported to the owner differently

## Status for 2026
No change from the 2026 legislative session. Confirm line numbers on the 2026 PIT-ADJ and PIT-1.

## Required Information
- Each entity's name and FEIN
- Federal Schedule K-1 for each entity
- Box 2 of each entity's New Mexico withholding statement

## Questions
- Do you own an interest in a partnership, S corporation, or LLC with New Mexico income?
- Did the entity withhold New Mexico tax on your share?
- Did the entity pay entity-level or composite tax for you?

## Common Errors
- Claiming the withholding as a payment on line 29 without the addition on line 5
- Adding back oil and gas withholding, which belongs elsewhere
- Using the K-1 income figure instead of the box 2 tax amount

## Prompt
- My partnership withheld New Mexico tax on my share of income.
- I received a New Mexico pass-through withholding statement.
