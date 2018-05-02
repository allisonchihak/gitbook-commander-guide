# Adyen Integration

To create a new `Adyen integration`, navigate to the main integrations page using the following path:

* **Main Menu &gt; Settings &gt; Integrations**

Look for the `+` icon and click on it. Next, look for the `Accounting` section and click on `Adyen integration`. In a modal window, you will see the following fields to complete:

* **Default** - Pre-filled with `No`
* **Name**
* **Notification e-mail**
* **Descriptor** 
* **Default currency** 
* **Supported credit card types**
* **Username**
* **Password**
* **Public key**
* **Storage**
  * **Per gateway**
  * **Per merchant account**
* **Options**
  * **Allow refunding settled payments**
  * **Channel manager usage enabled**
  * **Distributor usage enabled**
  * **Gateway used externally**
  * **Navigator usage enabled**
  * **Send payment receipt copy**
* **Notes**

When all information is correctly entered, click `Create` and you will see the following additional fields:

* **Enabled** - Select this box to enable this integration
* **Created \(UTC\)** - Time that this integration was created
* **Updated \(UTC\)** - Time that integration settings were most recently updated

### Settings

* **Payment Gateway Accounts** - Click here to see all currently existing gateway accounts listed with the following details. 
  * **Currency**
  * **Token ID**
  * **Default**

To add a new account, look for the `+` button and click on it. You will see the following fields to complete:

* **Currency**
* **Token ID**

## Adyen Merchant invoice

A Merchant fee is the contractual rate for Mews Merchant payment processing. Once you receive your invoice for Merchant payments, you can follow the following steps to check the details:

Navigate to our `Payment Report` using the following path:

* **Main Menu &gt; Finance &gt; Payment report**

You can also access the payment report directly from the Mews dashboard under the `Finance` section.

Once you've arrived, choose the following options for your filters:

* **Mode** - Settled
* **Start date** - 1st day of the month you'd like to check \(e.g. 1st January\)
* **End Date** - 1st day of the next month \(e.g. 1st February\)
* **States** - Charged, Settled
* **Type** - Select all
* **Filter** - Gateway CC payments
* **Credit cards** - Select all
* **Currency** - Leave blank \(`-`\)
* **Employee** - Leave blank \(`-`\)
* **Integration** - Adyen Merchant Integration
* **Charge Currency** - Leave blank \(`-`\)

When all filter options are correctly chosen, click `OK` and then `Export`

Once you've downloaded the the Excel export, open the file and navigate to the `Credit Card Payments` tab. Look for column `P`, labeled `Fee total net`, which is where you'll find the amount charged by Mews for which you received the invoice.

> #### Mews Clues
>
> Please note that Mews commission is charged for both payments and refunds.

