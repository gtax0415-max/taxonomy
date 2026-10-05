---
type: credit
jurisdiction: Minnesota
tax_year: 2026
category: family-dependent
source_doc: Children's Social Security numbers or ITINs, dates of birth, and residency records / Schedule M1DQC Row 10 / federal Form 1040 Line 11 (AGI) / Minnesota advance-payment Summary Letter (if advances received)
form: Form M1
line: "22"
refundable: yes
via:
  - Schedule M1DQC (Row 10, qualifying children) → Schedule M1CWFC, Line 15 → Schedule M1REF, Line 2 → Form M1, Line 22
routing:
  - "Credit larger than 2026 advance payments → remaining credit (M1CWFC line 26) → Schedule M1REF, Line 2 → Form M1, Line 22"
  - "2026 advance payments larger than the credit → repayment (M1CWFC line 27) → Form M1, Line 14b (an additional TAX)"
  - "Election on the 2026 return → advance payments of the 2027 credit in three installments after July 1, 2027"
federal_counterpart: "Federal Child Tax Credit (Schedule 8812 → Form 1040, Lines 19 and 28)"
---
# Minnesota Child Tax Credit
## Description
Fully refundable credit per qualifying child under 18, with no limit on the number of children. Calculated on Schedule M1CWFC together with the Working Family Credit, and the two share one phase-out. Unlike the federal Child Tax Credit, it is FULLY refundable and requires no earned income.
## 2026 — MN Department of Revenue published figures
(TY2026 inflation-adjusted amounts, 12/1/2025; 2026 Schedule M1CWFC final draft, 10/1/2026)
CREDIT PER QUALIFYING CHILD (under 18): $1,800
NUMBER OF CHILDREN: no limit
PHASE-OUT THRESHOLD (combined with Working Family Credit): $38,770 married filing jointly / $32,680 all other filing statuses
PHASE-OUT RATE: 12% of the GREATER of AGI or earned income above the threshold
INVESTMENT INCOME LIMIT: $12,200
| Household | Maximum combined credit | Fully phased out — MFJ | Fully phased out — others |
|---|---|---|---|
| 1 young child (with max WFC) | $2,188 | $57,000 | $50,910 |
| 2 young children (with max WFC) | $3,988 | $72,000 | $65,910 |
Each additional child adds $1,800 to the maximum and $15,000 to the phase-out end point.
## 2025 — for comparison
$1,750 per child; phase-out began at $37,910 MFJ / $31,950 others.
## How it compares with the federal Child Tax Credit
| | Minnesota 2026 | Federal 2026 |
|---|---|---|
| Amount per child | $1,800 | $2,200 |
| Refundable | Fully | Partially (up to $1,700 per child) |
| Earned income required | No | Yes for the refundable part ($2,500 floor) |
| Phase-out starts | $32,680 / $38,770 MFJ | $200,000 / $400,000 MFJ |
| ID requirement | SSN or ITIN | SSN for the child and for at least one parent (OBBBA) |
| Child age | Under 18 | Under 17 |
A family can claim both. The Minnesota credit targets far lower incomes.
## Qualifying child
Minnesota uses the federal EIC definition of qualifying child (relationship, residency of more than half the year, joint-return test), restricted to children under 18 at year-end, with one exception: an SSN, ITIN, or ATIN issued or applied for by the due date is enough.
- Schedule M1DQC row numbering for 2026: row 6 dependent, row 7 Form 8332 release, row 8 months lived with you, row 9 full-time student, row 10 disabled, row 11 QUALIFYING CHILD, row 12 qualifying older child
- The 2026 Schedule M1CWFC (final draft) still tells filers to count "Row 10" for line 7, which conflicts with the renumbered M1DQC (row 11). Use the qualifying-child row on the final M1DQC
- A non-custodial parent who receives the exemption by Form 8332 (row 7) CANNOT treat the child as a qualifying child for the Minnesota Child Tax Credit; the custodial parent who released the exemption may still claim the credit
See minnesota/deductions/exemptions/schedule-m1dqc.md.
## Advance payments — a Minnesota feature
- ELECTION: On the 2026 return, a family can elect to receive part of the 2027 credit in advance. Advance = 50% of the 2026 child tax credit (prorated to exclude children who were 17 at the end of 2026), paid in THREE equal installments starting after July 1, 2027
- CONDITIONS: original return filed by April 15; at least one qualifying child under 17 at the end of 2026; Minnesota resident on December 31, 2026; cannot elect on an amended return
- RECONCILIATION: Anyone who received 2026 advance payments (elected on the 2025 return) MUST file a 2026 return, even if not otherwise required. Excess advances are REPAID on Form M1, Line 14b
- MINIMUM CREDIT BASE: protects advance recipients whose income rose. Equals 50% of the prior-year credit, reduced if the number of qualifying children falls
- Joint filers are each treated as having received half the advances; divorce splits them 50/50
- SNAP: advance payments may affect SNAP benefits; taking the credit at filing time does not
## Key eligibility rules
- Full-year or part-year Minnesota resident. Full-year nonresidents are NOT eligible. Part-year residents prorate by the Schedule M1NR percentage
- Same eligibility screens as the Working Family Credit: not a dependent, investment income at or under $12,200, no federal EIC ban
- MARRIED FILING SEPARATELY barred except the separated-spouse exception (see income-based/working-family-credit.md)
## Required Information
- Each child's name, SSN or ITIN, date of birth, relationship, months lived with you
- AGI, earned income, investment income
- 2026 advance payments received (Summary Letter), 2025 Minimum Credit Base (2025 M1CWFC line 28), 2025 number of qualifying children (2025 M1CWFC line 7)
- Bank information if electing 2027 advances
## Questions
- How many children under 18 lived with you more than half of 2026?
- Did you receive advance payments of your 2026 Minnesota Child Tax Credit?
- Do you want part of your 2027 credit paid in advance?
- Did your filing status change from 2025 (affects how advances are split)?
- Does anyone in the household use an ITIN?
## Common Errors
- Assuming it works like the federal credit (it is fully refundable and phases out at much lower income)
- Forgetting to reconcile 2026 advance payments, or not filing at all after receiving them
- Using the federal age limit (under 17) instead of Minnesota's (under 18)
- Applying a separate phase-out instead of the combined phase-out with the Working Family Credit
- Splitting advances incorrectly after a change in filing status
## Prompt
- How much is the Minnesota Child Tax Credit for 2026?
- I got advance child tax credit payments from Minnesota. What do I do?
- Can I get the Minnesota child credit if my kids have ITINs?
