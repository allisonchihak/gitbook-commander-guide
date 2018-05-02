# EET CZ Integration

The EET CZ integration is applicable only to properties located in the Czech Republic, and it is used to report income to the Czech Ministry of Finance. Before setting up the integration, please, make sure you have acquired an EET certificate from the Ministry of Finance. This file is referred to as a certificate file, which you will upload as part of the integration setup.

## Create

To create an EET CZ Integration, you must first navigate to the Mews Integrations page using the following path:

* **Main Menu &gt; Settings &gt; Integrations**

Look for the `+` icon and click on it. The next page contains a list of all integrations that you can create in Mews. Under the `Fiscalization` section, look for the `EET CZ integration` and click on it. You will see the following fields to complete:

* **Name** - Name of the integration, which will follow `EET CZ Integration` on the primary integrations page
* **Tax ID number** - VAT number of the person responsible for reporting your property's revenue
* **Site identifier** - Unique number assigned to your property by `Finanční správa` and used to identify its location; please contact your accounting team for more information about this field
* **Certificate password** - Password chosen when creating your certificate
* **Notes** - Add any additional notes or information that you'd like to include

When all information is correctly entered, click `Create` and you will see the following additional fields:

* **Enabled** - Select this field and click `Save` to enable the integration
* **Default** - `Yes` or `No`; Please note that this field is not editable
* **Created \(UTC\)** - Time that this integration was created
* **Updated \(UTC\)** - Time that this integration was most recently updated

### EET certificate file

This file is provided by the Czech Ministry of Finance and should have a `.P12` extension.

When all information is successfully entered, you can start issuing bills that include `Fiskální identifikační kód (FIK)` and `Bezpečnostního kódu poplatníka (BKP)`, which are required by Czech law.

If any data submission to EET fails, the system will automatically resend it within 48 hours, as is legally required.

## Delete

To delete a EET CZ integration, navigate to the main integrations page and click on the name of the unwanted integration. Look for the `Trashcan` icon, confirm deletion, and you will automatically be redirected to the main integrations page. Please note that once the integration is deleted, this action cannot be undone.

