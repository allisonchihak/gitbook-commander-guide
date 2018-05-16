# Accounting Ledger

The Guest Ledger Report is an overview of all guest profiles with unpaid/unsettled balances on their accounts.

Guests with future bookings are not problematic since the balances are not yet overdue, however if the account has an outstanding unsettled amount and no future bookings, the account will be highlighted with a "to be resolved" tag at the top of the report, indicating the need for action.

Below, you'll find an overview of each filter and feature that is visible on this report.

## Data Filters

* **Options**
  * **Highlight Open Payments** - Use this filter to highlight any accounts where an open/unsettled payment is posted. Please note that his option is applicable in countries where VAT is paid at the time of settling the bill \(Czechia, Germany, Denmark, etc.\) Open bills with a full payments, including deposits, should always be closed. 
* **Mode**
  * **Detailed** - See an itemized list including each individual item on customer accounts
  * **Grouped** - Shows only customer totals
* **Type**
  * **General** - All guest accounts with open balances including receivable payments \(i.e. invoices\)
  * **Guest Ledger** - All guest accounts with open balances
  * **Receivables** - All accounts with an open or overdue invoice payments
* **Group by** - indicates in which order you'd like the report variables to appear
  * **Accounting Category** - View in order of [accounting categories](../settings/finance-settings/accounting-categories.md) used at your property
  * **Consumption Date** - View in chronological order starting with the oldest charge until the most recent charge
  * **Customer** - View all customers who have open balances, appearing in alphabetical order by last name
  * **Service** - View report grouped by services ordered 
* **Tax** - Please note that a column for tax rate will be included in the `Accounting ledger` export
  * **Included** - Include tax in report
  * **Excluded** - View only revenue, without tax
* **Start Date & Time** - the selection of date/time, allows you to go back in time, and see the actual situation of the open balances at that time. This is important for accounting departments who run an end-of-month closure, and need to balance their books based on the opening balance and closing balance of the Guest Ledger.

## Data Columns

* **Group**
  * **Item** - Each `+` button indicates that the line is expandable. Click on the `+` to see each item description listed under customer name. Click the `-` button to hide the list of items again. 
  * **Consumed** - Date that item was consumed or posted on customer bill
  * **Closed** - Date that item was paid for and closed. This column will usually appear blank.
* **Consumed but Open**
  * **Revenue** - Items that have been consumed, but are still on an open bill. Please note that guests may have already departed from the hotel \(i.e. minibar items that are charged late to guest accounts\).
  * **Payments** - All payments made by customer that are still on open bills.
* **Closed but not Consumed**
  * **Revenue** - Items that have not yet been consumed but have already been paid for and closed on the bill prior to arrival \(i.e. a non-refundable accommodation payment for a guest staying in the future\). Mews would recommend against closing bills prior to departure date, as you are not able to change details of the booking once a bill is closed.
* **Deposit Ledger** - An overview of all pre-payments \(i.e. deposits\), against which no consumed revenue has been posted yet.
* **Guest Ledger** - An overview of all Consumed Revenue for which payment has not yet been received.
* **General Ledger** - A total sum of the Deposit Ledger and the Guest Ledger. Positive values represent the total amount of revenue that is due to be paid to the property. Negative values represent any amount that should be paid back to the customer.

## Mews Clues

* Each item in the accounting ledger is clickable. Click on any particular item to view the bill on which it was closed. 
* Please note that you may need to edit your [accounting categories](../settings/finance-settings/accounting-categories.md) or [service settings](../settings/sales-settings/services/) to allow for data to appear in more detail. 

