---
type: addition
category: qbi-addback
jurisdiction: CO
tax_year: 2026
source_doc: Federal Form 1040 as filed (line 11a AGI; line 13b QBI deduction on the 2026 form; it was line 13a in 2025) / Form 8995 or 8995-A / Colorado K-1 statement showing a SALT Parity election by the entity / federal Schedule F, if filed
form: Form DR 0104
line: "3"
via:
  - Form 1040, Line 13b (2026) → Form DR 0104, Line 3 (when a test below is met) → Line 10
routing:
  - "Federal AGI over $500,000 ($1,000,000 joint) and no Schedule F for the year → add back the entire QBI deduction"
  - "Partner or shareholder in an entity that made the SALT Parity election → add back the QBI deduction regardless of AGI"
  - "Otherwise → $0"
see_also:
  - credits/refundable/composite-salt-parity-tax-paid.md
  - income/federal-deductions-flowing-through.md
---
# Qualified Business Income Deduction Addback
## Description
Colorado requires high-income taxpayers, and owners in entities that paid Colorado tax under the SALT Parity election, to add back the federal section 199A QBI deduction. HB25B-1001 made the addback permanent for 2026 and later.

## Amount
- The entire QBI deduction, not just the part above the threshold

## Notes
- Example: joint filers, AGI $1,250,000, QBI deduction $42,000, no Schedule F → add $42,000. At AGI $990,000 → $0

## Required Information
- Federal AGI and QBI deduction
- Whether Schedule F was filed
- Any K-1 showing a SALT Parity election

## Questions
- Did you claim a QBI deduction, and what is your federal AGI?
- Did any partnership or S corporation make a SALT Parity election?
- Do you file Schedule F?

## Common Errors
- Adding back only the excess over the threshold
- Missing the SALT Parity addback below the threshold

## Prompt
- Does Colorado allow the QBI deduction?
