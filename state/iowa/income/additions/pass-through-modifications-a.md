---
type: income
category: additions
jurisdiction: IA
tax_year: 2026
source_doc: Federal Schedule K-1 (Form 1065, 1120-S, or 1041) with the entity's Iowa supplemental statement of Iowa modifications / entity's state-tax information letter
form: Form IA 1040
line: "3"
via:
  - Federal Schedule K-1 + entity's Iowa modification statement → IA Schedule 1, line 3 column A → line 12 → line 13 → line 21 → Form IA 1040, line 3
---
# Partnership, S Corporation, or Fiduciary Additions
## Description
Addition for Iowa modifications that a partnership, S corporation, estate, or trust passes through to its owners or beneficiaries. The entity computes the modification; the owner reports their share. Column A is used for net additions, column B for net subtractions.

## Amount
- Enter your share of the entity's net Iowa ADDITIONS as reported to you by the entity
- The entity reports this on its Iowa K-1 schedule (partnership Part II line 19(a), S corporation Part II line 17(a), fiduciary Part II line 9 on the 2025 forms). The Iowa K-1 is a state form, so for this taxonomy treat it as the delivery vehicle, not the source: the source is the entity's statement accompanying the federal K-1
- Typical pass-through additions: the entity's own municipal interest, bonus depreciation or Section 179 differences on pre-2021 property, and other nonconformity items

## Notes
- 2026: Iowa's rolling conformity means OBBBA changes flowing through the federal K-1 (for example 100% bonus depreciation) generally do not create an Iowa modification. No 2026 Iowa decoupling bill was enacted for individual pass-through items
- Do not double count: if the entity already reported an item as an Iowa modification, do not also enter it on line 1, 2, 9, or 11
- Nonresident and part-year owners still enter the modification here; source allocation happens on IA 126
- Line references follow the 2025 forms; confirm against the 2026 Iowa K-1 and Schedule 1 when released

## Required Information
- Federal Schedule K-1 for each entity
- Entity's Iowa modification statement showing additions and subtractions separately
- Entity name and FEIN

## Questions
- Do you own an interest in a partnership, S corporation, estate, or trust?
- Did the entity provide an Iowa supplemental statement or Iowa K-1?
- Does the statement show a net addition or a net subtraction?

## Common Errors
- Leaving the entity's Iowa modification off entirely because only the federal K-1 was reviewed
- Netting additions and subtractions from different entities into one figure in the wrong column
- Double counting an item already reported by the entity
- Entering a subtraction as a negative number in column A instead of a positive number in column B

## Prompt
- I received a K-1 from a partnership with Iowa adjustments.
- My S corporation sent an Iowa K-1 with modifications.
