---
type: donation
category: index
jurisdiction: PA
form: PA-40
line: "32, 33, 34, 35, 36"
---
# Pennsylvania Donations
## Description
A separate domain because A DONATION IS NOT A CREDIT. Credits reduce tax. Donations GIVE MONEY AWAY and produce no Pennsylvania tax benefit at all. They sit at the opposite end of the return and move the refund in the opposite direction.
## Files in this folder
- Refund Donation Lines (refund-donation-lines.md) — PA-40 lines 32 through 36, organization codes A through J
## Why this is its own domain and not part of credits/
| | CREDIT | DONATION |
|---|---|---|
| Effect on tax | REDUCES it | NONE |
| Effect on refund | INCREASES it | REDUCES it |
| Direction of money | To the taxpayer | Away from the taxpayer |
| PA-40 location | Lines 21 to 23 | Lines 32 to 36 |
| Requires an overpayment? | No | YES |
| Type key | `type: credit` | `type: donation` |
Filing these under credits/ would put an item that costs the taxpayer money in the same bucket as items that save it. Any query that sums "PA credits" would be wrong.
## The confusion this domain exists to prevent
Two things on the PA-40 involve giving to a cause, and they are OPPOSITES:
| | Refund donation lines 32-36 | EITC and OSTC on Schedule OC |
|---|---|---|
| Domain | donations/ | credits/business-incentive/ |
| What happens | You GIVE money away | You RECEIVE a tax credit |
| Requires an award? | No | YES, a DCED award |
| PA tax benefit | NONE | Up to 90% of the contribution |
A business owner asking about "donating on the PA return" almost always means the EDUCATIONAL IMPROVEMENT TAX CREDIT, which is a credit and lives in credits/. Establish which is meant before entering anything.
## No PA charitable deduction exists either
Pennsylvania allows NO CHARITABLE DEDUCTION OF ANY KIND. The Department's Deductions and Credits guide lists "Gifts to charity: No provision." So charitable giving reaches a PA return in exactly one place — these five lines — and even there it produces no benefit.
The PA-40 instructions describe DIRECT contributions to these organizations as "tax-deductible," which refers to the FEDERAL return, not the Pennsylvania one.
## One credit sits nearby and is easily confused
The ORGAN AND BONE MARROW DONOR CREDIT is a genuine CREDIT and lives in credits/civic-volunteer/. It goes to an EMPLOYER who kept paying an employee on donation leave. It has nothing to do with the Casey Memorial Organ and Tissue Donation Awareness Trust Fund at donation CODE D, which is a gift of refund money.
Same subject matter, opposite mechanics, different domains.
## Related
- Organ and bone marrow donor CREDIT — see state/pennsylvania/credits/civic-volunteer/organ-and-bone-marrow-donor-credit.md
- EITC and OSTC, which return up to 90% of a contribution — see state/pennsylvania/credits/business-incentive/
## Questions
- Do you have a Pennsylvania overpayment to allocate?
- Did you mean a donation, or the Educational Improvement Tax Credit?
- Which organizations, up to five of the ten?
## Prompt
- Can I donate part of my PA refund?
- What are lines 32 through 36 on the PA-40?
- I want to give to charity on my Pennsylvania return.
