---
type: income
category: earned
jurisdiction: CA
tax_year: 2026
source_doc: Form W-2 from each employer (box 1 federal wages, box 16 state wages, box 17 state tax withheld) / corrected Form W-2c, if issued
form: Form 540
line: "13"
via:
  - Form W-2, box 1 → federal Form 1040, Line 1a → federal AGI → Form 540, Line 13
  - "Differences only: Schedule CA (540), Part I, Section A, Line 1 → column B (Line 14) or column C (Line 16)"
---
# Wages (W-2)
## Description
Compensation from an employer, reported on Form W-2. California starts from federal AGI, so wages normally flow to the California return with no separate entry. Schedule CA is needed only when California treats some part of the pay differently from federal law.

## What counts as wages
- Earnings, salaries and hourly pay
- Bonuses and commissions
- Severance pay
- Tips

## Notes
- Line numbers follow the 2025 Form 540 and schedules; confirm them on the 2026 forms (expected December 2026)
- Wage-line differences (sick pay, treaty wages, employer HSA contributions, moving reimbursements): income/earned/wage-adjustments.md
- Military pay and combat pay: income/earned/military-pay.md
- No adjustment is needed when box 1 (federal) and box 16 (California) wages agree and no California difference applies
- Wages can be excluded or adjusted on Schedule CA, Part I, Section A, line 1 (for example, In-Home Supportive Services pay or certain fringe benefits treated differently by California)
- Box 17 California withholding is claimed as a payment on Form 540, line 71
- Missing W-2: ask the employer first. If no copy can be obtained, California has a substitute W-2 (FTB 3525)
- Lost W-2: request a copy from the employer. Wrong W-2: request a corrected W-2c

## Required Information
- Every W-2 for the filer and spouse
- Box 1, box 16 and box 17 amounts
- Any wage item California treats differently from federal law

## Questions
- How many employers did you have in 2026?
- Do box 1 and box 16 match on each W-2?
- Did you work outside California for part of the year?
- Did you receive a W-2 for In-Home Supportive Services work?

## Common Errors
- Entering wages on Schedule CA when no California difference exists
- Not reconciling box 1 and box 16 differences
- Missing California tax withheld (box 17) as a payment
- Filing without a W-2 instead of using the substitute form

## Prompt
- I have a W-2 from my job in California.
- My employer never sent me a W-2.
