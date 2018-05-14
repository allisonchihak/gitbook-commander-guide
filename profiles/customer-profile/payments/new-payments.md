# New Payments

To create a new payment from the Payments tab of the Customer profile, click on the `+ Payment` button and select the correct type of payment. If you have already created a chargeable preauthorization, you will see the additional option to [`Charge preauthorization`](preauthorizations.md).

Scroll down to find a detailed description of the payment processes for each method.

* [Cash](new-payments.md#cash)
* [Credit Card](new-payments.md#credit-card)
* [External](new-payments.md#external)
* [Terminal](new-payments.md#terminal)

## Cash

To create a new payment, click on the `+ Payment` button and select `Cash payment`

Next, you'll see a screen that includes all of the currencies that your property has chosen to enable, listed in alphabetical order.

In each row, you will see the following information:

* **Cashier** - Select the cashier that you are using. Please note that only the cashiers where the selected currency is enabled will appear in the drop-down list.
* **Currency** - Select the correct currency of the payment from the drop-down menu; please note that only enabled currencies for this cashier will appear as options
* **Amount** - Monetary amount not including currency symbols
* **Notes** - Add any additional notes or information that you'd like to include

If you select a currency that is not your default currency, you will also see the following two fields appear:

* **Exchange Rate** - Exchange rate to your default currency
* **Default currency** - The equivalent amount of your default currency

When all information is filled in, click the `Create` button.

At this time, you will be taken back the the `Payments` page of the customer's profile and this transaction will be visible under the `Payments` section of this page, with `Type` listed as `Cash payment`.

If you've chosen a currency that is not your default, it will first be listed as the originally accepted currency and then converted into your default.

> ### Mews Clues
>
> Please note that payments created directly from the payments screen will appear on the `Billing` section of the customer profile, but will not be connected to any particular bill.

## Credit Card

To create a new payment, click on the `+ Payment` button and select `Credit card payment`

On this screen, you will first see a list of current preauthorizations that are chargeable, followed by two different payment options.

**Charge online via Mews Merchant:**

* **Provider** - pre-filled with Mews
* **Credit card** - Choose a previously used card or select to add a new card. If charging a card on file, several of these fields will not appear. 
* **Credit card number** - Full 16-digit card number. Please note that Mews does not store full credit card details after processing.
* **Expiration** - Date when card becomes invalid
* **CVV** - 3 or 4-digit security code
* **Format** 
  * **Physical** - A card that is physically present at time of charging
  * **Virtual** - A temporarily valid card issued via an OTA and containing only the booking value
* **Currency** - Select the currency that you'd like to charge. This will be pre-filled with your default currency.
* **Amount** - Enter the monetary value to charge, not including currency symbols

When all details are correctly entered, click `Charge via internet` to finish payment.

**Charge online via Adyen:**

* **Provider** - pre-filled with Adyen
* **Credit Card** - choose from a previously used card already on file or select to add a new card
* **Currency** - Select the currency that you'd like to charge. This will be pre-filled with your default currency.
* **Amount** - Enter the monetary value to charge, not including currency symbols

Please note that if charging a new card, additional fields may appear for completion. When all details are correctly entered, click `Charge remotely` to finish payment.

**Add manually charged payment:**

Use this option if you are using an external payment terminal that is not associated with Mews Commander.

* **Credit Card** - Select a previously used card from the drop-down menu or select `New credit card`
* **Type** - Select the correct card type from the drop-down menu; please note that this drop-down will only display options that have been enabled in your `Accounting configuration` settings in the `Accepted manual credit card types` field. 
* **Last 4 digits** - Enter the last 4 digits of the full card number
* **Expiration** - Date when card becomes invalid
* **Name** - Pre-filled with customer name
* **Format** 
  * **Physical** - A card that is physically present at time of charging
  * **Virtual** - A temporarily valid card issued via an OTA and containing only the booking value
* **Currency** - Select the currency that you'd like to charge. This will be pre-filled with your default currency.
* **Amount** - Enter the monetary value to charge, not including currency symbols
* **Receipt Identifier** - A unique number created by the manual terminal to identify transactions later
* **Notes** - Notes will appear in the `Payments` section of customer profile, visible in parentheses after payment details and also in the `Notes` column of the same section

When all details are correctly entered, click `Created by terminal` to finish payment.

## External

To create a new payment, click on the `+ Payment` button and select `External payment`

Next, you'll be taken to a screen with the following fields:

* **Currency** - Select from the list of currencies that your property has enabled
* **Amount** - Enter the monetary amount of the payment
* **Type** - Select the external payment type from the list of your property has enabled
* **External Identifier** - Use this field if you are using an accounting service or external terminal that provides an identifier

When all information is properly completed, click the `Create` button.

At this time, you will be taken back the the `Payments` page of the customer's profile and this transaction will be visible under the `Payments` section of this page, with `Type` listed as `External payment`, followed by the specific payment type.

## Terminal

Use this option if you are using an external payment terminal that is not directly connected with Mews Commander.

To create a new payment, click on the `+ Payment` button and select `Payment terminal`

Next, you'll be taken to a screen with the following fields:

* **Payment Terminal** - select which terminal you are using from the drop-down menu
* **Currency** - Select the correct currency from your list of enabled currencies
* **Amount** - Enter the correct monetary value of the payment you are accepting

When all information is properly completed, click the `Create` button.

At this time, you will be taken back the the `Payments` page of the customer's profile and this transaction will be visible under the `Payments` section of this page, with `Type` listed as `Payment terminal`, and followed by the specific payment type.

