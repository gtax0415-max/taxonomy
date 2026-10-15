---
type: credit
category: earned-income
jurisdiction: CO
tax_year: 2026
source_doc: Forms W-2 / Forms 1099-NEC / federal Form 1040 as filed (lines 1z and 11a) with Schedules C, F and SE / Schedule K-1 (self-employment income) / ITIN or SSN for filer, spouse and children / proof of student, homeless youth or former foster youth status, if applicable
form: Form DR 0104
line: "31"
refundable: yes
via:
  - DR 0104TN → DR 0104CR, Line 9 → Line 26 → Form DR 0104, Line 31
routing:
  - "Filer, spouse or child has an ITIN or an SSN not valid for employment → continue"
  - "Work-eligible SSN, no qualifying children, under 25 at the end of 2026 → continue and mark a student/youth status"
  - "Federal EITC allowed in full → use the regular Colorado EITC (DR 0104CR line 5), not this credit"
  - "Full-year nonresident, nonresident alien, married filing separately (unless separated-spouse rule), Form 2555 filer → not eligible"
see_also:
  - credits/refundable/earned-income-tax-credit.md
  - credits/refundable/refundable-credits-total.md
---
# Colorado EITC for ITIN Filers and Certain Filers Under 25
## Description
Colorado's version of the earned income credit for people the federal EITC leaves out: households where the filer, spouse or child uses an ITIN (or an SSN not valid for work), and childless workers under 25 with a work-eligible SSN. The credit is figured as if the federal EITC applied, using the federal table, then multiplied by the Colorado rate.

## Amounts
- Rate for 2026: 25% of the computed federal-equivalent EITC (down from 50% for 2025). 25% is the statutory floor under HB24-1134; the higher tiers did not trigger for 2026
- 2026 federal EITC parameters (Rev. Proc. 2025-32):

| Qualifying children | Max federal credit | Phase-out begins (other / joint) | Phase-out ends (other / joint) |
|---|---|---|---|
| 0 | $664 | $10,860 / $18,140 | $19,540 / $26,820 |
| 1 | $4,427 | $23,890 / $31,160 | $51,593 / $58,863 |
| 2 | $7,316 | $23,890 / $31,160 | $58,629 / $65,899 |
| 3+ | $8,231 | $23,890 / $31,160 | $62,974 / $70,244 |

- Investment income limit for 2026: $12,200
- Part-year residents multiply by the Colorado income percentage

## Eligibility
- Earned income and AGI within the 2026 limits above
- Up to three qualifying children, or no children and the under-25 rules
- Under-25 childless filers must be one of: not a specified student (ages 19–24), a specified student (age 24), a qualified homeless youth (18–24), or a qualified former foster youth (18–24, with consent to disclose)

## Notes
- Earned income is built from wages and net self-employment earnings, with clergy, church-employee, Medicaid waiver and combat-pay adjustments, as on the federal EIC worksheet
- Use the 2026 IRS Publication 596 EIC table for the credit at earned income and at AGI; take the smaller
- Example: single, age 23, not a student, work-eligible SSN, no children, wages $9,000. $9,000 is on the 2026 no-child plateau ($8,680 – $10,860), so the federal-equivalent credit is $664. Colorado credit = $664 × 25% = $166

## Required Information
- Wage and self-employment income documents
- Federal AGI and investment income
- ITIN or SSN for each person and whether the SSN is valid for employment
- Age, student status, and homeless or foster youth status for under-25 filers
- Qualifying children's names, birth dates and identifying numbers

## Questions
- Do you, your spouse or your children have an ITIN?
- Were you under 25 with no qualifying children at the end of 2026?
- Are you a student, a homeless youth or a former foster youth?
- Did you claim the federal EITC?

## Common Errors
- Using this credit when the federal EITC was allowed in full
- Using the 50% rate from 2025
- Using the 2025 Pub 596 table or income limits
- Not marking a status box for an under-25 filer

## Prompt
- Can ITIN filers get the Colorado earned income credit?
- I'm 22, have no kids and work part time in Colorado.
