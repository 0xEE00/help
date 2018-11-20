# How To: Prepare BST report

This topic describes how to prepare BST report, which is used to report services and part of goods exchange and current/capital transfers with non-residents to Bank of Slovenia (BSI) on monthly basis grouped by BST codes and Countries/Regions Codes. Report is submitted through file.

## Assisted Setup

To enable BST Report functionality you need to set up fields in advanced Adriatic Localization that can be accessed through Assisted Setup.

1. Open Assisted Setup.
2. Choose Set up advanced Adriatic Localization.
3. Program opens wizard.
4. Go to Next page.
5. Choose localization country SI.
6. Enable option BST enabled.
7. Go to next page.
8. Check or correct data about company.
9. Go to next page.
10. Choose BST Report No. Series to create BST reports.
11. Choose BST Prepared by user ID that will prepare BST reports when exporting XML file to authorities.
12. Choose BST Responsible user ID that will be responsible for BST reports when exporting XML file to authorities.

## User Setup

1. Open User Setup page.
2. Populate fields Reporting Name, Reporting E-mail, Reporting Phone, Reporting Position for users that will be set as BST Prepared by user or BST Responsible User ID.

## Check and insert BST Codes lists

1. Open BST Codes.
2. Insert or adjust relevant records. Enter Code, Serial Num., Description, Totaling. Choose Type (Posting or Total). User sets Posting on BST Sectors that entries can be posted on.

## Populate master tables 

1. On Customer and Vendor cards populate fields Country/Region Code.
2. On relevant G/L Account cards populate fields BST Code. In order to apply any posting restrictions, select an option in fields BST Value Posting.

## Post some financial transactions

1. Post sales and purchase documents (Invoice, Credit Memos etc.)
2. Post general journals
3. Check these transaction in General Ledger Entries if fields BST Code and Country/Region Code are filled.

## Create BST Report document

1. Open new BST Report
2. Enter the Period Start Date and Period End Date.
3. Run periodic activity named Suggest Lines. If necessary put some additional filters on G/L Entry from where data will be taken and lines generated.
4. Check the generated lines and adjust and insert new ones if necessary.
5. Run the Export Report activity. Place a check mark in Export File field in order to generate xml file besides the report.