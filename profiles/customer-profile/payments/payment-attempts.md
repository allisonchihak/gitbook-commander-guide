# Payment Attempts

> ### In this article:
>
> * [About](payment-attempts.md#about)
> * [Attempts](payment-attempts.md#attempts)

## About

In this section of the payments tab, you can see all payment attempts that were not successfully completed.

During the charging process, if we find that there is something wrong with the provided card information \(i.e. expired, blocked by card holder, incorrect CVV code, etc.\), that card will be marked with a `Disabled` state badge, which is visible from the [customer's payment screen](./).

Disabled cards are not chargeable but will remain on the customer's profile as a reference. Customers must contact their bank for more information about the reason for the card's decline.

## Attempts

The following information is visible with each failed payment:

* **Type** - Payment type including card type and last 4 digits in case of card transactions
* **Identifier** - Any unique identifying number that corresponds to this transaction
* **Created** - Date and time that transaction was attempted, plus employee who created the transaction
* **Cashier** - In case of cash payments, this is the name of the cashier where payment was taken. 
* **Bill** - Corresponding bill number if transaction is connected with a closed bill or invoice. 
* **Notes** - Any notes or additional information. This often includes the reason for the failure.
* **State** - Current state of transaction. This should read `Failed`. Hover over the badge to see the original gateway value.
* **Value** - Amount that was charged including original currency and default currency values
* **Actions** - Applicable actions will appear in this column as needed. Hover over any action buttons to see their label.

If any transaction was not successful, you will be able to find it here. To retry for a successful payment, you may need to completely recreate it.

