# How To: Post documents with reverse charge VAT in two entries

This topic describes how to post documents for Reverse Charge VAT in two entries.

## Assisted Setup

To enable Reverse Charge Posting functionality you need to set field "VAT Enabled" and "Use VAT Output Date"  on table Core Setup that can be accessed through Assisted Setup.

1. Open Assisted Setup.
2. Choose Set up basic Adriatic Localization.
3. Program opens wizard where you accept warning & privacy note for extension.
4. Go to Next page.
5. Set option Adriatic Localization Enabled on CORE SETUP section.
6. Set option VAT enabled on VAT section.
6. Set option Use VAT Output Date on VAT section.

## Post Purchase Invoice

1. Open Purchase document and create new document.
2. Enter data about vendor number, posting date, document date on General FastTab and choose items and all needed data on Lines FastTab. 
3. Enter VAT Date and VAT Output Date on General FastTab.
4. Post Purchase Invoice by choosing post on action.

## Check Posted Purchase Invoice

1. Go to Posted Purchase Invoice. Open document.
2. Check field VAT Date and VAT Output Date on General FastTab that was transferred during posting from unposted purchase invoice.
3. Choose button Navigate and open VAT Entries for posted purchase invoice.
4. Program posted additional VAT entry for posting Reverse VAT. Standard functionality enables posting only one VAT Entry for Reverse VAT.