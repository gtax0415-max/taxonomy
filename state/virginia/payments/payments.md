---
type: index
category: index
jurisdiction: VA
tax_year: 2026
form: Form 760
line: "19a-36"
---
# Payments, Balance Due and Refund (Form 760, Lines 19a-36)
## Description
This folder covers the back half of Form 760 page 2: tax already paid (withholding, estimated payments, prior year overpayment, extension payments), the comparison with the net tax on Line 18, and the settlement: tax you owe (Line 27) or overpayment (Line 28), amounts taken from an overpayment or added to a balance (Lines 29-33, totaled on Line 34), and the final amount you owe (Line 35) or refund (Line 36). It also holds the items added on Line 34: voluntary contributions (Lines 30-31) and the addition to tax, penalties and interest (Line 32). The credits on Lines 23-25 sit in the same block but are covered in credits/, and consumer's use tax (Line 33) is in other-taxes/.
## How the lines flow
```
Line 19a  Your Virginia withholding (W-2, W-2G, 1099, VK-1)
Line 19b  Spouse's Virginia withholding (Filing Status 2 only)
Line 20   2026 estimated tax payments (Form 760ES)
Line 21   2025 overpayment applied to 2026 estimated tax
Line 22   Extension payments (Form 760IP)
Lines 23-25  Income-based credit, credit for tax paid to another state, Schedule CR credits (credits/)
Line 26   Add Lines 19a through 25
Line 27   Line 26 less than Line 18: Line 18 - Line 26 = Tax You Owe
Line 28   Line 18 less than Line 26: Line 26 - Line 18 = Tax Overpayment
Line 29   Overpayment credited to 2027 estimated tax
Line 30   Commonwealth Savers contributions (Schedule VAC, Section I)
Line 31   Other voluntary contributions (Schedule VAC, Section II)
Line 32   Addition to tax, penalty and interest (Schedule ADJ, Line 21)
Line 33   Consumer's use tax
Line 34   Add Lines 29 through 33
Line 35   Amount you owe: Line 27 + Line 34, OR Line 34 - Line 28 when Line 28 is less than Line 34
Line 36   Refund: Line 28 - Line 34 when Line 28 is greater than Line 34
```
Lines 27 and 28 are mutually exclusive, and so are Lines 35 and 36. Line 34 always increases a balance due or reduces a refund: contributions, next-year credits, penalties and use tax all come out of the overpayment first.
## Contributions (Lines 30-31)
Schedule VAC sends part or all of a refund to Commonwealth Savers education or ABLE accounts (Section I → Line 30) and to listed voluntary contribution organizations, library foundations and public school foundations (Section II → Line 31). Both are added into Line 34, so they reduce the refund on Line 36 or, for Section II, Section C, can be paid with a balance due on Line 35. They are not credits and do not reduce tax.
## Addition to tax, penalties and interest (Line 32)
Schedule ADJ, Line 18 (addition to tax from Form 760C or Form 760F) + Line 19 (late filing or extension penalty) + Line 20 (interest) = Line 21 → Form 760, Line 32. Fill in the Line 32 oval if Form 760C or Form 760F is enclosed.
## Files in this folder
- payments.md - this index (Lines 26-28 and 34 flow)
- virginia-withholding.md - Lines 19a and 19b
- estimated-tax-payments.md - Line 20
- prior-year-overpayment-applied.md - Line 21
- extension-payments.md - Line 22
- overpayment-credited-to-next-year.md - Line 29
- voluntary-contributions.md - Lines 30-31; Schedule VAC Sections I and II, Schedule VACS
- addition-to-tax-underpayment.md - Line 32; Schedule ADJ, Lines 18 and 21; Form 760C
- farmers-fishermen-and-merchant-seamen.md - qualifying farmer, fisherman or merchant seaman oval; Form 760F; Schedule ADJ, Line 18
- penalties-and-interest.md - Line 32; Schedule ADJ, Lines 19-20
- amount-you-owe.md - Line 35 and payment options
- refund-and-direct-deposit.md - Line 36, direct deposit and refund options
## Related
- Lines 23-25 credits: credits/credits.md
- Line 33 consumer's use tax: other-taxes/consumer-use-tax.md
- Line 18 net tax: tax-computation/tax-computation.md
## Questions
- How much Virginia tax was withheld for you and your spouse?
- Did you make 2026 estimated payments or apply last year's refund to 2026?
- Did you pay anything with an extension?
- If you are due a refund, do you want part applied to 2027 or donated?
- Did you pay enough during 2026 through withholding and estimated payments, and will you file and pay on time?
- If you owe, how will you pay?
## Prompt
- How do I figure out if I owe Virginia or get a refund?
- Where do my estimated payments go on the 760?
- Why is my refund smaller than my overpayment?
- Can I send my Virginia refund to my child's 529?
- Why is there a penalty line on my Virginia return?
