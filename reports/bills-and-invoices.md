# Bills and Invoices

The Bills and Invoices Report is an overview of all issued invoices and closed bills. This is a great resource if you need to find a bill after a customer's departure for reprinting or reviewing.

This report is split into two sections, Invoices first followed by Bills. Invoices are ordered numerically, from lowest number to highest, while bills can be found both numerically and chronologically.

This report is based on the selected interval, which is always displayed as part of the report header, just next to the title. If you know the bill number, you can search by bill number at the top of the screen. Alternatively you can use the date and time pickers to select a specific period during which the bill or invoice was closed and therefore narrow down your search.

Below, you will find an overview of all filters and features available in this report.

## Filters

* **Filter**
  * **Closed** - if you only would like to see closed invoices and bills
  * **Invoice due date** - all invoices that match the due date in the date selected
  * **Invoice paid** - all invoices that have been paid
* **Start date & time** - Date and time that report data begins. 
* **End date & time** - Date and time that report data ends.
* **State** - Choose a filter to see documents in that particular state
  * **Closed bill** - Only bills that have been closed
  * **Overdue invoice** - Invoices that are overdue and must be settled urgently
  * **Paid invoice** - Invoices for which payment has already been received
  * **Unpaid invoice** - Invoices for which payment has not yet been received
* **Options**
  * **Load Values** - Load the value of bills and invoices, allowing you to quickly see the total amount of outstanding revenue; this option will add two additional columns to the report, labeled `Revenue` and `Receivable value`
* **Minimum value** - Filter out bills or invoices above a certain value
* **Company** - Search for bills and invoices assigned to a particular company
* **Counter** - Select a counter from the drop-down menu to see only bills and invoices closed through there

## Invoices

Invoices are displayed with the following information:

* **Invoice number** - Click on this invoice number to be taken directly to the closed document
* **Customer** - Click on the customer name to be taken directly to customer profile
* **Company** - Company name an tax ID. This column will be blank if the invoice was not assigned to a company.
* **Issued** - Date and time that the invoice was issued plus the name of the employee who reviewed and issued the invoice
* **Due date** - Date that payment should be received by
* **Paid** - If already paid, date and time that payment was received. 
* **State** - This badge will contain the state of the current transaction, marked with the appropriate Mews action color
  * **Unpaid** - Invoice has been issued and not paid yet; displayed in blue, indicating that action is required
  * **Overdue** - Invoice has not paid yet, but it is past due date; displayed in orange, indication that urgent action is required
  * **Paid** - Invoice has been paid and settled; displayed in black, indicating that no action is required
  * **Closed** - Issued invoice without tracking enabled
* **Notes** - Any additional billing notes that you may want to include
* **Actions**
  * **Billing Icon** - For overdue or unpaid invoices, click on this to go directly to the customer's billing page

If the `Load balances` option is selected, you will see these two additional columns:

* **Revenue** - Total value of this item
* **Receivable value** - Outstanding balance to be received

## Bills

Bills are displayed with the following information:

* **Bill number** - Click on this invoice number to be taken directly to the closed document.
* **Customer** - Click on the customer name to be taken directly to customer profile.
* **Company** - Company name an tax ID. This column will be blank if the invoice was not assigned to a company.
* **Closed** - Date and time that the bill was closed plus the name of the employee who reviewed and closed the bill
* **State** - This badge will contain the state of the bill. This should always be marked as 'Closed'
* **Notes** - Any additional billing notes that you may want to include
* **Actions** - If a billing icon is displayed, click on this to be taken directly to the customer's billing page

If the `Load balances` option is selected, you will see these two additional columns:

* **Revenue** - Total value of this item
* **Receivable value** - Outstanding balance to be received

## Settings

As an optional feature, properties can choose how they'd like their deposits to be displayed on bills. Navigate to your `Accounting configuration` using the following path:

* **Main Menu &gt; Settings &gt; Property &gt; Finance &gt; Accounting configuration**

Look for `Options` and look for the following item in the drop-down menu:

* **Receivable tracking enabled** - Select this option to track the payments for outstanding invoices and their respective due dates; please note that if this option is not enabled, you cannot view revenue and receivable values in this report

> ### Mews Clues
>
> Please note that invoicing must first be enabled as an external payment type for the aforementioned setting to apply. Within your accounting configuration, select `Invoice` under the `Enabled external payment types` drop-down.

