---
type: tax
category: tax-computation
jurisdiction: AR
tax_year: 2026
source_doc: Computed from each spouse's net taxable income in columns A and B (no separate source document)
form: Form AR1000F
line: "30"
via:
  - Line 29, column A + line 29, column B → Form AR1000F, line 30 → line 33
---
# Combined Tax on Status 4
## Description
On Status 4, each spouse's column is taxed separately with the Regular Tax Table, and the two taxes are added on line 30. Because of the graduated rates, this often lowers the couple's tax.

## Notes
- Tax column A and column B separately (2026 rates in regular-tax-table.md)
- Line 30 = column A tax + column B tax
- Credits are combined on one return
- Both spouses must use the same table type; Low Income Tax Tables are not available on Status 4

## Required Information
- Each spouse's net taxable income (line 28, columns A and B)
- Status 2 tax, for comparison

## Questions
- Would filing Status 4 lower your tax compared with Status 2?
- Do both spouses have income?
- Does either spouse have negative income (Status 4 not allowed)?

## Common Errors
- Taxing the combined income once
- Using a Low Income Tax Table on Status 4
- Filing Status 4 when one spouse has negative total income

## Prompt
- How is tax figured when we file separately on the same return?
- We both work. Should we file separately on the same return?
