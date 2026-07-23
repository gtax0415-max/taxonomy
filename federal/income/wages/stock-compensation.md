---
type: income
category: wages
source_doc: Form W-2 Box 1 (compensation element, already included) and Box 12 code V (nonstatutory stock option income) / Form 3921 Box 3 (exercise price per share), Box 4 (fair market value per share at exercise), Box 5 (number of shares) / Form 3922 Box 3 (FMV at grant), Box 4 (FMV at exercise), Box 5 (exercise price paid per share), Box 6 (number of shares), Box 8 (price as if exercised at grant) / Form 1099-B Box 1d (proceeds) and Box 1e (cost basis, often understated) plus the broker's supplemental basis statement
form: Form 1040
line: "1a, 7, 17"
via:
  - Compensation element → Form W-2 Box 1 → Form 1040, Line 1a
  - ISO exercise → Form 6251 → Schedule 2, Line 1 → Form 1040, Line 17
  - Sale of shares → Form 8949 → Schedule D → Form 1040, Line 7
routing:
  - "RSU vesting → fair market value at vest → Form W-2 Box 1 → Form 1040, Line 1a"
  - "NQSO exercise → bargain element → Form W-2 Box 1, also shown in Box 12 code V → Form 1040, Line 1a"
  - "ISO exercise → (Form 3921 Box 4 minus Box 3) times Box 5 → Form 6251 AMT adjustment → Schedule 2, Line 1 → Form 1040, Line 17. NO regular-tax income at exercise"
  - "ISO disqualifying disposition → bargain element becomes ordinary income → Form W-2 Box 1 → Form 1040, Line 1a"
  - "ESPP qualifying disposition, discount portion → ordinary income → Form W-2 Box 1 → Form 1040, Line 1a. If the employer did not include it, Schedule 1, Line 8k → Schedule 1, Line 10 → Form 1040, Line 8"
  - "ESPP disqualifying disposition → full discount measured at purchase → Form W-2 Box 1 → Form 1040, Line 1a"
  - "Sale of shares from any of these → Form 1099-B Box 1d less ADJUSTED basis → Form 8949 → Schedule D → Form 1040, Line 7"
---
# Stock Compensation — RSUs, Stock Options, and ESPP
## Description
Equity granted by an employer. Stock compensation almost always creates TWO separate tax events: a COMPENSATION event, which is wages, and later a SALE event, which is a capital gain or loss. Confusing the two is the most expensive mistake in this area.
## The documents you receive
All three come from a third party, and each carries the numbers the return depends on:
- FORM W-2 — from your employer. Box 1 already includes the compensation element. Box 12 code V separately identifies nonstatutory stock option income
- FORM 3921, "Exercise of an Incentive Stock Option" — from the CORPORATION, due to you by January 31 after an ISO exercise. Box 1 grant date, Box 2 exercise date, Box 3 exercise price per share, Box 4 fair market value per share at exercise, Box 5 number of shares. The AMT adjustment is (Box 4 − Box 3) × Box 5
- FORM 3922, "Transfer of Stock Acquired Through an ESPP" — from the CORPORATION when you first transfer legal title. Box 1 grant or offering date, Box 2 purchase date, Box 3 FMV at grant, Box 4 FMV at purchase, Box 5 price you paid, Box 6 shares, Box 7 date title transferred, Box 8 price as if the option had been exercised on the grant date. Box 3 and Box 8 are what determine the ordinary income on a qualifying disposition
- FORM 1099-B — from the BROKER when you sell. Box 1d proceeds, Box 1e cost basis. Box 1e is the field that causes the double-taxation problem below
## Box-to-line mapping
- Form W-2 Box 1 → Form 1040, Line 1a
- Form W-2 Box 12 code V → informational; the amount is already inside Box 1, do not add it again
- Form 3921 Box 3, Box 4, Box 5 → AMT adjustment on Form 6251 → Schedule 2, Line 1 → Form 1040, Line 17
- Form 3922 Box 3, Box 5, Box 8 → the ordinary income portion at sale → Form W-2 Box 1 if the employer includes it, otherwise Schedule 1, Line 8k
- Form 1099-B Box 1d and Box 1e → Form 8949 → Schedule D → Form 1040, Line 7
## The double-taxation trap — read this first
When you sell shares you received as compensation, the broker's Form 1099-B often reports a COST BASIS that excludes the amount already taxed as wages on your Form W-2. If you enter that basis without adjusting it, you pay tax TWICE on the same money.
- The correct basis is what you paid PLUS the amount already included in Form W-2 Box 1
- For RSUs the basis is the full value at vesting, even though you paid nothing
- Brokers usually provide a SUPPLEMENTAL STATEMENT alongside Form 1099-B showing the adjusted basis. Use it
- The adjustment is made on Form 8949 using code B and an adjustment amount
This single issue accounts for a large share of overpaid tax on equity compensation.
## Restricted stock units (RSUs)
- Nothing happens at grant
- At VESTING, the full fair market value becomes WAGES in Form W-2 Box 1, subject to income tax and FICA
- Employers usually withhold by selling a portion of the shares ("sell to cover") at a flat supplemental rate that is often LOWER than the employee's actual marginal rate, producing an underpayment surprise
- Basis in the remaining shares equals the value at vesting
- Any later change in value is a capital gain or loss, short-term or long-term measured from the VESTING date
## Nonqualified stock options (NQSOs)
- Nothing at grant
- At EXERCISE, the bargain element — market value minus strike price — becomes WAGES in Form W-2 Box 1 and is also reported in Box 12 code V
- Basis equals the strike price PLUS the bargain element
- Holding period starts at exercise
## Incentive stock options (ISOs)
- Nothing at grant or, for regular tax, at exercise
- At EXERCISE the bargain element is an ALTERNATIVE MINIMUM TAX preference item on Form 6251, which can create a large AMT bill in a year with no cash received
- Form 3921 reports the exercise. The AMT adjustment is (Box 4 − Box 3) × Box 5, and it flows to Form 6251, then Schedule 2 Line 1, then Form 1040 Line 17
- QUALIFYING DISPOSITION — sold more than 2 years after grant AND more than 1 year after exercise: the entire gain is long-term capital gain, no wages at all
- DISQUALIFYING DISPOSITION — sold sooner: the bargain element becomes ordinary income, usually added to Form W-2 Box 1
- Exercising ISOs and holding across a year end is the classic AMT trap
## Employee stock purchase plans (ESPP)
- Form 3922 reports the transfer. Box 3 (FMV at grant) and Box 8 (price as if exercised at grant) are what fix the ordinary income on a qualifying disposition
- Nothing taxable at purchase for a qualified plan
- QUALIFYING DISPOSITION — sold more than 2 years after the grant or offering date AND more than 1 year after purchase: the DISCOUNT is ordinary income, and the remaining gain is long-term capital gain
- DISQUALIFYING DISPOSITION — sold sooner: the full discount measured at purchase is ordinary income, and the rest is capital gain or loss
- The ordinary income portion is often NOT on the Form W-2 for a qualifying disposition, so it must be reported separately — Schedule 1 Line 8k exists for stock option income not reported elsewhere
- ESPP ordinary income is NOT subject to Social Security or Medicare tax, unlike RSU and NQSO compensation, and no income tax is withheld at purchase
## How filing status changes the outcome
ALTERNATIVE MINIMUM TAX — the ISO trap. 2026 exemption amounts (Rev. Proc. 2025-32):
| Status | AMT exemption | Phase-out begins |
|---|---|---|
| Single (unmarried, not a surviving spouse) | $90,100 | $500,000 |
| Married filing jointly / QSS | $140,200 | $1,000,000 |
| Married filing separately | $70,100 | $500,000 |
The One Big Beautiful Bill Act made the higher exemptions permanent but RESET the phase-out thresholds to their 2018 levels and ACCELERATED the phase-out rate from 25 cents to 50 cents per dollar of excess. For someone exercising ISOs at higher income, that is a tax increase relative to 2025, when the thresholds were $625,350 single and $1,252,700 joint.
ADDITIONAL MEDICARE TAX of 0.9% on wages, which RSU vesting and NQSO exercises push up:
| Status | Threshold |
|---|---|
| Single / head of household | $200,000 |
| Married filing jointly / QSS | $250,000 |
| Married filing separately | $125,000 |
Not indexed since 2013. An employer withholds this only once YOUR OWN wages pass $200,000, so a two-earner couple can owe it at filing even though neither employer withheld enough.
LONG-TERM CAPITAL GAINS on the eventual sale, 2026 taxable income brackets:
| Status | 0% up to | 15% up to |
|---|---|---|
| Single | $49,450 | $545,500 |
| Married filing separately | $49,450 | $306,850 |
| Head of household | $66,200 | $579,600 |
| Married filing jointly / QSS | $98,900 | $613,700 |
The 3.8% net investment income tax applies above MAGI of $200,000 single, $250,000 joint, $125,000 married filing separately.
## Withholding is usually not enough
- The flat SUPPLEMENTAL WITHHOLDING rate is 22% on the first $1,000,000 of supplemental wages in a year and 37% above that. If your marginal rate is 32% or 35%, a large RSU vest is under-withheld and the shortfall shows up at filing
- Social Security tax stops at the 2026 wage base of $184,500, but Medicare tax has NO cap and the additional 0.9% starts at $200,000
- Consider an estimated payment in the quarter of a large vest or exercise
## Related
- The wages side: federal/income/wages/box-1a-w2-wages.md
- The sale side: federal/income/capital-gains/1099-b.md
## Required Information
- Type of equity: RSU, NQSO, ISO, or ESPP
- Grant date, vesting or exercise date, and sale date
- Strike price or purchase price, and fair market value at the taxable event
- Form W-2 Box 1 and Box 12 code V amounts
- Form 3921 for ISO exercises, Form 3922 for ESPP transfers
- Form 1099-B AND the broker's supplemental basis statement
## Questions
- What type of equity do you have — RSUs, options, or an ESPP?
- Did shares vest, or did you exercise options, during the year?
- Did you sell any shares, and how long did you hold them?
- For ISOs, did you exercise and hold across the year end (an AMT issue)?
- Did your broker provide a supplemental statement with adjusted cost basis?
- Was enough tax withheld at vesting, or should you make an estimated payment?
## Common Errors
- Using the Form 1099-B cost basis without adding the amount already taxed as wages, which taxes the same income twice
- Reporting RSU value as capital gain instead of wages
- Missing the AMT hit from exercising ISOs and holding
- Assuming the flat 22% supplemental withholding rate at vesting covers the actual tax owed when the marginal rate is higher
- Miscounting the holding period, which starts at VESTING for RSUs and at EXERCISE for options
- Omitting the ordinary income portion of a qualifying ESPP disposition because it is not on the Form W-2
## Prompt
- My RSUs vested this year.
- I exercised stock options from my company.
- I sold shares I got from work.
- I participate in my employer's stock purchase plan.
