---
type: income
category: income
jurisdiction: IN
tax_year: 2026
form: Form IT-40
line: "1-3"
---
# Income (Form IT-40, Lines 1-3)
## Description
Indiana does not list wages, interest, pensions or business income line by line. It starts from federal adjusted gross income (Form IT-40, line 1, from federal Form 1040 or 1040-SR, line 11) and modifies it:
- Add-backs (Schedule 1, total on line 7 → Form IT-40, line 2): items deducted or excluded federally that Indiana taxes, such as state income taxes deducted on federal Schedules C, E or F, the federal NOL deduction, out-of-state municipal bond interest, bonus depreciation and Section 179 expense over the Indiana ceiling, plus coded "other" add-backs on line 6.
- Deductions (Schedule 2 → Form IT-40, line 4) and exemptions (Schedule 3 → line 6) then reduce the result to Indiana adjusted gross income (line 7).
Every item of federal gross income therefore reaches Indiana through line 1 unless a Schedule 2 deduction removes it.
## How the lines flow
```
Line 1   Federal adjusted gross income (Form 1040/1040-SR, line 11)
Line 2   Indiana add-backs (Schedule 1, line 7)
Line 3   Line 1 + line 2
Line 4   Indiana deductions (Schedule 2, line 12)
Line 5   Line 3 - line 4
Line 6   Indiana exemptions (Schedule 3, line 7)
Line 7   Indiana adjusted gross income = line 5 - line 6
Line 8   State adjusted gross income tax = line 7 x 2.95% for 2026 (the 2025 form prints 3%)
Line 9   County tax (Schedule CT-40)
```
## 2026 conformity
For 2026 Indiana follows the Internal Revenue Code as amended and in effect on January 1, 2026 (SEA 243), so most P.L. 119-21 changes that flow through federal AGI also flow into line 1. Indiana keeps its own add-backs where it has decoupled (bonus depreciation, Section 179 over $25,000 (2025 amount; confirm against the 2026 form), business interest under IRC 163(j), and the new qualified production property modification under IC 6-3-2-30). The 2026-only Indiana deductions for qualified tips, qualified overtime and qualified passenger vehicle loan interest are Schedule 2 deductions (code to be assigned on the 2026 form), not part of this folder.
## Files in this folder
- income.md - this index (Form IT-40, lines 1-3)
- add-backs/add-backs.md - index, Schedule 1 lines 1-7 → Form IT-40, line 2
  - add-backs/tax-add-back.md - line 1 (state income taxes, PTET, wagering tax phase-out)
  - add-backs/net-operating-loss-add-back.md - line 2
  - add-backs/out-of-state-municipal-interest-add-back.md - line 3
  - add-backs/bonus-depreciation-add-back.md - line 4
  - add-backs/qualified-production-property-add-back.md - new 2026 modification (IC 6-3-2-30); line or code to be assigned on the 2026 form
  - add-backs/section-179-add-back.md - line 5
  - add-backs/conformity-add-back-120.md - line 6, code 120
  - add-backs/conformity-add-back-negative-147.md - line 6, code 147
  - add-backs/debt-discharge-nol-reduction-155.md - line 6, code 155
  - add-backs/employer-student-loan-payment-148.md - line 6, code 148
  - add-backs/excess-business-interest-142.md - line 6, code 142
  - add-backs/repatriated-dividend-deduction-139.md - line 6, code 139
  - add-backs/excess-business-loss-modification-151.md - line 6, code 151
  - add-backs/excess-inclusion-income-153.md - line 6, code 153
  - add-backs/qualified-preferred-stock-113.md - line 6, code 113
  - add-backs/research-experimental-expenditures-154.md - line 6, code 154
  - add-backs/student-loan-discharge-150.md - line 6, code 150
  - add-backs/discontinued-catch-up-add-backs.md - line 6, codes 108, 109, 110, 111, 112, 121, 126, 129, 130, 131, 135
## Related
- filing/federal-adjusted-gross-income.md - Form IT-40, line 1
## Questions
- What is your federal adjusted gross income?
- Do you have a business, farm, rental, partnership, S corporation or trust (federal Schedules C, E or F)?
- Did you deduct state income taxes, an NOL, bonus depreciation or Section 179 expense federally?
- Did you have out-of-state municipal bond interest?
## Prompt
- How does Indiana tax my income?
- Does Indiana start from federal AGI?
