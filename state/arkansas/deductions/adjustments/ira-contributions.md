---
type: adjustment
category: adjustments
jurisdiction: AR
tax_year: 2026
source_doc: Form 5498 (box 1, traditional IRA contributions) or IRA custodian contribution statements / Form W-2 box 13 "Retirement plan" checkbox (taxpayer and spouse) / federal Schedule 1 (Form 1040), line 20
form: Form AR1000F
line: "24"
via:
  - AR1000ADJ, line 3 → AR1000ADJ, line 19 → Form AR1000F (or AR1000NR), line 24
---
# Payments to a Traditional IRA
## Description
Deduction for contributions to a traditional IRA. Arkansas mirrors the federal limits and phase-out ranges, but the phase-out is tested against ARKANSAS AGI (before the IRA deduction), so the Arkansas deduction can differ from the federal one.

## Amounts
- Contribution limit for 2026: $7,500, up from $7,000 for 2025 (IRS Notice 2025-67)
- Catch-up at age 50 or older by year-end: $1,100, up from $1,000 → $8,600 total
- No employer plan for either spouse: full deduction up to the limit, every filing status
- Phase-out ranges for 2026 (federal figures; Arkansas's 2025 booklet used the 2025 federal figures exactly):
  - Single or head of household, covered by an employer plan: $81,000–$91,000 (2025: $79,000–$89,000)
  - Married filing jointly (Status 2), married filing separately on the same return (Status 4), or surviving spouse, contributor covered: $129,000–$149,000 (2025: $126,000–$146,000)
  - Contributor NOT covered but spouse covered: $242,000–$252,000 (2025: $236,000–$246,000)
  - Married filing separately on different returns (Status 5): $0–$10,000 (not indexed)

## Notes
- Arkansas adopts IRC sections one by one rather than on a rolling date. DFA had not posted 2026 AR1000F instructions as of October 2026, so confirm the 2026 phase-out table when the booklet is released
- Use the Arkansas AGI from AR1000F, not federal AGI, to read the phase-out table
- Status 4 filers enter each spouse's amount in columns (A) and (B)
- Roth IRA contributions are never deductible

## Required Information
- Traditional IRA contributions for 2026 by spouse (including those made by the April 2027 due date for 2026)
- Whether each spouse was an active participant in an employer plan (W-2 box 13)
- Ages at December 31, 2026
- Arkansas AGI before the IRA deduction

## Questions
- Did you contribute to a traditional (not Roth) IRA for 2026?
- Were you or your spouse covered by a retirement plan at work?
- Were you 50 or older by December 31, 2026?
- Is your Arkansas AGI near the phase-out range?

## Common Errors
- Copying the federal deduction without re-testing it against Arkansas AGI
- Using the 2025 $7,000 limit or 2025 phase-out ranges
- Deducting Roth IRA contributions
- Missing the $1,100 catch-up
- Applying the covered-participant range when only the spouse was covered

## Prompt
- I contributed $7,500 to a traditional IRA this year.
- I have a 401(k) at work and also put money in an IRA.
- My spouse has a pension but I don't. Can I deduct my IRA?
