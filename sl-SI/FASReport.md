# How To: Prepare FAS report

This topic describes how to prepare FAS report and prepare the xml data file as required by AJPES (Agency of the Republic of Slovenia for Public Legal Records and Related Services).

## Check and adjust setups

1. Open FAS Setup page. Populate fields FAS Report No. Series, FAS Resp. User ID, FAS Prep. By User ID, FAS Director User Id, Budget User Code, Company Sector Code.
2. Open User Setup page and on relevant users populate fields Reporting Name, Reporting E-mail, Reporting Phone, Reporting Position.

## Check and insert FAS code lists

1. Open FAS Sectors and insert and adjust relevant records.
2. Open FAS Instruments and insert and adjust relevant records.

## Populate master tables wih FAS Sector and Instrument

1. On Customer and Vendor cards populate field FAS Sector Code.
2. On relevatnt G/L Account cards place a check in field FAS Account. Select an option in FAS Type field. Populate fields FAS Instrument Code and FAS Sector Code. In order to apply any posting restrictions, select an option in fields FAS Sector Posting and FAS Instrument Posting.
3. On relevatnt Bank Account cards populate fields FAS Instrument Code and FAS Sector Code.

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