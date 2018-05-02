# Salto JustIN

Connecting key encoders to Mews is a great way to cut down on check-in time and simplify processes, allowing properties to send commands directly from Mews Commander to your customers' mobile devices without having to operate a separate Salto application.

Before customers arrive at your property, they must first download the JustIN Salto application on their mobile device. If the application is not downloaded and installed on the customer's phone, employees will receive an error message as they try to send the command from the Reservation Module.

If your property has chosen to integrate mobile keys, Mews would recommend that you include information about the application in your before start e-mails or confirmation e-mails, so the customer can download the application before their arrival.

Please note that in order for mobile keys to work, it is very important that customer phone numbers are formatted correctly in customer profiles, as data is taken directly from there. Numbers must have `+ country code` or `00` in front of the phone number or the employee will receive an error message as they try to complete send the command.

Should you be interested in integrating Salto mobile key encoders with your Mews PMS, please contact integrations@mewssystems.com.

* [Mews Connector](salto-justin.md#mews-connector)
* [Integration](salto-justin.md#integration)
* [Key Cutters](salto-justin.md#key-cutters)
* [Key Cutter Mapping](salto-justin.md#key-cutter-mapping)
* [Troubleshooting](salto-justin.md#troubleshooting)

## Mews Connector

If you have not yet done so, please see our article about [Mews Connector](https://mews-systems.gitbooks.io/commander-guide/content/settings/integrations/create-an-integration/facility-management/mews-connector.html) and follow those instructions before returning to this article.

If you have already installed Mews Connector, please proceed with the instructions below.

## Integration

Before you setup this integration, please note a limitation of Salto's service is that only Ethernet Encoders can be communicated to by an external service such as Mews. Please contact Salto Support, who can provide you with assistance to upgrade your encoders.

To create a new `Key cutter integration`, navigate to the main integrations page using the following path:

* **Main Menu &gt; Settings &gt; Integrations**

Look for the `+` icon and click on it. Next, look for the `Facility management` section and click on `Key cutter integration`. In a modal window, you will see the following fields to complete:

* **Name** - Salto
* **API URL** - This field consists of three parts:
  * Add `http://`
  * Following this, enter the local IP address of the Server where the Salto System application is running. For more information about finding your local IP address, [click here](https://support.microsoft.com/en-us/help/15291/windows-find-pc-ip-address). 
  * Lastly, enter the interface Port, which you can find in the `PMS Settings` inside Salto. Be sure to include a `:` between your IP address and interface port.
  * In your settings, please make sure that `TCP/IP` is enabled.
  * Please note that you should not add any spaces between these three pieces of data. When completed, your API URL will look something like this: `http://127.0.0.1:10003`
* **Username** - Leave this field blank; used only for VisiOnline integration
* **Password** - Leave this field blank; used only for VisiOnline integration
* **Notes** - Add any additional notes or information that you'd like to include

When all information is correctly entered, click `Create` and you will see the following additional fields:

* **Enabled** - Select this box to enable this integration
* **Created \(UTC\)** - Date and time that this integration was created
* **Updated \(UTC\)** - Date and time that integration settings were most recently updated

After selecting the `Enabled` option, don't forget to click `Save`.

## Key Cutters

Look for the `Key cutter` link and click on it. You will be automatically be redirected to a second page, where you will finish setup of your key cutters.

Look for the `+` button and click on it. You will see the following fields to complete:

* **Name** - Name each key cutter based on where the device is located or what will be easily understandable for your staff
* **Identifier** - Navigate to your `Salto Interface System (Server)` application. Click on the `Client` tab and copy the number found under the `No.` column, next to the name of your device
* **Data JSON** - Complete this field with `{ "Type":"IndustryStandardProtocol", "MobileKeys":"true" }`

When all details are correctly entered, click the `Create` button. Navigate back to your main `Key cutters` page, where you will see a list of active key cutters in your property's system. Add all key cutters that you would like to implement, using the same steps as described above for each one.

## Key Cutter Mapping

If your room numbers in Mews do not match the room numbers listed in Salto, you will need to set up a `Key Cutter Mapping` for each space to communicate the name difference between the two systems. If these two sets of data are already matching, you may not need to set up mappings.

To add a key cutter mapping, navigate back to your main Key cutter integration page and look for the `Key cutter mapping` link. Click on it and you will be automatically be redirected to a second page. Look for the `+` button and click on it. You will see the following fields to complete:

* **Room** - Here, you'll find a drop-down menu of all room numbers created in Mews
* **Lock identifier** - Enter the corresponding room number as is identified in Salto

When both fields are correctly entered, click the `Create` button. When you navigate back to your main `Key cutter mapping` page, where you will see a list of all mappings created for your property. Add all mappings that you would like to implement, using the same steps as described above for each one

Once you have completed all of the steps above, please inform `integrations@mewssystems.com` and we will activate the key cutters for your integration.

## Cut Keys

If all steps were above were correctly completed, you should see two new buttons in the Reservation module State tab after check-in is complete:

* **Cut all keys** - Cut keys for all companions included in the selected bookings
* **Cut key** - Cut a key for the number of companions in the selected room

If the reservation has not yet been checked-in, these buttons will be grey. Once check-in is complete, the button will change to blue, indicating that it is active and you can select the encoder that you'd like to send the key cutting commands to.

After clicking the `Cut keys` button, the customer's mobile devices should "ping" and they should have all necessary room data and also their key directly within the downloaded application.

Keys are valid from the moment of cutting until the checkout time of the reservation. If the guest prolongs their reservation, you will need to update their departure time first, and then cut a new key for those guests.

## Troubleshooting

If you receive an error that Mews cannot communicate to the Salto Interface application, please restart the application and log your issue with Salto.

Should you encounter any issues with the integration, please contact `integrations@mewssystems.com` for further assistance.

