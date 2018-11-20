# How To: Prepare FAS report

This topic describes how to prepare FAS report and prepare the xml data file as required by AJPES (Agency of the Republic of Slovenia for Public Legal Records and Related Services).

## Assisted Setup

To enable FAS Report functionality you need to set up fields in advanced Adriatic Localization that can be accessed through Assisted Setup.

1. Open Assisted Setup.
2. Choose Set up advanced Adriatic Localization.
3. Program opens wizard.
4. Go to Next page.
5. Choose localization country SI.
6. Enable option FAS enabled.
7. Go to next page.
8. Check or correct data about company.
9. Go to next page.
10. Choose FAS Report No. Series to create FAS reports.
11. Choose FAS Responsible user ID that will be responsible for FAS reports when exporting XML file to authorities.
12. Choose FAS Prepared by user ID that will prepare FAS reports when exporting XML file to authorities.
13. Choose FAS Director by user ID that will prepare FAS reports when exporting XML file to authorities.
14. Enter Budget User Code that will be exported to XML file.
15. Enter Company Sector Code of company that will be exported to XML file.

## User Setup

1. Open User Setup page.
2. Populate fields Reporting Name, Reporting E-mail, Reporting Phone, Reporting Position on relevant users.

## Check and insert FAS code lists

1. Open FAS Sectors and insert and adjust relevant records.
2. Open FAS Instruments and insert and adjust relevant records.

## Populate master tables wih FAS Sector and Instrument

1. On Customer and Vendor cards populate field FAS Sector Code.
2. On relevant G/L Account cards place a check in field FAS Account. Select an option in FAS Type field. Populate fields FAS Instrument Code and FAS Sector Code. In order to apply any posting restrictions, select an option in fields FAS Sector Posting and FAS Instrument Posting.
3. On relevant Bank Account cards populate fields FAS Instrument Code and FAS Sector Code.

## Post some financial transactions

1. Post sales and purchase documents (Invoice, Credit Memos etc.)
2. Post general journals
3. Check these transaction in General Ledger Entries if fields FAS Sector Code and FAS Instrument Code are filled.

## Create FAS Report document

1. Open new FAS Report
2. Enter the Period Start Date and Period End Date.
3. If this is not the first document, select the appropriate previous FAS Report document in field Previous Report No.
4. Run periodic activity named Suggest Lines. If necessary put some additional filters on G/L Entry from where data will be taken and lines generated.
5. Check the generated lines and adjust and insert new ones if necessary.
6. Run the Export Report activity. Place a check mark in Export File field in order to generate xml file besides the report.