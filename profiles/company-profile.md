# Company Profile

Company profiles can be used to book company rates, track company bookings and statistics, and allow company invoicing for business travelers.

If creating a company with multiple branches, you will need to create one main company profile first. Next, when creating the subsequent branching offices, you can assign the first main profile as the “Mother Company,” which will track all statistics of the company in the one primary account.

Upon creation of the company profile it is assigned a unique ID, which is displayed on the list of companies. This number can be very useful for accounting departments, who then use this unique ID to track company related revenue.

* [Filters](company-profile.md#filters)
* [Create a profile](company-profile.md#create)
* [Delete a profile](company-profile.md#delete)
* [CRM](company-profile.md#crm)

## Filters

Within this report, you can utilize the following filters:

* **Country** - Sort companies by the country where they are located

## Create

Navigate to the main companies page using the following path:

*  **Main menu &gt; Profiles &gt; Companies**

Here, you will see a current list of all existing Company Profiles. Properties can create as many profiles as necessary.

This main companies page is also a report, which you can export once or use to create an export schedule. You can also create a new company profile using most company field drop-downs throughout the system.

From the main companies page, **look for the** `+` **icon and click on it**. In the next screen, complete the following details to create each profile:

* **Mother company** - Primary company profile used to connect all branches of one company are. You can use this feature to run reservation report statistics for only the mother company, summarizing all underlying profiles.
* **Name** - Name of company
* **Company identifier** - Registration number of the company in the chamber of commerce. Please note that this field is only relevant for some properties. 
* **Tax ID number** - Used to identify this company in any external accounting software
* **Additional tax identifier** - Any additional unique code used for properties that utilize external accounting software
* **Invoice due interval** - used to specify the period of days that a client has to pay the invoice before it is overdue. Interval begins at the time that the invoice is issued and will change automatically in the system after this period of time.
* **Telephone** - Contact number for this company
* **Accounting code** - If you would like to map the company to your accounting system, you can set the accounting code in this field.
* **Contact person** - Name of the main contact person for this account
* **Contact** - Any additional contact details for the account
* **Notes** - Any additional notes or information that you'd like to include
* **IATA**
* **Channel** - This field is important for OTA company accounts. If you are creating a profile for an OTA, you have to in this field select the name of the OTA, so that it will pick up the correct mapping against the channel manager
* **Google Address search** - Search for an address and select it to automatically fill details or enter the address manually. 
* **Address line 1**
* **Address line 2**
* **City**
* **Postal code**
* **Country**
* **State/Province**

When all fields are correctly completed, click the `Create` button and you will see these additional fields appear:

* **Identifier** - this number can be very useful for accounting departments to track company related revenue.
* **Created \(UTC\)** - Date that company profile was created
* **Updated \(UTC\)** - Date that company profile was most recently updated

> ### Mews Clues
>
> Please note that if your enterprise operates multiple chains, company profiles will be shared in Mews between all of these properties. Therefore, if a profile already exists, you will be able to find that data in the system for each property.

## Delete

To delete a company profile, navigate to the main company page, **click on the unwanted profile, look for the** `trashcan`**icon and click on it.**

Once a profile is deleted, it is no longer possible to assign this profile to reservations. However for past bookings, or future bookings which already had this company profile assigned, the statistics will still show the results including this "deleted" account in reports.

## CRM

Unfortunately Mews does not currently offer a full Customer Relationship Management \(CRM\) solution. Therefore, in order to maintain and track some basic details about your companies, there are two open text fields included in the profile.

Use the `Contacts` section to record all necessary contact information and company data and use the `Notes` section in any way you find useful.

> ### Mews Clues
>
> Some useful information may include contract details, the company's website, e-mail addresses, live chat links, marketing materials, social media accounts, company statistics, etc.

