---
type: payment
category: payments
source_doc: Your own records of payments made (IRS Direct Pay confirmations, EFTPS records, cancelled checks, Form 1040-ES vouchers) / the prior-year Form 1040 Line 24 total tax and Line 11 AGI, which set the safe harbor / the prior-year Form 1040 Line 36 amount applied forward
form: Form 1040
line: "26"
via:
  - Estimated payments and prior-year overpayment applied → Form 1040, Line 26
  - Underpayment penalty → Form 2210 → Form 1040, Line 38
---
# Estimated Tax Payments (Form 1040-ES)
## Description
Quarterly payments made directly to the IRS by people whose income is not subject to withholding — the self-employed, investors, retirees, landlords, and anyone with large non-wage income. The U.S. system is pay-as-you-earn, so waiting until April is itself a penalty event.
## 2026 due dates
| Installment | Period covered | Due |
|---|---|---|
| 1st | January 1 – March 31 | April 15, 2026 |
| 2nd | April 1 – May 31 | June 15, 2026 |
| 3rd | June 1 – August 31 | September 15, 2026 |
| 4th | September 1 – December 31 | January 15, 2027 |
The periods are NOT equal quarters. The 2nd installment covers only two months and the 3rd covers three. If a due date falls on a weekend or holiday it moves to the next business day. Filing the return and paying in full by February 1, 2027 lets you skip the 4th installment.
## The safe harbors — meeting ANY one avoids the penalty
1. 90% of the CURRENT year's total tax, or
2. 100% of the PRIOR year's total tax, or
3. 110% of the PRIOR year's total tax if prior-year AGI exceeded $150,000 — or $75,000 if MARRIED FILING SEPARATELY. This is the only filing status difference in the estimated tax rules, and it is easy to miss: an MFS filer hits the 110% requirement at half the income everyone else does
The prior-year safe harbor is the practical choice: take last year's Form 1040 Line 24, multiply by 100% or 110%, divide by four, and pay that. It works no matter how much your income rises, which makes it valuable in a year with a big one-time gain.
DE MINIMIS: no penalty at all if the balance owed after withholding and credits is under $1,000.
## Each quarter stands alone
Paying a large amount in the fourth quarter does NOT cure a first-quarter shortfall. The penalty accrues from each missed due date until the underpayment is made up or the return is filed. This surprises people who assume "I paid it all by April so I am fine."
## Withholding is the escape hatch
Withholding is treated as paid EVENLY across the four due dates regardless of when it happened. An estimated payment counts only on its actual date. So a shortfall discovered in December can be fixed with heavy year-end withholding — from a bonus, a final paycheck, or a retirement distribution with a large withholding election — but NOT with a December estimated payment. See withholding.md
## The annualized income method
If your income was genuinely uneven — a business with a seasonal peak, a single large capital gain in December — Form 2210 Schedule AI lets you compute installments based on income actually earned in each period. It is more work but can eliminate a penalty that the flat method would impose.
## The penalty (Form 2210)
- Charged as interest, at the federal short-term rate plus 3 percentage points, set quarterly
- For 2026 the rate was 7% for the first quarter and 6% for the second (Rev. Rul. 2025-22 and later rulings). Confirm the current quarter's rate
- Computed per installment, compounding daily on the underpaid balance
- NOT deductible
- A waiver may be available for casualty, disaster, retirement after age 62, or disability
## Who typically needs to pay
- Self-employed filers — the 15.3% self-employment tax has nothing withheld against it. See federal/taxes/self-employment-tax.md
- Retirees taking IRA distributions without a withholding election
- Investors with large capital gains, dividends, or interest
- Landlords with rental income
- Anyone with significant income from a Schedule K-1
- Employees whose withholding does not cover the additional Medicare tax or net investment income tax
## Applying a prior-year overpayment
Form 1040 Line 36 lets you apply this year's overpayment to next year's estimated tax instead of taking a refund. The applied amount shows up on next year's Line 26 and counts as paid on the FIRST installment due date, which is often the cleanest way to cover the first quarter.
## Required Information
- Prior-year Form 1040 Line 24 total tax, and Line 11 AGI to test the $150,000 threshold
- Payments made this year, with dates
- Any prior-year overpayment applied forward
- Total withholding from all sources
## Questions
- Do you have income with no withholding — self-employment, investments, rentals, or retirement distributions?
- What was your total tax last year, and was your AGI above $150,000?
- What did you pay each quarter and on what dates?
- Was your income uneven across the year (the annualized method may help)?
- Could you fix a shortfall through year-end withholding instead?
## Common Errors
- Assuming a refund at filing proves there was no underpayment problem
- Paying everything in the fourth quarter and expecting that to cure earlier quarters
- Using 100% of prior-year tax when AGI over $150,000 requires 110%
- Forgetting the self-employment tax when estimating, and underpaying by 15.3% of net profit
- Missing the January 15 fourth installment because it falls in the next calendar year
- Overlooking the annualized income method after a single large year-end gain
## Prompt
- Do I need to make quarterly estimated tax payments?
- I am self-employed and do not know how much to pay.
- I owe an underpayment penalty.
- I had a big capital gain this year.
