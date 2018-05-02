# Spain police integration

This article is intended as a guide for all Spanish properties that wish to automatically generate their police reports daily. Reports are created in the format required by Spanish law and can be automatically sent to desired e-mail addresses.

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

## Format

The format of the export is **.csv**.

## Export

The report is generated and exported including the personal details of all guests arriving the day before the current date. Data is compiled into several lines. The first line is always consistent and contains data regarding your particular property, which includes the following items:

* **Record type** - This will always be a constant value of `1`, as your property's information is always the first line of the report
* **Hotel establishment code** - Unique code provided by the Spanish police
* **Hotel name** - Official name of your property 
* **Date** - Date that report was created in `YYYYMMDD` format
* **Time** - Time that report was created in `HHMM` 24-hour time format 
* **Number of reported guests** - This number should correspond to the number of following lines 

In the export, each piece of information is separated with a `|` symbol, so the first line of the final report will look similar the example below

`1|12345678|PROPERTYNAME|20180409|1622|1|`

The second and following lines will contain legally required information about yesterday's arriving guests, and includes the following information:

* **Record type** - This will always be a constant value of `2`
* **Spanish ID** - This field is only complete for Spanish citizens, and will indicate their identification number; for non-Spanish citizens, this field will be blank
* **Document number** - This field only applies to foreign guests, and includes the number of the identity document submitted during check-in; for Spanish citizens, this field will be blank
* **Document type** - One letter abbreviation corresponding to one of the accepted forms of identity document \(e.g. **P** for passport\)
* **Document expiration date** - Date of document's expiration in `YYYYMMDD` format
* **Last name** - Customer's surname
* **Second last name** - Second surname, if applicable
* **First name** - Customer's given name
* **Gender** - **F** for Female or **M** for Male
* **Birthdate** - Date of customer's birth in `YYYYMMDD` format
* **Nationality** - Customer's nationality stated without spaces
* **Reservation start** - Date that customer arrived in `YYYYMMDD` format, which should always be yesterday's date 

In the export, each piece of information is separated with a `|` symbol, so the second and following lines of the final report will look similar the examples below:

**Spanish Citizen:** `2|1223656||D|20200402|LASTNAME|SECONDLASTNAME|FIRSTNAME|M|19950412|ESPANA|20180411|`

**Non-Spanish Citizen:** `2||1223656|P|20200402|LASTNAME|SECONDLASTNAME|FIRSTNAME|F|19891105|ESTADOSUNIDOS|20180411|`

> ### Mews Clues
>
> Only guests with identity document information will be included in the export
>
> Properties are fully responsible for completing data for legally required fields
>
> Properties are fully responsible for delivering reports to the police as required
>
> Please note that the export will be generated based on yesterday's arrival data

## Delete

To delete this integration, navigate to the main integrations page and click on the title of the unwanted integration.

Look for the `Trashcan icon` in the top right-hand corner, click on it, confirm deletion, and when you return to the main integrations page, you should no longer see this integration listed with the others.

