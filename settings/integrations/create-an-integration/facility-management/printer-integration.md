# Printer Integration

Connecting printers to your system will allow you to send a `Print` command from the system directly to the printer, rather than printing via a PDF service. Below, you will find detailed instructions about how to setup your local printers using the printer integration.

* [Mews Connector](printer-integration.md#mews-connector)
* [Create](printer-integration.md#create)
* [Settings](printer-integration.md#settings)
* [Delete](printer-integration.md#delete)

## Mews Connector

Before you can install the printer integration, you must first download and install the Mews Connector application. Please see our article on [`Mews Connector`](mews-connector.md) for detailed instructions about that installation process and then return to this article to finish setup of your printer integration.

If you have already installed `Mews Connector`, you may proceed with your printer installation as is described below.

## Create

To create a new `Printer integration`, navigate to the main integrations page using the following path:

* **Main Menu &gt; Settings &gt; Integrations**

Look for the `+` icon and click on it. Next, look for the `Facility management` section and click on `Printer integration`. In a modal window, you will see the following fields to complete:

* **Name** - Chosen name will appear after `Printer integration` \(e.g. If you choose `PropertyName` as the name of the integration, it will appear as `Printer integration PropertyName` 
* **Notes** - Any additional notes or information that you'd like to include

When all information is correctly entered, click `Create` and you will see the following additional fields:

* **Enabled** - Select this box to enable this integration
* **Created \(UTC\)** - Date and time that this integration was created
* **Updated \(UTC\)** - Date and time that integration settings were most recently updated

After selecting the `Enabled` option, don't forget to click `Save`.

### Settings

Within the integration, under the `Settings` section, you can add and connect your passport scanning devices.

* **Printers** - Click here to add, manage, or delete individual printers

To add a new printer, look for the `+` button, click on it, and complete the following fields:

* **Name** - Choose an internal name to describe the printer itself. This name is seen in the system by your team to identify the device. For example, you could choose a name based on the make and model of the device or name it based on the location within your property, for example `Lobby printer`.
* **Printer name** - This should be the exact make and model name of the printer, as it is found in the settings of your computer \(e.g. "OKI-MC563-FE2048"\)
* **Driver name** - Leave this field blank
* **Port name** -  Leave this field blank
* **Ordering** - Indicates in which order the printing devices will appear, with the lowest number being the first in the list

When all entered information is correct, click the `Create` button and you will see the following two fields:

* **Created \(UTC\)** - Date and time that this integration was created
* **Updated \(UTC\)** - Date and time that integration settings were most recently updated

From this same page, you can manage or delete devices as needed.

## Delete

To delete a printer, navigate back to the main `Printers` page and click on the title of the unwanted device. Look for the `Trashcan` icon and click on it. Confirm deletion and you will automatically be redirected to the primary integration page.

