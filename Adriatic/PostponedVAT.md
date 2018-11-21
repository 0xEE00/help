# How To: Post documents with VAT Date that is different than Posting Date

This topic describes how to post documents for VAT Date in different period. When posting standard there is no possibility to post VAT Entry in different period than is entered in Posting Date.

## Assisted Setup

To enable Postponed VAT functionality you need to set field "VAT Enabled" and "Use VAT Output Date"  on table Core Setup that can be accessed through Assisted Setup.

1. Open Assisted Setup.
2. Choose Set up basic Adriatic Localization.
3. Program opens wizard where you accept warning & privacy note for extension.
4. Go to Next page.
5. Set option Adriatic Localization Enabled on CORE SETUP section.
6. Set option VAT enabled on VAT section.
6. Set option Use VAT Output Date on VAT section.

## Post Purchase Invoice for domestic vendor

1. Open Purchase document and create new document.
2. Enter data about vendor number, posting date, document date on General FastTab and choose items and all needed data on Lines FastTab. 
3. Enter VAT Date on General FastTab that is different than entered Posting Date.
4. Post Purchase Invoice by choosing post on action.

## Check Posted Purchase Invoice for domestic vendor

1. Go to Posted Purchase Invoice. Open document.
2. Check field VAT Date on General FastTab that was transferred during posting from unposted purchase invoice.
3. Choose button Navigate option on Invoice button for posted Purchase Invoice. Delete Posting Date from Navigate page and choose option Find on button Process.
4. Open VAT Entries for posted purchase invoice. Program posted two VAT Entries: 
- one for Postponed VAT that was posted on original Posting Date, 
- one for Realized VAT that was posted Posting Date  that was entered in field VAT Date.

## Post Purchase Invoice for EU vendor

1. Open Purchase document and create new document.
2. Enter data about vendor number, posting date, document date on General FastTab and choose items and all needed data on Lines FastTab. 
3. Enter VAT Date on General FastTab that is different than entered Posting Date.
4. Enter VAT Output Date on General FastTab that is different than entered VAT Date.
5. Post Purchase Invoice by choosing post on action.

## Check Posted Purchase Invoice for EU vendor

1. Go to Posted Purchase Invoice. Open document.
2. Check field VAT Date and VAT Output Date on General FastTab that was transferred during posting from unposted purchase invoice.
3. Choose button Navigate option on Invoice button for posted Purchase Invoice. Delete Posting Date from Navigate page and choose option Find on button Process.
4. Open VAT Entries for posted purchase invoice. Program posted four VAT Entries: 
- two for Postponed VAT that was posted on original Posting Date, 
- one for Realized VAT that was posted on Posting Date that was entered in field VAT Date.
- one for Realized VAT that was posted on Posting Date  that was entered in field VAT Output Date.
5. Program posted additional VAT entries for posting Reverse VAT. Standard functionality enables posting only one VAT Entry for Reverse VAT.