---
type: credit
category: income-based
jurisdiction: PA
source_doc: PA-40 Schedule A lines 6 and 7 and PA-40 Schedule B line 3 (tax-exempt interest and exempt-interest dividends) / Form 1099-R with distribution code 4 in box 7 (death benefits) / records of alimony, insurance proceeds, inheritances, gifts and prizes, nontaxable scholarships and grants, foster care payments / each dependent child's birth certificate and Social Security card for a first-time claim / pages 1 and 2 of the federal return for part-year residents, nonresidents, and adult or differently-named dependents
form: PA-40
line: "21"
refundable: no
via:
  - PA-40 Schedule SP, Section IV line 16 → PA-40, Line 21
routing:
  - "Unmarried, separated, or deceased → Schedule SP Column A → Eligibility Income Table 1"
  - "Married filing jointly → Schedule SP Column A → Eligibility Income Table 2"
  - "Married filing separately → Schedule SP Columns B and C, combined → Eligibility Income Table 2"
---
# Tax Forgiveness (PA-40 Schedule SP)
## Description
Pennsylvania's largest personal income tax relief provision and its substitute for the standard deduction, personal exemption, and low-income credits that its flat 3.07% rate otherwise lacks. It forgives 10% to 100% of the PA liability. NEARLY ONE IN FIVE PENNSYLVANIA HOUSEHOLDS QUALIFIES.
## The computation, Section IV
```
Line 12  PA tax liability, from PA-40 Line 12
Line 13  LESS resident credit, from PA-40 Line 22
Line 14  Net PA tax liability
Line 15  Forgiveness percentage, as a decimal, from the Eligibility Income Table
Line 16  Line 14 x Line 15 → PA-40, Line 21
```
The percentage applies to the liability AFTER the resident credit, not to the gross liability. Schedule OC restricted credits are then capped by whatever remains.
## Eligibility Income Table 1 — unmarried, separated, deceased
| Dependent children | 100% | 90% | 80% | 70% | 60% | 50% | 40% | 30% | 20% | 10% |
|---|---|---|---|---|---|---|---|---|---|---|
| 0 | $6,500 | $6,750 | $7,000 | $7,250 | $7,500 | $7,750 | $8,000 | $8,250 | $8,500 | $8,750 |
| 1 | $16,000 | $16,250 | $16,500 | $16,750 | $17,000 | $17,250 | $17,500 | $17,750 | $18,000 | $18,250 |
| 2 | $25,500 | $25,750 | $26,000 | $26,250 | $26,500 | $26,750 | $27,000 | $27,250 | $27,500 | $27,750 |
| 3 | $35,000 | ... | | | | | | | | $37,250 |
| 9 | $92,000 | ... | | | | | | | | $94,250 |
## Eligibility Income Table 2 — married claimants, EVEN IF FILING SEPARATELY
| Dependent children | 100% | 90% | 80% | 70% | 60% | 50% | 40% | 30% | 20% | 10% |
|---|---|---|---|---|---|---|---|---|---|---|
| 0 | $13,000 | $13,250 | $13,500 | $13,750 | $14,000 | $14,250 | $14,500 | $14,750 | $15,000 | $15,250 |
| 1 | $22,500 | $22,750 | $23,000 | $23,250 | $23,500 | $23,750 | $24,000 | $24,250 | $24,500 | $24,750 |
| 2 | $32,000 | ... | | | | | | | | $34,250 |
| 9 | $98,500 | ... | | | | | | | | $100,750 |
THE STRUCTURE IS SIMPLE ARITHMETIC. Base of $6,500 unmarried or $13,000 married, PLUS A $9,500 ALLOWANCE PER DEPENDENT CHILD, then $250 steps down through each 10% band. Anyone can reconstruct the whole table from those three numbers.
Above nine dependent children, see the PA Personal Income Tax Guide.
These figures are STATUTORY and are not indexed annually. 2025 figures shown, and the same amounts have held for many years.
FOR 2026: the 2026-27 budget signed July 12, 2026 continues all seven of the Governor's tax cuts but does NOT announce a Tax Forgiveness expansion. A third-party calculator site asserts expanded 2026 thresholds; that is UNCONFIRMED by the Department. Verify against the 2026 Schedule SP before using anything other than the figures above.
## WHAT ELIGIBILITY INCOME EXCLUDES — the correction that matters most
A widespread misconception, which earlier versions of this file repeated, is that Social Security and retirement income are added back. THEY ARE NOT. Schedule SP's Line 10 instructions EXPRESSLY EXCLUDE:
- SOCIAL SECURITY AND RAILROAD RETIREMENT BENEFITS
- RETIREMENT BENEFITS FROM PA-ELIGIBLE RETIREMENT PLANS after becoming eligible to retire and retiring
- United Mineworkers pensions
- MILITARY PENSION benefits
- Civil Service annuity payments
- Child support, unless received by a dependent child of a taxpayer who also qualifies
- Workers' compensation, occupational disease, and Heart and Lung pensions
- Payments for work injuries and damages for personal injury
- SICK PAY AND DISABILITY BENEFITS, including third-party insurer payments
- Damage awards and settlements for physical injury or sickness, pain and suffering, emotional distress
- Personal use of employer property NOT included in federal taxable income
- Long-term care insurance contracts without accumulated refundable reserves
CONSEQUENCE: a retired Pennsylvania couple living on Social Security and an IRA they draw after retiring can have SUBSTANTIAL cash income and NEAR-ZERO eligibility income. PA exempts retirement income from the tax AND from the forgiveness test. This is one of the most generous retiree provisions in the country.
CONTRAST WITH THE FEDERAL POSITION: federally, Social Security is partly taxable and every dollar of an IRA distribution is taxable. For PA both are excluded from the tax AND from the forgiveness test.
## What eligibility income INCLUDES — Schedule SP lines 1 to 10
| Line | Item |
|---|---|
| 1 | PA taxable income, from PA-40 Line 9 |
| 2 | Nontaxable interest, dividends, and gains; exempt-interest dividends; direct federal, PA, and PA political subdivision obligations; nontaxable portion of any gain; KOZ-exempt entity income; annualized income for decedents |
| 3 | ALIMONY received — NOT child support |
| 4 | Insurance proceeds and inheritances, including Form 1099-R distribution code 4 |
| 5 | Gifts, awards, and prizes, including noncash PA Lottery prizes and civic awards |
| 6 | NON-PA INCOME of part-year residents and nonresidents, including SCRA-exempt amounts |
| 7 | Nontaxable MILITARY income — NOT combat or hazardous duty pay |
| 8 | Gain excluded on the sale of a principal residence |
| 9 | Nontaxable scholarships, fellowships, stipends, federal and state education grants, employer tuition reductions — NOT student loans |
| 10 | Foster care payments; spousal support from outside the household; payments from persons outside the household; cafeteria plan payments for hospitalization, sickness, disability, death, supplemental unemployment or strike benefits; personal use of employer property IF in federal taxable income; government education grants |
If nothing belongs on lines 2 through 10, ENTER ZERO.
## Dependent children: the two-step test
STEP 1 — IS THE INDIVIDUAL A CHILD OF THE CLAIMANT? Natural child, adopted child, or step-child of a parent; GRANDCHILD of a grandparent; FOSTER CHILD of a foster parent. An AUNT, UNCLE, GUARDIAN, or unrelated person CANNOT claim a child here even if they claim them federally.
STEP 2 — CAN THE CLAIMANT CLAIM THE CHILD AS A FEDERAL DEPENDENT?
AGE IS NOT A BAR. Age, student status, and gross income matter only in deciding federal dependency. PARENTS WHO CAN CLAIM A QUALIFYING 30-YEAR-OLD CHILD FEDERALLY CAN CLAIM THAT CHILD ON SCHEDULE SP. This is much broader than most preparers assume.
NO OTHER ADULT may be claimed, even if claimed federally. A dependent parent produces no allowance.
Also disqualifying: a former spouse or the child's other parent has the right to claim the child by agreement or court decree.
## Married claimants cannot act independently
A MARRIED TAXPAYER CANNOT CLAIM TAX FORGIVENESS INDEPENDENTLY OF A SPOUSE. Both must use JOINT eligibility income and TABLE 2, even when filing separately. Spouses are never dependents of one another for this purpose, even when one has no eligibility income at all.
THERE IS NO ADVANTAGE TO FILING SEPARATELY. The Department says so directly. The spouse's SSN must appear on Schedule SP either way.
Filing separately for PA while filing jointly federally: each spouse completes Schedule SP AS IF FILING JOINTLY, reports the SAME dependents and the SAME joint eligibility income, fills the Married and Filing Separate ovals, CERTIFIES the information matches, and attaches a copy to BOTH returns.
When claiming together, EITHER spouse need meet the eligibility requirements, but joint eligibility income and Table 2 still apply.
## Dependents on another person's return
If you are claimed as a dependent on someone else's FEDERAL return, you can claim Tax Forgiveness ONLY IF that person also qualifies for it. Both eligibility questions at the top of Schedule SP must be answered Yes.
STUDENTS: a full-time student who is a dependent on a parent's federal return CANNOT claim the credit regardless of their own income UNLESS the parents qualify. If the parents do qualify, the student files their own PA-40 and Schedule SP.
DEPENDENT CHILDREN WITH INCOME: a dependent child with PA taxable income over $33 MUST FILE A PA-40. If the parents qualify, the child qualifies too, and must include any child support paid to the parent on the child's behalf in the child's own eligibility income.
WHERE ONE SPOUSE IS A DEPENDENT of another person, otherwise-qualifying married taxpayers MUST FILE SEPARATELY. The Department's example: Scott is his parents' dependent and ineligible; his wife Paula files Schedule SP, cannot claim Scott as a dependent, but MUST include his eligibility income. If Scott's parents qualify, Scott may also qualify by including Paula's income in his own total.
## Nonresidents and part-year residents CAN claim it
They must meet the same requirements and must include on LINE 6 all income earned, received, or realized OUTSIDE Pennsylvania. Paper filers must attach pages 1 and 2 of the federal return.
RECIPROCAL-STATE RESIDENTS with PA-taxable income in a class other than compensation must include on Line 6 both their nontaxable out-of-state income AND the compensation not taxable to PA under reciprocity.
## Decedents: annualization
Eligibility is tested against a FULL YEAR of income, so a decedent's income must be ANNUALIZED: realized income divided by days or months lived, multiplied by 365 or 12. Subtract the realized income from that product and report the remainder on LINE 2. ONE-TIME TRANSACTIONS such as a stock or property sale need not be annualized.
The prior year's eligibility income may be used if the person qualified then, had roughly the same income, and had no unusual transactions. The Department generally accepts a reasonable calculation. Describe the method on Schedule SP.
A SURVIVING SPOUSE FILING SEPARATELY must NOT include income in respect of a decedent, income belonging on the estate return, or any of the decedent's income including the decedent's half of joint income received before death.
## Substantiation
FIRST-TIME claimants, and anyone claiming a NEW dependent on a Schedule SP return, should attach BIRTH CERTIFICATES AND SOCIAL SECURITY CARDS for every dependent listed.
Attach pages 1 and 2 of the federal return if claiming an ADULT child, an ADOPTED child, a FOSTER child, or a child with a DIFFERENT LAST NAME.
With more than four dependent children, the Department recommends claiming all of them federally as well, even where no federal benefit results.
## Notes
- Schedule SP must be included with the ORIGINAL return; an amended Schedule SP goes with Schedule PA-40 X, and Section III of page 2 of the X must explain the change
- Forgiveness can produce a REFUND of tax already withheld, and forgives liabilities even where nothing has been paid. It cannot exceed the liability, so it is not refundable in the sense the child care credit is
- Whole dollars only; round at $0.50
## Required Information
- PA taxable income from PA-40 Line 9 and the resident credit from Line 22
- Each nontaxable item on lines 2 through 10
- Every dependent child's name, age, relationship, and SSN
- Spouse's SSN and eligibility income, ALWAYS, including on separate returns
- Whether anyone claims you as a federal dependent, and whether they qualify
## Questions
- What is your PA taxable income, and what nontaxable income did you receive?
- How many dependent CHILDREN can you claim federally, at any age?
- Are you married, and what is your spouse's eligibility income?
- Does anyone claim you as a dependent on their federal return?
- Did you receive alimony, an inheritance, gifts over the ordinary, or a scholarship?
## Common Errors
- Adding back Social Security, a PA retirement plan distribution, military pension, or Civil Service annuity, none of which belong in eligibility income
- Including child support as alimony on Line 3
- Omitting a dependent ADULT child who qualifies federally
- A guardian, aunt, or uncle claiming a child who is not their child under the two-step test
- A married taxpayer computing forgiveness on their own income alone
- Using Table 1 when married and filing separately; Table 2 applies
- A student claiming it while a parent's dependent, without confirming the parent qualifies
- Applying the percentage to the gross liability instead of the liability net of the resident credit
- Omitting birth certificates and Social Security cards on a first-time claim
- Failing to annualize a decedent's income
## Prompt
- Do I qualify for PA tax forgiveness?
- I am retired in Pennsylvania on Social Security and a pension.
- My son is 25 and I still claim him, does he count?
