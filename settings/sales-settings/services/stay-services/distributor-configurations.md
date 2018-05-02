# Distributor Configurations

The Mews Distributor can be set up and managed directly via the Mews Commander. These settings determine set up of our booking widget, which can be embedded directly into a property's website or linked anywhere. Properties can set up multiple configurations for use in different places or to send to different clientele.

Access your `Distributor configurations` using the following path:

* **Main Menu &gt; Settings &gt; Services &gt; Stay services &gt; Distributor configurations**

On this main page, you'll find a list of all configurations currently set up and in use. Below, you'll find a detailed description of each setting available and how they can be used in your Distributor setup.

## Create

To create a new Distributor configuration, navigate to the main page, look for the `+` button and click on it. In the next screen, enter a name for this particular configuration and click `Create`. You will be immediately redirected to your setting page, where you will see the following fields to complete:

* **Name** - Title of this configuration, visible only to your property's employees
* **Identifier** - Used to transfer some information from an API
* **City identifier** - Unique number that associates your property with the specific city in which it is located
* **Default** - Allows you to choose a default . If no configuration is provided, this one will be used. 
* **Language** - Select the language that should be displayed to customer; please note that user can change language if needed
* **Currency** - Select the currency of accommodation cost; if no currency is selected, your default currency will be used; this field will only show currencies available at your property
* **Start offset** - Number of days from current day that is added to the pre-filled start date; if no value is entered, the default is set to today's date
* **End offset** - Number of days from current day that is added to the pre-filled end date; if no value is entered, the default is set to two, meaning that the end date will be two days after today's date
* **Adult count** - Number of adults pre-filled for stay
* **Child count** - Number of children pre-filled for stay
* **Options** 
  * **Payment gateway enabled** - Take credit card payments online and directly through the Mews Distributor booking engine via Mews Merchant; if this option is not selected, customers must pay for bookings at the time of their arrival
* **Voucher code** - Create a configuration for a specific audience using any pre-filled voucher code 
* **Display voucher code** - Display or hide your voucher codes from guests booking via Mews Distributor
  * **Default** - If you select default, codes will be displayed
  * **No** - Codes will not be displayed to customers
  * **Yes** - Codes will be displayed to customers
* **Display special requests** - Add an additional field for guests to enter special requests with their booking; requests will automatically be added to the reservation's `Notes` field; by default, special requests will be displayed
* **Display rate comparison** - Display a banner at the bottom of space category selection including your property's direct rates compared to the rates from booking engines that are included in the `Online travel agencies` field below; by default, rate comparison will not be displayed
* **Display availability** - Display your property's availability for each space category, next to the maximum occupancy; by default, availability will be displayed
* **Child selection enabled** - Include an option to select how many children will be staying as part of reservation; if you do not allow children to stay at your property, select `No`; by default, child selection will be enabled
* **Online travel agencies** - Enter the websites that you would like to be displayed in rate comparison; please note that you must enter only one website per line, formatted like the following example: `booking.com`
* **Intro video URL** - Copy and paste a link to the video that should be displayed when opening Mews Distributor; video must be displayed in `.mp4` format on a cloud-based web page; please note that videos from YouTube, Vimeo, and other comparable sites are not properly formatted and therefore cannot be used
* **Google tag manager ID** - Use this field to integrate this booking engine into Google analytics and collect data about the number of visits to this address
* **Theme** - Choose a general theme for Distributor's color scheme
  * **Dark** - Background colors will be dark to contrast a lighter primary color
  * **Light** - Background colors will be light to contrast a darker primary color
* **Primary color** - Select the main color you'd like to see displayed in Distributor; color must be in a 6-digit hex code, formatted like the following example: `#006a00`

When all information is correctly entered or after you make any changes, click the `Save` button

Edit your configuration at any time by navigating to the primary distributor configurations page and then click on the title of the configuration that you'd like to edit.

## Category mappings

Category mappings are used to prevent some space categories from being displayed in Distributor. If left unspecified, all categories will be mapped and available in the Distributor.

To specify the available space categories, you must add only the categories that you'd like to be visible, and all others will be hidden from booking options.

To add a category mapping, click on the `+` button and you will see the following fields to complete:

* **Category** - Select the correct category from the drop-down list of all categories created and available at your property
* **Ordering** - Choose in which order you'd like the rooms to be displayed, with lower numbers being first in the list

When all details are correctly entered, click the `Create` button and when you return to the main `Category mappings` page, you will see a list of each category that has been added.

## Preview

Click here to see a preview of Distributor according to these specific configurations.

## Code

The generated script allows you to add the Distributor to your webpage.

> #### Mews Clues
>
> For guests booking via Mews Distributor, occupied space category images are displayed in greyscale and separated to the bottom to distinguish them from selectable categories.

## Settings

Data is drawn and added from several other places in the system, which means that it's important to keep everything updated according to how you'd like it to be displayed to your guests. Below, you will find information about all settings that are relevant to Mews Distributor:

### Space categories

All space categories should be fully configured, with the following details correctly completed:

* **Normal bed count** - used to determine availability
* **Extra capacity** - used to determine availability
* **Description** - This text will be visible to customers under each category in Distributor. Please note that it's important to complete descriptions in all languages in which you would like to serve your customers online
* **Image** - Photos for each space category will be visible as customer are booking
* **Order e-mail template** - For some categories, you might want to add some specific information to the standard confirmation e-mail. For example, if a space type is located in a different building, you may want to mention that. Type any additional details in this field, and they will automatically be added to the confirmation e-mail sent to customers who book this specific space category.

### Rates

All public rates automatically be displayed in Mews Distributor, so it is important that all rates have the following fields completed:

* **Name** - It is important to consider the naming of each rate as you are setting up your property. Below, you can find some examples of good and bad rate names:
  * **Bad Rate Names** - `Master Rate`, `BAR Rate`, `NR Rate`, `Min 2 nts rate`
    * These rates are not customer friendly, as guests often do not know abbreviations nor industry terminology
  * **Good Rate Names** - `Best Available - Flexible Rate!`, `Non Refundable - Best Deal!`
    * These names describe the benefits of that particular rate to the customer in very few words. Don't forget that customers can expand the description below, which will give them additional information
* **Descriptions** - Descriptions are listed next to each corresponding rate as customers are booking via Distributor. If you add a city tax or any service charges after the booking is made, it would be important to include such information in rate descriptions. 
* **External Name** - Use this field if you would like to set up a customer-friendly name that is different from the name that you use internally and seen only by your staff in the Mews Commander. This is the rate name that the guest will see in Distributor and also in confirmation e-mails.

### Products

If you would like to offer any products while booking, such as breakfast, wine, flowers, etc., you can create stay products, which the customer can select while booking to then added in addition to any rate selected. When setting up your stay products, it is important to consider the following fields:

* **Name** - Product names, used only internally if `External name` is also provided
* **Descriptions** - Descriptions are listed next to each corresponding item as customers are booking via Distributor. If you include any service charges for this item, it would be important to include such information in the description. 
* **External Name** - Use this field if you would like to set up a customer-friendly name that is different from the name that you use internally and seen only by your staff in the Mews Commander. This is the product name that the guest will see in Distributor and also in confirmation e-mails.
* **Options**
  * **Bill as package** - Package this item into service category 'revenue'
  * **Exclude price from offer** - Product cost will be added to the service order after booking is made
  * **Offer to customer** - Product will be available for customers to order; please note that this setting must be selected for item to appear in Distributor
  * **Selected by default** - Product will be automatically preselected but can still be deselected before payment
* **Charging** - Choose the method of payment for each item; below, you can find examples of items that may be used for each method:
  * **Once** - Extra cleaning fee for a dog
  * **Per person per night** - Breakfast
  * **Per room night** - Parking

For more information, please see our article about [`Stay products`](stay-products.md)

## Resources

* For more information, please see our [video](https://vimeo.com/234180455) about Distributor configurations.
* [Here](https://mews-systems.gitbooks.io/distributor-guide/content/distributor-widget.html), you can find additional information for webmasters, which they may find useful when integrating the Distributor into your website.

