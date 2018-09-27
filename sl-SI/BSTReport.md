# How To: Prepare BST report

This topic describes how to prepare BST report, which is used to report services and part of goods exchange and current/capital transfers with non-residents to Bank of Slovenia (BSI) on monthly basis grouped by BST codes and Countries/Regions Codes. Report is submitted through file.

## Check and adjust setups

1. Open BST Setup page. Choose BST Report No. Series,  Prep. By User ID, Resp. User ID.
2. Open User Setup page and on relevant users populate fields Reporting Name, Reporting E-mail, Reporting Phone, Reporting Position.

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