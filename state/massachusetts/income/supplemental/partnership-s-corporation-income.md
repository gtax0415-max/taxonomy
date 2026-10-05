---
type: income
jurisdiction: MA
tax_year: 2026
category: supplemental
source_doc: Federal Schedule K-1 (Form 1065 / 1120-S) / Massachusetts Schedule 3K-1 (partnerships) / Massachusetts Schedule SK-1 (S corporations), including SK-1 Line 32e and 3K-1 Line 41e (PTE excise credit)
form: Massachusetts Form 1
line: "7"
rate: "5.0% (Part B); interest, dividends and gains are reclassified"
via:
  - Massachusetts 3K-1 / SK-1 → Schedule E-2 (one per entity) → Schedule E Reconciliation Lines 25-35 → Line 58 → Form 1, Line 7
  - Interest and dividends in the K-1 → Schedule E-2 Lines 9-10 → Schedule B / Form 1, Line 5
  - Capital gains in the K-1 → Massachusetts Schedule B / Schedule D
  - PTE excise credit on 3K-1 Line 41e / SK-1 Line 32e → Schedule E-2 header → Schedule CMS
routing:
  - "Passive income/loss → Lines 1-2; non-passive → Lines 3, 5; Section 179 from the entity → Line 4 (Massachusetts limit)"
  - "Prior-year loss suspended by at-risk, basis or passive rules → fill in Line 12 oval"
  - "Any investment not at risk → fill in Line 13 oval"
---
# Partnership and S Corporation Income (Schedule E-2)
## Description
Distributive share of partnership and S corporation ordinary income or loss, one Schedule E-2 per entity, using the MASSACHUSETTS K-1 (3K-1 or SK-1) — which already reflects Massachusetts depreciation and other differences — rather than the federal K-1.
## Key points
- Use the Massachusetts K-1 amounts; the entity computes Massachusetts differences
- Interest (other than Massachusetts bank interest) and dividends included in income are removed on Lines 9-10 and taxed as Part A on Schedule B
- Section 179 passed through is subject to the Massachusetts limit
- The 90% refundable PTE Excise Credit amount from this entity is entered in the E-2 header and claimed on Schedule CMS — see credits/business/pass-through-entity-excise-credit.md
## Notes
- An S corporation may itself owe Massachusetts corporate excise; that does not change the shareholder's E-2
- Federal QBI deduction does not exist in Massachusetts
## Required Information
- Massachusetts Schedule 3K-1 or SK-1 for each entity
- Federal K-1 for reconciliation
- Basis, at-risk and passive loss carryforwards
## Questions
- Did you receive a Massachusetts 3K-1 or SK-1, not just a federal K-1?
- Does the K-1 show a PTE excise credit?
- Do you have suspended losses from prior years?
## Common Errors
- Using the federal K-1 instead of the Massachusetts K-1
- Leaving interest and dividends in Line 8
- Missing the PTE excise credit on the K-1
## Prompt
- I'm a partner in an LLC.
- My S corporation sent me an SK-1.
