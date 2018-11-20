# How To: Prepare KRD report

This topic describes how to prepare KRD report and prepare the xml data file as required by Bank of Slovenia for certain business entities which do business with foreign countries.

## Assisted Setup

To enable KRD Report functionality you need to set up fields in advanced Adriatic Localization that can be accessed through Assisted Setup.

1. Open Assisted Setup.
2. Choose Set up advanced Adriatic Localization.
3. Program opens wizard.
4. Go to Next page.
5. Choose localization country SI.
6. Enable option KRD enabled.
7. Go to next page.
8. Check or correct data about company.
9. Go to next page.
10. Choose KRD Report No. Series to create KRD reports.
11. Choose KRD Responsible user ID that will be responsible for KRD reports when exporting XML file to authorities.
12. Choose KRD Prepared by user ID that will prepare KRD reports when exporting XML file to authorities.
13. Choose Default KRD Affiliation Type that applies to company and will be exported to XML file.
14. Enter KRD Blank LCY Code that will be used for exporting entries that are posted with blank currency. 
15. Enter KRD Blank LCY Num that will be used for exporting entries that are posted with blank currency.

## User Setup

1. Open User Setup page. 
2. Populate fields Reporting Name, Reporting E-mail, Reporting Phone, Reporting Position on relevant users.

## Check and insert KRD code lists

1. Open KRD Sectors and insert and adjust relevant records.
2. Open KRD Codes and insert and adjust relevant records for all Types (Affiliation Type, Instrument Type, Maturity).

## Populate master tables wih KRD data

1. On Customer and Vendor cards populate fields KRD Sector Code, KRD Affiliation Type.
2. On relevant Customer Posting Group and Vendor Posting Group records populate fields KRD Claim/Liability, KRD Instrument Type, KRD Maturity.

## Post some financial transactions

1. Post sales and purchase documents (Invoice, Credit Memos etc.)
2. Post general journals.
3. Check these transaction in Customer Ledger Entires and in Vendor Ledger Entries to see if KRD related data were transfered ok.

## Create KRD Report document

1. Open new KRD Report
2. Enter the Period Start Date and Period End Date.
3. If this is not the first document, select the appropriate previous KRD Report document in field Previous Report No.
4. Run periodic activity named Suggest Lines. If necessary put some additional filters on Cust. Ledger Entry and Vendor Ledger Entry from where data will be taken and lines generated.
5. Check the generated lines and adjust and insert new ones if necessary.
6. Run the Export Report activity. Place a check mark in Export File field in order to generate xml file besides the report.