---
type: tax
category: taxes
source_doc: Form 1099-NEC Box 1 (nonemployee compensation), Form 1099-K Box 1a (platform payments), Form 1099-MISC Box 3 (other income from a business) or Box 6 (medical and health care payments) / Schedule K-1 (Form 1065) Box 14 code A (net earnings from self-employment) / Form W-2 for a minister or church employee with no Social Security or Medicare withheld / business books and records for cash income with no information return
form: Form 1040
line: "23"
via:
  - Business income → Schedule C, Line 31 or Schedule F, Line 34 → Schedule SE → Schedule 2, Line 4 → Form 1040, Line 23
  - Partnership income → Schedule K-1 (Form 1065) Box 14 code A → Schedule SE → Schedule 2, Line 4 → Form 1040, Line 23
  - Half of the tax → Schedule 1, Line 15 → Form 1040, Line 10 (a deduction)
routing:
  - "Form 1099-NEC Box 1, Form 1099-K Box 1a, Form 1099-MISC Box 3 → Schedule C, Line 1 → Schedule C, Line 31 → Schedule SE → Schedule 2, Line 4"
  - "Farm income → Schedule F, Line 34 → Schedule SE → Schedule 2, Line 4"
  - "Schedule K-1 (Form 1065) Box 14 code A → Schedule SE → Schedule 2, Line 4"
  - "Unreported tips → Form 4137 → Schedule 2, Line 5 (NOT Line 4)"
  - "Misclassified employee → Form 8919 → Schedule 2, Line 6 (NOT Line 4)"
---
# Self-Employment Tax (Schedule SE)
## Description
Social Security and Medicare tax on net earnings from self-employment. Filed on about 23.8 million returns (IRS SOI, TY 2022), making it by far the most common additional tax. An employee splits these taxes with an employer; a self-employed person pays BOTH halves.
## The rate
- 15.3% total: 12.4% Social Security plus 2.9% Medicare
- Applied to 92.35% of net earnings, not 100%. The 7.65% reduction approximates the employer-side deduction an employee gets
- The 12.4% Social Security portion stops at the wage base: $184,500 for 2026
- The 2.9% Medicare portion has NO ceiling and applies to every dollar
- Above $200,000 ($250,000 joint, $125,000 married filing separately), an additional 0.9% applies — see additional-medicare-tax.md
## The $400 filing threshold
You must file Schedule SE if net earnings from self-employment are $400 or more. This threshold is statutory and has NOT changed since 1990. It is far below the income tax filing threshold, so many people who owe no income tax still owe self-employment tax.
## Filing status barely matters here — with one exception
The 15.3% rate, the 92.35% factor, and the $400 threshold are identical for every filing status. The one thing that matters is that the Social Security WAGE BASE IS PER PERSON, not per return. On a joint return each spouse gets their own $184,500 for 2026 and each files a SEPARATE Schedule SE. You cannot combine a couple's earnings against one base, and you cannot shift one spouse's earnings to the other.
The additional Medicare tax layered on top DOES vary by filing status — $200,000 single, $250,000 joint, $125,000 married filing separately — and unlike the wage base it applies to the COUPLE'S COMBINED earnings on a joint return. See federal/taxes/additional-medicare-tax.md
## W-2 wages use up the Social Security base first
If you have both a job and a side business, your W-2 Social Security wages count against the $184,500 base FIRST. Only the remaining room is subject to the 12.4% portion. Someone earning $184,500 in wages owes only the 2.9% Medicare portion on their self-employment income. Employers cannot see each other's wages, so this coordination happens on your return.
## The three Schedule K-1s — only ONE generates self-employment tax
This is the single most valuable distinction in this file:
- SCHEDULE K-1 (FORM 1065), partnerships — Box 14 code A reports net earnings from self-employment. A GENERAL partner's distributive share IS subject to the tax. A LIMITED partner's share generally is NOT, though guaranteed payments for services are subject to it either way
- SCHEDULE K-1 (FORM 1120-S), S corporations — has NO self-employment box at all. Shareholder distributions are NEVER subject to self-employment tax. Only the shareholder's W-2 salary carries Social Security and Medicare tax. This is precisely why owners elect S-corporation status, and precisely why the IRS scrutinizes whether the salary is reasonable
- SCHEDULE K-1 (FORM 1041), estates and trusts — a beneficiary's share generally does NOT carry self-employment tax. Box 14 code A on this form is tax-exempt interest, not self-employment earnings. Do not confuse it with the Form 1065 code A
See federal/income/pass-through/schedule-k1.md for the full box layout of all three.
## What is and is not subject to it
SUBJECT: Schedule C net profit, Schedule F net farm profit, general partner distributive share and guaranteed payments for services (Schedule K-1 Form 1065 Box 14 code A), director fees, and ministers' and clergy income.
NOT SUBJECT: S-corporation shareholder distributions (only the W-2 salary is), rental income on Schedule E, farm rental on Form 4835, limited partner distributive share, capital gains, interest and dividends, hobby income, and notary fees.
## Two W-2 situations that look wrong but are correct
- STATUTORY EMPLOYEE — Form W-2 Box 13 has a "statutory employee" checkbox. The income goes on SCHEDULE C so expenses can be deducted, but it is NOT subject to self-employment tax, because Social Security and Medicare were already withheld. Do not carry it to Schedule SE
- MINISTER OR CHURCH EMPLOYEE — receives a Form W-2 with NO Social Security or Medicare withheld. That income IS subject to self-employment tax under special Schedule SE rules, even though it arrives on a W-2
## Related lines that are NOT self-employment tax
Both sit on Schedule 2 near Line 4 and are easy to confuse:
- FORM 4137, Social Security and Medicare tax on unreported tips → Schedule 2, LINE 5. See federal/income/wages/box-1c-unreported-tips.md
- FORM 8919, uncollected Social Security and Medicare tax on wages, used when an employer misclassified you as a contractor → Schedule 2, LINE 6. Filing this instead of Schedule SE means you pay only the EMPLOYEE half
## Half of it is deductible — but only against income tax
One half of the self-employment tax is an above-the-line deduction on Schedule 1 Line 15. It reduces INCOME TAX only. It does NOT reduce the self-employment tax itself. See federal/deductions/adjustments/self-employment-tax-deduction.md
## Notes
- Credits that reduce income tax generally do NOT reduce self-employment tax. A filer with zero income tax can still owe thousands here
- Because nothing is withheld, self-employment tax is the usual reason a first-year freelancer faces an unexpected bill and an underpayment penalty
- The tax is computed BEFORE the QBI deduction and is unaffected by it
## Required Information
- All Forms 1099-NEC, 1099-K, and 1099-MISC received, plus records of income with no information return
- Net profit from each business (Schedule C Line 31, Schedule F Line 34)
- Partnership self-employment earnings (Schedule K-1 Form 1065 Box 14 code A)
- Whether you are a general or limited partner
- Form W-2 with the Box 13 statutory employee box checked, if any
- Total W-2 Social Security wages for the year
- Any church or clergy income subject to special rules
## Questions
- Did you have net earnings from self-employment of $400 or more?
- Do you also have W-2 wages, and how much (this uses up the Social Security base)?
- Are you a general partner or a limited partner?
- Which type of K-1 did you receive — Form 1065, Form 1120-S, or Form 1041?
- Is the Form W-2 Box 13 statutory employee box checked?
- Were you misclassified as a contractor when you were really an employee (Form 8919 instead)?
- If you have an S corporation, is your salary reasonable relative to distributions?
## Common Errors
- Assuming credits or the QBI deduction reduce self-employment tax — they do not
- Forgetting that W-2 wages use up the Social Security base first, and overpaying
- Missing the tax entirely on small side income above $400
- Applying the rate to 100% of net earnings instead of 92.35%
- Treating limited partner or S-corporation distributions as subject to it
- Confusing Form 1041 K-1 Box 14 code A (tax-exempt interest) with Form 1065 K-1 Box 14 code A (self-employment earnings)
- Carrying statutory employee income from Schedule C to Schedule SE
- Filing Schedule SE and paying both halves when the employer misclassified you and Form 8919 would charge only the employee half
## Prompt
- I am self-employed and owe self-employment tax.
- I have a side business and a regular job.
- Why do I owe so much when my business barely made a profit?
