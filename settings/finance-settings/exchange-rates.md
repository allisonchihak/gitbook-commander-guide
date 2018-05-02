# Exchange rates

### Finance Settings:

## Exchange Rates

Below, you will find an overview of all features regarding your property's exchange rates. Your property may support as many currencies as you would like, however your default currency must be chosen during your property's initial setup. You can find your default currency displayed under the 'Globalization' section in the [Main Property Settings](../main-property-settings/), however this is only editable using a Global Admin account.

On the exchange rates screen, you will find a list of all currencies that your property has chosen to support, each with its own column. They will be listed in alphabetical order with the following information:

* **Currency** - The 3-letter abbreviation of the currency, such as 'EUR', 'GBP', or 'USD'
* **Is enabled** - Selected checkboxes are enabled, or deselect to disable
* **To \[Default Currency\]** - Exchange rate of that currency to default currency
* **From \[Default Currency\]** - Exchange rate of default currency to that currency

The Mews Commander works with a multi-currency environment, meaning that you can follow a different sales currency \(or multiple sales currencies\) that will at some point be converted to the local currency. If you do not regularly update the exchange rate, it is likely that exchange rate differences will occur.

If you would like to update your exchange rates manually, you can set those rates on this page. However, to avoid problems with exchange rate differences, Mews would recommend hotels change their exchange rate a minimum of one time per month. Alternatively, you can use the [Exchange Rate Provider Integration](../integrations/create-an-integration/accounting/exchange-rate-provider-integration.md) to create automatic updates.

If an exchange rate difference occurs, causing a discrepancy in the customer's billing, you will see a notice on the [customer's billing screen](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/profiles/customer-profile/customer-profile-sections/billing.md). If you see this notice, it is a result of the system automatically calculating the amount and posting the correction to ensure the correct handling of the exchange rates. Discrepancies are most commonly caused when charges are paid in advance for future bookings, as with non-refundable rates for example.

### Add an Exchange Rate

Navigate to the exchange rate settings using the following path:

* Main Menu - Settings - Property - Finance - Exchange Rates

Look for the + button in the top right corner and click on it.

The next screen will present you with a drop-down menu including all currencies supported by Mews Commander, listed in alphabetical order. Select the currency that you'd like to add to your property and click 'Create'. This will take you back to your list of currencies, where you will should see the new currency in the updated list.

Once you've added the new currency, the exchange rate will not be automatically set, and you will see the the rates are listed as 1 to 1. To update this list, manually enter the rates you'd like to use, or wait until the automatic update time set in the [Exchange Rate Provider Integration](../integrations/create-an-integration/accounting/exchange-rate-provider-integration.md).

