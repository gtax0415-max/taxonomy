---
type: refund
category: refund-balance-due
jurisdiction: new-jersey
tax_year: 2026
source_doc: No external source document — computed on the return / bank routing and account numbers (e-check or direct deposit)
form: Form NJ-1040
line: "67, 68, 69, 78, 79, 80"
via:
  - Line 54 > Line 66 → Line 67 amount you owe
  - Line 66 > Line 54 → Line 68 overpayment
  - Lines 69 through 77 → Line 78 total adjustments
routing:
  - "Amount on Line 67 → Line 79 = Line 67 + Line 78"
  - "Amount on Line 68 but less than Line 78 → Line 79 = Line 78 − Line 68"
  - "No amount on 67 or 68 but amount on 78 → Line 79 = Line 78"
  - "Amount on Line 68 → Line 80 refund = Line 68 − Line 78"
---
# Balance Due, Overpayment, and Refund
## Lines
- LINE 67 Amount you owe = Line 54 − Line 66 (when Line 66 is smaller). Over $400 → consider raising withholding (NJ-W4) or estimated payments
- LINE 68 Overpayment = Line 66 − Line 54 (when Line 66 is larger)
- LINE 69 Amount of the overpayment to CREDIT TO 2027 estimated tax (the 2025 form says "credit to your 2026 tax"; for the 2026 return this becomes 2027). Reduces the refund
- LINES 70–77 Charitable fund donations (reduce the refund or increase the balance due)
- LINE 78 Total adjustments = Lines 69 through 77
- LINE 79 BALANCE DUE (fill in the oval if paying by e-check or credit card)
- LINE 80 REFUND = Line 68 − Line 78
## 2026 return deadlines
- File and pay by April 15, 2027
- Payment methods: e-check or credit card (processing fee) online or by phone, or check/money order payable to "State of New Jersey – TGI" with Form NJ-1040-V, SSN on the check
- Balances under $1 need not be paid; refunds of $1 or less require an enclosed statement requesting them
- Pay a 2026 balance and a 2027 estimate as SEPARATE payments
## Penalties and interest
- Late filing: 5% per month or part of a month, up to 25% of the unpaid tax, plus up to $100 per month late
- Late payment: 5% of the balance due
- Interest: prime rate + 3% per year, compounded annually on unpaid tax, penalties, and interest (see TB-21(R))
## Refunds
- Must file to claim a refund; generally three years from the due date (including extensions) to claim it
- Refunds can be offset for debts owed to NJ agencies, the IRS, or other states/cities with set-off agreements
## Mailing addresses (paper)
- Payment enclosed: State of New Jersey, Division of Taxation, Revenue Processing Center – Payments, PO Box 111, Trenton, NJ 08645-0111
- Refund or no tax due: State of New Jersey, Division of Taxation, Revenue Processing Center – Refunds, PO Box 555, Trenton, NJ 08647-0555
## Questions
- Do you want your overpayment refunded or applied to 2027?
- Will you pay electronically or by check?
- Do you want to donate to a New Jersey charitable fund?
## Common Errors
- Reporting a carry-forward on Line 69 larger than the overpayment
- Mailing a payment and a 2027 estimate together as one payment
- Mailing a balance-due return to the refund address
## Prompt
- I owe New Jersey money. How do I pay?
- Can I apply my New Jersey refund to next year?
