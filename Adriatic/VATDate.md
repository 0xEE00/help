# How To: Post documents with VAT Date

This topic describes how to post documents with VAT Date.

VAT Date is added to Sales and Purchase documents.

## Assisted Setup

To enable VAT Date functionality you need to set field "VAT Enabled" on table Core Setup that can be accessed through Assisted Setup.

1. Open Assisted Setup.
2. Choose Set up basic Adriatic Localization.
3. Program opens wizard where you accept warning & privacy note for extension.
4. Go to Next page.
5. Set option Adriatic Localization Enabled on CORE SETUP section.
6. Set option VAT enabled on VAT section.

## Report Selection

To view reports with added VAT Date you need to change report numbers on Report Selection page that is part of Sales Documents functionality.
1. Open page Report Selection - Sales.
2. Choose option Invoice on field Usage. Enter Report ID 13062751 to print Sales Invoice with additional data.
3. Choose option Credit Memo on field Usage. Enter Report ID 13062752 to print Sales Credit Memo with additional data.

## Post Sales Invoice

1. Open Sales Invoice and create new document.
2. Enter data about Customer Number, Posting Date, Document Date and choose items in lines. 
3. Enter VAT Date on General FastTab. 
4. Post Sales Invoice by choosing post action.

## Check and print Posted Sales Invoice

1. Go to Posted Sales Invoice and open posted document.
2. Check field VAT Date on General FastTab that was transferred during posted from unposted sales invoice.
3. Print Sales Invoice. Field VAT Date is added to printout of Sales Invoice.

## Post Purchase Invoice

1. Open Purchase document and create new document.
2. Enter data about vendor number, posting date, document date on General FastTab and choose items and all needed data on Lines FastTab. 
3. Enter VAT Date on General FastTab.
4. Post Purchase Invoice by choosing post on action.

## Check Posted Purchase Invoice

1. Go to Posted Purchase Invoice. Open document.
2. Check field VAT Date on General FastTab that was transferred during posting from unposted purchase invoice.
