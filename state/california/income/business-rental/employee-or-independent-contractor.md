---
type: income
category: business-rental
jurisdiction: CA
tax_year: 2026
source_doc: Form W-2 issued for California purposes / Form 1099-NEC, 1099-K or 1099-MISC issued for federal purposes for the same pay / federal Schedule C, Schedule SE and Schedule 1 as filed (Lines 15 and 17 deductions)
form: Form 540
line: "14, 16"
via:
  - "Federal Schedule C gross receipts → Schedule CA (540), Part I, Section A, Line 1a, column C (add as wages) → Form 540, Line 16"
  - "Same amount as business income → Schedule CA (540), Part I, Section B, Line 3, column A and column B (remove) → Form 540, Line 14"
  - "Self-employed health insurance deduction: Schedule CA (540), Part I, Section C, Line 17, column B (not allowed)"
  - "Self-employment tax deduction: Schedule CA (540), Part I, Section C, Line 15, column B (not allowed)"
  - "Nonresident/part-year: same entries on Schedule CA (540NR), Part II"
---
# Employee or Independent Contractor (Worker Classification Differences)
## Description
A worker can be an independent contractor for federal purposes but an EMPLOYEE for California (for example, under AB 5). Such a worker may get a 1099 for federal purposes and a W-2 for California. Schedule CA then moves the income from business income to wages and removes deductions only self-employed people can take.

## Income adjustments (resident, Schedule CA (540))
- Reported federally as Schedule C gross receipts (line 7) → enter as WAGES on Part I, Section A, line 1a, column C
- Reported federally as business income (Schedule 1, line 3) → enter the same amount on Part I, Section B, line 3, in column A AND column B to remove it

## Deduction adjustments
- SELF-EMPLOYED HEALTH INSURANCE: not allowed. Enter the federal amount in Section C, line 17, column A and remove it in column B. The premiums may instead count as medical expenses (Part II, lines 1–4)
- SELF-EMPLOYMENT TAX deduction: not allowed. Enter in Section C, line 15, column A and remove it in column B
- Unreimbursed employee expenses: may become a California miscellaneous itemized deduction (see deductions/itemized/miscellaneous-itemized-deductions.md)

## Nonresident or part-year resident
- Same entries on Schedule CA (540NR), Part II (medical on Part III, lines 1–4)

## Proposition 22
- The California Supreme Court upheld Proposition 22 on July 25, 2024. App-based rideshare and delivery drivers (for example, Lyft, Uber, DoorDash, Instacart, Postmates) are INDEPENDENT CONTRACTORS for California when its conditions are met, so no reclassification adjustment applies to them

## Notes
- Line numbers follow the 2025 Form 540 and schedules; confirm them on the 2026 forms (expected December 2026)

## Required Information
- Both the federal 1099 and the California W-2 for the same pay
- How the amount was reported federally (Schedule C line 7 or Schedule 1 line 3)
- Federal SE tax and SE health insurance deductions
- Residency status

## Questions
- Did you get a 1099 for federal and a W-2 for California for the same work?
- How did you report the income on your federal return?
- Did you take the self-employment tax or self-employed health insurance deduction?
- Are you an app-based driver covered by Proposition 22?

## Common Errors
- Counting the same income twice (as wages and as business income)
- Keeping the SE tax or SE health insurance deduction for California
- Reclassifying Proposition 22 drivers as employees

## Prompt
- My employer gave me a 1099 but California says I'm an employee.
- I got a W-2 for California and a 1099-NEC for federal for the same job.
