# How To: View VAT Identifier on VAT Entries

This topic describes posting of VAT Identifier when posting VAT entries for certain combination of VAT Product Posting Group and VAT Business Posting Group from VAT Posting Setup that is entered on unposted document to VAT Entries.

Functionality is enabled when extension is installed.

## VAT Identifier

1. Open page VAT Identifiers.
2. Enter Code and Description for each VAT Identifier.

Code|Description
----|-----------
12|D-DA + B-22 - ODB (8, 18)
14|K-DA + B-22 - OBR (7,14)

## VAT Posting Setup

1. Open VAT Posting Setup.
2. Choose VAT Identifier for each combination on VAT Posting Setup.

VAT Bus. Posting Group|VAT Prod. Posting Group|VAT Identifier
----------------------|-----------------------|--------------
D-DA|B-22|12
K-DA|B-22|14

## Post Sales Invoice

1. Open Sales document.
2. Enter data about Customer Number, Posting Date, Document Date and choose items in lines. 
3. Choose VAT Product Posting Group that has entered VAT Identifier for combination with VAT Business Posting Group.
4. Post Sales Invoice.

VAT Bus. Posting Group|VAT Prod. Posting Group
----------------------|-----------------------
K-DA|B-22

## Check Posted Sales Invoice

1. Go to Posted Sales Invoice.
2. Choose Navigate Button.
3. Open VAT Entry that is posted for Sales Invoice.
4. Check VAT Identifier for posted VAT Entry. VAT Identifier was transferred from VAT Posting Setup.

VAT Bus. Posting Group|VAT Prod. Posting Group|VAT Identifier|Type
----------------------|-----------------------|--------------|----
K-DA|B-22|14|Sale

## Post Purchase Invoice

1. Open Purchase document.
2. Enter data about Vendor Number, Posting Date, Document Date and choose items in lines. 
3. Choose VAT Product Posting Group that has entered VAT Identifier for combination with VAT Business Posting Group.
4. Post Purchase Invoice.

VAT Bus. Posting Group|VAT Prod. Posting Group
----------------------|-----------------------
D-DA|B-22

## Posted Purchase Invoice

1. Go to Posted Purchase Invoice.
2. Choose Navigate Button.
3. Open VAT Entry that is posted for Purchase Invoice.  
4. Check VAT Identifier for posted VAT Entry. VAT Identifier was transferred from VAT Posting Setup. 

VAT Bus. Posting Group|VAT Prod. Posting Group|VAT Identifier|Type
----------------------|-----------------------|--------------|----
D-DA|B-22|12|Purchase

## Post General Journal for Sale Posting Type

1.	Go to General Journals. Open Batch for posting.
2.	Enter all mandatory data for posting Journal such as Account Type, Account No., Posting Date, Document Number, Amount, Balance Account Type and Balance Account No.
3.	Choose General Posting Type, General Product Posting Group and General Business Posting Group.
4.	Choose VAT Product Posting Group and VAT Business Posting Group that was previously created.

    Account Type|Account No.|Gen. Posting Type|General Bus. Posting Group|General Prod. Posting Group|VAT Bus. Posting Group|VAT Prod. Posting Group|Amount|Bal. Account Type|Bal. Account No.
    ------------|-----------|-----------------|--------------------------|---------------------------|----------------------|-----------------------|------|-----------------|----------------
    G/L Account|760010|Sale|D-DA|B-SPL|D-DA|B-22|100,00|Customer|Customer No.

5.	Post Journal.
6.	Open VAT Entries for Journal and check VAT Identifier. VAT Identifier was transferred from VAT Posting Setup.

VAT Bus. Posting Group|VAT Prod. Posting Group|VAT Identifier|Type
----------------------|-----------------------|--------------|----
K-DA|B-22|14|Sale

## Post General Journal for Purchase Posting Type

1.	Go to General Journals. Open Batch for posting.
2.	Enter all mandatory data for posting Journal such as Account Type, Account No., Posting Date, Document Number, External Document Number, Amount, Balance Account Type and Balance Account No.
3.	Choose General Posting Type, General Product Posting Group and General Business Posting Group.
4.	Choose VAT Product Posting Group and VAT Business Posting Group that was previously created.

Account Type|Account No.|Gen. Posting Type|General Bus. Posting Group|General Prod. Posting Group|VAT Bus. Posting Group|VAT Prod. Posting Group|Amount|Bal. Account Type|Bal. Account No.
------------|-----------|-----------------|--------------------------|---------------------------|----------------------|-----------------------|------|-----------------|----------------
G/L Account|415010|Purchase|D-DA|B-SPL|D-DA|B-22|100,00|Vendor|Vendor No.

5.	Post Journal.
6.	Open VAT Entries for Journal and check VAT Identifier. VAT Identifier was transferred from VAT Posting Setup.

VAT Bus. Posting Group|VAT Prod. Posting Group|VAT Identifier|Type
----------------------|-----------------------|--------------|----
D-DA|B-22|12|Purchase