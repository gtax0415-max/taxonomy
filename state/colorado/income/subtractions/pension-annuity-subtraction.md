---
type: subtraction
category: pension-annuity
jurisdiction: CO
tax_year: 2026
source_doc: Form 1099-R for each recipient (pensions, annuities, IRAs; box 7 code 4 for death benefits) / Form RRB-1099-R, if applicable / Form SSA-1099 (for the Social Security reduction)
form: Form DR 0104
line: "11"
via:
  - Taxable 1099-R income by person → limit less that person's Social Security subtraction → DR 0104AD, Line 4 (primary) and Line 6 (spouse) → DR 0104AD subtotal → Form DR 0104, Line 11
routing:
  - "65 or older on December 31, 2026 → $24,000 minus that person's Social Security subtraction"
  - "55 to 64 → $20,000 minus that person's Social Security subtraction"
  - "Under 55 receiving as a beneficiary after the earner's death → $20,000 minus Social Security; enter the deceased earner's SSN or ITIN"
  - "Under 55 own pension or early IRA withdrawal → $0"
see_also:
  - income/subtractions/social-security-subtraction.md
  - income/subtractions/military-retirement-subtraction.md
  - filing/deceased-taxpayer.md
---
# Pension, Annuity, IRA and Disability Income Subtraction
## Description
Colorado subtracts part of pension, annuity, IRA and disability income (not SSDI), with limits by age. Each person's limit is reduced by their own Social Security subtraction.

## Amount
- Age 65+: up to $24,000
- Age 55 – 64, or under-55 beneficiary: up to $20,000
- Each limit is reduced by the same person's Social Security subtraction
- Unchanged for 2026 (a 2025 bill to remove the caps, SB25-136, did not pass)

## Notes
- Each spouse claims only on their own income; the primary uses line 4, the spouse line 6
- Attach all 1099-Rs
- Example: primary age 67, taxable Social Security $18,000 and pension $30,000 → limit $24,000 − $18,000 = $6,000 → subtract $6,000

## Required Information
- 1099-R for each person
- Ages
- Social Security subtraction by person
- Deceased earner's SSN for beneficiary payments

## Questions
- How old were you and your spouse on December 31, 2026?
- Whose name is on each 1099-R, and was any received as a beneficiary?

## Common Errors
- Combining both spouses' pensions on one line
- Not reducing the limit by Social Security
- Claiming for an under-55 early IRA withdrawal

## Prompt
- How much of my pension is exempt in Colorado?
