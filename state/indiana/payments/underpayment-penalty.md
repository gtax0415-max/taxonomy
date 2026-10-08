---
type: tax
category: underpayment-penalty
jurisdiction: IN
tax_year: 2026
source_doc: Records of 2026 estimated payments and dates / Forms W-2 and 1099 showing Indiana withholding / prior-year (2025) tax liability / income records by period if income was uneven
form: Form IT-40; Schedules IT-2210 and IT-2210A
line: "20, 20a"
via:
  - Schedule IT-2210 Section C required annual payment → Section D short method line 13 or Section E regular method line 21 (10% of underpayment) → Form IT-40, Line 20
  - Schedule IT-2210A annualized installments → line 27 (10% of underpayment) → Form IT-40, Line 20; Line 20a Code A
  - Line 20 → subtracted from overpayment on Line 21, or added to tax due on Line 23
routing:
  - "Tax after credits and withholding less than $1,000 → no penalty"
  - "Paid the lesser of 90% of 2026 tax or 100% of 2025 tax (110% if 2025 federal AGI over $150,000, $75,000 MFS) on time → no penalty"
  - "No Indiana liability for 2025 (no return required and none filed) → from 2026, prior-year tax treated as $0 under IRC 6654 → no penalty (SEA 453)"
  - "At least two-thirds of gross income from farming or fishing → IT-2210 Section A and Section D short method, 66 2/3% test; Code F on line 20a"
  - "Uneven income (seasonal, lump sum) → IT-2210A; Code A on line 20a"
  - "Return filed and all tax paid by the early filer date → no 4th installment required"
see_also:
  - tax-computation/tax-computation.md
  - other-taxes/credit-recapture.md
  - tax-computation/state-adjusted-gross-income-tax.md
  - payments/payments.md
---
# Penalty for Underpayment of Estimated Tax (Form IT-40, Lines 20 and 20a; Schedules IT-2210 and IT-2210A)
## Description
Indiana income tax is pay-as-you-go. If withholding and timely estimated payments do not cover enough of the year's state and county tax, a penalty of 10% of the underpayment for each underpaid installment period applies. Generally, if you owe $1,000 or more (2025 amount; confirm against the 2026 form) in state and county tax for the year that is not covered by withholding, you need to make estimated payments. Complete Schedule IT-2210 or IT-2210A to figure the penalty or to show an exception, and enter any penalty on line 20. DOR will also compute and assess the penalty where appropriate.
## Who may owe it
- Total credits, including timely estimated payments, are less than 90% of this year's tax or 100% of last year's tax, or
- You underpaid the minimum amount for one or more installment periods, even if a refund is due.
## 2026 installment due dates (booklet)
April 15, 2026; June 15, 2026; Sept. 15, 2026; Jan. 15, 2027. An overpayment applied on line 19 of the 2025 return counts as paid on the date the 2025 return was filed.
## Schedule IT-2210, Section C: required annual payment
```
1  Current-year tax: IT-40 lines 8 + 9, plus Schedule 4, line 3 recapture
2  Credits other than withholding, PTET and estimated payments (Schedule 5, lines 5-11, and Schedule 6, line 8)
3  Line 1 - line 2
4  Line 3 x 90% (farmers/fishermen x .667)
5  Withholding and PTET credit (Schedule 5, lines 1-3)
6  Line 3 - line 5; if less than $1,000, stop: no penalty
7  Prior year's tax (100%, or 110% if prior-year federal AGI over $150,000, $75,000 MFS)
8  Lesser of line 4 or line 7; if not more than line 5, stop: no penalty
```
If you did not file a prior-year return, the 2025 instructions say to enter "N/A" on line 7 and use line 4. See the 2026 rule below.
## Section D: short method
Usable only if you made no estimated payments, paid four equal amounts on time, or are a farmer or fisherman who paid by the January 15 date. Line 12 = line 8 minus withholding and estimated payments; line 13 = line 12 x 10% → IT-40, line 20. Not usable if any payment was late or payments were unequal.
## Section E: regular method
Each column: required installment (line 8 / 4), withholding (line 5 / 4), estimated payments made by the due date (late payments go in the next column), overpayment carried forward (net of earlier underpayments, never negative), underpayment. Line 21 = total underpayment x 10%.
## Schedule IT-2210A: annualized method
For income received unevenly (fireworks, Christmas sales, a December lump sum) or substantial changes in withholding. Periods 1-1 to 3-31, 5-31, 8-31 and 12-31; annualization factors 4.0, 2.4, 1.5, 1.0; exemptions from IT-40 line 6; state tax at the state rate (the 2025 schedule prints 3%; use 2.95% for 2026) plus county tax; applicable percentages .225, .450, .675, .900; minimum tax 25% of line H per period; penalty line 27 = total underpayment x 10%. Mark "A" on line 20a.
## Farmers and fishermen
If at least two-thirds of gross income for the current or prior year was from farming or fishing (IT-2210 Section A, 66.7% test), there is one payment date. For 2025 the options were: Option 1, pay all estimated tax by Jan. 15, 2026 and file by April 15, 2026; or Option 2, make no estimated payment and file and pay all tax by March 2, 2026. Use Section D and mark "F" on line 20a. For 2026 the equivalent dates are on the 2026 schedule (expected January 15, 2027 for Option 1); confirm against the 2026 form. Booklet example: Henry had two-thirds farm income in 2023 but not in 2024 or 2025; he could use the farmer rules for 2024 but not for 2025.
## Early filers
If you file and pay all tax due by Feb. 2, 2026 (the 2025-year date), you need not make the 4th installment; check the Section B (IT-2210) or Section 1 (IT-2210A) box and include the tax paid with the return (minus household employment tax, use tax, credit recapture and any amount applied to next year) as a 4th-period payment. The 2026-year early filer date will be on the 2026 schedules; confirm against the 2026 form.
## 2026 change: no prior-year liability (SEA 453)
Effective January 1, 2026 (IC 6-3-4-4.1 as amended by SEA 453-2025), if an individual did not file a return for the preceding taxable year and can establish that there was no liability under IC 6-3 and IC 6-3.6 for that year, IRC section 6654 is applied as if the preceding year's tax liability was $0. Under the IRC 6654 rule, a $0 prior-year liability means no estimated tax penalty for 2026. The 2025 schedule's "N/A" instruction for line 7 is replaced by this rule; confirm how the 2026 schedule shows it. SEA 243-2026 also clarifies (effective July 1, 2026) that the individual penalty is computed at the rate in IC 6-8.1-10-2.1(b), not a fixed amount.
## Form discrepancies to note
- IT-2210, line 2 lists credits from Schedule 5, lines 5 through 11; IT-2210A, line B lists Schedule 5, lines 5 through 12.
- IT-2210 line 7 instructions subtract Schedule 5, lines 4 through 11 from prior-year tax, but the worked example uses "Schedule 5, lines 4 through 10"; the IT-2210A example adds "line 14".
- The 110% caution box in IT-2210A says "if your 2025 filing status is married filing separately" while IT-2210 says "2024 filing status".
## Example
Single filer, 2026 IT-40 lines 8 + 9 = $4,800, no other credits, withholding $2,000, no estimated payments. 2025 tax was $4,000 and 2025 federal AGI was $90,000 (2025 amounts; confirm against the 2026 form). Line 3 = $4,800; line 4 = $4,320; line 6 = $2,800 (not under $1,000); line 7 = $4,000; line 8 = $4,000. Short method: line 12 = $4,000 - $2,000 = $2,000; line 13 = $200 → IT-40, line 20.
## Questions
- What was your total Indiana state and county tax for 2025, and your 2025 federal AGI?
- Did you file a 2025 Indiana return? If not, did you have any Indiana liability?
- How much was withheld, and when and how much did you pay in estimates for 2026?
- Was your income received evenly? Is two-thirds of your income from farming or fishing?
- Will you file and pay before the early filer date?
## Common Errors
- Using 100% instead of 110% of prior-year tax when prior-year federal AGI exceeded $150,000
- Using the short method after paying estimates late or in unequal amounts
- Forgetting Code A or Code F on line 20a
- Leaving out Schedule 4 recapture from current-year tax
- Not claiming the 2026 no-prior-year-liability exception
## Prompt
- Will I owe an Indiana underpayment penalty if I didn't make estimated payments?
- I'm a farmer. When do I have to pay Indiana estimated tax?
