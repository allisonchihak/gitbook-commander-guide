# Portugal police integration

This article is intended as a guide for all Portuguese properties that wish to automatically generate their police reports daily. Reports are created in the format required by Portuguese law and can be automatically sent to desired e-mail addresses.

## Create

To create a Spanish Police Integration, you must first navigate to the Mews Integrations page using the following path:

* **Main Menu &gt; Settings &gt; Integrations**

Look for the `+` icon and click on it. The next page contains a list of all integrations that you can create in Mews. Under the `Legal environment` section, look for the `Spanish Police Integration` and click on it. You will see the following fields to complete:

* **Name** - This field is optional
* **Hotel code** - Hotel establishment code provided by the Spanish police.
* **To** - E-mail address where the export should be sent. Include multiple e-mail addresses using either commas or semicolons
* **Daily report execution time** - Time when should the export be generated and sent. By default it is set up to 9:00AM but you may change it to any time of the day you wish \(the logic is that when you fill in 0 hours and 0 minutes it is generated at midnight. If you fill in 10 hours and 45 minutes it is generated at 10:45AM, etc.\).
* **Notes**

Once all details are properly completed click the button `Create` and select the box to **Enable** the integration.

## Settings

Hotels can set up the integration by themselves following the points below:

**Name:** This field may remain blank **Property code:** Property code provided by the Portuguese police **Tax ID number:** Tax ID number of the hotel **To:** Email address where the export should be sent; you can enter multiple e-mails, which can be separated using either comaa or semicolons **Daily report execution time:** Time when should the export be generated and sent. By default it is set up to 9:00AM but you may change it to any time of the day you wish \(the logic is that when you fill in 0 hours and 0 minutes it is generated at midnight. If you fill in 10 hours and 45 minutes it is generated at 10:45AM, etc.\).

When all fields are correctly completed, click on the `Save` button and you'll see the additional field at the top:

**Enable** - select this option to the integration.

## Format

The format of the export is `.dat`.

## Generated data

The report is generated for all the arriving guests for**yesterday**.

1st line consists of:

**0** \(Constant value\)\|**BA03**\(File type - consant value\) \|**Tax ID number**\|**Hotel code**\|**Name of the hotel**\|**Hotel address**\(Address line 1\) \|**City of the hotel**\|**Postal code** \(First 4 digits\) \|**Postal code** \(Last 3 digits\) \|**Telephone number of the hotel**

2nd line and further consist of:

**1** \(Constant value\)\|**Last name**\|**First name** \|**Nationality** \(\_ISO 3166-1 aplha-3\_format\) \|**Birthdate**\|**Document number**\|**Document type**\|**Country of issue** \(\_ISO 3166-1 aplha-3\_format\) \|**Customer country of residence**\(\_ISO 3166-1\_aplha-3 format\) \|**Reservation start**\|**Reservation end**

## Notes

Hotels are responsible for the all the fields being filled in accordingly.

Hotels are also responsible to make sure that the reports are delivered to the police as required.

### Delete an Integration

To delete this integration, navigate to the main integrations page and click on the title of the unwanted integration.

Look for the `Trashcan icon` in the top right-hand corner and click on it. Click again on `Delete` when you see the confirmation dialog window. When you return to the main integrations page, you should no longer see this integration listed with the others.

