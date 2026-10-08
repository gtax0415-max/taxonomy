---
type: deduction
category: net-operating-loss
jurisdiction: IN
tax_year: 2026
source_doc: Federal Form 172 (2024 and later) or Form 1045 (2023 and earlier) / loss-year federal Form 1040 / records of the Indiana NOL used in each intervening year
form: Schedule 2
line: "9"
via:
  - Schedule IT-40NOL Part 1, line 8 (Indiana NOL) → Carryforward Worksheet, line 9 (NOL deduction) → Part 2, Column 5 → Schedule 2, Line 9 → Line 12 → Form IT-40, Line 4
routing:
  - "Loss year after 2011 → carry forward only; no carryback claim may be filed after Dec. 31, 2011"
  - "Federal standard or itemized deductions increased the federal NOL → use a pro forma federal form without them"
  - "More than one loss year → separate Schedule IT-40NOL for each"
see_also:
  - deductions/schedule-2/schedule-2.md
  - deductions/federal-items-without-indiana-effect.md
---
# Indiana Net Operating Loss Deduction (Schedule 2, Line 9)
## Description
You may deduct any allowable Indiana net operating loss carried forward from earlier years to 2026. Complete Schedule IT-40NOL to figure the amount available this year and enter it on line 9 as a positive figure. An Indiana NOL can exist without a federal NOL because Indiana modifications (add-backs and deductions) enter the computation.
## How the NOL is figured (Schedule IT-40NOL)
Part 1, Computation of Indiana NOL (loss year):
```
Line 1  Federal AGI from IT-40, line 1
Line 2  Certain add-backs and deductions: 100-code add-backs (other than Code 155) minus 600-code deductions
Line 3  Modifications for federal NOLs under IRC 172, 512 or other sections (from federal Form 172, Part 1:
        line 9 less itemized or standard deductions in line 6, not below zero; lines 17, 21, 22)
Line 4  Lines 1 + 2 + 3; if greater than zero, enter zero
Line 5  Certain federal NOLs as a negative number (excess business loss from federal Schedule 1, line 8p;
        excess inclusion portion; estate or trust termination losses)
Line 6  Code 151 or Code 153 adjustments
Line 7  Lines 5 + 6; if greater than zero, enter zero
Line 8  Lines 4 + 7 = Indiana NOL available to carry forward
```
Carryforward Worksheet (one column per intervening year): line 5 intervening year Indiana AGI (federal AGI plus add-backs minus the listed 600-code deductions and exemptions, not below zero); line 6 NOL available; line 7 or 8 the excess either way; line 9 the smaller of line 5 or line 6 = the NOL deduction.
## Key rules
- Indiana NOLs may be carried forward up to 20 years after the loss year.
- No carryback claim may be filed after December 31, 2011 (P.L. 172-2011).
- For 2021 and later, itemized deductions are not permitted in figuring an Indiana NOL; a carryforward computed with itemized deductions must be recalculated without them.
- Discharged debt (Title 11 bankruptcy, insolvency, qualified farm indebtedness) reduces NOL carryforwards, first the current-year NOL, then oldest to newest.
- Enclose a Schedule IT-40NOL for every loss year carried forward. Failure to include them results in an initial disallowance. Keep the loss-year federal return.
## Form discrepancy
Schedule 2 has its own line 9 for the Indiana NOL deduction. The IT-40NOL instructions (booklet page 51) still say to enter the deduction "on IT-40 Schedule 1 (Schedule 2 for the 2009 tax year and beyond), under line 11". Use Schedule 2, line 9.
## Example
A 2024 Indiana NOL of $30,000 (2025 amount; confirm against the 2026 form) was partly used in 2025: 2025 intervening-year Indiana AGI was $12,000, so $18,000 remained (worksheet line 8). For 2026, intervening-year Indiana AGI before the NOL is $40,000. Line 9 of the worksheet = smaller of $40,000 or $18,000 = $18,000 → Schedule 2, line 9.
## Questions
- Do you have an Indiana NOL from a prior year, and which loss year(s)?
- Do you have the Schedule IT-40NOL and Carryforward Worksheet from each prior year?
- How much of each loss has already been used?
## Common Errors
- Entering the NOL as a negative number
- Using the federal NOL amount without Indiana modifications
- Including itemized deductions in an Indiana NOL for 2021 and later
- Omitting the Schedule IT-40NOL for each loss year
## Prompt
- I have a business loss carryforward. How do I deduct it on my Indiana return?
