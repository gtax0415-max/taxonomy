---
type: addition
category: deduction-addback
jurisdiction: CO
tax_year: 2026
source_doc: Federal Form 1040 as filed (line 11a AGI; line 12e standard or itemized deduction) / federal Schedule A, if itemized
form: Form DR 0104
line: "4"
via:
  - Form 1040, Line 12e − cap − state income tax already added back (Schedule A part) → Form DR 0104, Line 4 → Line 10
routing:
  - "Federal AGI $300,000 or less → $0"
  - "Single, married filing separately or head of household, AGI over $300,000 → line 12e minus $1,000"
  - "Joint, AGI over $300,000 → line 12e minus $2,000"
  - "Reduce by the Schedule A state income tax already added back, not by a pass-through entity's state tax share"
see_also:
  - income/additions/state-income-tax-addback.md
  - filing/filing-status.md
---
# Standard or Itemized Deduction Addback (High Earners)
## Description
Colorado limits the federal standard or itemized deduction for taxpayers with federal AGI over $300,000. Proposition MM (approved by voters in November 2025; HB25-1274) cut the allowed amount sharply starting in 2026.

## Amount
- Allowed deduction for 2026: $1,000 (single, separate, head of household) or $2,000 (joint)
- 2023 – 2025 caps were $12,000 / $16,000
- Addback = federal deduction − allowed cap − state income tax already added back from Schedule A

## Notes
- Applies whether the taxpayer itemized or took the standard deduction
- The cap is measured against Form 1040 line 12e only. On the 2026 Form 1040 the Schedule 1-A deductions (tips, overtime, car loan interest, seniors) are on line 13a, the QBI deduction on line 13b, and the new non-itemizer charitable deduction on line 12f; none of these is part of line 12e. DOR has not said whether the line 12f charitable deduction is reached by this addback
- DOR's 2026 guidance names the caps for "single" and "joint"; applying $1,000 to separate and head of household follows the 2025 pattern and is not separately confirmed
- Example: single, AGI $420,000, itemized deductions $60,000 including $25,000 state income tax (line 2 addback $25,000) → $60,000 − $1,000 − $25,000 = $34,000

## Required Information
- Federal AGI
- Federal standard or itemized deduction
- State income tax addback

## Questions
- Was your 2026 federal AGI over $300,000?
- What deduction did you claim on your federal return?

## Common Errors
- Using the 2025 $12,000 / $16,000 caps
- Not reducing by the state income tax addback
- Reducing by the pass-through state tax share

## Prompt
- What is the Colorado deduction addback for high earners in 2026?
