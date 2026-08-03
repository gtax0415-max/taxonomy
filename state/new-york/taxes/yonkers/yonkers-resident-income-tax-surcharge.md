---
type: tax
category: yonkers
jurisdiction: Yonkers
source_doc: NO EXTERNAL SOURCE DOCUMENT — the surcharge is computed from the return's own figures. Inputs are Form IT-201 line 46 (total New York State taxes) and the refundable credit amounts already computed on Forms IT-213, IT-214, IT-216, IT-215, IT-209, IT-272, IT-201-ATT, and IT-119. Records establishing Yonkers residency dates support Item D2
form: Form IT-201
line: "55"
refundable: no
via:
  - Yonkers worksheet in the Form IT-201 instructions → Form IT-201, Line 55
---
# Yonkers Resident Income Tax Surcharge
## Description
A surcharge of 16.75% imposed on a Yonkers resident's NET NEW YORK STATE TAX. It is not a tax on income. If your state tax is zero, your Yonkers surcharge is zero, no matter how much you earned.
## Rate
16.75% (0.1675). Applied to net state tax after the worksheet subtractions below.
## The threshold question
Did you enter an amount MORE THAN ZERO on Form IT-201 line 46, total New York State taxes?
- If NO: nothing on line 55. Skip to line 56
- If YES: complete the Yonkers worksheet
## The worksheet
```
a  Amount from Form IT-201, line 46
b  Form IT-213, line 9      (Empire State child credit)
c  Form IT-214, line 20     (real property tax credit)
d  Form IT-216, line 14     (child and dependent care credit)
e  Form IT-215, line 16     (earned income credit; status 5 uses line 17)
f  Form IT-209, line 32     (noncustodial parent EIC; or the larger of line 32 or 42)
g  Form IT-272, line 5 or 7 (college tuition credit, if the credit was elected)
h  Total from Form IT-201 lines 69 and 69a (NYC school tax credits)
i  Form IT-201-ATT, line 13 (other refundable credits)
j  Add lines b through i
k  Form IT-119, line 3      (STAR reconciliation amount)
l  Line j minus line k
m  Line a minus line l      ← net state tax
n  0.1675
o  Line m times line n      → Form IT-201, Line 55
```
## What the worksheet is really doing
It reduces state tax by the REFUNDABLE credits before applying the surcharge. A Yonkers resident whose refundable credits wipe out their state tax owes no surcharge. Credits therefore work twice: once against state tax, once again by shrinking the Yonkers base.
Note that NONREFUNDABLE credits are already reflected in line 46, so they are not listed separately. The worksheet only backs out the refundable ones.
## Married couples with split Yonkers residency
If you file jointly and only ONE spouse was a full-year Yonkers resident while the other was a full-year Yonkers NONRESIDENT:
1. Enter special condition code Y1 at Item G on Form IT-201
2. On a SEPARATE SHEET, compute the surcharge on the state tax of the Yonkers resident ONLY, as if you had filed separate federal returns
3. Enter that amount on line 55
4. Write the Yonkers resident's name, Social Security number, and "Yonkers resident income tax surcharge" on the sheet
5. Submit the sheet with the return
Skipping the Y1 code is a common omission and it causes the return to be questioned even when the arithmetic is right.
## Part-year Yonkers residents
Do NOT use line 55. Complete Form IT-360.1, Change of City Resident Status, and enter the result at LINE 57 instead. Submit Form IT-360.1 with the return.
The same special accrual rules described for part-year New York City residents apply here.
## Estimated tax
Yonkers has its own column on the Form IT-2105 estimated tax worksheet. The estimate is computed as 16.75% of the New York State column amount at line 21. The $300 threshold for making estimated payments is tested separately for Yonkers.
## Required Information
- Form IT-201 line 46
- Each refundable credit amount feeding the worksheet
- Form IT-119 STAR reconciliation amount, if any
- Months of Yonkers residence
- Each spouse's Yonkers residency status
## Questions
- Were you a Yonkers resident for the full year?
- Is your Form IT-201 line 46 amount greater than zero?
- Which refundable credits are you claiming?
- Was your spouse also a Yonkers resident?
- Did you move into or out of Yonkers during the year?
## Common Errors
- Applying 16.75% to income rather than to state tax
- Applying it to line 46 without backing out the refundable credits
- Omitting special condition code Y1 when only one spouse is a Yonkers resident
- Using line 55 for a part-year resident instead of line 57
- Forgetting the Form IT-119 STAR reconciliation subtraction
- Overlooking the surcharge in estimated tax planning
## Prompt
- How much is the Yonkers surcharge?
- I live in Yonkers and my spouse lives elsewhere.
- I moved to Yonkers in March.
