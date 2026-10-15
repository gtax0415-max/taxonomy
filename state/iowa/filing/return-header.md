---
type: filing
category: filing
jurisdiction: IA
tax_year: 2026
source_doc: Federal Form 1040 header as filed (names, SSNs or ITINs, address) / Social Security cards or ITIN letters / voter registration card, property tax statement, or lease showing the residence on December 31, 2026
form: Form IA 1040
line: "Step 1"
via:
  - Federal Form 1040 header → Form IA 1040, Step 1 (name, SSN, address)
  - Residence on December 31, 2026 → county number and school district number → Form IA 1040, Step 1 → school district surtax (line 19)
---
# Personal Information: Names, SSNs, Address, County, and School District
## Description
Identification block of the IA 1040. Names and numbers must match the federal return; the county and school district numbers determine the school district surtax.

## Fields
- Last name, first name, and middle initial for the taxpayer and spouse, exactly as on the federal return
- SSN or ITIN for each. A missing number can stop processing
- Current mailing address. Foreign addresses use city, country, and postal code
- COUNTY NUMBER: county of residence on December 31, 2026 (Iowa's 99 counties are numbered alphabetically, 01–99)
- SCHOOL DISTRICT NUMBER: the four-digit district where you LIVED on December 31, 2026, entered even if you have no children in school. It is not necessarily the district your children attend
- Dates of birth, used for the 65-or-older credit, the low-income exemption, and the health insurance deduction

## Special codes
- Nonresident (no Iowa residence in 2026): county "00", school district "0000" — no school district surtax
- Part-year resident who moved OUT before December 31: county "00", school district "9999" — no surtax
- Part-year resident who moved IN: county and district where living on December 31 — surtax may apply
- Servicemembers: county and district of the Iowa home of record, even if stationed elsewhere

## Notes
- The school district number drives the surtax rate on line 19, so a wrong district means a wrong tax
- Find the district on a voter registration card, the county assessor's site, or IDR's Tax Mapper (school surtax search)
- Moving after filing: update the address with IDR so notices and refunds arrive
- Unchanged for 2026. Step references follow the 2025 IA 1040

## Required Information
- Names and SSNs/ITINs as on the federal return
- Mailing address
- Physical residence on December 31, 2026
- Dates of birth

## Questions
- Where did you live on December 31, 2026?
- Did you move into or out of Iowa during 2026?
- Has your name or address changed since last year?

## Common Errors
- Entering the district where children attend school instead of the district of residence
- Using the mailing-address town to guess the district (district lines don't follow city limits)
- Names or SSNs that don't match the federal return
- Using "0000" or "9999" for a full-year resident

## Prompt
- What school district number do I use on my Iowa return?
- We moved to Iowa in June; what county do we enter?
