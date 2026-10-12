---
type: exclusion
category: pass-through-entity-exclusion
jurisdiction: LA
tax_year: 2026
source_doc: Schedule K-1 (federal Form 1065 or 1120-S) / entity's statement that it elected to pay Louisiana income tax at the entity level, with the owner's share of income
form: Form IT-540, Schedule E
line: "Schedule E, Lines 4A to 4G, code 24E"
via:
  - Owner's share of electing entity's income → Schedule E code 24E → Line 4H → Line 5 → Form IT-540, Line 7
  - A loss instead → Schedule E, Line 2D (addition)
---
# Pass-Through Entity Exclusion (Code 24E)
## Description
Owners of a partnership, LLC, or S corporation that elected to pay Louisiana income tax at the entity level exclude their share of its income, because the entity already paid the tax.

## Rules
- Exclude the owner's share of net income from an entity that properly filed a Louisiana corporate return under the entity-level election
- No exclusion for income that did not bear the entity-level tax
- A loss is added back on Schedule E Line 2D instead
- Federal changes to the entity's return must be reported to LDR within 60 days

Example: a shareholder of an electing S corporation excludes $20,000 of K-1 income.

## 2026 change for S corporations
Act 382 of the 2025 Regular Session (applies from January 1, 2026) makes S corporations pass-through entities for Louisiana by default: the S corporation files an informational return and income flows to shareholders. S corporations may still make the entity-level election (LDR Revenue Information Bulletin 25-032), and only then does 24E apply. An entity-level election and a composite return can't be used for the same year.

## Notes
- Authority: R.S. 47:297.14
- LDR requires its pass-through exclusion form attached; that state form is not a source document here

## Required Information
- Election status for 2026
- Owner's share of income

## Questions
- Did the business elect to pay Louisiana tax at the entity level for 2026?
- Is it an S corporation? (No election means the income is taxable to you)

## Common Errors
- Excluding S corporation income when no entity-level election was made
- Excluding a loss instead of adding it back

## Prompt
- My S corporation paid Louisiana tax itself. Do I report the income?
