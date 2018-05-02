# Rates

Rates are used to define per day pricing for reservations made at your property. As customers create bookings, either via online travel agencies or directly, properties often prefer to offer multiple rate choices. Properties can create up to 100 different rates to offer to customers.

Navigate to the main rates page using the following path:

* **Main Menu &gt; Services &gt; Stay &gt; Rates**

This page contains a list of all active rates, organized by their rate groups. Each rate is listed with the following information:

* **Name** - Internal name for this rate
* **Base rate** - Identifies another rate that this rate depends on, if applicable
* **Type** - Public or private
  * **Private** - Rate is visible only to employees
  * **Public** - Rate is visible to anyone
* **External name** - Name displayed to customers
* **Enabled** - Choose to enable or disable your rate
* **Default** - Yes or no; identifies your default rate for booking

From this page, you can create rates, or click on the `Name` of any rate to manage its settings. Below, you'll find a detailed description of how to create and manage your property's rates.

* [Create](./#create)
* [Manage](./#manage)
* [Delete](./#delete)
* [Best Available \(BAR\)](./#best-available-bar)
* [Dependent](./#dependent)
* [Non-refundable](./#non-refundable)

## Create

To create a rate, navigate to the main rates page using the path described above. Look for the `+` button and click on it. Next, you will see the following fields to complete:

* **Service** - Pre-filled with `Stay`
* **Base rate** - This drop-down menu contains all rates available at your property; select a base rate if you'd like to create a dependent rate based off the price of an existing rate; if you're creating an independent rate, leave this field blank
* **Enabled** - To enable this rate, select this box; if the rate is not enabled, guests will not be able to make bookings with this rate
* **Default** - Pre-filled with `No`; to change your default rate, navigate to the main rates page, click on the rate you'd like to make default, and look for the toggle button in the `Detail` tab; the `Rate management` button on the Mews Dashboard will lead you directly to the `Pricing` tab of your selected default rate; Please note that default rate is the base number often used to help calculate other dependent rates, excluding all products or additional fees that you may want to add
* **Type** - Choose who this rate should be visible to
  * **Private** - Rate is visible only to employees
  * **Public** - Rate is visible to anyone
* **Group** - Choose the rate group to which this new rate belongs; for more information, please see our article about `Rate Groups`
* **Accounting category** - Choose the applicable accounting category as per your property's settings
* **Segment** - Apply a standard segment for this rate as per your property's settings; please note that this setting will override any other segment rules in place
* **Name** - Internal name as displayed to your employees
* **Short name** - Abbreviated name used in reports or other places where space is limited
* **Description** - Description will be displayed in Mews Distributor for customers; include any additional details or important information; for example, some properties include cancellation policy information here
* **Ordering** - Choose in which order you'd like your rates to be displayed 
* **External name** - Name of rate displayed to customers while booking via Mews Distributor and in all e-mail confirmations

When these fields are correctly completed, click the `Create` button and you will see these additional fields to complete:

* **Currency** - Choose which currency you'd like this rate to be charged in 
* **Price** - Choose the price per night for this rate
* **Tax rate** - Choose the correct and applicable tax rate; please consult with your accounting team for further assistance 
* **Empty bed adjustment** - If space is not full to capacity, apply a price adjustment for empty space
* **Extra bed adjustment** - If adding an additional bed to accommodate extra guests, apply a price adjustment for exceeding capacity

## Manage

To manage a rate, navigate to the main rates page and click on the `Name` of the rate that you'd like to manage. When you click on the rate, you will be automatically redirected to the first `Detail` tab of the rate. Each rate will have three tabs that you can switch between:

* **Detail** - All items that were present at the time that you created this rate, in addition to the following:
  * **Created \(UTC\)** - Time that this rate was created
  * **Updated \(UTC\)** - Time that this rate was last updated
* **Pricing** - Set price adjustments for each space category and view your occupancy
* **Restrictions** - Create date, earliness, or length restrictions for this rate 

For more detailed information about how to manage each of these tabs, please see the individual articles for each one, which are linked above.

## Best Available \(BAR\)

Your default rate should always be your Best Available Rate \(BAR\). Please note that if you choose this rate to be your default rate, it will act as the base number often used to help calculate other dependent rates, which excludes all products or additional fees that you may want to add:

* **Name**: Name this field correctly with its full name, as this is the rate that is visible to the customer directly in the Mews Distributor.
* **Short Name**: Create a short name for all the rates, as this will display better in report columns.
* **Ordering**: This put a numerical order into the list of rates in the earlier "Rates" section.
* **Price**: which is the base from which all other space types float.
* **Currency**: Ensure that you select the correct currency in the base rate, as this will affect the sales currency of the hotel. Once you have set the base rate, it will update all future dates with this rate. The base rate is the sales rate, inclusive of VAT, but exclusive of products \(such as breakfast\).
* **Tax rate**: select the correct tax rate that applies
* **Empty Bed Adjustment**: Rooms are sold inclusive of VAT and are assumed to be for the base number of people the room can accommodate in regular beds \(not taking into account extra beds\). If the hotel differentiates its pricing if you , for example, go from double, to single, you can fill in the value with which the rate should drop. Note that in order to lower the rate you have to fill in a negative value \(for example: -10\)
* **Extra Bed Adjustment**: Same as above. The room is assumed to be sold a full capacity of beds, however if you have the possibility to place 1 or more extra beds, in this field you can put the value with how much you would like to charge an extra bed

## Dependent \(Floating\)

Once you have set up your "Best Available Rate" in the system, you can create rates that float off this BAR rate at discounted percentages. One such example is a “Non-Refundable Rate,” which, for example, you can set at a 10% discount from the BAR rate. The system will automatically calculate the discount for all room types, saving a lot of work for revenue and reservations managers.

Some examples of rates that can float:

* Non-Refundable Rate
* Advance Purchase Rates: For example, if you wish to give a discount for guests who book 21 days in advance. You must ensure that you set a "New Earliness Restriction" \(see above\).
* Long Stay Rates: For example, if a customer books 7 days or longer, they would receive a 15% discount. You must ensure that you set a "Length Restriction" \(see above\).

## Non-Refundable

1. In the Stay screen, select the "New Rate" button to start creating a new rate.
2. **Base Rate**: Select the rate from which you would like to float a discounted rate. Be very careful with this field. Once you have created a rate floating off another rate, you cannot change it \(and you would have to delete it completely and rebuild it if you did need to change it\). It is recommended to float the rate off the BAR rate.
3. **Type**: If you would like to offer this rate only to specific travel agents or companies or with a special booking code \(for the booking engine\), you need to select "Private" in this box. However if you would like the rate to be publicly available, then select "Public".
4. **Name**: Name this field correctly with its full name, as this is the rate that is visible to the customer directly in the Mews Distributor.
5. **Short Name**: Create a short name for all rates, as this will display better in report columns.
6. Create the rate, and in the next screen, you need to "Enable" it by ticking the box and setting the discount in either a percentage or absolute amount \(in the set currency\)

