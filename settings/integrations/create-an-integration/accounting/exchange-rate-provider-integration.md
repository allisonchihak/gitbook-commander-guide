# Exchange Rate Provider Integration

To create a new `Exchange Rate Provider Integration`, navigate to the main integrations page using the following path:

* **Main Menu &gt; Settings &gt; Integrations**

Look for the `+` icon and click on it. Next, look for the `Accounting` section and click on `Exchange Rate Provider Integration`. In a modal window, you will see the following fields to complete:

* **Name** - Rename the integration if you would like to add multiple exchange rate provider integrations for different currencies.
* **Source** - Choose the source of the rates provided
  * Bank of England
  * Czech National Bank
  * European Central Bank
  * Open Exchange Rates
* **Relative adjustment** - Add a percentage adjustment to the exchange rate. Enter 0 or leave this field empty to have values set to actual rate.
* **Period**
  * **Daily** - Exchange rates will update once per day at 00:00
  * **Monthly** - Exchange rates will update at 00:00 on the first of each month
  * **Yearly** - Exchange rates will update at 00:00 on the first day of each year
* **Update offset** - This number represents the delay before each update within the selected period. The offset allows you to specify the time and/or day of the update. Offset can be any value between 0 and chosen period.
  * **Days** - Number of days delayed before update
  * **Hours** - Number of hours delayed before update
  * **Minutes** - Number of minutes delayed before update
* **Options**
  * **Send update e-mails** - 
  * **Update disabled rates** - Select this box if you would like to update all rates, even if they are not being used. 
* **Notification e-mail** - 
* **Notes** - 

When all information is correctly entered, click `Create` and you will see the following additional fields:

* **Enabled** - Select this box for automatic exchange rate updates, or deselect it to update your rates manually.
* **Last successful update** - Date and time of the most recent update
* **Created \(UTC\)** - Date and time that this integration was created
* **Updated \(UTC\)** - Date and time that integration settings were most recently updated

> ## Mews Clues
>
> In your integration settings, select 'Send update e-mails' to receive a daily summary of all conversion changes, including both successful and failed updates. Regardless of daily e-mail preferences, properties will automatically receive an e-mail notification in case of any failed updates.
>
> Please note that update offset fields can be combined with period to create a custom update time, however please note that the absolute value must be greater than zero and legitimate period of time. For example, the default update time is 00:00, so you may select a daily update with an offset of 6 hours for an update every day at 06:00.

