---
type: deduction
category: deductions
jurisdiction: IN
tax_year: 2026
form: Form IT-40
line: "4-7"
---
# Deductions and Exemptions (Form IT-40, Lines 4-7)
## Description
Indiana starts from federal adjusted gross income (Form IT-40, line 1, from federal Form 1040 or 1040-SR, line 11 on the 2025 form). Add-backs from Schedule 1 are added on line 2. Indiana then allows two kinds of reductions:
- Deductions (Schedule 2, lines 1-11, total on line 12 → Form IT-40, line 4): the renter's and homeowner's property tax deductions, state tax refunds, U.S. government interest, Social Security and railroad retirement, active military pay, private school/homeschool, Indiana NOL, nontaxable unemployment, and the coded "other deductions" under line 11 (including the three 2026-only deductions for qualified tips, qualified overtime and qualified passenger vehicle loan interest).
- Exemptions (Schedule 3, lines 1-6, total on line 7 → Form IT-40, line 6): personal, dependent, additional dependent child, age 65 or blind, additional age 65 (income-tested) and adopted child.
Because Indiana starts from federal AGI, federal deductions taken below the AGI line (standard or itemized deductions, QBI, the senior deduction, the non-itemizer charitable deduction) never reach the Indiana return. See federal-items-without-indiana-effect.md.
## How the lines flow
```
Line 1   Federal AGI (Form 1040/1040-SR, line 11)
Line 2   Indiana add-backs (Schedule 1, line 7)
Line 3   Line 1 + line 2
Line 4   Indiana deductions (Schedule 2, line 12)
Line 5   Line 3 - line 4
Line 6   Indiana exemptions (Schedule 3, line 7)
Line 7   Indiana adjusted gross income = line 5 - line 6
         → line 8 state tax (2.95% for 2026) and Schedule CT-40, line 1 county tax
```
## Key rules
- Each deduction is allowed only for an amount included in federal AGI (line 1). Income already excluded federally (for example combat zone pay, or tax-exempt interest) cannot be deducted again.
- No double benefit: amounts already deducted on federal Schedule C, E or F (property tax, long-term care premiums) are not deducted again.
- Line 11 deductions are entered with the deduction name, the three-digit code and the amount. Attach additional sheets for more than three.
- Line 7 (Indiana AGI) is also the starting point for county tax on Schedule CT-40. Spouses in different counties split line 7 between them.
- Scope is the full-year resident Form IT-40. Part-year and nonresident filers use Form IT-40PNR (Schedules C and D), which is out of scope.
## Files in this folder
- deductions.md - this index (Form IT-40, lines 4-7)
- federal-items-without-indiana-effect.md - federal below-the-line deductions that do not reach Indiana
- schedule-2/schedule-2.md - index, Schedule 2 lines 1-12 → Form IT-40, line 4
  - schedule-2/renters-deduction.md - line 1
  - schedule-2/homeowners-residential-property-tax-deduction.md - line 2
  - schedule-2/state-tax-refund.md - line 3
  - schedule-2/interest-on-us-government-obligations.md - line 4
  - schedule-2/taxable-social-security-benefits.md - line 5
  - schedule-2/taxable-railroad-retirement-benefits.md - line 6
  - schedule-2/active-military-service-deduction.md - line 7
  - schedule-2/private-school-homeschool-deduction.md - line 8
  - schedule-2/indiana-net-operating-loss-deduction.md - line 9
  - schedule-2/nontaxable-unemployment-compensation.md - line 10
  - schedule-2/ line 11 code files (24 codes plus three 2026-only deductions) - see schedule-2/schedule-2.md
- exemptions/exemptions.md - index, Schedule 3 lines 1-7 → Form IT-40, line 6
  - exemptions/personal-exemption.md - line 1
  - exemptions/dependent-exemption.md - line 2, Schedule IN-DEP Box 5
  - exemptions/additional-dependent-child-exemption.md - line 3, Schedule IN-DEP Boxes E, F and 6
  - exemptions/age-65-or-blind-exemption.md - line 4
  - exemptions/additional-age-65-exemption.md - line 5
  - exemptions/adopted-child-exemption.md - line 6, Schedule IN-DEP-A
  - exemptions/dependent-qualification-rules.md - who is a dependent (booklet pages 24-28)
## Related
- tax-computation/tax-computation.md - lines 8-11
- tax-computation/county-tax.md - Schedule CT-40, which starts from line 7
## Questions
- What is your federal AGI, and what Schedule 1 add-backs do you have?
- Did you rent, or pay Indiana property tax on, your main home?
- Do you have Social Security, railroad retirement, military pay or military retirement in federal AGI?
- Did you receive tips, overtime or pay interest on a new car loan in 2026, and did you claim the federal Schedule 1-A deductions?
- Who are your dependents, and is anyone 65 or older or blind?
## Prompt
- What deductions does Indiana allow?
- Does Indiana have a standard deduction?
- Can I deduct my rent in Indiana?
