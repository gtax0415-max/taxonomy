---
type: income
category: retirement
jurisdiction: new-jersey
tax_year: 2026
source_doc: Form 1099-R (Box 1, Box 2a, Box 7) / Form 5498 / plan statement of employee after-tax contributions / IRA contribution history and records of prior withdrawals / federal Form 8606
form: Form NJ-1040
line: "20a, 20b"
via:
  - Noncontributory plan → full amount → Line 20a
  - Contributory plan → Worksheet A (method) → Three-Year Rule or Worksheet B (General Rule) → Line 20a taxable / Line 20b excludable
  - IRA withdrawal → Worksheet C → Line 20a taxable / Line 20b excludable
routing:
  - "Qualified Roth IRA distribution → not reported at all"
  - "Nonqualified Roth distribution → earnings on Line 20a, contributions on Line 20b"
  - "Qualifying rollover → not reported"
  - "Traditional-to-Roth conversion → amount that would be taxable if withdrawn goes on Line 20a"
  - "Taxpayer 62+ or disabled with Line 27 ≤ $150,000 → exclusion on Line 28a"
---
# Pensions, Annuities, and IRA Withdrawals
## Description
Retirement distributions are taxable in NJ, but the NJ taxable amount often DIFFERS from the federal Box 2a amount because New Jersey taxed most employee contributions when they were made.
## Taxable (Line 20a)
- Private-sector pensions; federal, state, local, and teachers' pensions
- Civil Service (OPM) pensions, even if based on military service credit
- 401(k) and Keogh distributions; early retirement benefits
- Pension amounts reported on an NJK-1
- Disability pensions starting the year the recipient turns 65
## Not taxable (not reported)
- Social Security; Railroad Retirement
- U.S. military pensions and survivor benefits
- Disability pensions before the year the recipient turns 65
## Computing the taxable portion
- NONCONTRIBUTORY plans: fully taxable
- CONTRIBUTORY plans (other than IRAs): complete Worksheet A in the first year
  - THREE-YEAR RULE: if both employee and employer contributed and contributions will be recovered within 36 months, report everything on Line 20b until contributions are recovered; afterward, fully taxable on Line 20a
  - GENERAL RULE (Worksheet B): otherwise, excludable % = previously taxed contributions ÷ expected return; applied to each year's payment. Recompute only if payments decrease
- 401(k): contributions made on/after 1/1/1984 were not taxed, so distributions are fully taxable (unless contributions exceeded the federal limit, or were made before 1984)
- Contributions to a non-401(k) plan made BEFORE moving to NJ are treated as previously taxed
- IRAs (Worksheet C): taxable % = accumulated earnings ÷ total IRA value (year-end value + current-year distributions). Carry unrecovered contributions forward year to year (Part II), or reconstruct them (Part III)
- Lump-sum distributions: amount above previously taxed contributions is taxable in the year received; NJ has no income averaging
## Notes
- 403(b), 457, and TSP contributions were taxed by NJ going in, so a portion of those withdrawals comes out tax-free — the NJ taxable amount is usually LOWER than the federal amount
- Part-year residents: include only amounts received while a resident
- See GIT-1 & 2, Retirement Income, and TB-44 (Roth IRAs)
## Required Information
- All Forms 1099-R with distribution codes
- Total contributions and which were taxed by NJ
- Prior Worksheets B and C
- IRA year-end values and contribution history
## Questions
- Is the payment from a pension, 401(k), 403(b), 457, IRA, Roth IRA, or military retirement?
- Did you contribute to the plan, and were those contributions taxed by New Jersey?
- Is this the first year of payments?
- Was any distribution rolled over or converted to a Roth?
## Common Errors
- Reporting the federal Box 2a amount without the NJ calculation
- Taxing U.S. military retirement pay
- Using the IRA method (Worksheet C) for a pension, or vice versa
- Losing track of unrecovered IRA contributions year to year
- Reporting a qualified Roth distribution
## Prompt
- I started receiving my state pension this year.
- I took a distribution from my IRA. How much is taxable in New Jersey?
- Is my military retirement taxed in New Jersey?
