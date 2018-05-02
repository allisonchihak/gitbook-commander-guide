# Internals

## Internals Tab

The internals tab allows properties to add special notes and tags to any customer's profile and alert staff about customers that may require additional assistance for a variety of reasons.

* [Filters](internals.md#filters)
* [Language](internals.md#language)

### Filters

Within this tab, you'll find the following items, most of which can be edited at any time.

* **Number** - Unique number assigned to each customer by the system automatically; please note that this field is not editable. 
* **Options**
  * **Send marketing e-mails** - Select this option if customer would like to receive marketing e-mails from Mews; please note that invitation to online check-in and other e-mails related directly to their booking are not included in opt out
* **Classifications** - Each classification corresponds to an icon, which, when selected, is displayed next to the customer name. These can be used to help your team to quickly identify whether a customer may require any additional assistance. You may select any and all classifications that apply.
  * **Blacklisted** - Customers cannot create a new booking using the Mews Distributor or directly in the Mews Commander. If a blacklisted guest tries to book via the Distributor, they will receive a message to contact the hotel directly.
  * **Cashlist** - Indicates that the customer should pay all extra charges in cash, and therefore cannot order items via Distributor. Cashlist individuals are identified via some POS integrations, so if they try to post items their room via POS, the system will display an error message. 
  * **Disabled** - Customer may require physical assistance and or special space assignments based on their needs. 
  * **Friend or family** - Customer is friend or family of the owner 
  * **Important** - Please note that there is also a `Very important` classification, which your property can use as you see fit
  * **Loyalty program** - Use this classification if your property has an internal loyalty program that a customer is a member of
  * **Media** - This indicates that customer may either draw attention of the media or may be a member of the media
  * **Military**- Used for any members of the military
  * **Paymaster account** - Used to mark "dummy" accounts, which are chargeable without a reservation. Paymaster accounts are used to collect of multiple charges for a group or all items which will then be sent in one cohesive bill, rather than charging items separately to individuals or sending many multiple bills to the same place simultaneously. Paymaster accounts are commonly used for events or for posting items from an external POS. \(e.g. properties could create a guest account called "Restaurant Charges", which, when labeled with `Paymaster` internal label, will be identifiable by external POS systems and used for group charges; Some travel agencies may prefer to use `Paymaster` accounts as City Ledgers, sending one invoice for all reservations per month, therefore you can create a customer profile for that agency and then move all bills there to be invoiced at once.\)
  * **Previous complaint** - Customer who may have had a previous complaint or bad experience, allowing you to make up for it in their next visit
  * **Problematic** - Customer created some kind of problem or conflict during their last visit and may possibly be the cause of problems in their following stays 
  * **Returning** - Customer has stayed at property before and is returning on a subsequent visit
  * **Staff** - Person is staff at this property or another affiliated property 
  * **Top management** - Guest is top management of a business or company group that may be staying at property
  * **Very important** - Please note that there is also an `Important` classification, which your property can use as you see fit
* **Accounting Code** - Each guest profile has a unique accounting code, automatically assigned, however, if you would like to manually assign accounting codes, this is possible through this open text field.
* **Loyalty Code** - Use this field for a loyalty code that may be used as part of an internal loyalty program
* **Guest Profile Notes** - Guest Profile notes are used for notes about a specific guest. Notes will be visible on several reports \(e.g. Reservations Report, Reservations Overview, Guest In House\) which enables this information to be clearly noticeable for all team members. 
* **Language** - Chosen preferred language of the guest, which is first assigned by default and later editable via the guest's user profile. Please see below for more details.
* **Culture \(Formatting\)** - Determines formatting of date and time, alphabetical order and local calendar preferences \(e.g. the first day of a week\).
* **Created \(UTC\)** - Date and time that customer profile was created
* **Updated \(UTC\)** - Date and time that customer profile was most recently updated

### Language

The guest profile language field specifies the customer's preferred language of communication, and is the language in which the system will communicate with the guest.

We feel that the language preference should be chosen by guest, rather than any property. Therefore, this setting is determined by the following criteria:

* If guest used Mews Distributor to complete their booking, or if the guest completed online check-in, their selected language will automatically be detected and then transferred to their customer profile as their primary language choice
* If no language selection is made, default language will be set automatically by the system based on the selected Nationality field
* If Nationality is not specified, the customer will receive communication in the default language of the property where they have a reservation

If the guest has selected a preferred language for communication, no property will be able to override this setting. Rather, this field must be updated by the customers themselves within their Mews Navigator profile.

## Reporting

Customer classifications are a useful tool for analyzing your property data. In the following reports, you can use these items as a filter, which then can help you in gathering statistics.

In the following reports, you can use this data to filter results:

* **Reservation Report** &gt; **Group by** &gt; Customer Classification
* **Customer Statistics** &gt; **Group by** &gt; Customer Classification

