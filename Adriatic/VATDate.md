# How To: Post documents with VAT Date

This topic describes how to post documents with VAT Date that different than Posting Date.

VAT Date is added to General Journal, Sales and Purchase documents. When posting documents with different dates, program uses functionality for posting unrealized amounts on unrealized accounts using Posting Date. When user posts postponed VAT, program creates additional VAT Entry with new Posting Date as realized amounts.

## Add Accounts to VAT Posting Setup

1. Open VAT Posting Setup.
2. Enter Sales VAT Unrealized Account. This account will be used for posting unrealized reverse charge VAT (VAT Entry with Type Sale).
3. Enter Sales VAT Account. This account will be used for posting realized reverse charge VAT (VAT Entry with Type Sale).

## Post Sales Invoice

1. Open Sales document.
2. Enter data about customer and items. 
3. Enter VAT Date. 
4. Post Sales Invoice on action.

## Print Sales Invoice

1. Go to Posted Sales Invoice.
2. Check field VAT Date.
3. Print Sales Invoice. Field VAT Date is added to print.

## Post Purchase Invoice

1. Open Purchase document.
2. Enter data about vendor and items. 
3. Enter VAT Date.
4. Post Purchase Invoice on action.

## Posted Purchase Invoice

1. Go to Posted Purchase Invoice.
2. Check field VAT Date.
