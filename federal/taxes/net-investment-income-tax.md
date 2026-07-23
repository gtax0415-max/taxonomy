---
type: tax
category: taxes
source_doc: Form 1099-INT Box 1, Form 1099-DIV Box 1a and Box 2a, Form 1099-B (capital gains), Schedule E (passive rental and royalty income), Schedule K-1 passive income
form: Form 1040
line: "23"
via:
  - Form 8960 → Schedule 2, Line 12 → Form 1040, Line 23
---
# Net Investment Income Tax (Form 8960)
## Description
A 3.8% surtax on investment income for higher-income taxpayers, enacted under IRC Section 1411. Filed on about 9.0 million returns (IRS SOI, TY 2022) — the most common additional tax after self-employment tax.
## The threshold — frozen since 2013
| Filing status | MAGI threshold |
|---|---|
| Single / head of household | $200,000 |
| Married filing jointly / QSS | $250,000 |
| Married filing separately | $125,000 |
These amounts are NOT indexed for inflation and have not moved since the tax took effect in 2013. Each year inflation pulls more taxpayers over the line. Note the marriage penalty: two single filers get $400,000 of combined room, a married couple only $250,000.
## How the tax is computed
The 3.8% applies to the LESSER of:
1. Net investment income, or
2. The amount by which MAGI exceeds the threshold
So a taxpayer $10,000 over the threshold with $200,000 of investment income pays 3.8% on $10,000, not on $200,000. Crossing the threshold does not tax all investment income.
## What counts as net investment income
INCLUDED: interest, dividends, capital gains, rental and royalty income, non-qualified annuity income, passive business income, and income from trading in financial instruments.
NOT INCLUDED: wages, self-employment income, Social Security benefits, tax-exempt municipal bond interest, distributions from IRAs and qualified retirement plans, income from a business in which you MATERIALLY PARTICIPATE, and gain excluded under Section 121 on a home sale.
Investment income is reduced by allocable expenses — investment interest, state income tax attributable to that income, and rental expenses.
## The retirement distribution quirk
IRA and 401(k) distributions are NOT net investment income, so they are never taxed at 3.8% directly. But they DO count toward MAGI, so a large distribution can push you over the threshold and expose your other investment income to the tax.
## Real estate professionals
Rental income is presumptively passive and therefore subject to the tax. A qualifying real estate professional who materially participates can treat it as non-passive and exclude it. See federal/income/rental-royalty/passive-activity-limits.md
## Notes
- The 3.8% stacks on top of the capital gains rate, making the top effective rate on long-term gains 23.8%
- Estates and trusts hit the threshold at a very low income level, which is why trust distributions to beneficiaries are often planned around it
- Excluded home sale gain does not count, but the NON-excluded portion does. See federal/income/capital-gains/home-sale.md
## Required Information
- All investment income by type
- MAGI
- Allocable investment expenses and state taxes
- Whether any business or rental income is passive or non-passive
## Questions
- Is your MAGI above $200,000 ($250,000 joint, $125,000 married filing separately)?
- What is your total investment income?
- Do you have rental income, and do you materially participate?
- Did you take a large retirement distribution that raised MAGI?
- Did you sell a home or other appreciated asset this year?
## Common Errors
- Assuming the tax applies to all investment income once the threshold is crossed
- Forgetting that retirement distributions raise MAGI even though they are not investment income
- Treating municipal bond interest as taxable here — it is not
- Missing deductible investment expenses that reduce the base
- Overlooking that a one-time capital gain can trigger it in a single year
## Prompt
- I owe a 3.8% tax on my investment income.
- What is the net investment income tax?
- I sold stock and my income went over $200,000.
