---
type: computation
category: tax-computation
jurisdiction: KS
tax_year: 2026
source_doc: Federal Form 1040 as filed for 2026 (filing status) / the Kansas taxable income figured from the filer's documents (no separate source document)
form: Form K-40
line: "8"
via:
  - Form K-40, line 7 (taxable income ≤ $100,000) → Tax Table row and filing-status column → line 8 → line 12
---
# Tax Table
## Description
If Kansas taxable income (line 7) is $100,000 or less, the tax on line 8 is looked up in the Kansas Tax Table, not computed by formula. Above $100,000, use the Tax Computation Worksheet.

## How the table works
- Rows are $50 bands of taxable income; the tax shown is the tax at the MIDPOINT of the band, using the 2026 rates (5.20% / 5.58%)
- Columns: single or married filing separate / married filing joint / head of household (head of household tax equals single, because the brackets are the same)
- The lowest band(s) round to $0 tax (the prior file noted no tax below $26 of taxable income; confirm against the 2026 table)

## Example
Single, taxable income $30,020: find the $30,000–$30,050 row. Midpoint $30,025: $23,000 × 5.20% + $7,025 × 5.58% = $1,196 + $392 = $1,588 (approximately; use the printed amount).

## Notes
- Because rates and brackets are unchanged for 2026, the 2026 table is expected to match 2025 except for headings; confirm once KDOR publishes the 2026 booklet
- Software that computes exact tax instead of using the table can differ from the table result by up to a few dollars; the TABLE amount is what Kansas expects for $100,000 or less

## Required Information
- Kansas taxable income (line 7)
- Filing status

## Questions
- What is your filing status?
- Is your Kansas taxable income $100,000 or less?

## Common Errors
- Computing by formula instead of using the table at $100,000 or less
- Reading the wrong filing status column
- Using the table above $100,000

## Prompt
- How do I find my Kansas tax?
- My taxable income is $55,000. What is my Kansas tax?
