---
type: income
jurisdiction: MA
tax_year: 2026
category: other-income
source_doc: Form 1099-G Box 1 (unemployment compensation) and Box 11 (state income tax withheld) / federal Form 1040 Schedule 1 Line 7
form: Massachusetts Form 1
line: "8a"
rate: "5.0% (Part B)"
via:
  - Form 1099-G → U.S. Schedule 1, Line 7 → Form 1, Line 8a
  - Form 1099-G Massachusetts withholding → Form 1, Line 38b
routing:
  - "Unemployment benefits → Line 8a (same as federal)"
  - "Repayment of unemployment benefits in a later year → Schedule Y, Line 14 (claim of right) or Line 9a (Trade Act repayment)"
---
# Unemployment Compensation
## Description
Unemployment benefits are fully taxable in Massachusetts as 5.0% Part B income, in the same amount as federal.
## Notes
- DOR matches Line 8a against Department of Unemployment Assistance records
- Voluntary Massachusetts withholding on Form 1099-G goes on Line 38b
- PFML benefits are NOT unemployment — see pfml-distributions.md
## Questions
- Did you receive unemployment in 2026? Was Massachusetts tax withheld?
## Common Errors
- Omitting the 1099-G
- Missing the withholding credit
## Prompt
- I collected unemployment this year.
