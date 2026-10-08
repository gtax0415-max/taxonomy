---
type: income
category: add-back
jurisdiction: IN
tax_year: 2026
source_doc: Federal Form 4562 Part I (Section 179 expense) / federal Schedule K-1 passing through Section 179 expense
form: Schedule 1
line: "5"
via:
  - Federal IRC Section 179 expense figured with a ceiling above $25,000 minus Section 179 expense figured with the $25,000 Indiana ceiling → Schedule 1, Line 5 → Line 7 → Form IT-40, Line 2
routing:
  - "Federal Section 179 expense figured with a ceiling of no more than $25,000 → no add-back"
  - "Federal Section 179 expense figured with a ceiling above $25,000 → add back the difference"
  - "Excess business loss year → see code 151"
see_also:
  - income/add-backs/add-backs.md
  - income/add-backs/bonus-depreciation-add-back.md
  - income/add-backs/excess-business-loss-modification-151.md
---
# Section 179 Expense Add-Back (Schedule 1, Line 5)
## Description
Indiana allows IRC Section 179 expense figured with a ceiling of no more than $25,000 (2025 amount; confirm against the 2026 form). If you figured Section 179 expense for federal purposes using a ceiling of more than $25,000, add back the difference between the federal amount and the amount figured with the $25,000 ceiling.
## Later years
The cost not expensed for Indiana is recovered through regular Indiana depreciation in later years, so keep an Indiana depreciation schedule. That later depreciation is a negative modification (the 2025 booklet does not name the line; report it consistently with the bonus depreciation catch-up and confirm against the 2026 form).
## Example
Federal Section 179 expense $60,000 on equipment. Indiana allows $25,000. Line 5 = $35,000. The $35,000 is then depreciated for Indiana in later years.
## Questions
- Did you or a pass-through entity elect Section 179 expense in 2026? How much?
- Is any Section 179 expense from K-1s?
- Was part of the deduction disallowed by the federal business income limit or an excess business loss?
## Common Errors
- Adding back the whole Section 179 amount instead of the excess over $25,000
- Applying the $25,000 ceiling twice to the same pass-through amount without checking the entity-level computation
- Forgetting later-year Indiana depreciation on the excess
## Prompt
- I expensed $100,000 under Section 179. How much does Indiana add back?
