---
type: income
category: interest
source_doc: Form 1099-INT Box 9
form: Form 1040
line: "2a"
included_in: Form 1099-INT Box 8
routing:
  - "This amount is already part of Box 8, so it is reported on Form 1040, Line 2a as tax-exempt interest (do not add it again)"
  - "For regular tax: not taxed"
  - "For Alternative Minimum Tax (AMT): this interest must be added back on Form 6251, which may increase tax for people subject to AMT"
---
# Form 1099-INT — Box 9: Specified Private Activity Bond Interest
## Description
The portion of your tax-exempt interest (already counted in Box 8) that comes from "private activity bonds." This interest is free from regular federal income tax, but it counts as income when calculating the Alternative Minimum Tax (AMT).
## Notes
- Box 9 is not extra interest — it is a slice of the Box 8 amount, broken out separately
- Because it is inside Box 8, you report it once on Form 1040, Line 2a (through the Box 8 total)
- The reason it is listed separately: people who owe AMT must add this interest back on Form 6251, where it can raise their tax
- If you are not subject to AMT, Box 9 has no effect on what you owe
cd ~/Desktop/taxonomy
git pull
git status
find federal/income/interest -type f
