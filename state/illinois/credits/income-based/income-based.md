---
type: credit
category: income-based
jurisdiction: IL
tax_year: 2026
form: Form IL-1040
line: "29, 30"
---
# Income-Based Credits
## Description
Credits that scale with earned income. Illinois has ONE: the earned income tax credit, a straight 20% of the federal EITC — but with eligibility BROADER than federal law, which is the distinctive feature. The child tax credit is computed from it and lives in family-dependent/, but is listed here because nothing about it is independent of the EITC.
## Credits in this folder
- Earned Income Tax Credit (earned-income-credit.md) — Schedule IL-E/EITC, Step 4 → Form IL-1040, Line 29. Refundable
- Expanded EITC Worksheet and Qualifications Questionnaire (expanded-eitc-worksheet.md) — the recomputation path for ITIN filers and childless workers aged 18-24 or 65+, feeding Step 4, Line 6
## Two credits, one federal input
| Credit | Rate | Line |
|---|---|---|
| Illinois EITC | 20% of the federal EITC (or of the federal EITC you WOULD get under Illinois's expanded rules) | 29 |
| Illinois Child Tax Credit | 40% of the Illinois EITC if a qualifying child is under 12 | 30 |
Together they are worth 28% of the federal EITC to a family with a child under 12.
## Where Illinois goes beyond federal law
Since tax year 2023 Illinois grants the EITC to two groups the IRS excludes:
- Filers, spouses, and children using an ITIN instead of a Social Security number
- Childless workers aged 18 through 24 and 65 and older
These filers compute a "pro forma" federal EITC on the Illinois Expanded EITC Worksheet and take 20% of that — see expanded-eitc-worksheet.md.
## Schedule IL-E/EITC does three jobs
| Step | Output | IL-1040 line |
|---|---|---|
| 2 | Dependent exemption allowance, $2,925 per dependent for 2026 (an allowance, not a credit; gone above $500,000 joint / $250,000 other AGI) | 10d |
| 3-4 | Illinois EITC | 29 |
| 5 | Illinois Child Tax Credit | 30 |
Any amount on Line 29 or 30 requires the schedule plus federal Form 1040 pages 1-2 and Schedule 1 to be attached.
## What Illinois does NOT have
- No noncustodial parent credit (New York's IT-209 has no analogue)
- No local EITC — Chicago and Cook County levy no income tax
- No separate household or low-income credit; the $2,925 exemption allowance (2026) is the only other low-income relief, and it vanishes above $500,000 / $250,000 AGI
## Rate history
5% (2000-2011) → 7.5% (2012) → 10% (2013-2016) → 14% (2017) → 18% (2018-2022) → 20% (2023 onward). A bill to move to 30% for 2026 (HB4680) was introduced in the 104th General Assembly; it had not been enacted as of IDOR Bulletin FY 2027-01, so the 2026 rate is 20%.
## Related
- Federal earned income credit, the input — see federal/credits/income-based/earned-income-credit.md
- The child tax credit built on top of it — see family-dependent/child-tax-credit.md
## Questions
- Did you claim the federal earned income credit, or would you have qualified except for using an ITIN or being 18-24 or 65+ without children?
- Do you have a qualifying child under 12?
## Prompt
- I got the federal EITC, does Illinois have one?
- I file with an ITIN, can I get the Illinois earned income credit?
- I am 22 with no kids, do I qualify for the Illinois EITC?
