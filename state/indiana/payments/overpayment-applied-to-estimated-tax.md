---
type: payment
category: overpayment-applied
jurisdiction: IN
tax_year: 2026
source_doc: Form ES-40 worksheet for next year (line I installment, line J state portion, line K your county portion, line L spouse's county portion) / county codes
form: Form IT-40
line: "19a, 19b, 19c, 19d"
via:
  - Form IT-40, Line 18 overpayment → Line 19a (your county tax, with county code) + Line 19b (spouse's county tax, with county code) + Line 19c (state adjusted gross income tax) → Line 19d total (not more than line 18) → next year's estimated tax account; remainder → Line 21 refund
routing:
  - "Want some or all of the overpayment credited to next year's estimates → lines 19a-19d"
  - "County portion of the ES-40 installment (worksheet line K) → line 19a with your 2-digit county code"
  - "Spouse lived in a different county on Jan. 1 → spouse's county portion (line L) on line 19b with spouse's county code"
  - "State portion (worksheet line J) → line 19c"
  - "Line 19d plus line 20 more than line 18 → reduce line 19d to line 18 minus line 20"
see_also:
  - payments/payments.md
  - payments/estimated-payments.md
  - payments/refund-and-direct-deposit.md
  - payments/underpayment-penalty.md
  - filing/county-codes.md
  - payments/schedule-in-donate-donations.md
---
# Overpayment Applied to Next Year's Estimated Tax (Form IT-40, Lines 19a-19d)
## Description
If line 18 shows an overpayment, you can apply some or all of it to next year's estimated tax account instead of having it refunded. On the 2025 form the amount is applied to 2026 estimates; on the 2026 return it is applied to 2027 estimates. Indiana splits the amount between county and state tax using the Form ES-40 worksheet:
- Line 19a: amount to offset your estimated county tax (ES-40 worksheet, line K), with your 2-digit county code.
- Line 19b: if your spouse lived in a different county than you on Jan. 1 of the new year, amount to offset your spouse's estimated county tax (worksheet line L), with the spouse's county code.
- Line 19c: amount to offset estimated state tax (worksheet line J).
- Line 19d: total of a + b + c; cannot be more than line 18.
## Limits and ordering
- Line 19d is limited to line 18 minus line 20 (the estimated tax penalty). If line 19d plus line 20 exceeds line 18, adjust.
- Donations come first: if you entered Schedule IN-DONATE donations and an amount to apply, the overpayment goes first to the selected funds, then to the estimated account, and any remainder is refunded.
## Timing
The amount on line 19d is treated as paid on the day the return is filed (postmarked), so it counts toward the installment due on or after that date (for the 2025 return: filed April 15, 2026 → 1st installment; June 3, 2026 → 2nd; July 22, 2026 → 3rd).
## Examples (2025 booklet)
- Mark and Megan have a $420 overpayment and apply $300. ES-40: line I $300, line J $270, line K $30. Line 19a $30 with their county code; line 19c $270; line 19d $300. Refund $120.
- Stu wants $500 per installment and has a $30 overpayment. He enters $30 on line 19c and line 19d, and pays the other $470 through INTIME or with Form ES-40.
## Questions
- Do you want any of your overpayment applied to next year's estimated tax? How much?
- What county did you (and your spouse) live in on Jan. 1 of the new year?
- Is any estimated tax penalty on line 20 reducing the overpayment?
## Common Errors
- Putting the whole amount on line 19c without the county split
- Omitting the county code on line 19a or 19b
- Line 19d larger than line 18 minus line 20
- Expecting the applied amount to count as a 1st-quarter payment when the return is filed late
## Prompt
- Can I apply my Indiana refund to next year's estimated tax?
- What are lines 19a and 19b on the IT-40?
