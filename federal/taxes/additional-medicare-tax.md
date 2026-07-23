---
type: tax
category: taxes
source_doc: Form W-2 Box 5 (Medicare wages and tips) and Box 6 (Medicare tax withheld) / Schedule SE (self-employment earnings) / Form 1099-MISC or partnership records for railroad retirement compensation
form: Form 1040
line: "23"
via:
  - Form 8959 → Schedule 2, Line 11 → Form 1040, Line 23
routing:
  - "Medicare wages above the threshold → Form 8959 → Schedule 2, Line 11 → Form 1040, Line 23"
  - "Excess Medicare tax the employer already withheld → Form 8959 → credited in the payments section of Form 1040"
---
# Additional Medicare Tax (Form 8959)
## Description
A 0.9% surtax on wages and self-employment income above a threshold, enacted under IRC Section 3101(b)(2). Filed on about 7.9 million returns (IRS SOI, TY 2022). Unlike regular Medicare tax, the employer pays no matching share.
## The threshold — frozen since 2013
| Filing status | Threshold |
|---|---|
| Single / head of household | $200,000 |
| Married filing jointly / QSS | $250,000 |
| Married filing separately | $125,000 |
Same amounts as the net investment income tax, and also NOT indexed. The two taxes are cousins: one hits earned income, the other investment income.
## The withholding mismatch — the most common surprise
An employer must begin withholding the 0.9% once YOUR wages from THAT employer exceed $200,000, regardless of your filing status or your spouse's income. That creates two errors in opposite directions:
- A MARRIED COUPLE each earning $150,000 owes the tax on $50,000 of combined wages, but NEITHER employer withheld anything. The balance is due at filing
- A SINGLE filer earning $210,000 at one job had withholding start at $200,000, which is correct
- A person with TWO JOBS each paying $150,000 has $300,000 of wages, owes tax on $100,000, and had nothing withheld
Any over-withholding is credited back on the return through Form 8959.
## What it applies to
- Medicare wages, from Form W-2 Box 5
- Self-employment income, from Schedule SE
- Railroad Retirement Tax Act compensation
Wages and self-employment income are combined against a single threshold, but wages are counted FIRST.
## What it does not apply to
Investment income of any kind. That is the net investment income tax instead — see net-investment-income-tax.md
## Notes
- There is no employer match, and no cap. The 0.9% applies to every dollar above the threshold
- For a self-employed person the total Medicare rate above the threshold becomes 3.8% (2.9% plus 0.9%)
- The 0.9% is NOT deductible as part of the self-employment tax deduction, which covers only half of the 15.3%
## Required Information
- Form W-2 Box 5 Medicare wages from every employer
- Form W-2 Box 6 Medicare tax withheld
- Self-employment earnings from Schedule SE
- Filing status and spouse's wages if filing jointly
## Questions
- What are your combined Medicare wages and self-employment earnings?
- If married filing jointly, what is the couple's combined total?
- Did you have more than one employer, or both wages and self-employment income?
- Was any additional Medicare tax already withheld (Form W-2 Box 6)?
## Common Errors
- A two-earner couple assuming their employers withheld enough
- Someone with multiple jobs assuming the same
- Confusing this with the net investment income tax, which uses the same thresholds but a different base
- Expecting the employer to match it — there is no employer share
## Prompt
- I owe additional Medicare tax.
- My spouse and I both earn six figures and we owe extra at filing.
- Why is there an extra 0.9% on my wages?
