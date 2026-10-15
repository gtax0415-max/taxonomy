---
type: income
category: federal-deductions-flowing-through
jurisdiction: CO
tax_year: 2026
source_doc: Federal Schedule 1-A as filed (tips, overtime, car loan interest, enhanced senior deduction) and Form 1040 lines 12f, 13a and 13b / Forms W-2 (box 12 code TP tips and code TT overtime) / Form 1098 or lender statement for car loan interest / Form 8995 / federal Form 1040 as filed
form: Form DR 0104
line: "1"
via:
  - Federal deductions below AGI → already out of federal taxable income → Form DR 0104, Line 1, with no Colorado entry unless an addition applies
routing:
  - "Qualified tips deduction → no Colorado addback"
  - "Enhanced senior deduction ($6,000 per person 65 or older) → no Colorado addback (not on the additions list; not separately stated by DOR)"
  - "Car loan interest deduction → no Colorado addback (not on the additions list; not separately stated by DOR)"
  - "Qualified overtime deduction → added back for 2026 (overtime-deduction-addback)"
  - "QBI deduction → flows through unless AGI is over $500,000 / $1,000,000 or a SALT Parity election applies (line 3)"
  - "Standard or itemized deduction → flows through unless AGI is over $300,000 (line 4; 2026 caps $1,000 / $2,000)"
see_also:
  - income/additions/overtime-deduction-addback.md
  - income/additions/qbi-deduction-addback.md
  - income/additions/standard-itemized-deduction-addback.md
---
# Federal Deductions That Flow Through to Colorado
## Description
Because Colorado starts from federal taxable income, every federal deduction reduces Colorado income unless Colorado requires an addback. For 2026, the new federal tips, car loan interest and senior deductions flow through, but the overtime deduction is added back.

## Notes
- DOR states expressly that no addback is required for the tips deduction; the senior and car loan interest deductions have no addback in law, but DOR has not addressed them by name
- 2026 Form 1040 placement: Schedule 1-A deductions on line 13a (they were on line 13b in 2025), QBI deduction on line 13b (was 13a), new non-itemizer charitable deduction ($1,000 / $2,000) on line 12f; taxable income on line 15 = line 11b − line 14
- Senior deduction for 2026: $6,000 per person born before January 2, 1962, reduced by 6% of modified AGI over $75,000 ($150,000 joint)
- W-2 box 12 code TT reports qualified overtime; code TP reports cash tips
- The high-earner cap on the standard or itemized deduction does not reach the Schedule 1-A deductions, which are on a separate Form 1040 line
- Example: server with $22,000 of qualified tips deducted on Schedule 1-A → federal taxable income already excludes the $22,000; no Colorado entry

## Required Information
- Federal Schedule 1-A deductions

## Questions
- Did you take any deductions on federal Schedule 1-A for 2026?
- Was any of it for overtime?

## Common Errors
- Adding back the tips or senior deduction
- Forgetting to add back the overtime deduction for 2026

## Prompt
- Does Colorado tax my tips if they are deductible federally?
