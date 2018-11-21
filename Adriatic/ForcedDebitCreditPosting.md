# How To: Post G/L Accounts only on Debit or Credit Amount.

Most financial transactions are posted to the general ledger as they are entered on documents or journals. For example if Amount is entered on Journal window in Debit Amount, than amount is posted on Debit Amount in General Ledger Entry.
For some accounts there is need to post amount only on one side, for example Credit amount. For this cases we can set posting only for certain side on G/L Account card.

## Assisted Setup

To enable Forced Debit or Credit posting functionality you need to set Adriatic Localization that can be accessed through Assisted Setup.

1. Open Assisted Setup.
2. Choose Set up basic Adriatic Localization.
3. Program opens wizard where you accept warning & privacy note for extension.
4. Go to Next page.
5. Set option Adriatic Localization Enabled on CORE SETUP section.
6. Set option Force Debit/Credit on GENERAL LEDGER section.
7. Choose button Finish to confirm setup.

## Setup default posting on G/L Account Card

1. Open G/L Account Card.
2. Go to General FastTab.
3. Choose Debit/Credit from options: 
Both|Posting of all general ledger entries as they are entered on General Journal.
Debit|Posting all general ledger entries only in Debit Amount.
Credit|Posting all general ledger entries only in Credit Amount.

## Post Journal

1. Open General Journal.
2. Enter G/L Account.
3. Enter Debit or Credit Amount.
4. Choose the Post action.

## Check Ledger Entries

1. Open General Ledger Entries.
2. Check if amount is posted on Debit or Credit Amount, that was set on G/L Account Card as default posting.

## Post Sales Credit Memo

1. Open Sales credit memo and create new document.
2. Enter data about customer number, posting date, document date on General FastTab and choose G/L Account and all needed data on Lines FastTab. 
3. Post Sales Credit memo by choosing post on action.

## Check Posted Purchase Credit Memo

1. Go to Posted Sales Credit Memo. Open document.
2. Choose button Navigate and open General Ledger Entries.
3. Amounts are posted on Debit or Credit Amount, as defined on G/L Account Card.

## Post Purchase Credit Memo

1. Open Purchase credit memo and create new document.
2. Enter data about vendor number, posting date, document date on General FastTab and choose G/L Account and all needed data on Lines FastTab. 
3. Post Purchase credit memo by choosing post on action.

## Check Posted Purchase Credit Memo

1. Go to Posted Purchase Credit Memo. Open document.
2. Choose button Navigate and open General Ledger Entries.
3. Amounts are posted on Debit or Credit Amount, as defined on G/L Account Card.
