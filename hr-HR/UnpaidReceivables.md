# How To: Prepare Unpaid Receivables Report

This topic describes the report in Business Central that you can use to prepare information about Customer overdue and unpaid receivables to Tax authorities. For this purpose, the government has made form that is called OPZ-STAT-1 (Overdue and uncollected receivables). The report contains data on issued invoices which were not collected/paid within the legal or agreed period.

## Assisted Setup

To enable Unpaid Receivables functionality you need to set up fields in advanced Adriatic Localization that can be accessed through Assisted Setup.

1. Open Assisted Setup.
2. Choose Set up advanced Adriatic Localization.
3. Program opens wizard.
4. Go to Next page.
5. Choose localization country HR.
6. Enable option Unpaid Receivables Enabled.
7. Go to next page.
8. Check or correct data about company.
9. Go to next page.
10. Enter Data Start Balance Date that will be used for overdue and unpaid receivables.
11. Choose button Finish to confirm setup.

## Setup Date for Unpaid Receivables

1. Open Sales & Receivables Setup.
2. Go to General FastTab.
3. Enter Extended Data Start Balance Date for those transactions that indicate the recording of the opening balance or transactions that are posted trough general journal and that the system did not register the original amount and the amount of VAT it is necessary to enter this information manually. To accrue what are the items in the G/L setup must enter the posting date of the opening balance, which indicates that on that date and all dates before he recorded the initial state and that is for them possible/necessary to enter the original amount and the amount of VAT.

## Post entries with extended data

1. Open General Journals
2. Enter lines for opening balance for Customers.
3. Enter fields: Open Amount (LCY) Without Unrealized Exch. Rate Adj, Original Document Amount (LCY) and Original Amount (LCY) for each entry.
4. To post the journal, choose the Post action.

## Print report OPZ-STAT-1

1. Open Overdue and Uncollected Receivables report.
2. Enter Until Due Date that Tax authority prescribed (every three month: March 31, June 30, September 30, December 31). 
3. Choose Company Official to print User on report.
4. Choose Preview or Print as PDF.
