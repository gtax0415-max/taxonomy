---
type: addition
category: additions
jurisdiction: NC
tax_year: "2026"
source_doc: NC K-1 for Form D-403 (partnership) or Form CD-401S (S corporation) showing taxed PTE income or loss / federal K-1 showing state and local taxes deducted by the entity / S corporation built-in gains tax information
form: Form D-400
line: "7, 9"
via:
  - Schedule S, Part A, Line 5 (S corporation built-in gains tax) → Form D-400, Line 7
  - Schedule S, Part A, Line 8 (state, local, or foreign income tax deducted by S corp, partnership, estate or trust) → Form D-400, Line 7
  - Schedule S, Part A, Line 14 (taxed PTE loss) → Form D-400, Line 7
  - Schedule S, Part B, Line 38a (taxed PTE income, NC-sourced) and 38b (non-NC-sourced) → Line 38c → Form D-400, Line 9
---
# Pass-Through Entity Adjustments
## Description
Adjustments for owners of partnerships and S corporations, most of them tied to North Carolina's elective PASS-THROUGH ENTITY TAX (the "Taxed PTE" SALT-cap workaround).
## The taxed PTE pair
When a partnership or S corporation elects to pay North Carolina tax at the entity level:
- The owner DEDUCTS their share of North Carolina-sourced income already taxed at the entity (Line 38a)
- The owner ADDS BACK their share of North Carolina-sourced loss (Line 14)
- A resident owner may also deduct non-North Carolina income taxed at the entity level by another state or D.C. (Line 38b) — the entity must supply this figure by other means because it is not on the NC K-1
## Other additions
- Line 5: shareholder's share of S corporation income reduced by built-in gains tax under IRC 1366(f)(2)
- Line 8: owner's share of state, local, or foreign income tax the entity deducted under IRC 164 — added back so it is not deducted twice
## NEW for 2026 — S corporation shareholder losses (S.L. 2026-31)
Effective for tax years beginning on or after January 1, 2026, G.S. 105-153.5(c1) was rewritten:
- A shareholder may DEDUCT S corporation losses or deductions as provided in G.S. 105-131.4
- A shareholder must ADD BACK S corporation losses or deductions included in AGI to the extent they exceed the shareholder's combined adjusted basis in stock and debt under G.S. 105-131.3
## NEW for 2026 — federal partnership audit adjustments (S.L. 2026-31, Part II)
For federal partnership adjustments (BBA centralized audit regime) that become final on or after January 1, 2026:
- A partner ADDS any increase in distributive share from a final federal partnership adjustment (G.S. 105-153.5(c2)(24)) and DEDUCTS any decrease ((c2)(25))
- The partnership reports within 90 days and notifies partners; each partner files within SIX MONTHS of the final adjustment
- An audited partnership may instead elect to pay at the entity level; partners then may not claim a deduction, credit, or refund for that amount
- Special statute of limitations: one year after the return reporting the adjustment or three years after the original return, whichever is later
Expect new Schedule S lines for these on the 2026 form.
## Notes
- The NC K-1 line numbers identify each amount (2025: CD-401S NC K-1 Lines 9-10; D-403 NC K-1 Lines 10-11)
- With the federal SALT cap at $40,400 for 2026 ($20,200 married filing separately), reduced for MAGI over $505,000, the PTE election is less universally valuable; confirm whether the entity still elected
- Beginning 2026, a taxed partnership may not pass through to its partners credits earned in years the election is in effect (G.S. 105-154.1(c))
## Required Information
- NC K-1s from every pass-through
- Entity-level state tax deductions from the federal K-1
## Questions
- Do you own a partnership or S corporation that elected to pay North Carolina tax at the entity level?
- Did the entity deduct state income taxes?
## Common Errors
- Double-counting taxed PTE income by leaving it in AGI
- Missing the add-back of entity-deducted state taxes
## Prompt
- My S corporation elected the North Carolina PTE tax.
- What do I do with my NC K-1?
