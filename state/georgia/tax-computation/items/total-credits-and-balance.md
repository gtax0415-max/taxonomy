---
type: computation
category: tax-computation
subtype: balance
jurisdiction: GA
tax_year: "2026"
source_doc: No external source document — totaled on the return from the credit amounts already entered on Lines 17-21 and the tax on Line 16. The supporting documents live with each individual credit (see credits/)
form: Form 500
line: "22, 23"
refundable: n/a
via:
  - Form 500, Line 22 (sum of Lines 17-21, capped at Line 16) → Line 23 (Line 16 minus Line 22)
---
# Total Credits and Balance (Georgia)
## Description
Line 22 totals every credit used on Lines 17–21 and enforces the universal liability cap; Line 23 is the remaining tax balance that payments and withholding are then applied against.
## The lines
- Line 22 = sum of Lines 17–21 (Low Income + Other State + Eligible Itemizer + IND-CR Summary + Schedule 2)
- Line 22 CANNOT exceed Line 16 (the tax). Credits are nonrefundable in aggregate here — they can zero out tax but not create a refund (except the separately-handled refundable Timber credits on Schedule 2B)
- Line 23 = Line 16 minus Line 22; if zero or negative, enter zero
## The universal liability cap
The total credit used from the low income credit, the other state(s) tax credit, all IND-CR schedules, and all Schedule 2s cannot exceed the tax liability on Line 16. This is the same cap referenced throughout the credits/ branch.
## Required Information
- Credit amounts from Lines 17–21
- Line 16 tax (for the cap)
## Questions
- What credits are you claiming on Lines 17–21?
- Do your total credits exceed your Line 16 tax?
## Common Errors
- Letting total credits exceed Line 16 (they are capped)
- Expecting nonrefundable credits to generate a refund
- Forgetting refundable Timber credits are claimed separately on Schedule 2B, not here
## Prompt
- Can my Georgia credits create a refund?
- What if my credits are bigger than my tax?
- How do I total my Georgia credits?
## Related
- The individual credits themselves — see credits/
- Refundable Timber credits (Schedule 2B) — see credits/business-passthrough.md
