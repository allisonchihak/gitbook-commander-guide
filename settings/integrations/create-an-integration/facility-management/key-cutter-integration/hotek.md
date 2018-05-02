# Hotek

Connecting key encoders to Mews is a great way to cut down on check-in time and simplify processes, allowing properties to send commands directly from Mews Commander to your key encoding devices without having to operate a separate Hotek application.

Should you be interested in integrating Hotek key encoders with your Mews PMS, please contact integrations@mewssystems.com.

* [Mews Connector](hotek.md#mews-connector)
* [Integration](hotek.md#integration)
* [Key Cutters](hotek.md#key-cutters)
* [Key Cutter Mapping](hotek.md#key-cutter-mapping)
* [Troubleshooting](hotek.md#troubleshooting)

## Mews Connector

If you have not yet done so, please see our article about [Mews Connector](https://mews-systems.gitbooks.io/commander-guide/content/settings/integrations/create-an-integration/facility-management/mews-connector.html) and follow those instructions before returning to this article.

If you have already installed Mews Connector, please proceed with the instructions below.

## Integration

To create a new `Key cutter integration`, navigate to the main integrations page using the following path:

* **Main Menu &gt; Settings &gt; Integrations**

Look for the `+` icon and click on it. Next, look for the `Facility management` section and click on `Key cutter integration`. In a modal window, you will see the following fields to complete:

* **Name** - Hotek
* **API URL** - This field consists of three parts. You can use the image just below for reference:
  * Add `http://`
  * Following this, enter the local IP address of the computer where the Hotek Interface System \(Client & Server\) application is running. For more information about finding your local IP address, [click here](https://support.microsoft.com/en-us/help/15291/windows-find-pc-ip-address). 
  * Lastly, enter the interface Port, which you can find in the `Hotek Interface System (Server)`. Be sure to include a `:` between your IP address and interface port.
  * In your settings, please make sure that `Show message at client` is enabled and in the `Interface type` field, select`TCP/IP`.
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
* **Identifier** - Navigate to your `Hotek Interface System (Server)` application. Click on the `Client` tab and copy the number found under the `No.` column, next to the name of your device
* **Data JSON** - Complete this field with `{ "Type": "HotekKeyCutter" }`

When all details are correctly entered, click the `Create` button. Navigate back to your main `Key cutters` page, where you will see a list of active key cutters in your property's system. Add all key cutters that you would like to implement, using the same steps as described above for each one.

## Key Cutter Mapping

If your room numbers in Mews do not match the room numbers listed in Hotek, you will need to set up a `Key Cutter Mapping` for each space to communicate the name difference between the two systems. If these two sets of data are already matching, you may not need to set up mappings.

To add a key cutter mapping, navigate back to your main Key cutter integration page and look for the `Key cutter mapping` link. Click on it and you will be automatically be redirected to a second page. Look for the `+` button and click on it. You will see the following fields to complete:

* **Room** - Here, you'll find a drop-down menu of all room numbers created in Mews
* **Lock identifier** - Enter the corresponding room number as is identified in Hotek

When both fields are correctly entered, click the `Create` button. When you navigate back to your main `Key cutter mappings` page, you will see a list of all mappings created for your property. Add all mappings that you would like to implement, using the same steps as described above for each one.

Once you have completed all of the steps above, please inform `integrations@mewssystems.com` and we will activate the key cutters for your integration.

## Cut Keys

If all steps were above were correctly completed, you should see two new buttons in the Reservation module State tab after check-in is complete:

* **Cut all keys** - Cut keys for all companions included in the selected bookings
* **Cut key** - Cut a key for the number of companions in the selected room

If the reservation has not yet been checked-in, these buttons will be grey. Once check-in is complete, the button will change to blue, indicating that it is active and you can select the encoder that you'd like to send the key cutting commands to.

After clicking the `Cut keys` button, the selected key cutter should "ping" and the display will indicate which room the key\(s\) is have been cut for.

Keys are valid from the moment of cutting until the checkout time of the reservation. If the guest prolongs their reservation, you will need to update their departure time first, and then cut a new key for those guests.

## Troubleshooting

If you receive an error that Mews cannot communicate to the Hotek Interface application, please restart the application and log your issue with Hotek.

Should you encounter any issues with the integration, please contact `integrations@mewssystems.com` for further assistance.

