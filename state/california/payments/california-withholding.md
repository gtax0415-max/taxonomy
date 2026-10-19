---
type: payment
category: payments
jurisdiction: CA
tax_year: 2026
source_doc: Form W-2 (box 17) / Form W-2G (box 15) / Forms 1099-DIV (box 16), 1099-INT (box 17), 1099-K (box 8), 1099-MISC (box 16), 1099-NEC (box 5), 1099-OID (box 14), 1099-R (box 14) showing California tax withheld
form: Form 540
line: "71"
via:
  - California withholding from federal information returns → Form 540, Line 71
---
# California Income Tax Withheld
## Description
California income tax withheld from wages and other payments, credited against the tax on Form 540, line 71.

## What to include
- W-2 box 17; W-2G box 15; the California withholding box on Forms 1099-DIV, 1099-INT, 1099-K, 1099-MISC, 1099-NEC, 1099-OID and 1099-R

## What NOT to include
- City, local or county tax; tax withheld by other states
- Withholding from Forms 592-B or 593 (goes on line 73; see payments/nonresident-and-real-estate-withholding.md)
- Nonconsenting nonresident member's tax from an LLC Schedule K-1 (568), line 15e
- SDI (it is not income tax)

## Notes
- Line numbers follow the 2025 Form 540 and schedules; confirm them on the 2026 forms (expected December 2026)
- EXCESS SDI CREDIT no longer exists: since 2024 California has no SDI taxable wage limit, so the excess SDI (or VPDI) line was removed from the return
- Too little withholding can trigger the estimated tax penalty when the balance due is $500 or more ($250 MFS) and withholding is under 90% of total tax
- Employees adjust California withholding with EDD Form DE 4, which is separate from federal Form W-4
- Tax generally is not withheld from 1099-MISC or 1099-NEC income; use estimated payments instead

## Required Information
- Every W-2 and 1099 showing California withholding

## Questions
- Did your employer or payers withhold California tax?
- Do you have withholding for other states on your W-2?

## Common Errors
- Including other states' withholding or SDI
- Putting 592-B or 593 withholding on line 71

## Prompt
- How do I report the California tax withheld on my W-2?
