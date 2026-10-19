---
type: credit
category: income-based
jurisdiction: NM
tax_year: 2026
source_doc: Federal Form 1040 as filed (household, dependents, age 65 and blind boxes) / dependents' residency (where each dependent lived during 2026)
form: Form PIT-1
line: "24"
refundable: yes
via:
  - PIT-1 Line 5 → PIT-RC Lines 1–3 (exemption count for the rebate table) → PIT-RC, Line 13a
---
# Household Members and Extra Exemptions (PIT-RC Lines 1–3)
## Description
Builds the exemption count used to look up the low income comprehensive tax rebate. It starts from PIT-1 line 5 and adds extra exemptions for blindness and age.

## How to count
- Line 1: exemptions from PIT-1 line 5
- Line 2a: subtract household members who do not qualify (for example, a nonresident dependent; a resident dependent temporarily out of state still counts)
- Line 2c: add 1 for each spouse who is blind (1 or 2)
- Lines 2e, 2f: add 2 for each spouse who is 65 or older
- Line 2h: married filing separately, subtract exemptions the other spouse claims; each exemption can be used only once
- Line 3: the result, carried to line 13a

## Example
Married couple, both 66, one blind, no dependents: 2 + 1 (blind) + 2 + 2 (age) = 7, so they use the "6 or more" column.

## Status for 2026
No change from the 2026 legislative session.

## Required Information
- PIT-1 line 5 count
- Ages and blindness of each spouse
- Where each dependent lived

## Questions
- Are you or your spouse 65 or older, or blind?
- Did any dependent live outside New Mexico permanently?

## Common Errors
- Forgetting the two extra exemptions for each spouse 65 or older
- Counting a nonresident dependent
- Both separate filers counting the same dependents

## Prompt
- How many exemptions do I use for the New Mexico rebate table?
