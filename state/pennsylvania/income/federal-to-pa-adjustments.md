---
type: income
category: federal-reconciliation
jurisdiction: PA
source_doc: FEDERAL FORM 1040 LINE 2b (taxable interest) and LINE 2a (tax-exempt interest) / FEDERAL FORM 1040 LINE 3b (ordinary dividends) / federal Schedule 1 for HSA and MSA distributions reported as Other income / federal Schedules K-1 / Form 1099-DIV box 2a / IRC Section 965 Transition Tax Statement / 1099-Q for 529 distributions
form: PA-40
line: "2, 3"
refundable: no
via:
  - Federal Form 1040, Line 2b → PA Schedule A, Line 1 → adjustments → PA-40, Line 2
  - Federal Form 1040, Line 3b → PA Schedule B, Line 1 → adjustments → PA-40, Line 3
---
# Federal-to-PA Adjustments (Schedules A and B)
## Description
PA does NOT start from federal AGI. But for TWO classes — INTEREST and DIVIDENDS — it DOES start from a specific federal figure and reconcile. PA SCHEDULES A AND B ARE RECONCILIATION SCHEDULES — the only place on the PA return where a federal figure is the starting point.
Both schedules carry the same caution on their face: FEDERAL AND PA RULES FOR THIS INCOME ARE DIFFERENT.
## The other six classes do NOT reconcile
| Class | Starts from federal? |
|---|---|
| Compensation, lines 1a-1c | NO. W-2 Box 16 is computed under PA rules by the employer |
| INTEREST, line 2 | YES. Schedule A line 1 is the federal figure |
| DIVIDENDS, line 3 | YES. Schedule B line 1 is federal Form 1040 line 3b |
| Business, line 4 | NO. PA Schedule C or F from SEPARATE PA books and records |
| Sale of property, line 5 | NO. AMOUNTS FROM FEDERAL SCHEDULE D MAY NOT BE CORRECT FOR PA |
| Rents and royalties, line 6 | NO. PA Schedule E |
| Estate or trust, line 7 | NO. PA-41 RK-1 or NRK-1 |
| Gambling, line 8 | NO. PA Schedule T from W-2G and own records |
So the reconciliation concept applies to exactly two classes. Everywhere else PA computes independently and a federal figure is a starting guess at best.
## PA SCHEDULE A — interest reconciliation
```
Line 1   Interest income reported on your FEDERAL return
ADDITIONS
Line 2   TAX-EXEMPT INTEREST from federal Form 1040 line 2a
Line 3   Other addition adjustments, with description
Line 4   Subtotal
REDUCTIONS
Line 5   Interest from federal Schedule K-1s
Line 6   Interest from DIRECT OBLIGATIONS OF PENNSYLVANIA and its municipalities
Line 7   Interest from DIRECT OBLIGATIONS OF THE U.S. GOVERNMENT
Line 8   Other reduction adjustments, with description
Line 9   Subtotal
Line 10  Line 4 less Line 9
PA-SPECIFIC INCLUSIONS
Line 11  Distributions from LIFE INSURANCE, ANNUITY, or ENDOWMENT contracts in federal taxable income
Line 12  Distributions from CHARITABLE GIFT ANNUITIES in federal taxable income
Line 13  Distributions from IRC 529 QUALIFIED TUITION PROGRAMS FOR NON-EDUCATIONAL PURPOSES
Line 14  Distributions from HEALTH AND MEDICAL SAVINGS ACCOUNTS in federal taxable income
Line 15  Interest from PA S CORPORATIONS AND PARTNERSHIPS, per RK-1 or federal K-1
Line 16  Total → PA-40, Line 2
```
### The exemption pattern reverses the federal one
PA EXEMPTS ITS OWN obligations AND U.S. GOVERNMENT direct obligations, and TAXES tax-exempt interest from everywhere else by adding it back at line 2.
FEDERALLY, municipal bond interest is exempt no matter which state issued it, and U.S. TREASURY interest is TAXABLE.
PENNSYLVANIA DOES THE OPPOSITE ON BOTH. It exempts only its OWN obligations and those of the U.S. GOVERNMENT, and adds back every other state's municipal interest at Schedule A line 2.
| Holding | Federal | Pennsylvania |
|---|---|---|
| PA municipal bond | Exempt | EXEMPT |
| Other state's municipal bond | Exempt | TAXABLE |
| U.S. Treasury obligation | TAXABLE | EXEMPT |
### Line 3 additions named in the instructions
Taxable distributions from PA ABLE SAVINGS PROGRAM FUND accounts; SELF-CHARGED INTEREST; AMORTIZATION OF BOND PREMIUM; NOMINEE INTEREST; and related expenses. The list is explicitly NOT exhaustive.
### Line 13, the 529 clawback
A 529 distribution for NON-EDUCATIONAL PURPOSES is PA-TAXABLE INTEREST. Contributions made in TAX YEARS 2005 AND EARLIER have their own treatment; THE TOTAL AMOUNT OF DISTRIBUTIONS CLAIMED AS DEDUCTIONS FOR TAX YEARS 2006 AND LATER IS TAXABLE.
This pairs with the Schedule O deduction: money deducted going in is taxed coming out if not used for education. See deductions/other-deductions/qualified-tuition-program-529.md.
### Line 16 cannot be negative
THE RESULT CANNOT BE A NEGATIVE NUMBER. If it is, an amount has been left off an addition line or excess adjustments were recorded. Interest is a class that cannot show a loss.
## PA SCHEDULE B — dividend reconciliation
```
Line 1   Dividend income from LINE 3b OF YOUR FEDERAL RETURN
REDUCTIONS
Line 2   Dividends from federal Schedule K-1s
Line 3   PENNSYLVANIA EXEMPT-INTEREST DIVIDEND income
Line 4   Other reduction adjustments, with description
Line 5   Subtotal
Line 6   Line 1 less Line 5
ADDITIONS
Line 7   TOTAL EXEMPT-INTEREST DIVIDENDS
Line 8   Other addition adjustments, with description
Line 9   REPATRIATION OF FOREIGN INCOME, IRC SECTION 965
   9a    Total earnings and profits on line 1 of the IRC 965 Transition Tax Statement
   9b    Payments of those earnings received in PRIOR years
   9c    Payments received in the CURRENT year
Line 10  CAPITAL GAINS DISTRIBUTIONS
Line 11  Dividends from PA S CORPORATIONS AND PARTNERSHIPS
Line 12  Total → PA-40, Line 3
```
### IRC Section 965 repatriation
PA taxes SECTION 965 REPATRIATED FOREIGN EARNINGS AS DIVIDEND INCOME, and it does so ON A CASH RECEIPT BASIS — line 9c captures payments received IN THE CURRENT YEAR, with prior-year receipts backed out at 9b.
The federal regime taxed the deemed inclusion up front with an eight-year instalment election. PA instead taxes what is ACTUALLY PAID OUT, year by year. The two timelines do not align, and a taxpayer who finished paying the federal transition tax may still have PA income arriving.
### Capital gains distributions
Line 10 is where Box 2a mutual fund capital gain distributions enter the DIVIDEND class. See dividends.md.
## When you must SUBMIT the schedule
A rule with no federal analogue:
IF PA-TAXABLE INTEREST OR DIVIDEND INCOME EQUALS THE FEDERAL AMOUNT AND THERE ARE NO ADJUSTMENT AMOUNTS, report on the PA-40 line but DO NOT SUBMIT the schedule.
IF THERE IS ANY AMOUNT ON AN ADJUSTMENT LINE — Schedule A lines 2 through 15, or Schedule B lines 2 through 11, excluding the subtotal lines — YOU MUST COMPLETE AND SUBMIT the schedule.
So the schedule's presence is itself a signal that federal and PA diverge.
NONRESIDENTS ARE NOT REQUIRED TO COMPLETE PA SCHEDULE A.
## Separate schedules for taxpayer and spouse
A TAXPAYER AND SPOUSE MUST COMPLETE SEPARATE SCHEDULES if either has an amount on an adjustment line. One schedule may be used only where ALL income is earned JOINTLY. Complete the TAXPAYER, SPOUSE, or JOINT oval.
Where separate schedules are prepared, INCLUDE ONLY THAT PERSON'S SHARE on each line.
This follows from the rule that spouses are separate taxpayers. See class-system-and-losses.md.
## Schedules D, J, and T are NOT reconciliation schedules
- SCHEDULE D carries an explicit warning: AMOUNTS FROM FEDERAL SCHEDULE D MAY NOT BE CORRECT FOR PA INCOME TAX PURPOSES. It is built transaction by transaction, not reconciled. For 2025 it adds a DIGITAL ASSET QUESTION and a LIKE-KIND EXCHANGE section
- SCHEDULE J takes POSITIVE AMOUNTS ONLY from PA-41 RK-1s or NRK-1s. No federal starting figure
- SCHEDULE T is built from W-2G totals plus other winnings and the taxpayer's own cost records
## Amended returns
An amended PA Schedule A or B must be included with SCHEDULE PA-40 X, and SECTION III ON PAGE 2 OF THE PA-40 X must explain any increase or decrease.
## 2026
All five schedules carry 2025 revision codes EX 04-25. No 2026 revisions have issued. The PA rate remains 3.07% and the reconciliation structure is statutory.
CHECK ON RELEASE: whether the IRC 965 line survives on the 2026 Schedule B, since the federal transition tax instalment period has run, and whether the Schedule D digital asset question changes.
## Required Information
- Federal Form 1040 lines 2a, 2b, and 3b
- Federal Schedule 1, for HSA and MSA distributions
- Federal Schedules K-1 where no PA RK-1 was issued
- The ISSUER of each tax-exempt holding, since PA and federal exemptions differ
- IRC 965 Transition Tax Statement and the history of payments received
- Which spouse owns each item
## Questions
- Does your PA interest or dividend figure differ from the federal one? If so, the schedule must be filed
- Do you hold municipal bonds issued outside Pennsylvania?
- Do you hold U.S. Treasury obligations, which PA exempts?
- Did you take a 529 distribution for a non-educational purpose?
- Do you have IRC 965 repatriation payments arriving this year?
## Common Errors
- Assuming PA starts from federal AGI; it starts from specific federal LINES for two classes only
- Failing to add back out-of-state municipal interest at Schedule A line 2
- Failing to deduct U.S. government direct obligations at Schedule A line 7
- Omitting a 529 non-educational distribution from Schedule A line 13
- Reporting Box 2a capital gain distributions on Schedule D instead of Schedule B line 10
- Filing one joint schedule where an adjustment line requires separate schedules
- Submitting Schedule A or B when no adjustment exists, or omitting it when one does
- Using federal Schedule D amounts directly for PA
## Prompt
- Does Pennsylvania start from my federal AGI?
- I have municipal bonds from New Jersey.
- What is PA Schedule A for?
