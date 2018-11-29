# How To: Print Informative VAT on Sales Invoice

This topic describes posting of Informative VAT in Sales invoices that enables printing of VAT for informative purposes in accordance with the 76. Article of Slovenian Value Added Tax Act. In this case VAT is not calculated and posted, but only printed in two additional columns of VAT Amount Specification: Informative VAT % and Informative VAT amount. 

Functionality is enabled when extension is installed.

## VAT Posting Setup

1. Open VAT Posting Setup.
2. Enter VAT % (Informative) for combination that applies for this article. VAT % in tas case should be 0.

VAT Bus. Posting Group|VAT Prod. Posting Group|VAT Identifier|VAT %|VAT % (Informative)
----------------------|-----------------------|--------------|-----|-------------------
K-DA|ODB-22|36|0|22
K-DA|ODB-9,5|35|0|9,5

## Post Sales Invoice

1. Open Sales document.
2. Enter data about customer and items. 
3. Choose VAT Product Posting Group that applies to informative VAT.
4. Enter Unit price excl. VAT.
4. Post Sales Invoice.

VAT Bus. Posting Group|VAT Prod. Posting Group|Unit price excl. VAT
----------------------|-----------------------|--------------------
K-DA|ODB-22|1.000,00

## Print Sales Invoice

1. Go to Posted Sales Invoice and check entries.

Check posted General Ledger Entries.

G/L Account No.|Amount
---------------|------
760010|-1.000,00
120010| 1.000,00

Check VAT Entries.

VAT Bus. Posting Group|VAT Prod. Posting Group|Type|Base|Amount
----------------------|-----------------------|----|----|------
K-DA|ODB-22|Sale|1.000,00|0,00

2. Choose Print action and check VAT Specification about Informative VAT on printout.

VAT %|VAT Amount Exl. VAT|VAT Amount|Amount Incl. VAT|VAT % Informative|VAT Amount (Informative)
-:|-:|-:|-:|-:|-:
0|1.000|0,00|1.000,00|22|220,00