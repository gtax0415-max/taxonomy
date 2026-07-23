---
type: tax
category: taxes
source_doc: Form 3921 Box 3, Box 4, Box 5 (ISO exercises) / Form 1099-INT Box 9 (private activity bond interest) / Schedule A (state and local taxes added back) / depreciation schedules
form: Form 1040
line: "17"
via:
  - Form 6251 → Schedule 2, Line 1 → Form 1040, Line 17
---
# Alternative Minimum Tax (Form 6251)
## Description
A parallel tax system. You compute tax two ways — the regular way and the AMT way — and pay the HIGHER of the two. The AMT disallows deductions the regular system permits and adds back certain preference items. Filed on about 5.7 million returns (IRS SOI, TY 2022).
## 2026 amounts (Rev. Proc. 2025-32)
EXEMPTION — the amount of AMTI shielded before AMT applies:
| Filing status | Exemption | Phase-out begins | Fully gone at |
|---|---|---|---|
| Single / head of household | $90,100 | $500,000 | $680,200 |
| Married filing jointly / QSS | $140,200 | $1,000,000 | $1,280,400 |
| Married filing separately | $70,100 | $500,000 | — |
RATES: 26% on the first $244,500 of taxable excess ($122,250 married filing separately), then 28% above that.
## What OBBBA changed for 2026 — a tax increase for some
The One Big Beautiful Bill Act made the higher TCJA exemptions permanent, but it also:
- RESET the phase-out thresholds to 2018 levels. For 2025 they were $626,350 single and $1,252,700 joint; for 2026 they drop to $500,000 and $1,000,000
- DOUBLED the phase-out rate from 25 cents to 50 cents per dollar of excess AMTI
The exemption therefore disappears twice as fast, starting at a lower income. Households between roughly $500,000 and $1.3 million are pulled back into AMT exposure that they had escaped in 2025.
## What triggers it
- INCENTIVE STOCK OPTIONS. The bargain element at exercise is an AMT preference item even though no regular tax applies and no cash was received. This is the classic trigger. See federal/income/wages/stock-compensation.md
- LARGE STATE AND LOCAL TAX deductions, which the AMT adds back entirely
- PRIVATE ACTIVITY BOND interest, tax-exempt for regular tax but not for AMT. See federal/income/interest/tax-exempt/box-9-private-activity-bond.md
- Large capital gains, which raise AMTI and push the exemption into phase-out
- Accelerated depreciation on business property
## The credit for prior-year AMT
AMT paid because of a TIMING item, such as an ISO exercise, generates a minimum tax credit on Form 8801 that can be recovered in later years when regular tax exceeds tentative minimum tax. AMT from permanent items, such as disallowed state taxes, generates no credit.
## Notes
- The standard deduction itself is disallowed in the AMT calculation
- Because the SALT cap already limits state tax deductions for regular tax, fewer filers hit AMT than before 2018 — but the 2026 phase-out reset reverses part of that
- If you exercise ISOs and hold across a year end, model the AMT before December 31. Exercising and selling in the same year avoids the AMT preference entirely
## Required Information
- Form 3921 for each ISO exercise: Box 3 exercise price, Box 4 fair market value at exercise, Box 5 shares
- State and local taxes deducted on Schedule A
- Form 1099-INT Box 9 private activity bond interest
- Depreciation claimed on business property
- Any minimum tax credit carryforward from prior years (Form 8801)
## Questions
- Did you exercise incentive stock options and still hold the shares at year end?
- Is your income between $500,000 and $1.3 million (the new phase-out zone)?
- Do you have large state and local tax deductions?
- Do you hold private activity municipal bonds?
- Do you have an AMT credit carryforward from a prior year?
## Common Errors
- Exercising ISOs late in the year without modeling the AMT
- Assuming the 2025 phase-out thresholds still apply in 2026
- Forgetting to claim the minimum tax credit on Form 8801 in later years
- Overlooking private activity bond interest reported in Form 1099-INT Box 9
## Prompt
- I exercised stock options and now owe alternative minimum tax.
- What is AMT and why do I owe it?
- I have a lot of state tax deductions and high income.
