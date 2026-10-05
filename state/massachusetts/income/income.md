---
type: index
jurisdiction: MA
category: income
form: Massachusetts Form 1
tax_year: 2026
---
# Massachusetts Income (Form 1)
## Description
Root index for income reported on Massachusetts Form 1. Massachusetts does NOT start from federal AGI. It rebuilds income line by line from the federal return and sorts it into CLASSES that are taxed at different rates. Every income file in this folder states its class and rate.
## Line numbers
From the 2025 Form 1 and schedules (revised August 4, 2026). The 2026 forms are not yet released; re-check every `line:` value when they are.
## Income classes and 2026 rates
| Class | What it includes | Rate | Where it lands |
|---|---|---|---|
| Part B / 5.0% income | Wages, pensions, Massachusetts bank interest, business, rental, unemployment, lottery, Schedule X items | 5.0% | Form 1, Lines 3-10 → Line 22 |
| Part A interest and dividends | Interest (other than Massachusetts banks) and dividends | 5.0% | Schedule B → Form 1, Line 20 |
| Part A short-term gains | Short-term capital gains, short-term business property gains | 8.5% | Schedule B → Form 1, Line 23a |
| Part A collectibles | Long-term gains on collectibles and pre-1996 installment sales | 12% | Schedule B → Form 1, Line 23b |
| Part C long-term gains | Long-term capital gains excluding collectibles | 5.0% | Schedule D → Form 1, Line 24 |
| 4% SURTAX | All taxable income above $1,107,750 (2026; 2025: $1,083,150) | +4% | Schedule 4% Surtax → Form 1, Line 28b |
Optional 5.85% election: a taxpayer may voluntarily pay 5.85% instead of 5.0% on 5.0% income and long-term gains (not on 8.5% or 12% income).
## Why classes matter
- DEDUCTIONS (Lines 11-15, Schedule Y) reduce only 5.0% Part B income. The charitable deduction, for example, cannot reduce dividends or capital gains
- Losses cross classes only in narrow ways: up to $2,000 of short-term or long-term capital loss may offset interest and dividends
- EXEMPTIONS apply first to Part B; only EXCESS exemptions spill over to interest, dividends and capital gains (single, head of household and joint filers only)
- No NOL: a business loss cannot be carried forward or back in Massachusetts
## Line map
| Form 1 line | Income | File |
|---|---|---|
| 3 | Wages, salaries, tips | wages/wages.md → wages/wages-salaries-tips.md |
| 4 | Taxable pensions and annuities | retirement/pensions-and-annuities.md |
| 5 | Massachusetts bank interest | interest-dividends/massachusetts-bank-interest.md |
| 6a | Business income (Schedule C) | business/schedule-c-business-income.md |
| 6b | Farm income (U.S. Schedule F) | business/farm-income.md |
| 7 | Rental, royalty, partnership, S corp, trust, REMIC (Schedule E) | supplemental/ |
| 8a | Unemployment compensation | other-income/unemployment-compensation.md |
| 8b | Massachusetts state lottery | other-income/gambling-winnings.md |
| 9 | Other income (Schedule X) | other-income/ and retirement/ira-keogh-roth-distributions.md |
| 20 | Interest and dividends (Schedule B) | interest-dividends/interest-and-dividends.md |
| 23a / 23b | Short-term and collectible gains (Schedule B) | capital-gains/short-term-and-collectible-gains.md |
| 24 | Long-term capital gains (Schedule D) | capital-gains/long-term-capital-gains.md |
| — | Social Security (NOT taxed) | retirement/social-security.md |
## 2026 federal law Massachusetts does NOT follow (TIR 26-4)
Massachusetts determines gross income under the Code as of January 1, 2024, so most of Public Law 119-21 does not flow through for 2026:
- No tax on tips, no tax on overtime, car loan interest deduction, senior deduction — NOT allowed
- Trump accounts — NOT adopted
- Dependent care assistance increase to $7,500 — NOT adopted (Massachusetts exclusion stays $5,000)
- Exclusion for employer student loan payments — NOT adopted
- QBI deduction (Section 199A), SALT cap changes, mortgage interest changes — not relevant / not adopted
- Expanded QSBS exclusion — NOT adopted
- 100% bonus depreciation (Section 168(k)) — NOT adopted
- Section 179 increase, 163(j) change, 168(n) — NOT adopted until 2027
- Section 174A domestic R&E expensing — ADOPTED for 2026 forward (no retroactive or transition relief)
- Business meal exceptions, 529 expanded expenses, ABLE changes, wagering-loss limit — ADOPTED
## Related
- Deductions: massachusetts/deductions/deductions.md
- Credits: massachusetts/credits/credits.md
- Other taxes and penalties: massachusetts/other-taxes/other-taxes.md
