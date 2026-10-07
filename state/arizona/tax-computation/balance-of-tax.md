---
type: tax-computation
category: balance-of-tax
jurisdiction: AZ
tax_year: 2026
source_doc: Completed Form 140, lines 46 to 51
form: Form 140
line: "48, 52"
via:
  - Line 46 + line 47 → line 48; line 48 - lines 49, 50 and 51 → line 52 (0 if the credits are larger) → lines 60 and 61
routing:
  - "Lines 49 + 50 + 51 greater than line 48 → line 52 = 0; the excess nonrefundable credit is not refunded"
see_also:
  - credits/dependent-tax-credit.md
  - credits/family-income-tax-credit.md
  - credits/nonrefundable-credits-form-301/nonrefundable-credits-form-301.md
  - payments/tax-due-and-overpayment.md
---
# Subtotal and Balance of Tax (Form 140, Lines 48 and 52)
## Description
Line 48 = line 46 + line 47. Line 52 = line 48 - lines 49, 50 and 51; if the sum of lines 49, 50 and 51 is greater than line 48, enter 0. The credits on lines 49 to 51 are nonrefundable; unused amounts may carry forward only where the credit form allows.
## Example
Line 46 $1,445, line 47 $0 → line 48 $1,445. Dependent Tax Credit $250, Form 301 credits $1,009 → line 52 = $1,445 - $250 - $1,009 = $186.
## Notes
- The example's $250 Dependent Tax Credit reflects the 2026 rate of $125 per dependent under 17 (two children)
- Form 140 line and box numbers follow the 2025 Form 140; ADOR had not released the 2026 Form 140 when this was revised, so confirm them against it
## Required Information
- Form 140, lines 46 to 51
## Questions
- Which nonrefundable credits do you claim?
## Common Errors
- Entering a negative balance of tax
## Prompt
- What is the balance of tax on Form 140?
