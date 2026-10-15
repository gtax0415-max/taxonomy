---
type: deduction
category: subtractions
jurisdiction: IA
tax_year: 2026
source_doc: Form 1099-R (box 2a taxable amount and box 7 distribution code) / Form RRB-1099-R (Tier 2 and non-equivalent Tier 1 railroad retirement) / Form 5498 or plan statement identifying the plan type / proof of age (date of birth) or disability (SSA award letter) / death certificate and relationship records for a survivor or inherited IRA beneficiary
form: Form IA 1040
line: "3"
via:
  - Form 1099-R box 2a (qualifying plans) → Form 1040 lines 4b and 5b → IA Schedule 1, line 7 column B → line 12 → line 13 → line 21 → Form IA 1040, line 3
routing:
  - "Recipient 55+, disabled, or qualifying survivor: all qualifying retirement income → line 7"
  - "Railroad retirement (RRB-1099-R): line 7 at any age"
  - "Military retired pay: line 4, not line 7"
---
# IRA, Pension, and Railroad Retirement Income Exclusion
## Description
Since 2023 Iowa fully excludes retirement income for eligible recipients. There is no dollar cap.

## Who qualifies
Each recipient is tested separately. The recipient must be:
- 55 or older on December 31, 2026, OR
- Disabled (retired on disability or determined disabled by Social Security or another government agency), OR
- A surviving spouse, or a survivor with an insurable interest, in a person who would have qualified by age or disability. Spouses, parents, and children are deemed to have an insurable interest; others must prove a financial stake in the decedent's life. Being named beneficiary alone is not enough, OR
- A surviving spouse receiving a deceased spouse's protection-occupation, sheriff, deputy, firefighter, or police pension (Iowa Code chapters 97A, 97B.49B, 97B.49C, 410, 411), regardless of the decedent's age

## Qualifying income
- Traditional, Roth, SEP, and SIMPLE IRAs, including Roth conversion income
- 401(k), 403(b), 457(b), Keogh, qualified pensions (including IPERS), ESOP distributions, and annuities under IRC 402(a)
- Railroad retirement on Form RRB-1099-R: excluded at ANY age

## Not qualifying
- Nonqualified deferred compensation plans (IRC 409A)
- Nonqualified annuities (usually Form 1099-R box 7 code D)

## Inherited IRAs
- A beneficiary under 55 qualifies only through the survivor rule: the beneficiary must have an insurable interest (for example a child or spouse) and the decedent must have been 55 or older or disabled. A beneficiary who is 55 or older qualifies on their own age

## Notes
- Military retired pay goes on line 4; Social Security on line 5
- Excluded retirement income is added back for the health insurance deduction income test
- Iowa tax withheld in error on a 1099-R is refunded through the return
- Unchanged for 2026. Line number follows the 2025 Schedule 1

## Required Information
- Each Form 1099-R and RRB-1099-R, with the recipient identified
- Recipient's date of birth or disability documentation
- For survivors: relationship to and age of the decedent

## Questions
- Who received each distribution, and how old were they on December 31, 2026?
- Are you disabled or receiving disability retirement?
- Is any distribution from an inherited IRA or a deceased spouse's pension?
- Is any payment from a nonqualified plan or annuity (code D)?

## Common Errors
- Testing age on the older spouse instead of the actual recipient
- Excluding a code D nonqualified annuity or 409A deferred compensation
- Excluding an inherited IRA for a beneficiary under 55 with no insurable interest
- Putting military retired pay here instead of line 4

## Prompt
- I'm 58 and took money out of my 401(k). Is it taxed in Iowa?
- I inherited an IRA from my father. Can I exclude it?
