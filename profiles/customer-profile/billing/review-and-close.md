# Review and Close

A bill is a combined list of bill items and payments with a balance of zero, which has been `closed` and assigned a number for reference. From the moment that a bill is closed, it is considered a legal document and cannot be amended.

Below, you'll find a detailed description about how to balance and close a bill in Mews Commander.

* [Settings](review-and-close.md#settings)
* [Privileges](review-and-close.md#privileges)
* [Balance](review-and-close.md#balance)
* [Close](review-and-close.md#close)
* [Items](review-and-close.md#items)
* [Tax](review-and-close.md#tax)

## Settings

There are a few settings that directly apply to invoicing, which can all be found in your `Accounting configuration`.

Within the `Bill closing` field, you will find three different options to choose from:

* **Always allow** - You may close bills at any time, even if the items on the bill have not yet been consumed \(for example a future stay\).
* **Only with consumed items** - You may only close bills that have consumed items on them. Therefore, if there is a future stay, the system will not allow you to close this bill until the day of checkout. This setting is extremely restrictive to front desk, and we do not recommend using it.
* **Only with consumed items half day window** - You may not close a bill with consumed items until the day of departure, however you can make changes to the booking up until departure. From the moment that a bill is closed, you cannot make changes to that booking because the items that are already on that closed bill would be affected by the change. This is the most flexible setting and we recommend this option over the others.

For more information check [`Accounting configuration`](../../../settings/finance-settings/accounting-configuration.md).

## Privileges

When setting up employee profiles, please note that within the `Workplace privileges` field, you must select `Modify closed bills` to give specific access to edit bills within the editable history window.

Mews would suggest that this privilege be given to a small number of employees, considering that it is easy to make mistakes and it can be difficult to resolve accounting-related errors.

## Balance

To balance a bill, navigate to the customer profile `Billing` screen of the guest. When ready for payment, move all `Unpaid items` to the `Open bill` of the customer.

In the `Open bills` section, you will see the `Balance` displayed in your default currency. This number represents the amount that the customer owes to the property in exchange for goods and services.

Look for the `+ Payment` and click on it. When creating a new payment, the full balance owed will automatically be pre-filled for any payment method you choose.

Once payment is successfully made, it will appear as a separate item in the customer's `Open bill`, specifying payment method and amount. Payments will always appear as a negative value, which will balance the positive value of the charged items, creating a final balance of zero.

## Close

Once the bill is balanced to zero, look for the `Close` button and click on it.

A new window will appear, where you will see the following fields to complete:

* **Customer** - Pre-filled with name of customer
* **Company** - Only present for Company bills. Search for and select the correct Company.
* **Tax ID Number** - Only present for Company bills. Used to identify a business entity for accounting purposes.
* **Address** - Customer's billing address, pre-filled with the address from the customer's profile. If different, search for the billing address in the Google address bar and select to automatically fill address details. This will be editable after the bill is closed.  
* **Options** - Only present for Company bills.
* **Display customer** - It may not be necessary to include the name of the customer if billing a company.
* **Notes** - Add any additional notes or information. This will be editable after the bill is closed.
* **Printer** - Select where you would like to print this bill. If a printer is selected, it will print automatically when you click `Close`
* **Bill Counter** - Select the bill counter that you'd like to use to close this bill.
* **Fiscal registry** - Select the correct fiscal registry integration that your accounting team is using. Please consult your accounting team for more information.

If all information has been reviewed and is correct, click on the `Close` button.

This bill is now successfully closed and you will be automatically redirected to the final closed document. Just below this button, you can find a full summary of all items included in the bill.

## Items

A complete list of each bill item is always included in closed bills. Items may include stay services as well as any products or additional services that the customer may have ordered. Bill items are expandable and collapsible using the `+` and `-` buttons, however when the invoice is printed or exported as a document, all items are fully listed in their expanded form.

Stay items include the following information on each line:

* **Reservation number** - Unique number generated by Mews and connected to the reservation
* **Customer** - Name of customer who made the reservation
* **Dates of stay** - Date of arrival and date of departure
* **Room category** - Room category used for duration of stay. Requested category may not be listed here.
* **Room number** - Space used for the duration of stay.

All items, including stay items, are listed with the following details:

* **Bill item** - Name of bill item according to property settings. Click on this title to be view reservation or order details for any item.
* **Created** - Date and time that item was created in system.
* **Tax rate** - Correct tax percentage for each item
* **Net** - Cost of item, excluding tax
* **VAT** - Tax alone, excluding item cost
* **Value** - Total cost, including tax and item cost
* **Totals** - Total sum listed under each respective column

> ### Mews Clues
>
> If some of these fields are not visible, the information may be collapsed. Click on the `+` and `-` buttons to see more or less.

Below the bill item summary, you will see a summary of all received payments, displayed with the following details:

* **Payment** - Payment type and card details, if applicable
* **Created** - Date and time that payment was created
* **Value** - Amount paid including the respective currency symbols. Received payments are listed as a negative value.
* **Totals** - Total sum of payments listed under the `Value` column

At the very bottom of the `Review and close` page, you will see `Balance`, which states a total balance owed including value and currency. This number should always be zero.

## Tax

Lastly, you will see a list of totals from all items and expenses on that particular bill, listed by tax rate. Balances include the following details:

* **Tax rate** - List of each tax rate included in bill items
* **Net** - Cost of bill items grouped by tax rate, excluding tax
* **VAT** - Tax alone, excluding item cost
* **Value** - Total cost of items per tax rate, including tax and item cost
* **Totals** - Total sums of Net, VAT, and Value

> ### Mews Clues
>
> As long as there are unpaid items on a customer profile, the system does not allow you to complete checkout. If it is necessary to check out a guest with unpaid items, you must select the box labeled `Check out with unbalanced bill`
>
> In your stay settings, under the `Options` section and the `Visit Options` field, you can select `Close balanced bills at checkout` option so that balanced open bills do not need to be manually closed each time

