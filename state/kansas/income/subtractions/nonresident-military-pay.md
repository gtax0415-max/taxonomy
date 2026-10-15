---
type: subtraction
category: subtractions
jurisdiction: KS
tax_year: 2026
source_doc: Form W-2 from DFAS (military wages) / military Leave and Earnings Statement showing home of record and state of legal residence / PCS orders stationing the service member in Kansas / non-military spouse's W-2 and military ID or marriage certificate
form: Form K-40
line: "2"
via:
  - Schedule S, line A15 → line A26 → line A27 → Form K-40, line 2
---
# Military Compensation of a Nonresident Servicemember
## Description
Military pay is taxable only by the service member's state of legal residence. A nonresident stationed in Kansas subtracts military compensation. The Kansas income of a non-military spouse living in Kansas solely because of the service member's orders is also subtracted.

## Amount
- 2026 military compensation of a NONRESIDENT service member
- Kansas-source income of the non-military spouse who resides in Kansas only because the member is stationed here under orders
- Unchanged for 2026

## Notes
- SCOPE: OUT OF SCOPE for this taxonomy (team decision 2026-09-30: full-year residents with Kansas income only). Kept so the tool can recognize and route the situation.
- A Kansas-domiciled service member stationed elsewhere stays a Kansas resident and is fully taxable; no subtraction
- Nonresidents use Schedule S, Part B, and this subtraction also enters the Kansas-source modification

## Required Information
- State of legal residence (Leave and Earnings Statement)
- Military wages on the DFAS W-2
- Spouse's Kansas wages and military orders

## Questions
- Is Kansas your state of legal residence or home of record?
- Are you in Kansas only because of military orders?
- Does your spouse work in Kansas?

## Common Errors
- A Kansas resident service member subtracting military pay
- Missing the spouse's exemption

## Prompt
- I'm stationed at Fort Riley but my home of record is Texas.
- My husband is stationed in Kansas and I work here.
