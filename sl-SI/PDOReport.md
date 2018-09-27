# How To: Prepare PDO report

This topic describes how to prepare PD-O report and prepare the xml data file according to Slovene legislation.

## Check and adjust setups

1. Open PDO Setup page. Populate fields PDO Report No. Series, Prep. By User ID, Resp. User ID. Enter PDO VAT Identifier Filter Code.

2. Open User Setup page and on relevant users populate fields Reporting Name, Reporting E-mail, Reporting Phone, Reporting Position.

3. Open VAT Posting Setup and insert or adjust relevant records. For combination of VAT Business Posting Group and VAT Product Posting Group:
- Enter VAT % (informative) for combination.
- Field VAT Calculation Type should be Normal VAT and field VAT % should be 0.
- Enter Sales VAT Account, VAT Identifier.

## Populate master tables wih VAT Business Posting Group and VAT Product Posting Group

1. On Customer and Vendor cards populate fields Country/Region Code and VAT Business Posting Group.
2. On relevatnt G/L Account cards populate fields VAT Business Posting Group and VAT Product Posting Group.
3. On relevatnt Items cards populate field VAT Product Posting Group.

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