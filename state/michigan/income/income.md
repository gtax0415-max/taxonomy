---
type: index
category: income
jurisdiction: michigan
tax_year: 2026
source_doc: FEDERAL Form 1040, Line 11 (adjusted gross income)
form: Form MI-1040
line: "10-14"
---
# Michigan Income
## Description
Michigan does not have its own definition of gross income. It starts from FEDERAL adjusted gross income and then adds income the federal return excludes (additions) and removes income Michigan does not tax (subtractions). Everything below AGI on the federal return — the federal standard or itemized deduction, the QBI deduction, and similar — is ignored.
## Flow
FEDERAL Form 1040 Line 11 → MI-1040 Line 10 → + Schedule 1 Line 9 (MI-1040 Line 11) → − Schedule 1 Line 31 (MI-1040 Line 13) → MI-1040 Line 14 income subject to tax.
## Folders
- additions/ — Schedule 1, Lines 1-9 (income Michigan taxes that is not in federal AGI, or deductions Michigan does not allow)
- sourcing/ — forms that divide income between Michigan and other states, or adjust gains: Schedule NR, MI-1040H, MI-461 (with Form 5606), MI-1040D, MI-8949, MI-4797
## What Michigan taxes differently from the federal return
| Item | Federal | Michigan | File |
|---|---|---|---|
| Interest on OTHER states' municipal bonds | Exempt | Taxable (added) | additions/other-state-bond-interest.md |
| Interest on U.S. government obligations | Taxable | Exempt (subtracted) | deductions/subtractions/us-government-obligations.md |
| Social Security benefits | Partly taxable | Exempt | deductions/retirement/social-security-military-railroad.md |
| Military pay and military retirement | Taxable | Exempt | deductions/retirement/social-security-military-railroad.md |
| Pensions and IRA distributions | Taxable | Subtraction up to $67,610 / $135,220 in 2026 | deductions/retirement/retirement-pension-subtraction.md |
| Self-employment tax deduction | Deducted in AGI | Added back | additions/income-taxes-deducted-addback.md |
| Qualified tips and overtime (2026-2028) | Deducted below AGI | Subtracted | deductions/subtractions/tips-and-overtime.md |
| Federal NOL deduction | In AGI | Added back; Michigan NOL used instead | additions/federal-nol-addback.md |
| Bonus depreciation, § 179, § 163(j), § 174, § 168(n) | 2025 federal law (OBBBA) | Decoupled | additions/miscellaneous-additions.md |
| Federal senior deduction, car loan interest, QBI | Below-AGI federal deductions | No Michigan equivalent under current law | — |
## IRC conformity (2025 PA 24)
PA 24 (signed October 7, 2025) moved Michigan's general IRC reference date to January 1, 2025, while keeping the option to use the current IRC, and decoupled from several OBBBA business provisions. For individuals and flow-through owners: bonus depreciation under § 168(k) is computed as the provision stood on December 31, 2024 (the phase-down, which for 2026 means 20% bonus rather than federal 100%); § 168(n) qualified production property is disregarded; §§ 179, 163(j), and 174 apply as of December 31, 2024, and § 174A immediate R&E expensing is not allowed. Treasury's February 2026 notice focused on 2025 and said more guidance for later years is coming. Adjustments are computed on the Schedule 1 decoupling worksheet and reported on Schedule 1 Line 8 (net add-back) or Line 23 (net subtraction).
## Questions
- What is your federal AGI (Form 1040, Line 11)?
- Were you a Michigan resident all year?
- Do you have business, rental, or gain items from other states?
- Do you have income from U.S. bonds or other states' municipal bonds?
## Prompt
- How does Michigan calculate taxable income?
- Why is my Michigan income different from my federal AGI?
