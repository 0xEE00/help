# How To: Post documents as Red Reversal

This topic describes posting of correction purchase and sales documents as red reversal when expected costs to G/L is enabled.

Functionality is enabled when extension is installed.

## General Ledger Setup

1. Open General Ledger Setup.
2. In field Show Amounts choose option All Amounts.

### Inventory Setup

1. Open Inventory Setup
2. Set field Post Neg. Transfers as Corr.
3. Set field Expected Cost posting to G/L.

## Post Purchase Receipt

1. Open Purchase Order and create new document.
2. Enter data about vendor number, posting date, document date on General FastTab and choose items and all needed data on Lines FastTab. 
3. Post Purchase Receipt by choosing post Receipt on action.

### Undo Posted Purchase Receipt

1. Open previously posted receipt.
2. Choose option Undo Receipt on button Functions to post correction of posted receipt.

## Check Posted Purchase Receipt

1. Go to Posted Purchase Receipt. Open document.
2. Choose button Navigate option on Process button. 
3. Open General Ledger Entries for posted purchase receipt. Program posted all ledger entries that were posted for expected costs as red reversal of original posted purchase invoice.

## Post Sales Shipment

1. Open Sales Order and create new document.
2. Enter data about customer number, posting date, document date on General FastTab and choose items and all needed data on Lines FastTab. 
3. Post Shipment by choosing post Ship on action.

### Undo Posted Sales Shipment

1. Open previously posted shipment.
2. Choose option Undo Shipment on button Functions to post correction of posted shipment.

## Check Posted Sales Shipment

1. Go to Posted Sales Shipment. Open document.
2. Choose button Navigate option on Process button. 
3. Open General Ledger Entries for posted Sales Shipment. Program posted all ledger entries as red reversal of original posted Sales Shipment.