---
type: filing
category: filing
jurisdiction: IA
tax_year: 2026
source_doc: Federal Form 1040 as filed with the "someone can claim you as a dependent" box / Forms W-2 and 1099 for the dependent's income / parent's federal return listing the dependent
form: Form IA 1040
line: "Step 2"
via:
  - Federal Form 1040 dependent checkbox → Form IA 1040, Step 2 Yes/No → filing requirement and exemption test on line 4
routing:
  - "Claimed on another's Iowa return, line 4 under $5,000: no tax due, file only for a refund"
  - "Claimed on another's Iowa return, line 4 $5,000 or more: must file and pay"
---
# Single Filer Claimed as a Dependent on Another Person's Iowa Return
## Description
A single filer must answer YES or NO to whether they were claimed as a dependent on someone else's Iowa return. Dependent filers use a separate, lower test than the general $9,000 threshold.

## Rule for 2026
- A dependent filer must file if Iowa taxable income (IA 1040, line 4) is $5,000 or more
- Under $5,000 of Iowa taxable income: no Iowa tax is due. File only to get withheld Iowa tax refunded
- For this test nothing is added back to line 4 (unlike the general income test, which adds back the federal deduction, QBI, and other items)
- The dependent filer still claims the $40 personal credit on their own return
- The $5,000 figure is statutory and not indexed

## Notes
- If the question is left blank, IDR treats the filer as a dependent
- A student with W-2 wages and Iowa withholding usually files only to claim a refund
- Unchanged for 2026. Step references follow the 2025 IA 1040

## Required Information
- Whether a parent or other person claimed the filer on their 2026 Iowa return
- Dependent's W-2s and 1099s
- Iowa tax withheld

## Questions
- Did your parents or anyone else claim you as a dependent for 2026?
- Did you have Iowa income tax withheld from your pay?

## Common Errors
- Leaving the Yes/No question blank
- Applying the $9,000 single threshold to a dependent
- Dropping the $40 personal credit because someone else claimed the filer
- Adding back the standard deduction for the $5,000 test

## Prompt
- My son earned $4,000 at a summer job and had Iowa tax withheld.
- Do I need to file an Iowa return if my parents claim me?
