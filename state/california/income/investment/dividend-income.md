---
type: income
category: investment
jurisdiction: CA
tax_year: 2026
source_doc: Form 1099-DIV (box 1a ordinary dividends, box 1b qualified dividends, box 2a capital gain distributions, box 12 exempt-interest dividends) / brokerage consolidated statement
form: Form 540
line: "13"
via:
  - Form 1099-DIV → federal Form 1040, Line 3b → federal AGI → Form 540, Line 13
  - "Differences only: Schedule CA (540), Part I, Section A, Line 3 → column B (Line 14) or column C (Line 16)"
---
# Dividend Income
## Description
Payments from a company based on stock ownership, reported on Form 1099-DIV. California has NO lower rate for qualified dividends: all dividends are taxed as ordinary income.

## Notes
- Line numbers follow the 2025 Form 540 and schedules; confirm them on the 2026 forms (expected December 2026)
- Add (column C): controlled foreign corporation dividends in the year distributed, regulated investment company capital gains in the year distributed, distributions of pre-1987 S corporation earnings
- Children's dividends reported by the parent or child differently from federal: adjust per FTB 3803
- Usually flows through federal AGI with no adjustment
- The federal qualified-dividend rate does not carry over to California
- Section 199A (REIT) dividends: California has no qualified business income (QBI) deduction; the federal deduction is taken below AGI, so no Schedule CA entry is needed
- Exempt-interest dividends from funds holding non-California municipal bonds may be taxable in California
- Dividends from funds holding U.S. obligations may be partly exempt in California, if the fund meets California's requirements

## Required Information
- All 1099-DIV forms
- Fund statements showing the share of income from U.S. obligations or from bonds of each state

## Questions
- Did you receive dividends or mutual fund distributions?
- Do any funds hold municipal or U.S. government bonds?

## Common Errors
- Expecting a lower California rate on qualified dividends
- Missing California adjustments for exempt-interest dividends

## Prompt
- I received dividends from my stock portfolio.
- Does California give a lower rate on qualified dividends?
