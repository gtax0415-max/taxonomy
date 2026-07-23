---
type: income
category: wages
source_doc: Form W-2 Box 1 (compensation element, already included) and Box 12 code V (nonstatutory stock option income) / Form 3921 (ISO exercise) / Form 3922 (ESPP transfer) / Form 1099-B and broker supplemental statements when shares are sold
form: Form 1040
line: "1a, 7"
via:
  - Compensation element → Form W-2 Box 1 → Form 1040, Line 1a
  - Sale of the shares → Form 1099-B → Form 8949 → Schedule D → Form 1040, Line 7
routing:
  - "RSU vesting → value at vest is WAGES in Form W-2 Box 1 → Form 1040, Line 1a"
  - "NQSO exercise → bargain element is WAGES in Form W-2 Box 1, also shown in Box 12 code V → Form 1040, Line 1a"
  - "ISO exercise → NO regular tax, but the bargain element is an AMT preference item → Form 6251"
  - "ESPP qualifying disposition → the discount is ordinary income, the rest is capital gain"
  - "Sale of any of these shares → Form 1099-B → Form 8949 → Schedule D → Form 1040, Line 7"
---
# Stock Compensation — RSUs, Stock Options, and ESPP
## Description
Equity granted by an employer. Stock compensation almost always creates TWO separate tax events: a COMPENSATION event, which is wages, and later a SALE event, which is a capital gain or loss. Confusing the two is the most expensive mistake in this area.
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
- Form 3921 reports the exercise
- QUALIFYING DISPOSITION — sold more than 2 years after grant AND more than 1 year after exercise: the entire gain is long-term capital gain, no wages at all
- DISQUALIFYING DISPOSITION — sold sooner: the bargain element becomes ordinary income, usually added to Form W-2 Box 1
- Exercising ISOs and holding across a year end is the classic AMT trap
## Employee stock purchase plans (ESPP)
- Form 3922 reports the transfer
- Nothing taxable at purchase for a qualified plan
- QUALIFYING DISPOSITION — sold more than 2 years after the grant or offering date AND more than 1 year after purchase: the DISCOUNT is ordinary income, and the remaining gain is long-term capital gain
- DISQUALIFYING DISPOSITION — sold sooner: the full discount measured at purchase is ordinary income, and the rest is capital gain or loss
- The ordinary income portion is often NOT on the Form W-2 for a qualifying disposition, so it must be reported separately
## Related
- The wages side: federal/income/wages/box-1a-w2-wages.md
- The sale side: federal/income/capital-gains/1099-b.md
- Schedule 1 Line 8k exists for stock option income not reported elsewhere
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
- Assuming the flat supplemental withholding rate at vesting covers the actual tax owed
- Miscounting the holding period, which starts at VESTING for RSUs and at EXERCISE for options
- Omitting the ordinary income portion of a qualifying ESPP disposition because it is not on the Form W-2
## Prompt
- My RSUs vested this year.
- I exercised stock options from my company.
- I sold shares I got from work.
- I participate in my employer's stock purchase plan.
