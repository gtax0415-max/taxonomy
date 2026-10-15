---
type: credit
category: energy-home
jurisdiction: CO
tax_year: 2026
source_doc: Seller's invoice for the residential energy storage system showing purchase price, installation address and installation date / written assignment of the credit from the building owner to the seller
form: Form DR 0104
line: "31"
refundable: partially
via:
  - DR 1307 → DR 0104CR, Line 15 (seller, assigned credit) → Line 26 → Form DR 0104, Line 31
  - DR 1307 → DR 0104CR, Line 60 (owner, not assigned) → nonrefundable
routing:
  - "Owner assigned the credit to the seller → seller claims it here, refundable"
  - "Owner kept the credit → nonrefundable, DR 0104CR line 60"
see_also:
  - credits/refundable/refundable-credits-total.md
  - credits/nonrefundable/residential-energy-storage-nonrefundable.md
---
# Residential Energy Storage Systems Credit
## Description
Credit for buying and installing a qualifying battery storage system at a residence in Colorado (SB22-051, extended by SB25-026). It is refundable only when the owner assigns it to the seller, who passes the value through as a discount.

## Amount
- 10% of the purchase price of the system
- 2026 is the LAST year (SB25-026 extended it through tax year 2026)

## Eligibility
- Residential energy storage system installed at a Colorado residence in 2026
- Refundable portion: seller that was assigned the credit by the building owner

## Notes
- The owner's nonrefundable credit has no carryforward
- Example: homeowner assigns the credit on a $15,000 battery → seller claims $1,500

## Required Information
- Invoice with purchase price and installation details
- Assignment from the owner

## Questions
- Did you install a home battery system in Colorado in 2026?
- Did the owner assign the credit to the seller?

## Common Errors
- An owner claiming the refundable seller line
- Assuming the credit continues after 2026

## Prompt
- Who claims the Colorado battery storage credit?
- I installed a home battery this year.
