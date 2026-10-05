---
type: credit
category: refundable-credit
jurisdiction: IN
tax_year: 2026
source_doc: Lake County (Indiana) property tax bill or receipts for the principal residence / deed or land contract / IT-40 completed through line 7 / Schedule 2, line 2 homeowner's deduction if one was entered
form: IT-40 Schedule 5
line: "7"
refundable: true
via:
  - IT-40, Line 7 + Schedule 2, Line 2 → Step 2, Line 3 (Modified Indiana AGI) → Worksheet A, B, C or D → Schedule 5, Line 7 → Schedule 5, Line 13 → IT-40, Line 12
  - Final Step → remove the homeowner's residential property tax deduction from Schedule 2, Line 2
routing:
  - "Did not pay Lake County (Indiana) property tax on your residence → no credit"
  - "Single or joint, Modified Indiana AGI under $18,000 → Worksheet A (maximum $300)"
  - "Single or joint, Modified Indiana AGI $18,000 to $18,599 → Worksheet B (phase-out from $18,600)"
  - "Single or joint, Modified Indiana AGI over $18,599 → no credit"
  - "Married filing separately, under $9,000 → Worksheet C (maximum $150)"
  - "Married filing separately, $9,000 to $9,299 → Worksheet D (phase-out from $9,300)"
  - "Married filing separately, over $9,299 → no credit"
  - "Credit claimed → no homeowner's residential property tax deduction (Schedule 2, Line 2)"
see_also:
  - credits/schedule-5/schedule-5.md
  - deductions/deductions.md
---
# Lake County Residential Income Tax Credit (IT-40 Schedule 5, Line 7)
## Description
A refundable credit for low-income homeowners who pay property tax to Lake County (Indiana) on their residence. The credit is the smaller of the property tax paid or $300 ($150 married filing separately) (2025 amounts; confirm against the 2026 form), phased out as Modified Indiana AGI rises from $18,000 to $18,600 ($9,000 to $9,300 married filing separately).
## Requirements (all three)
1. You paid property tax to Lake County (Indiana) on your residence. The residence is your principal dwelling, and you must own it or be buying it under contract.
2. Your Modified Indiana AGI is less than $18,600.
3. You are not claiming the Homeowner's Residential Property Tax Deduction on Schedule 2, line 2.
## Steps
- Step 1: Did you pay property tax to Lake County (Indiana) on your residence during the year? If no, stop.
- Step 2: Prepare IT-40 through line 7.
  1. Enter IT-40, line 7.
  2. Enter any homeowner's residential property tax deduction on Schedule 2, line 2.
  3. Modified Indiana AGI = line 1 + line 2.
- Step 3, single or married filing jointly: over $18,599 stop; under $18,000 Worksheet A; $18,000 to $18,599 Worksheet B.
- Step 3, married filing separately: over $9,299 stop; under $9,000 Worksheet C; $9,000 to $9,299 Worksheet D.
## Worksheets
| Worksheet | Use | Lines |
|---|---|---|
| A | single or joint, Step 2 line 3 under $18,000 | A1 property tax paid on the Lake County residence; A2 maximum credit $300; A3 smaller of A1 or A2 |
| B (phase-out) | single or joint, $18,000 to $18,600 | B1 $18,600; B2 Step 2 line 3; B3 B1 - B2 (zero or negative: stop); B4 B3 x 0.5, rounded; B5 property tax paid; B6 smaller of B4 or B5 |
| C | married filing separately, under $9,000 | C1 property tax paid; C2 maximum credit $150; C3 smaller of C1 or C2 |
| D (phase-out) | married filing separately, $9,000 to $9,300 | D1 $9,300; D2 Step 2 line 3; D3 D1 - D2 (zero or negative: stop); D4 D3 x 0.5, rounded; D5 property tax paid; D6 smaller of D4 or D5 |

The worksheet result (A3, B6, C3 or D6) goes on Schedule 5, line 7.

Booklet wording differs slightly between Step 3 and the worksheet headings: Step 3 sends $18,000 to $18,599 to Worksheet B and stops above $18,599, while Worksheet B's heading says "between $18,000 and $18,600" (and D says $9,000 and $9,300 against Step 3's $9,299). The arithmetic agrees: at $18,600, B3 is zero and the credit is zero.
## Final Step
You cannot claim both the homeowner's property tax deduction and this credit in the same year. If you claim the credit, remove any homeowner's residential property tax deduction from Schedule 2, line 2. This raises IT-40, line 7 to the Step 2, line 3 amount and changes Indiana AGI, the state tax and the county tax.
## Example
Single, Lake County homeowner, IT-40 line 7 $17,400 after a $800 homeowner's deduction on Schedule 2, line 2; property tax paid $800.
- Step 2: $17,400 + $800 = $18,200 → Worksheet B.
- B3 = $18,600 - $18,200 = $400; B4 = $200; B5 = $800; B6 = $200 → Schedule 5, line 7.
- Final Step: remove the $800 from Schedule 2, line 2; IT-40 line 7 becomes $18,200.
## Questions
- Do you own (or buy under contract) your principal residence in Lake County, Indiana?
- How much property tax did you pay to Lake County on it during the year?
- What is your filing status?
- Did you enter a homeowner's residential property tax deduction on Schedule 2, line 2?
## Common Errors
- Keeping the homeowner's property tax deduction on Schedule 2 while taking the credit
- Using IT-40 line 7 without adding back the Schedule 2, line 2 deduction
- Claiming for a rental property, a second home or a home outside Lake County
- Using the $300 maximum on a married filing separately return
- Skipping the 0.5 phase-out factor on Worksheet B or D
## Prompt
- I live in Lake County, Indiana, and my income is low. Is there a property tax credit?
- Should I take the homeowner's deduction or the Lake County credit?
