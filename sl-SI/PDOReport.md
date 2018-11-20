# How To: Prepare Delivery Declaration Report

This topic describes how to prepare PD-O report and prepare the xml data file according to Slovene legislation.

## Assisted Setup

To enable PDO Report functionality you need to set up fields in advanced Adriatic Localization that can be accessed through Assisted Setup.

1. Open Assisted Setup.
2. Choose Set up advanced Adriatic Localization.
3. Program opens wizard.
4. Go to Next page.
5. Choose localization country SI.
6. Enable option PDO enabled.
7. Go to next page.
8. Check or correct data about company.
9. Go to next page.
10. Choose PDO Report No. Series to create PDO reports.
11. Choose PDO Prepared by user ID that will prepare PDO reports when exporting XML file to authorities.
12. Choose PDO Responsible user ID that will be responsible for PDO reports when exporting XML file to authorities.
13. Enter VAT Ident. Filter Code that will be used to filter VAT Entries in PDO Report. 

## User Setup

1. Open User Setup page.
2. Populate fields Reporting Name, Reporting E-mail, Reporting Phone, Reporting Position on relevant users.

## VAT Posting Setup

1. Open VAT Posting Setup and insert or adjust relevant records. For combination of VAT Business Posting Group and VAT Product Posting Group:
- Enter VAT % (informative) for combination.
- Field VAT Calculation Type should be Normal VAT and field VAT % should be 0.
- Enter Sales VAT Account, VAT Identifier.

## Populate master tables wih VAT Business Posting Group and VAT Product Posting Group

1. On Customer and Vendor cards populate fields Country/Region Code and VAT Business Posting Group.
2. On relevant G/L Account cards populate fields VAT Business Posting Group and VAT Product Posting Group.
3. On relevant Items cards populate field VAT Product Posting Group.

## Post some financial transactions

1. Open sales and purchase documents (Invoice, Credit Memos etc.). Enter VAT Correction Date on documents, which means, for which VAT date transactions, which are corrected with this document, were previously reported (period for correction is calculated from this date). On lines choose appropriate VAT Product Posting Group and VAT Business Posting Group.
2. Post sales and purchase documents (Invoice, Credit Memos etc.). 
3. Post general journals
4. Check these transaction in General Ledger Entries if fields  VAT Business Posting Group and VAT Product Posting Group are filled.

## Create PDO Report document

1. Open new PDO Report
2. Enter the Period Start Date and Period End Date.
3. If this is not the first document, select the appropriate previous FAS Report document in field Previous Report No.
4. Run periodic activity named Suggest Lines. If necessary put some additional filters on G/L Entry from where data will be taken and lines generated.
5. Check the generated lines and adjust or insert new ones if necessary.
6. Run the Export Report activity. Place a check mark in Export File field in order to generate xml file besides the report.