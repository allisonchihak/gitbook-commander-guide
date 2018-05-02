# Accounting configuration

Accounting configuration is where you can manage all of your accounting-related settings.

When setting up Accounting configuration, Mews would advise that you consult with your accounting team for further guidance, since this configuration would be most important to them and it may not be necessary to complete all available fields.

Below, you will find a description of each item located on your Accounting configuration page:

* **Tax precision** - Some accountants in hotels prefer very specific precision of their numbers in reports. For example if a number is 2.342453 without having the tax precision set, we will try to keep this number as complete as possible. However if you set the tax precision to 2, it will cut the number off at 2.34 in all reports and calculations. Once this setting is switched on, all postings from that point forward will follow this tax precision, and they cannot be reverted. So be careful with this setting to be sure this is what you would like to achieve.
* **Editable history window** - The Editable history window is a setting that determines how far you can go back in time when editing minor reservation details. This window is maximum 7 days, and it ONLY allows modification of items that are not on closed bills yet. Reservations with items on closed bills CANNOT be modified in any way. The only way to correct closed bills, is by posting a manual rebate \(with reasoning\), which will be tracked as a separate transaction.

  As our system does not have a Night audit, the Editable history window is necessary to deal with no-shows and walk-ins during the next morning.

  Although, the Editable history window is useful, it should be handled carefully, as a negligent use of it can cause issues with your accounting data.

  For instance, if you change information about reservations in the past, the integration partners would not necessarily proceed with reconciliation, therefore, serious accounting errors can be caused.

As new bookings are made, clickable dates will be restricted to your editable history window settings. If you are working with multiple properties, dates will be visible according to the maximum editable history window settings within your properties.

* **Options**
  * **Optional credit card payment details** - Selecting this option means that Mews will not require the hotel to complete the receipt identifier details when posting manual credit card payments. Selecting this option will significantly speed up the check-in and checkout processes. This option is only applicable for payments that are made on an external terminal and then manually input later using information from the terminal receipt. Payments made via the Mews Payment gateway \(Adyen/Stripe\) include all payment details, which are automatically recorded by our system
  * **Receivable tracking enabled** - This will allow you to track the payments for outstanding invoices and their respective due dates. You can find this information in the [Bills and Invoices](../../reports/bills-and-invoices.md) report. If you have enabled "Invoice" as an external payment option, we would recommend selecting this option as well.
  * **Separate deposits on bill** - Select this option to create a separate section of `Deposits` on all your bills; if selected, `Deposits` will appear between the `Items` and `Payments` sections.
* **Enabled external payment types** - Select which of these external payment types you'd like to accept at your property. An external payment type is defined as any payment that is made through an external source that is not associated with the Mews PMS.
  * **Bacs - **A wire transfer within United Kingdom financial institutions.
  * **Bad debts - **An outstanding balance that is recorded as a loss of revenue or unlikely to be received regardless of reason
  * **Bank charges **-** **a fee or charge from a financial institution 
  * **Barter - **any non-monetary payment including special deals. Please note that VAT Rates still apply to the value of the product or service. This is only applicable to properties in Germany.
  * **Cash** - A cash payment, including all supported currencies. 
  * **Commission **- A sum of money paid upon the completion of a task, often relating to the selling of certain number of goods and services.
  * **Complimentary **- Any item or service that you'd like to provide to a customer without charge. Please note that VAT still applies to the value of the item or service. 
  * **Credit card** - A credit card processed by an external system
  * **Cross settlement - **A foreign exchange transaction in which your property receives a different currency than the original listing
  * **Exchange rate difference - **A leftover amount of currency that is a result of exchange rate fluctuation, causing a difference between the former and current payment balances. The rate difference is recorded as an external payment to allow balance of zero.
  * **Exchange rounding difference** - Exchange rate difference for amounts less than one whole unit of currency
  * **Invoice** - An invoice processed by an external system
  * **Prepayment - **Revenue received in the past with already reported tax
  * **Reseller - **Revenue coming from any reseller of goods or services
  * **Unspecified -** A payment that comes from a source not otherwise specified 
  * **Wire transfer** - An electronic payment sent directly from a bank account to your property
* **Bill closing**
  * **Always allowed** - You may close bills at any time, even if the items on the bill have not yet been consumed \(for example a future stay\)
  * **Only with consumed items** - You may only close bills that have consumed items on them. Therefore, if there is a future stay _or transfer planned and pre-paid _**\(?\)**, the system will not allow you to close this bill until the day of checkout. This setting is extremely restrictive to front desk, and we do not recommend using it.
  * **Only with consumed items half day window** -** **You may not close a bill with consumed items until the day of departure, however you can make changes to the booking up until departure. From the moment that a bill is closed, you cannot make changes to that booking because the items that are already on that closed bill would be affected by the change. This is the most flexible setting and we recommend this option over the others.
* **Invoice due interval** - The standard number of days within which an invoice should be settled. For example, if you issue an invoice and it should be settled within 30 days, this field should be set to 30. When a new invoice is created, it will be set to this number of days by default, however you can manually specify a different due interval if necessary.
* **Tax rate codes **- Open text fields where mapping codes can be entered as dictated by the accounting software of your choice. These are also known as VAT Rate fields. These are used for accounting exports that may require mapping of all products and payments, including their VAT Rates. VAT Rates vary by country. Please consult your accounting team for further guidance.
* **Default invoice counter** - This is the counter through which all invoices will be processed by default. Should there be a more appropriate counter for an invoice, you can still choose a different counter before any invoice is issued to a client. 

The following configuration options include a list of every possible payment type that is available in the system. Should your accounting system \(or internal accounting procedures\) incorporate different [accounting categories](accounting-categories.md), you must first [create those Accounting Categories](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/settings/finance-settings/accounting-categories/create-an-accounting-category.md) for each payment type, as well as their specific accounting codes.

Once created, you can return to the Accounting Configuration Screen and select the correct [Accounting Category](accounting-categories.md) for each payment type. After each payment is correctly mapped, your accounting integrations will automatically pick up this mapping information.

Regarding the display of data in the [Accounting Report](../../reports/accounting-report.md), assigned [Accounting Categories](accounting-categories.md) for different products, services, room type, rates, etc. are all mapped in the same way as payments.

* **Cash payment** - Any payment received in the form of cash. This includes all currencies that your property has chosen to support. 
* **Invoice payment** - Any payment received and used to settle a previously issued invoice. 
* **Unspecified credit card payment** - Any credit card payment that was made and received using a payment terminal that is not connected to or associated with the Mews PMS.
* **Additional expenses** - Any payment that is for a reason relating to accommodation, but is not for accommodation itself.
  * **Cancellation fee** - A fee incurred by a client as a direct result of cancelling accommodation. 
  * **Custom item** - Any item that cannot be otherwise categorized but is related to accommodation. 
  * **Deposit** - A sum of money that is paid in advance to secure accommodation services booked for the future.
  * **Exchange rate difference** - A leftover amount of currency that is a result of exchange rate fluctuation, causing a difference between the former and current payment balances. 
  * **Night rebate** - Any rebate given for a night of accommodation. 
  * **Product order rebate** - Any rebate given for a product order
  * **Product service order rebate** - Any rebate given for a product service order
  * **Service charge** - A charge incurred as a result of another service provided \(i.e. additional cleaning fees for damaged property\)
* **Terminal payments** - Terminal payments include all credit card payments made using a physical terminal. Select which credit card types you would like to support at your property. If you've chosen not to support a certain card type, it may not be necessary to assign an accounting category to that item. Please consult with your accounting team for further guidance.
* **Gateway payments** - Gateway payments include all online credit card payments. Select which credit card types you would like to support at your property. If you've chosen not to support a certain card type, it may not be necessary to assign an accounting category to that item. Please consult with your accounting team for further guidance.
* **External payments** - Select the [accounting categories](accounting-categories.md) associated with the enabled external payment types you've selected above. An external payment type is defined as any payment that is made from an external source that is not associated with the Mews PMS. This list is identical to the possible external payment types you can enable above. Descriptions of each item can be found above. If you've chosen not to enable a certain payment type, it may not be necessary to assign an [accounting category](accounting-categories.md) to that item. Please consult with your accounting team for further guidance.
* **Bill header** - This information will appear at the top of your Bills, Proformas, and Invoices. Complete this field with all official hotel details that you'd like to be available. These details may include address, hotel name, VAT, bank details, etc. Using HTML format, you may also use this space to add a personalized message.
* **Bill footer **- This information will appear at the bottom of your Bills, Proformas, and Invoices. Using HTML format, you may complete this field with any additional information, contact details, or personalized messages from your property. This space is a great opportunity for including marketing material, such as upcoming deals or promotional codes.

> ## Mews Clues:
>
> Please note that the design of the bill cannot be modified in any way. This design was chosen because the format is valid across all hotels worldwide. We are not able to make exceptions because of the increased risk of bugs or misprinting. In order to minimise those risks, we have chosen to use one universal template.

