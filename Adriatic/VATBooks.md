# How To: Report VAT to a Tax Authority

This topic describes the reports in Business Central that you can use to submit information about value-added tax (VAT) amounts for sales and purchases to tax authorities in your region. 

VAT Books functionality is used in addition to the periodic VAT statements that company submit in order to settle VAT. Tax Authority requires to submit periodic reports of transactions including VAT. VAT books for Tax Authority and internal demand can be created through VAT books setup. Primary aim of this feature was to simplify and improve application setup and make it user friendly.

## Create new VAT Book

1. From Accountant Role Center select VAT Books from the ribbon. 
2. Enter new code and description for newly created VAT Book by choosing New from the ribbon.

### Columns Setup
To create columns that will be printed on VAT Book choose Column Name Setup on Process action:
1. Enter Column number to define sequence of columns that will be printed in VAT Books.
2. Enter Description to define columns that will be printed in VAT Books.

### VAT Book Groups
Choose New to create new VAT Book Groups:
1. Enter Code to define VAT Book Group.
2. Enter Book Link Code.
3. Enter Description for VAT Book Group.
4. Choose Group Type for VAT Book Group to define how VAT Books should be printed:
- VAT Entries to print detailed VAT Book.
- Total to print only sum of VAT Entries.
5. Choose Totaling from list of VAT Books if Group Type Total is chosen. This function is used only in Serbia.
6. Enter Tag Name to prepare export of VAT Book. This function is used only in Serbia.
7. Choose Include Columns from list of preset Columns. This function is used only in Serbia.
8. After line is inserted choose VAT Identifiers by choosing Process in ribbon. Enter list of all VAT Identifiers that will be printed on VAT Books.

### VAT Book Setup
VAT Book Setup defines content of VAT Books. For each combination of VAT Book Groups Code and VAT Identifier, you can define which columns from VAT Entries will be printed.
1. Go to columns of VAT Book.
2. Choose Operator that defines how value from VAT Entries will be shown.
3. Choose Value that defines column in VAT Entries that will be shown.
4. Choose Condition to filter VAT Entries by additional fields that are in VAT Entries such as Type: Purchase or Sale.

## To preview data
VAT Book can be previewed by choosing button VAT Review on Process.
1. Choose period to filter date of VAT Book in field View by.
2. Enter Date Filter to filter VAT Entries by Posting Date.

## To export data
- VAT Book can be printed by choosing button VAT Book on Report. Before printing choose VAT Book Code and additional filters if needed.
- VAT Book can be exported to XML by choosing button Export to XML. Before exporting enter Date Filter, PPPDV Date and Responsible Person. This function is used only in Serbia.
- VAT Book can be exported to TXT by choosing button Export to TXT. Before exporting choose VAT Book Code and additional filters if needed. This function is used only in Slovenia.
