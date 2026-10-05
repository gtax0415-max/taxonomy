---
type: index
jurisdiction: MA
category: credits
form: Massachusetts Form 1
tax_year: 2026
---
# Massachusetts Credits (Form 1)
## Description
Root index for Massachusetts personal income tax credits claimed on Form 1 (residents) or Form 1-NR/PY (nonresidents and part-year residents). Mirrors the federal credit taxonomy, with one structural difference: most Massachusetts credits do NOT have their own Form 1 line. Only five credits are claimed directly on Form 1; everything else flows through Schedule CMS (Credit Manager Schedule).
## Line numbers
Line numbers in this folder come from the 2025 Form 1 (revised August 4, 2026), the latest form published. The 2026 Form 1 is not yet released. Re-check every `line:` value when DOR publishes the 2026 form.
## Where each credit lands on Form 1
| Line | Credit | Refundable | File |
|---|---|---|---|
| 29 | Limited Income Credit | No | income-based/limited-income-credit.md |
| 30 | Income tax due to another state or jurisdiction (Schedule OJC) | No | other-jurisdiction/credit-for-taxes-paid-to-other-jurisdictions.md |
| 31 | Other credits (Schedule CMS, Sections 1 and 3) | No | credit-manager/credit-manager.md |
| 43 | Earned Income Credit | Yes | income-based/earned-income-credit.md |
| 44 | Senior Circuit Breaker Credit (Schedule CB) | Yes | senior/senior-circuit-breaker-credit.md |
| 46 | Child and Family Tax Credit | Yes | family/child-and-family-tax-credit.md |
| 47 | Other refundable credits (Schedule CMS, Sections 2 and 4) | Yes | credit-manager/credit-manager.md |
| 48 | TOTAL REFUNDABLE CREDITS (lines 43 through 47) | — | — |
Related, not a credit: Line 25 Credit recapture amount (Schedule CRS) — credit-manager/credit-recapture.md. Line 27 No Tax Status — income-based/limited-income-credit.md.
## Ordering on the return
Nonrefundable credits (lines 29-31) reduce Line 28 TOTAL TAX and cannot take it below 0 (Line 32). Refundable credits (lines 43-47) are added to payments on Line 51 and can produce a refund with no tax owed.
## Categories
- income-based/ — Earned Income Credit, Limited Income Credit
- family/ — Child and Family Tax Credit
- senior/ — Senior Circuit Breaker Credit
- other-jurisdiction/ — Credit for taxes paid to other states, U.S. territories and Canada
- residential-property/ — Lead Paint, Septic (Title 5), Solar and Wind Energy
- business/ — Farming and Fisheries, EOAC, EDIP, PTE Excise, Farm Food Donation, certificate-based credits
- credit-manager/ — Schedule CMS mechanics and Schedule CRS recapture
## Federal categories with NO Massachusetts analog
- health-insurance/ — Massachusetts has no premium tax credit on the income tax return. ConnectorCare subsidies are administered by the Health Connector, not DOR. Schedule HC can produce a PENALTY (Form 1, Line 35), never a credit
- foreign-tax/ — Massachusetts does NOT credit tax paid to foreign countries, with one exception: Canada and its provinces (see other-jurisdiction/)
- education, retirement-savings, adoption, clean vehicle, residential clean energy (federal Section 25D ended for expenditures after 2025) — no Massachusetts credit. Adoption is an EXEMPTION on Form 1, Line 2f, not a credit
## Rate context for 2026
- Base rate 5.0%; short-term gains and collectibles 8.5% and 12% (Schedule B)
- 4% SURTAX on taxable income over $1,107,750 for 2026 (2025: $1,083,150). Matters for the other-jurisdiction credit
