---
type: income
jurisdiction: MA
tax_year: 2026
category: retirement
source_doc: Form 1099-R Boxes 1, 2a, 7 (distribution code), 14 (state tax withheld) / federal Form 1040 Lines 5a and 5b / records of contributions previously taxed by Massachusetts
form: Massachusetts Form 1
line: "4"
rate: "5.0% (Part B)"
via:
  - Form 1099-R → Form 1, Line 4 → Line 10
  - Form 1099-R Box 14 (Massachusetts withholding) → Form 1, Line 38b with Schedule 62-WH
routing:
  - "Exempt government pension (U.S., Massachusetts or its subdivisions, contributory; noncontributory uniformed services) → enter 0 on Line 4 and note the source"
  - "Taxable private pension → federal 1040 Line 5b, adjusted for contributions previously taxed by Massachusetts"
  - "Contributory pension from another state that does not tax Massachusetts pensions → report on Line 4, deduct on Schedule Y, Line 13"
  - "IRA / Keogh distributions → NOT here; Schedule X, Line 2"
---
# Pensions and Annuities
## Description
Taxable pension and annuity income, taxed as 5.0% Part B income. Massachusetts exempts several categories of government pensions entirely and requires recovery of contributions that Massachusetts already taxed.
## Exempt pensions (enter 0)
- CONTRIBUTORY pensions from the U.S. government, the Commonwealth of Massachusetts, or its cities, towns and counties
- NONCONTRIBUTORY pensions and survivorship benefits from the U.S. uniformed services (Army, Navy, Marine Corps, Air Force, Coast Guard, Public Health Service commissioned corps, NOAA)
- Massachusetts state court judges appointed on or after January 2, 1975
- Lump-sum return of previously taxed contributions to a U.S. or Massachusetts public employee leaving before retirement
## Taxable, with an offsetting deduction
Contributory pensions from ANOTHER STATE (or its subdivisions) are reported on Line 4, but are deductible on Schedule Y, Line 13 if that state does not tax Massachusetts government pensions (reciprocity; see TIR 95-9).
## Basis recovery (private plans)
For 403(b) and Section 404 plan distributions, subtract contributions (including rollover contributions) that were previously taxed by Massachusetts until they are fully recovered. Enter the adjusted amount on Line 4.
## Notes
- Massachusetts does not tax Social Security — see social-security.md
- Rollovers not taxable federally are generally not taxable in Massachusetts
- Taxable portion of a traditional-to-Roth rollover follows Schedule X, Line 2 rules
- Noncontributory pension received after a lump-sum withdrawal of contributions is fully taxable
## Required Information
- Every Form 1099-R with payer type (federal, Massachusetts public, other state, private)
- Massachusetts-taxed contribution history for private plans
- Massachusetts withholding (Box 14)
## Questions
- Who pays your pension — the federal government, Massachusetts, a city or town, another state, or a private employer?
- Is it a contributory plan?
- Did you contribute after-tax money that Massachusetts already taxed?
## Common Errors
- Reporting an exempt Massachusetts or federal pension
- Missing the Schedule Y, Line 13 deduction for reciprocal other-state pensions
- Reporting IRA distributions on Line 4 instead of Schedule X
- Not recovering previously taxed contributions
## Prompt
- I retired from the City of Boston. Is my pension taxable?
- I get a military pension.
- I have a pension from Connecticut / New York state.
