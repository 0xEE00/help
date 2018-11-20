# How To: Prepare VIES report

This topic describes how to prepare VIES report and prepare the xml data file according to local legislation.

## Assisted Setup

To enable VIES Report functionality you need to set up fields in advanced Adriatic Localization that can be accessed through Assisted Setup.

1. Open Assisted Setup.
2. Choose Set up advanced Adriatic Localization.
3. Program opens wizard.
4. Go to Next page.
5. Choose localization country SI.
6. Enable option VIES enabled.
7. Go to next page.
8. Check or correct data about company.
9. Go to next page.
10. Choose Default VIES County from options Slovenia or Croatia.
11. Choose Default VIES Type from options ZP or PDV-S if Croatia is set in field VIES Country.
12. Enter VIES Company Branch Code if company has Branch or enter 00000.
10. Choose VIES Report No. Series to create VIES reports.
11. Choose VIES Prepared by user ID that will prepare VIES reports when exporting XML file to authorities.
12. Choose VIES Responsible user ID that will be responsible for VIES reports when exporting XML file to authorities. 

## User Setup

1. Open User Setup page.
2. Populate fields Reporting Name, Reporting E-mail, Reporting Phone, Reporting Position on relevant users.

## VAT Setup

1. Open VAT Posting Setup and insert or adjust relevant records. 
2. For combination of VAT Business Posting Group and VAT Product Posting Group:
- Enter VAT %, VIES Goods and EU Service. 
- Field VAT Calculation Type should be Normal VAT. 
- Enter Sales VAT Account and Purchase VAT Account.

## Populate master tables 

1. On Customer and Vendor cards populate fields Country/Region Code and VAT Business Posting Group.
2. On relevant G/L Account cards populate fields VAT Business Posting Group and VAT Product Posting Group.
3. On relevant Items cards populate field VAT Product Posting Group.

## Post some financial transactions

1. Open sales and purchase documents (Invoice, Credit Memos etc.). 
- Enter VAT Correction Date on documents, which means, for which VAT date transactions, which are corrected with this document, were previously reported (period for correction is calculated from this date). 
- On lines choose appropriate VAT Product Posting Group and VAT Business Posting Group.
- Set a check mark in EU 3-Party Trade if transactions from the document need to be reported in VIES as 3-Party Trade. 
- Set a check mark in EU Customs Procedure, if transactions from document need to be reported in VIES as transactions from special customs procedures.

2. Post sales and purchase documents (Invoice, Credit Memos etc.). 
3. Post general journals
4. Check these transaction in General Ledger Entries if fields VAT Business Posting Group and VAT Product Posting Group are filled.

## Create VIES Report document

1. Open new VIES Report
2. Enter the Period Start Date and Period End Date.
3. If this is not the first document, select the appropriate previous FAS Report document in field Previous Report No.
4. Run periodic activity named Suggest Lines. If necessary put some additional filters on G/L Entry from where data will be taken and lines generated.
5. Check the generated lines and adjust or insert new ones if necessary.
6. Run the Export Report activity. Place a check mark in Export File field in order to generate xml file besides the report.