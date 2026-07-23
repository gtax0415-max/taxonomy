---
type: income
category: retirement
source_doc: Form 1099-R Box 1 (gross distribution), Box 2a (taxable amount, often equal to Box 1 because the custodian cannot tell), Box 7a (code 7, or code Y where the custodian uses it) / the charity's written acknowledgment / the custodian's confirmation that the check was payable to the charity
form: Form 1040
line: "4a, 4b"
via:
  - Form 1099-R Box 1 → Form 1040 Line 4a (full distribution)
  - Form 1040 Line 4b = Line 4a minus the QCD, with "QCD" written beside the line
routing:
  - "Qualified charitable distribution → EXCLUDED from income entirely; Form 1040 Line 4a shows the gross, Line 4b shows only the remainder"
  - "Any part not meeting the QCD rules → taxable IRA distribution → Form 1040 Line 4b"
---
# Qualified Charitable Distribution (QCD)
## Description
A direct transfer from an IRA to a qualified charity by an owner age 70.5 or older. The amount never enters income at all. For a retiree who takes the standard deduction, this is worth more than a charitable deduction, because it reduces AGI rather than merely reducing taxable income for the small minority who itemize.
## 2026 amounts
- $111,000 per individual, up from $108,000 for 2025. Indexed annually under SECURE 2.0
- A married couple filing jointly can do $222,000 — $111,000 from EACH spouse's own IRA. It is a per-person limit, not a per-return limit
- One-time election to fund a split-interest vehicle (charitable gift annuity or charitable remainder trust): $55,000 for 2026, up from $54,000
## The age is 70.5 — not the RMD age
QCD eligibility begins at exactly age 70.5, tested on the DATE OF THE DISTRIBUTION. Someone who turns 70.5 on June 1 can make a QCD on June 2 but not on May 31. SECURE and SECURE 2.0 raised the RMD start age to 73 and later 75, but they did NOT move the QCD age. So there is a window of several years in which a taxpayer can make QCDs before any RMD is required.
## Why it beats a deduction
- The QCD is EXCLUDED from gross income, so it never reaches AGI
- A lower AGI can reduce the taxable portion of Social Security, reduce Medicare IRMAA surcharges, and preserve deductions and credits that phase out with AGI
- It works for the roughly 90% of filers who take the standard deduction, who get nothing at all from a cash gift on Schedule A
- It is NOT subject to the 60%-of-AGI limit on cash contributions, nor to the 0.5% AGI floor that applies to itemized charitable gifts beginning in 2026
- Bunching is unnecessary. The exclusion is available every year regardless of Schedule A
## It counts toward the RMD — with a timing trap
A QCD satisfies the required minimum distribution dollar for dollar. But ORDERING MATTERS: the first dollars out of the IRA in a year are treated as the RMD. If you take a regular distribution first and make the QCD afterward, the regular distribution has already used up the RMD and cannot be undone. Schedule the QCD as the FIRST distribution of the year.
## The requirements
- Direct TRUSTEE-TO-TRUSTEE transfer. A check made payable to you and then endorsed over to the charity does NOT qualify
- The recipient must be a qualifying public charity. DONOR-ADVISED FUNDS, private foundations, and supporting organizations are excluded — a QCD to a DAF is disqualified entirely and becomes a fully taxable distribution
- Traditional, rollover, and INHERITED IRAs qualify if the account holder is 70.5 or older. SEP and SIMPLE IRAs qualify only if no longer active
- Employer plans such as 401(k)s do NOT qualify. Roll to an IRA first
- No goods or services may be received in return. A written acknowledgment is required, the same as for any charitable gift
## Reporting — the custodian will not do it for you
The custodian reports the distribution on Form 1099-R like any other. Box 1 shows the gross, and Box 2a often shows the same amount because the custodian has no way to know the money went to charity.
- Form 1040 Line 4a: the FULL distribution from Form 1099-R Box 1
- Form 1040 Line 4b: the taxable remainder AFTER subtracting the QCD
- Write "QCD" beside Line 4b to explain why the two lines differ
Beginning with 2025 forms, the IRS added Form 1099-R Box 7 code Y for qualified charitable distributions. For 2025 its use was OPTIONAL, so many forms still show code 7. Either way the reporting responsibility is yours.
## The post-70.5 IRA contribution offset
If you make a DEDUCTIBLE traditional IRA contribution in or after the year you turn 70.5, a special ordering rule reduces the amount that can be excluded as a QCD, cumulatively across years. Contributing and making QCDs in the same period partially cancels the benefit.
## Related
- The distribution itself: federal/income/retirement/1099-r.md
- Charitable rules and qualified organizations: federal/deductions/itemized/charitable-contributions.md
- Missing an RMD: federal/taxes/retirement-account-penalties.md
## Required Information
- Form 1099-R Box 1, Box 2a and Box 7a
- The charity's written acknowledgment and confirmation of direct payment
- Your age on the date of each distribution
- Total QCDs across ALL IRAs for the year, against the single $111,000 limit
- Any deductible IRA contributions made at or after age 70.5
## Questions
- Were you at least 70.5 years old on the date of the distribution?
- Did the custodian pay the charity DIRECTLY, or did the check come to you first?
- Was the recipient a public charity, or a donor-advised fund (which disqualifies it)?
- Was the QCD the first distribution of the year, so it covers the RMD?
- What is the total of all QCDs across all your IRAs?
- Have you made deductible IRA contributions since turning 70.5?
## Common Errors
- Assuming Form 1099-R reports the QCD for you, and reporting the full amount as taxable on Line 4b
- Taking the RMD first and making the QCD afterward, so the QCD no longer offsets the RMD
- Sending the money to a donor-advised fund, which voids the entire QCD
- Endorsing a check made out to you over to the charity instead of a direct transfer
- Attempting a QCD from a 401(k) rather than an IRA
- Making a QCD before turning exactly 70.5
- Expecting a QCD above the RMD to reduce future years' RMDs — each year stands alone
## Prompt
- I am over 70 and want to give to charity from my IRA.
- I made a qualified charitable distribution this year.
- Can I donate my required minimum distribution to charity?
- I take the standard deduction but still give to my church.
