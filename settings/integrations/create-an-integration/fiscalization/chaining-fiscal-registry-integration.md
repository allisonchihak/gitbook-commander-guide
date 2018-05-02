# Chaining fiscal registry integration

This integration is used exclusively at French properties to register and manage fiscal data. Please note that if you are working in a French legal environment, setting up and enabling this integration is mandatory. If you are not working from a French legal environment, you will not be able to create and setup this integration.

Below, you can find detailed information about how to set up and enable this integration at your property. If you are experiencing any trouble, please do not hesitate to contact us for assistance.

## Counter

Before creating this integration, please note that you must create one bill counter that will be solely dedicated to this integration.

Navigate to the counters page using the following path:

* **Main Menu &gt; Settings &gt; Property &gt; Counters**

To create a new bill counter, look for the `+` button, click on it, and select `Bill counter`. You will see the following fields to complete:

* **Value** - Enter the value from which you would like to start counting
* **Name** - Please note that this new counter must be used only as a fiscal registry counter, so you may want to name this new counter accordingly
* **Number format** - Should you wish to have your bills or invoices start with a prefix number, this is the field where you can set this value. Bills and invoices \(currently\) share the same line of numbering, so for example, to set up documents starting with 2018 in front of the automatic line of numbering, you must follow this value with a placeholder so the system knows how to format it. For this example, this `Number format` should be completed with `2018{0:0000}`
* **Title** - Important for accounting exports in case bills must have a specific title
* **Bill type code** - Important for accounting exports, in case bills must have a specific accounting code
* **Display CID** - Only applicable to Norwegian properties

> ### Mews Clues
>
> Please also note that this new counter cannot be set as default.

When your new Fiscal registry counter has been successfully created, you can proceed with creating the integration.

## Create

To create a new `Chaining fiscal registry integration`, navigate to the main integrations page using the following path:

* **Main Menu &gt; Settings &gt; Integrations**

Look for the `+` icon and click on it. Next, look for the `Fiscalization` section and click on `Chaining fiscal registry integration`. In a modal window, you will see the following fields to complete:

* **Name** - Chosen name will appear after `Chaining fiscal registry integration` \(e.g. If you choose `PropertyName` as the name of the integration, it will appear as `Chaining fiscal registry integration PropertyName` 
* **Tax ID number** - Please consult with your accounting team to check that you enter the correct Tax ID number
* **Bill counter** - From the drop-down menu, select the counter that you've just created for this integration. Please note that once you've selected this counter and clicked the `Create` button, you will not be able to change this bill counter selection later.
* **Notes** - Add any additional notes or information that you'd like to include

When all information is correctly entered, click `Create`. Please note that after this step, only Name and Tax ID number will be editable. After clicking `Create`, you will see the following additional fields:

* **Enabled** - Select this box to enable this integration. Please note that only one fiscal registry integration ca be enabled at one time. 
* **Default** - This column should always say `Yes`, if  you find that is not the case, please contact our support team.
* **Registry identifier** - A unique identifier of your property's virtual fiscal registry.
* **AES encryption key** - An encryption key that is generated automatically and used to encrypt and protect your sensitive data.
* **Turnover** - A sum of all bill totals registered by this virtual registry, including negative values. 
* **Created \(UTC\)** - Date and time that this integration was created
* **Updated \(UTC\)** - Date and time that integration settings were most recently updated

After selecting the `Enabled` option, and when you've checked your information again, don't forget to click `Save`. Your integration set-up should be successfully completed.

Next, return to any [customer's billing page](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/profiles/customer-profile/customer-profile-sections/billing.md) and [close a bill](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/profiles/customer-profile/customer-profile-sections/billing/review-and-close.md). When you've successfully [reviewed and closed the bill](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/profiles/customer-profile/customer-profile-sections/billing/review-and-close.md), you should see a unique QR code in the bottom section were `Fiscal Record` is usually found. This code can be used to identify customer bills in the future.

