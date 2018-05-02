# Duetto Reservation Export Integration

Duetto is a cloud-based hotel revenue management software and revenue strategy solution. Below, you can find instructions about how to set up the Duetto integration for your property. Follow these instructions in order and if you have any trouble, please do not hesitate to contact our integrations team for assistance.

Duetto doesn’t pull data directly from Mews but receive an export of our `Reservation report` every hour to have the latest data.

If you have reached an agreement with Duetto on using their software with the integration with Mews, they have sent us \(and you\) request for access token and also shared with you the steps to setup the integration in Mews.

## Target

First, in order to complete the following steps, you must have received your account details from Duetto, as that information is required in all further steps. If you have not yet received those details, please contact Duetto directly.

To create an export target, navigate to the `Export targets` page using the following path:

* **Main Menu &gt; Exports &gt; Targets**

Look for the `+` icon, click on it, and select `FTP export target`. In a modal window, you will see the following fields to complete:

* **Name** - Copy and paste from your Duetto configuration details
* **URL** - Copy and paste from your Duetto configuration details
* **Port** - Copy and paste from your Duetto configuration details
* **Username** - Copy and paste from your Duetto configuration details
* **Password** - Copy and paste from your Duetto configuration details
* **Mode** - From the drop-down menu, select `Active`

When all information is correctly entered, click `Create` and you will see the following additional fields:

* **Created \(UTC\)** - Date and time that this target was created
* **Updated \(UTC\)** - Date and time that target settings were most recently updated

If any changes are made, please don't forget to click `Save`

> ### Mews Clues
>
> Please note that you can also create an FTP Target directly from your export schedule settings using all details described above.

## Integration

After creating your FTP export target, you must create and setup your Duetto integration in Mews.

To create a new `Duetto Reservation Export integration`, navigate to the main integrations page using the following path:

* **Main Menu &gt; Settings &gt; Integrations**

Look for the `+` icon and click on it. Next, look for the `Business intelligence` section and click on `Duetto Reservation Export integration`. In a modal window, you will see the following fields to complete:

* **Name** - This field is optional. If you do add a name, it will appear after `Duetto Reservation Export integration`
* **Dataset identifier** - Complete with `mws`
* **Notes** - Include any notes or additional information 

When all information is correctly entered, click `Create` and you will see the following additional fields:

* **Enabled** - Select this box to enable this integration
* **Created \(UTC\)** - Date and time that this integration was created
* **Updated \(UTC\)** - Date and time that integration settings were most recently updated

After you select the `Enabled` box, please don't forget to click `Save`.

## Export schedule

Since Duetto operates using details from our `Reservation report`, you must next create an export schedule to send that information.

Navigate to our `Reservation report` either directly from the Mews Dashboard in the `Reservations` section, or using the following path:

* **Main Menu &gt; Reservations &gt; Reservation report**

When the report opens, click on the `OK` button and select `Create Duetto reservation export integration`

Once you have selected this item, you should see a success message stating that the export schedule was successfully created and you will be redirected to the `Export schedule` settings.

Under the `Report configuration` section, all settings should be automatically pre-selected and should be correct without any editing.

Under the `Export schedule` section, you will see the following fields:

* **Enabled** - Please be sure that this box is selected or the report will not work
* **Name** - Rename this schedule as desired
* **Next start** - Please refer to your Duetto configuration settings
* **Frequency** - Please refer to your Duetto configuration settings
* **Export target** - From the drop-down menu, select the FTP target that you just created
* **Options** - If you would like to receive notifications about exports sent, select this item
* **Created \(UTC\)** - Date and time that this export schedule was created
* **Updated \(UTC\)** - Date and time that export schedule settings were most recently updated

After completing all settings, click the `Save` button and Duetto will receive an updated `Reservation report` every hour.

## Historical reservations

Once you have completed the steps to send future data, you must also generate a Duetto reservation report within Mews to include your past reservation data

Navigate to our `Reservation report` either directly from the Mews Dashboard in the `Reservations` section, or using the following path:

* **Main Menu &gt; Reservations &gt; Reservation report**

Complete the report filters with the following options:

* **Mode** - Detailed
* **Filter** - Created or updated
* **Start & End** - Unless given other instructions from Duetto, you should create a report with data from the beginning of your property's operations until the present day. Please note that due to high load of data \(reservations\), you should run the report should for only three months at a time until the operation interval is fully accounted for. \(e.g. If your property has been operating for one year, you will generate four reports.\)
* **Options** - Select only the following two items
  * **Include additional expenses**
  * **Include nights**
* **Values** - Net 

Please note that all other fields may be left blank, completing only the fields mentioned above.

When all fields are correctly completed, click the `OK` button and select `Duetto reservation export integration`.

After clicking, you will automatically be redirected to another screen, stating that reports will be generated in the system and you will receive a notification when the job is complete. Click `Exports` to navigate to our Export center, where you can download and save each reports.

Navigate back to the `Reservation report` and repeat all steps as described above to run your remaining reports. Once complete, send all the generated reports to Duetto and they can complete the rest of your setup.

## Troubleshooting

Should you encounter any issues with the integration or when generating your reports, please contact `integrations@mewssystems.com` for further assistance.

