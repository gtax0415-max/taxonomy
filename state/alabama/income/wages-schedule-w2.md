---
type: income
category: income
jurisdiction: AL
tax_year: 2026
source_doc: Form W-2 (box 16 Alabama wages, box 17 Alabama withholding, box 12 codes) / Form W-2G and 1099 forms showing Alabama withholding
form: Form 40
line: "5b"
via:
  - Each W-2 → Schedule W-2, lines 1–15 → line 18, columns I + J → Form 40, line 5b
  - Schedule W-2, line 18, column G → Form 40, line 5a → line 22
---
# Wages and Schedule W-2
## Description
Alabama wages are reported from W-2 BOX 16 (state wages), not box 1, and listed on Schedule W-2 with the employer's details and Alabama withholding.

## How Schedule W-2 works
- Columns: A employee SSN; B employer EIN; C statutory employee; D Schedule C filed; E state code; F Alabama employer ID; G Alabama tax withheld; H federal wages (box 1); I Alabama wages (box 16); J additional taxable wages from other states
- Lines 1–15: one row per W-2
- Line 16: total W-2 withholding; line 17: Alabama tax withheld on 1099s and W-2Gs; line 18: grand total
- Line 18, columns I + J → Form 40, line 5b; column G → line 5a

## Alabama wage rules
- 401(k) deferrals are excluded within the federal limit (Code of Alabama §40-18-14(a)(3)(j)); cafeteria plan and dependent care benefits are also excluded
- Contributions to the Retirement Systems of Alabama are NOT excluded for Alabama
- Tips are fully taxable; Alabama does not follow the federal "no tax on tips" deduction
- Overtime is fully included in wages. The 2024–2025 Alabama overtime exclusion ended June 30, 2025. For 2026 there is a separate $1,000 deduction for the overtime premium (see deductions/overtime-deduction.md)

## 2026 changes
- Act 2026-551 (HB 250): employer contributions to a Trump Account and employer payments on an employee's qualified education loan are excluded (see income/exempt/trump-account-and-education-loan.md)

## Notes
- W-2 items not in box 16 (for example, unreported tips on Form 4137, taxable dependent care benefits) go on page 2, Part I, line 7, not line 5b

## Example
Two W-2s with box 16 wages of $95,000 and $100,000: both listed on Schedule W-2; line 5b is $195,000.

## Required Information
- Every W-2 with its box 16 and box 17 amounts
- Employer EIN and Alabama ID

## Questions
- Do you have all your Forms W-2?
- Do box 1 and box 16 differ on any W-2?
- Did you work in another state?

## Common Errors
- Using box 1 federal wages instead of box 16
- Treating tips or overtime as exempt
- Putting box-16-excluded items on line 5b

## Prompt
- Where do wages go on Alabama Form 40?
