---
type: income
jurisdiction: MA
tax_year: 2026
category: other-income
source_doc: U.S. Form 461 / federal Form 1040 Schedule 1 Line 8p / Massachusetts Schedule TDS (to explain differences)
form: Massachusetts Form 1
line: "9"
rate: "5.0% (Part B)"
via:
  - U.S. Schedule 1, Line 8p (adjusted for Massachusetts differences) → Schedule X, Line 6 → Form 1, Line 9
routing:
  - "Federal excess business loss → add back on Schedule X, Line 6"
  - "Massachusetts amount differs from federal (e.g., depreciation) → explain on Schedule TDS"
---
# Excess Business Loss Adjustment
## Description
Business losses above an annual threshold are disallowed. Federally the disallowed amount becomes a net operating loss carryforward; in Massachusetts it is simply LOST, because Massachusetts allows no NOL for individuals.
## Thresholds
- 2025: $313,000 single / $626,000 joint (2025 Form 1 instructions)
- 2026: Massachusetts does NOT adopt the P.L. 119-21 modification of IRC 461(l) (TIR 26-4). The federal 2026 threshold reflects that law's rebasing; the Massachusetts 2026 threshold is pending DOR guidance and may differ
## How it works
Recompute the excess business loss using Massachusetts income and deductions (no bonus depreciation, Massachusetts Section 179 limits) and enter it on Schedule X, Line 6. Explain any difference from U.S. Schedule 1, Line 8p on Schedule TDS.
## Questions
- Did you file U.S. Form 461?
- Do your business losses exceed the threshold?
## Common Errors
- Carrying a disallowed loss forward in Massachusetts
- Using the federal figure without Massachusetts depreciation adjustments
## Prompt
- I have a large business loss this year.
