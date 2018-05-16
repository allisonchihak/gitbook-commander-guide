# Credit Cards

Mews does not store full credit card data. For data security reasons, we store only the last 4 digits of guests' cards and the card type.

In order to innovate the way payments are taken within the PMS, we use integrations with Adyen and Stripe. These companies allow storage of guest cards directly in the Mews Commander, once a card is stored in the system, this allows direct charging from the PMS, without requiring external credit card machines.

> * [Credit Cards](credit-cards.md#credit-cards)
> * [Add](credit-cards.md#add)
> * [Delete](credit-cards.md#delete)

## Credit Cards

Here, you will see a list of credit cards that the customer has used to make payments. The following information is visible from the payments screen:

* **Type** - Credit card type
* **Number** - Credit card number. Please note that only the last 4 digits are visible and the rest are marked out with stars. For some cards, you may also see the first 6 digits, but you will never see the full readable card number. 
* **Name** - Name on card. Please note that since we do not ask for the name, this field will remain blank.
* **Expiration Date** - Date that the card will expire and become invalid
* **Format**
  * **Physical** - Card was physically present on the property at the time of transaction.
  * **Virtual** - Card information was received via telephone or by a third party
* **Identifier** - a unique series of letters and numbers assigned to each transaction for easy identification
* **Created** - Date and time that transaction was created, plus employee who created the transaction
* **Notes** - Any additional notes that may be included with transaction. These cannot be added manually but will automatically be included in case there is any note from the credit card provider. 
* **State** - In case of gateway cards, you will be able to see the if the card is currently chargeable.
* **Actions** - Each icon represents a different action. Hover over the icons to see their label.
  * **Preauthorization** - create a new preauthorization for an existing card or select 'New credit card' from the drop-down list to add a new card
  * **Credit card payment** - Make a payment with an existing credit card or select 'New credit card' to add a payment with a different card
  * **Delete** - Remove credit card details from the customer's profile. Please note that once you've deleted these card details, you must reenter that information in order to use the card again in the future. 

## Add

To add a new credit card, click on the '**+ Credit Card**' button on the payment screen. From here, you will presented with two options:

**Online Chargeable Credit Card**

This left section is for online cards using Stripe & Adyen.

* **Provider** - Pre-filled with Adyen
* **Credit Card Number** - The full 16-digit number is required for this field. Please note that after information has been submitted, only the last 4 digits will be visible.
* **Expiration** - Date that the card will expire and become invalid
* **Format**
  * **Physical** - Card was physically present on the property at the time of transaction
  * **Virtual** - Card information was received via telephone or by a third party

**Credit Card**

This right-hand side is for cards that are being charged manually via an external terminal.

* **Type** - Select credit card type from the drop-down list
* **Last 4 digits** - The last 4 digits of the card number
* **Name** - Name on card. Please note that since we do not ask for the name, this field will remain blank.
* **Expiration date** - Date that the card will expire and become invalid
* **Format**
  * **Physical** - Card was physically present on the property at the time of transaction
  * **Virtual** - Card information was received via telephone or by a third party

Once you have stored a credit card, you will see an "Identifier" which indicates that the card has been verified by the bank and has now become chargeable through the system

Each card will appear in a list in this credit cards section and will be available in the drop-down options when this customer makes any future payments.

## Delete

In the list of cards, look for the trash can icon under the 'Actions' column and click on it.

When you see the confirmation box, click `Delete`

When you return to the Payments page, you will no longer see this card in the Credit Cards section and it will no longer appear in drop-down options for card payments.

