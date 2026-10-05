---
type: income
jurisdiction: MA
tax_year: 2026
category: wages
source_doc: Form W-2 Box 16 (state wages, Massachusetts) and Box 17 (Massachusetts withholding) / Form W-2 Box 1 for reconciliation / federal Form 1040 Line 1z / Form 2555 (foreign earned income excluded federally)
form: Massachusetts Form 1
line: "3"
rate: "5.0% (Part B)"
via:
  - Form W-2 Box 16 → Form 1, Line 3 → Line 10 (total 5.0% income)
  - Form W-2 Box 17 → Form 1, Line 38a (withholding)
routing:
  - "Most taxpayers → Line 3 equals federal Form 1040 Line 1z"
  - "Massachusetts state, city, town or county employee contributing to a pension → use W-2 Box 16 (higher than Box 1); deduct contributions up to $2,000 on Line 11a/11b"
  - "Foreign earned income excluded federally (Form 2555 / IRC 911) → ADD BACK to Line 3"
  - "Medicaid waiver payments included in Line 3 → exclude via Schedule Y, Line 9a"
  - "Firefighter/police line-of-duty incapacity pay (MGL ch 41 §111F) or treaty-exempt pay → Schedule Y, Line 4a / 4b"
  - "Tips or commissions not on a W-2 → Schedule X, Line 4"
---
# Wages, Salaries, Tips and Other Employee Compensation
## Description
All wages and allocated tips from Forms W-2, taxed as 5.0% Part B income. Usually equal to federal Form 1040, Line 1z, but use the Massachusetts state wage figure (W-2 Box 16) and watch for the differences below.
## Where federal and Massachusetts wages differ
| Item | Federal | Massachusetts |
|---|---|---|
| Massachusetts public pension contributions | Excluded | TAXED (in Box 16); deduct up to $2,000 on Line 11 |
| Foreign earned income exclusion (IRC 911) | Excluded | TAXED — add back |
| Tips deduction (IRC 224, P.L. 119-21) | Deduction allowed | NOT allowed |
| Overtime deduction (IRC 225, P.L. 119-21) | Deduction allowed | NOT allowed |
| Dependent care assistance (2026) | Up to $7,500 excluded | Only $5,000 excluded; excess TAXED |
| Employer parking / transit + vanpool (2026) | $340 per month each | $335 per month each; excess TAXED |
| Qualified bicycle commuting reimbursement (2026) | Not excludable (repealed) | Up to $20 per month ($240/yr) EXCLUDED |
| Employer contributions to Trump accounts | Excluded | Not adopted — confirm Box 16 |
| Employer student loan repayment (2026) | Excluded up to $5,250 (made permanent) | Massachusetts does not adopt the permanent extension; see deductions/schedule-y/student-loan-deductions.md |
| Medicaid waiver payments | Excluded via Schedule 1 | Exclude via Schedule Y, Line 9a |
Massachusetts amounts above come from TIR 25-9 (transportation) and TIR 26-4 (Public Law 119-21 conformity).
## 401(k), 403(b), Section 125
Massachusetts generally follows the federal exclusion for 401(k) and 403(b) elective deferrals and Section 125 cafeteria plan amounts, so Box 16 usually matches Box 1 for these. Employer HR systems sometimes get Massachusetts-specific differences wrong — reconcile Box 1 to Box 16 when they differ.
## Notes
- DOR and the IRS exchange data; differences between federal and Massachusetts wages not explained by state law can trigger audit
- Nonresidents report only Massachusetts-source wages on Form 1-NR/PY
- Paid Family and Medical Leave benefits are NOT wages here — see other-income/pfml-distributions.md
## Required Information
- All Forms W-2 (Boxes 1, 12, 14, 16, 17)
- Form 2555, if any foreign earned income was excluded
- Employer pension contribution amounts (government employees)
- Dependent care, transit, parking and bicycle benefit amounts
## Questions
- Do your W-2 Box 1 and Box 16 amounts differ? Why?
- Are you a Massachusetts state or municipal employee contributing to a pension?
- Did you exclude foreign earned income on your federal return?
- Did you claim the federal tips or overtime deduction?
- Did you receive more than $5,000 of dependent care benefits?
## Common Errors
- Using W-2 Box 1 instead of Box 16 for public employees
- Carrying the federal tips or overtime deduction into Massachusetts
- Not adding back foreign earned income
- Forgetting excess dependent care, parking or transit benefits for 2026
## Prompt
- How do I report my W-2 on my Massachusetts return?
- My Massachusetts wages are higher than my federal wages.
- Can I deduct my tips or overtime in Massachusetts?
