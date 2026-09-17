---
type: credit
category: income-based
jurisdiction: IL
tax_year: 2026
source_doc: Federal Form 1040 or 1040-SR pages 1-2 AND Schedule 1 (MUST BE ATTACHED whenever Line 29 or 30 has an amount) / federal EITC from Form 1040 Line 27 and federal Schedule EIC / for expanded-eligibility filers, the Illinois Expanded EITC Worksheet built from Form 1040 Line 1z, Schedule SE Part I, Schedule C or F, and a pro forma Form 1040 if no federal return was required / SSN or ITIN, date of birth, relationship, and months in home for every dependent and qualifying child / Schedule NR Line 48 decimal for nonresidents and part-year residents / spouse's SSN from the joint federal return if filing separately in Illinois
form: Form IL-1040
line: "29"
refundable: yes
via:
  - Schedule IL-E/EITC, Steps 2-3 (child tables) → Step 4, Line 9 → Form IL-1040, Line 29
routing:
  - "Federal EITC allowed and no additional ITIN children → skip Line 5 → Line 6 = federal EITC → × 20% → Line 9 → IL-1040 Line 29"
  - "ITIN filer, spouse, or child; or age 18-24 / 65+ with no qualifying child → check a box on Line 5 → EITC Qualifications Questionnaire → Illinois Expanded EITC Worksheet Parts 1-5 → Worksheet Line 23 → Step 4, Line 6 → IL-1040 Line 29"
  - "Nonresident or part-year resident → Step 4, Line 8 = Schedule NR Line 48 decimal → prorated Line 9"
  - "Qualifies AND a dependent under 12 → continue to Step 5 for the Child Tax Credit → IL-1040 Line 30"
---
# Illinois Earned Income Tax Credit
## Description
Refundable credit equal to 20% of the federal earned income credit, claimed on Schedule IL-E/EITC — the same schedule that computes the dependent exemption allowance (Step 2 → IL-1040 Line 10d) and the Child Tax Credit (Step 5 → Line 30). Since tax year 2023 Illinois has EXPANDED ELIGIBILITY beyond federal law, so people with no federal EITC at all can still receive an Illinois one by rebuilding the federal computation on the Illinois Expanded EITC Worksheet. Publication 132 is IDOR's plain-language guide.
## Amount for 2026
- 20% of the federal EITC allowed (Step 4, Line 6 × 20%)
- For expanded-eligibility filers, 20% of the federal EITC they WOULD receive, from Worksheet Line 23
- Nonresidents and part-year residents multiply by the Schedule NR, Line 48 decimal on Line 8
| Qualifying children | 2026 max federal EITC | Illinois EITC (20%) | Child Tax Credit on top (40% of IL EITC, child under 12) |
|---|---|---|---|
| Zero | $664 | $133 | n/a |
| One | $4,427 | $885 | $354 |
| Two | $7,316 | $1,463 | $585 |
| Three or more | $8,231 | $1,646 | $658 |
(2025: $130 / $866 / $1,430 / $1,609.) Federal figures are from Rev. Proc. 2025-32; the Illinois rate is unchanged at 20% under 35 ILCS 5/212(a)(vi).
## Who Illinois adds that the IRS excludes
You may claim the Illinois EITC if you meet EVERY federal requirement except that you (or your spouse, if married):
- File using an IRS-issued ITIN rather than a Social Security number — for you, your spouse, and/or any qualifying child. No SSN is required anywhere on the Illinois claim, and/or
- Were aged 18 through 24, or 65 and older, on the last day of the tax year and had NO qualifying child (federal law limits childless filers to ages 25 through 64)
These filers check the applicable box on Step 4, Line 5, complete the EITC Qualifications Questionnaire, and then the Illinois Expanded EITC Worksheet. A filer who received the federal EITC but has an ADDITIONAL child with an ITIN whom the IRS would not count also goes through Line 5 and the worksheet, and can end up with a larger Illinois credit than 20% of the federal one. See expanded-eitc-worksheet.md.
## Federal limits Illinois adopts for 2026
Earned income and federal AGI must both be under the completed-phaseout amount (Rev. Proc. 2025-32; these replace Table 1 in the 2025 instructions):
| Qualifying children | Single, head of household, widowed | Married filing jointly |
|---|---|---|
| Zero | $19,540 | $26,820 |
| One | $51,593 | $58,863 |
| Two | $58,629 | $65,899 |
| Three or more | $62,974 | $70,244 |
(2025, for amended returns: $19,104 / $26,214; $50,434 / $57,554; $57,310 / $64,430; $61,555 / $68,675.)
Investment income must be $12,200 or less for 2026 ($11,950 for 2025). Investment income is Form 1040 Lines 2a + 2b + 3b + 7 (capital gain, zero if a loss); filers with Schedule E, Form 4797, personal-property rental income, Form 8814, or passive activity income must use Worksheet 1 in federal Publication 596 instead. This is a CLIFF: one dollar over and the Illinois EITC and the Child Tax Credit built on it disappear along with the federal credit.
## Other federal rules that carry over
- No federal Form 2555 (foreign earned income)
- You, or your spouse on a joint return, were a U.S. resident for at least half the year, and your main home was in the U.S. more than half the year (military on extended active duty abroad count as in the U.S.)
- Married filing separately or head of household while married: allowed only if you lived apart from your spouse for the last six months of the year, or are legally separated under a written agreement or decree of separate maintenance and lived apart at year end. A childless filer who is married and not filing jointly is barred outright
- You cannot be another person's qualifying child, and a childless filer cannot be claimable as another person's dependent (ignore this if that person is not required to file and files only for a refund)
- A qualifying child may be claimed by only one person
- Federal special rules for military members, clergy, and people with disabilities apply
## Qualifying child, Illinois definition
- Age: under 19 and younger than you (or your spouse on a joint return); or under 24, a full-time student for at least five months, and younger than you; or any age if permanently and totally disabled at any time during the year
- Relationship: son, daughter, stepchild, adopted or foster child, brother, sister, half- or step-sibling, grandchild, niece, or nephew
- Residency: lived with you in the United States more than half the year
- Identification: a valid SSN OR ITIN
- Did not file a joint return with a spouse except to claim a refund of withholding
## The two child tables
- Step 2, Dependent Information: every dependent, with an "eligible for Illinois EITC" checkbox for those who also meet the qualifying-child test. Line 1 of Step 2 also produces the $2,925 per-dependent exemption allowance for IL-1040 Line 10d, which is disallowed above $500,000 joint / $250,000 other federal AGI
- Step 3, Qualifying Child Information (other than a dependent): children from federal Schedule EIC who are NOT your dependents — a child who lives with you but is claimed as a dependent by the other parent, for instance. Do not repeat Step 2 children here
Each row needs name, SSN or ITIN (enter "died" for a child who died before a number was issued), relationship, date of birth, full-time-student and disability boxes, and months lived with you (maximum 12).
## Step 4 mechanics
- Line 2 / Line 3: if you filed a joint federal return but a separate Illinois return, enter the spouse's SSN from the joint federal return on Line 3a. Both spouses may claim the Illinois EITC only in the INJURED-SPOUSE situation, and the federal credit reported on both Line 6s combined cannot exceed the joint federal credit
- Line 5: check a box and complete the Questionnaire and Expanded Worksheet if any ITIN or age-expansion situation applies; otherwise skip to Line 6 with the federal Form 1040 Line 27 amount
- Line 8: nonresident or part-year decimal from Schedule NR Line 48
- Line 9: the Illinois EITC → IL-1040 Line 29
## Notes
- Fully refundable; you must FILE to get it even with no tax due and no filing requirement
- The refund is excluded from income and resources for means-tested benefit programs
- IDOR reviews every EITC claim and may request documentation, especially where the federal return shows business income or loss
- Fraudulent claims can bar the credit for up to ten years plus penalties; intentionally false information is a crime under IITA Section 1301
- Omitting the federal pages 1-2 and Schedule 1 is the most common processing delay
## Required Information
- Federal EITC from Form 1040 Line 27 and the number of qualifying children on Schedule EIC
- Full child details for Steps 2 and 3, including which dependents are EITC-eligible
- Whether you, your spouse, or any child uses an ITIN, and whether you are 18-24 or 65+ with no qualifying child
- For expanded filers: Line 1z wages, Schedule SE amounts, Schedule C/F profit, investment income lines, federal AGI, and the pro forma Form 1040 if none was filed
- Schedule NR Line 48 decimal if not a full-year resident
- Spouse's SSN from the joint federal return if filing separately in Illinois
## Questions
- Did the IRS allow you a federal earned income credit, and how much?
- If not, was that only because of an ITIN, or because you are 18-24 or 65+ with no children?
- Do you have a child with an ITIN whom the IRS did not count?
- Is your investment income $12,200 or less?
- Do you have a dependent under 12 for the Child Tax Credit?
- Were you an Illinois resident all year?
- Did you file jointly for federal purposes but separately for Illinois?
## Common Errors
- Assuming an ITIN filer, or a 19-year-old with no children, cannot claim — Illinois allows both, unlike the IRS and unlike New York
- Taking 20% of the federal credit when a Line 5 box applies, and missing the larger worksheet-based credit
- Listing a Step 2 dependent again in Step 3, or omitting a non-dependent qualifying child from Step 3
- Forgetting the federal pages 1-2 and Schedule 1 attachment
- Forgetting to prorate on Line 8 as a part-year resident, or prorating as a full-year resident
- Both spouses claiming on separate Illinois returns outside the injured-spouse case
- Skipping Step 5 and losing the Child Tax Credit
- Using an old rate (18% or lower) or the 2025 income limits on a 2026 return
## Prompt
- I claimed the EITC on my federal return and live in Illinois.
- I work with an ITIN in Chicago, do I get any earned income credit?
- I am 22 with no kids and got nothing federally, does Illinois give me anything?
- Does Illinois have its own earned income credit and how much is it?
