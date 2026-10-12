---
type: filing
category: filing
jurisdiction: MO
tax_year: 2026
statute: RSMo 143.101
source_doc: Lease, deed, or mortgage statement for each home / driver's license and voter registration / record of days spent in Missouri / W-2s showing work state
form: Form MO-1040
line: "31, 32"
line_basis: 2025 form numbering (2026 Missouri forms expected December 2026); amounts are 2026
via:
  - Full-year resident, Missouri income only → line 31 = $0, line 32 = 100%
  - Resident with income taxed by another state → Form MO-CR → line 31
  - Nonresident or part-year resident → Form MO-NRI → line 32
---
# Residency Status
## Description
Residency decides whether all income is taxed (resident) or only Missouri-source income (nonresident).

## Amounts for 2026
- Resident: (1) domiciled in Missouri, unless they keep no permanent home in Missouri, keep a permanent home elsewhere, and spend 30 days or less in Missouri; or (2) not domiciled in Missouri but keep a permanent home here and spend more than 183 days here
- No change for 2026

## Eligibility
- Every filer

## Notes
- Product scope (team decision 2026-09-30): the template covers full-year residents with Missouri income only, so line 31 is $0 and line 32 is 100%. Residents with other-state income, part-year residents, and nonresidents are out of scope
- Military: a Missouri home of record is presumed Missouri domicile
- Example: full-year Columbia resident with only Missouri income → line 32 = 100%

## Required Information
- Domicile, homes kept, days in Missouri
- Income taxed by another state

## Questions
- Did you live in Missouri all year?
- Did you earn income taxed by another state?

## Common Errors
- Using MO-NRI as a full-year resident
- Treating a domiciled resident working out of state as a nonresident

## Prompt
- Am I a Missouri resident?
