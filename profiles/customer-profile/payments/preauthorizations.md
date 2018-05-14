# Preauthorizations

Preauthorizations are the practice within the banking industry of verifying electronic transactions made with a debit card or credit card. Banks will hold this balance as unavailable until either the merchant charges the transaction \(also called settlement\) or the hold "falls off", meaning that the balance becomes available again.

## Past and Current

Here, you can see a list of preauthorizations, both past and current. The following information is visible from the payments screen:

* **Credit card** - Card type and obfuscated card number revealing only the last 4 digits of the card number
* **Sequence code** - Any additional code used to identify this transaction; please consult with your accounting team for further information
* **Code** - Three-digit CVV code
* **Identifier** - a unique series of letters and numbers assigned to each transaction for easy identification
* **Expiration** - Date that the preauthorization will expire and funds will be released
* **Created** - Date and time that preauthorization was created, plus employee who created the transaction
* **Notes **- Any additional notes or information included for the transaction
* **State**
* * **Chargeable **- A successfully created preauthorization that is ready to be charged; this badge is displayed in blue indicating required action
  * **Charged **- When a preauthorization is successfully charged, badge will change black and will be labeled 'Charged'. Hover over this badge to see originally preauthorized amount and the charged amount. You will also see this transaction listed in the `Payments` section, with a matching `Identifier`** **number. 
  * **Canceled **- When a preauthorization is canceled, state badge will change to a grey color and will be displayed with 'Canceled'. Hover over the badge to see the originally canceled amount and the date and time of cancellation. 
* **Value** - The monetary value of the original preauthorization, including currency
* **Actions**
  * **Cancel **- Click this button to cancel a preauthorization. Please note that it may take 3-5 days for the bank to release funds that were being held for this preauthorization. 
  * **Charge **- Click this button to charge the preauthorized amount. You must confirm the amount that was originally preauthorized, but it is possible to charge only a partial amount from the original value. Once charged, the transaction will appear in the Payments section. You can also click on the + Payment button and select 'Charge preauthorization' if there is one that's already chargeable. 

## Create

To create a new preauthorization, click the `+Preauthorization` button on the payments screen. If you are using a card that is not on file, you will need to complete the following information. You'll have two options:

**Charge online via Adyen:**

For online cards charged using Stripe & Adyen, you can use the `Charge online` form:

* **Provider** - pre-filled with `Mews` or `Adyen`
* **Credit Card** - Choose from a previously used card already on file or select to add a new card
* **Credit Card Number** - The full 16-digit number is required for this field. Please note that after information has been submitted, only the last 4 digits will be visible.
* **Expiration** - Date that the card will expire and become invalid
* **Format**
  * **Physical** - Card was physically present on the property at the time of transaction
  * **Virtual** - Card information was received via telephone or by a third party
* **Currency** - Select the currency that you'd like to charge. This will be pre-filled with your default currency
* **Amount** - Enter the monetary value of the preauthorization, not including currency symbols
* **Notes** - Include any notes or additional information as necessary

When all fields are correctly completed, click `Create via internet` and you will see the preauthorization appear in the `Payment` section, which is then available for charging at the desired time. 

**Add manually charged payment**

For cards being charged manually via an external terminal that is not associated with Mews Commander, you can use the `Manually charged` form:

* **Credit Card** - Select `New credit card` or a previously used card, identified by the card type and first 6 and last 4 digits
* **Type** - Select credit card type from the drop-down list
* **Last 4 digits** - The last 4 digits of the card number
* **Expiration** - Date that the card will expire and become invalid
* **Name** - Full name exactly as it appears on card
* **Format**
  * **Physical **- Card was physically present on the property at the time of transaction
  * **Virtual **- Card information was received via telephone or by a third party
* **Currency** - Select the currency that you'd like to charge. This will be pre-filled with your default currency.
* **Amount** - Enter the monetary value of the preauthorization, not including currency symbols
* **Code** - Three-digit CVV code
* **Receipt Identifier** - Include any identifying code produced by the terminal receipt; please consult with your accounting team for further information
* **Sequence Code** - Any additional code used to identify this transaction; please consult with your accounting team for further information
* **Notes** - Include any notes or additional information as necessary

When all fields are correctly completed, click `Created by terminal` to complete the transaction on your external device. 

## Charge

Once the card information has been submitted, you will see it appear under the preauthorizations section.

To charge the preauthorization, click the arrow icon under the `Actions` column. A window will appear with the following information:

* **Provider** - Pre-filled with `Mews`
* **Preauthorization** - Preauthorization, card type, obfuscated card number \(original amount with currency\)
* **Amount** - Pre-filled with originally preauthorized amount. If you would like to charge a different amount than what was originally preauthorized, you may enter that amount here. Please note that you can charge less than the original amount, but you cannot charge more. 

If all information is correct, click the `Charge` button.

At this time, the badge previously labeled `Chargeable` will change to `Charged`, the icons previously under the `Actions` column will disappear, and you will see this transaction appear under the `Payments` section.

To locate the correct an already charged preauthorization, compare the `Identifier` numbers, which will be the same under both the `Preauthorizations` and `Payments` sections.

## Automate

Navigate to your rate group settings to automate preauthorizations, which can then be processed later at the time of your choosing. Below, you will find a list of settings that directly apply to automating your preauthorizations. To select these options, navigate to your rate group settings using the following path:

* **Main Menu &gt; Settings &gt; Services &gt; Stay &gt; Rate groups**

Click on the rate groups that you would like to automate, and within each one, look for the following settings:

* **Settlement action** - Desired action at the time of settlement trigger. Please note that settlement action only applies to automatic settlements.
  * **Create preauthorization** - Preauthorization will be created for the card on file at the time of settlement trigger including any applicable offset, however card will not be charged until manually processed by an employee

Please note that if you choose to automate your preauthorizations, you will also have to complete the rest of the fields concerning automatic settlement as are fully described in our article about [`Rate groups`](../../../settings/sales-settings/services/stay-services/rate-groups/).

## Cancel

If you would like to release the preauthorization, select the `X` button under the `Actions` column and the bank will be notified to release the transaction. Please note that it may take 3-5 business days for Adyen to release the transaction.

> ### Mews Clues:
>
> * Mews does not store full credit card data. For data security reasons, we store only the last 4 digits of guests' cards and the card type.
> * You can also use the `+ Payment` button to charge a preauthorization that has already been created. However, you cannot create a new preauthorization from this button.
> * If you charge a different amount than what was originally preauthorized, the original amount will appear here \(under the `Preauthorizations` section\) but the updated and correctly charged amount will appear under the 'Payments' section.
> * If you charge the preauthorization partially, the remaining amount will be released to the guest account automatically
> * Hover over the action icons and the state badges for a moment to see other currency values or to see labels in case you've forgotten what the icon means.

