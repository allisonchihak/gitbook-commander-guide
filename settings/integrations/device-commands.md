# Device Commands

Device commands is where you can check a full list of commands from Mews to your devices that are enabled using Mews Connector. Here, you can check for any items that may still be pending, items canceled, or errors that may have occurred. You can also see all successful commands that were sent and received.

## Filters

* **Device** - Drop-down menu of all devices that you have connected to your Mews PMS via Mews Connector
* **State**
  * **Canceled** - If item has not processed within 24 hours, it will automatically be canceled by the system
  * **Error** - Failed item usually because of an unknown connection problem
  * **Pending** - Waiting to be processed; if item is not able to be processed within 24 hours, it will automatically be canceled by the system
  * **Processed** - Command has been successfully processed and completed
  * **Processing** - Item in progress
  * **Received** - Command was received but has not yet been processed
* **Start date & time** - Filter to see all commands within a specific interval, starting with this date and time
* **End date & time** - Filter to see all commands within a specific interval, ending with this date and time

## Features

* **Device** - Name of device as was provided during initial set up; click on device name to edit any device details
* **Integration** - Name of integration as was provided during initial set up; click on integration name to edit any integration details
* **Data** - If command details pertain to a specific stay, a link to that booking will be available here, including confirmation number, reservation owner, date of arrival - date of departure, and assigned space; click on this data to open booking details in the reservation module
* **Created** - Date and time that command was created as well as the name of creator
* **Updated** - Date and time that command was most recently updated
* **State** - Current status of command, displayed in a badge with the appropriate Mews action color
* **Notes** - If command is in error state, this column may provide additional details as per the reason for failure

## Notifications

If any commands were not successful, users will receive a notification of this failure, which will also state any additional details as to the reason for failure. Notification will be accompanied by the corresponding device command icon.

Please note that users will only be notified of failed items, which indicates that action is required for those items. All successful commands will be automatically processed and completed upon being received.

