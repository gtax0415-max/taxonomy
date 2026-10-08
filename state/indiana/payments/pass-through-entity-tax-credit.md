---
type: payment
category: pass-through-entity-tax-credit
jurisdiction: IN
tax_year: 2026
source_doc: Federal Schedule K-1 and the pass-through entity's statement of Indiana pass-through entity tax paid on your behalf
form: Schedule 5
line: "3"
refundable: true
via:
  - Indiana PTET credited to you on Schedule IN K-1 or IT-41 Schedule IN K-1 → Schedule 5, Line 3 → Line 13 → Form IT-40, Line 12
  - PTET deducted in federal AGI → added back on Schedule 1, Line 1
routing:
  - "Indiana PTET credited on an IN K-1 → Schedule 5, line 3; enclose every IN K-1 reporting it"
  - "PTET paid to another state or locality → not on this line"
  - "PTET → never reported as withholding or estimated payments"
see_also:
  - payments/payments.md
  - income/add-backs/tax-add-back.md
  - payments/indiana-withholding.md
  - payments/estimated-payments.md
---
# Pass Through Entity Tax Credit (Schedule 5, Line 3)
## Description
If a partnership, S corporation, or estate or trust elected to pay Indiana pass through entity tax (PTET), the owner claims the PTET credited to them from Schedule IN K-1 or IT-41 Schedule IN K-1 on Schedule 5, line 3. Include all Schedule IN K-1s reporting PTET credit to verify the claim. Schedule 5 is the refundable credit schedule, so this credit can produce a refund.
## Rules
- Do not report PTET as withholding or as estimated tax payments.
- Do not report PTET paid to another state or locality on this line.
- The PTET deducted in figuring federal AGI is added back on Schedule 1, line 1 (see income/add-backs/tax-add-back.md); a later PTET refund is a negative entry there.
- The PTET rate follows the individual rate in IC 6-3-2-1 (HEA 1427 (2025)), which is 2.95% for 2026.
- For estimated tax penalty purposes, PTET is combined with withholding (Schedule IT-2210, line 5).
## Example
Ari owns 40% of an LLC that elected Indiana PTET for 2026 and paid $11,800; Ari's IN K-1 credits $4,720. Ari adds back the PTET deducted in federal AGI on Schedule 1, line 1 and enters $4,720 on Schedule 5, line 3.
## Questions
- Did any partnership, S corporation, estate or trust elect Indiana PTET for 2026?
- What PTET credit does each Schedule IN K-1 show?
## Common Errors
- Entering PTET on Schedule 5, line 1 or line 4
- Claiming another state's PTET
- Not enclosing the IN K-1s
- Claiming the credit without the matching line 1 add-back
## Prompt
- My S corporation paid the Indiana pass through entity tax. How do I get credit?
