# Stay Services

In this section all parts of accommodation services and related products are described in detail. You can navigate to your stay settings using the following path:

* **Main Menu &gt; Settings &gt; Services &gt; Stay**

To make any changes to the stay settings found on this page, simply change the details and click `Save`.

## General settings

* **Enterprise** - Pre-filled with your property's name. This field is not editable.
* **Name** - Usually labeled `Stay`, this is the title of your accommodation settings
* **Short name** - An abbreviation of the previously chosen name, used in some places with space constrictions. 
* **Description** - A custom description of your stay services to display on Mews Navigator. You can also include any other important information for guests, such as hours of service or purchase details. 
* **Ordering** -  Choose the order in which you'd like this product category to appear. Items with the lower numbers will display first, and items with higher order numbers will appear later in the selection. In case you need to place a new item at the top of the list, you may use negative values to avoid editing all other service categories.
* **Housekeeping interval** - Period of time after which the room status of your property's spaces will automatically change to `Dirty`. \(e.g. A housekeeping interval of one day will reset room status to `Dirty` every day overnight\)
* **Reservation assignment strategy**
  * **Bottom up** - New reservations will be assigned starting with lower room numbers first
  * **Top down** - New reservations will be assigned starting with higher room numbers first
  * **Random** - Rooms will be assigned at random, ensuring that all rooms receive the same number of bookings and wear. Please note that if you have a lot of business travelers, we recommend against this setting, as it will spread groups all over the hotel.
* **Availability calculation strategy**
  * **Diffusive** - Overbookings will transfer to your next available space category and any transferred bookings will automatically reflect in your availability data system-wide
  * **Discrete** - Prevent overbookings from affecting the vacancy of any space categories that were not originally selected; in this case, properties must manually resolve overbookings and availability data for all non-selected categories will not be affected
* **Check-in type** - This setting will determine which message will be displayed to guests at the end of online check-in, informing them how they will receive keys to their room.
  * **Classic** - Inform guests to pick up their key at reception when they arrive
* **Kiosk** - Inform guests to pick up their key at a kiosk when they arrive
* **Online** - Inform guests that they will receive further information about key retrieval 

## Options

* **Channel manager segment** - Define a segment for all bookings made via Channel Managers
* **Distributor segment** - Define a segment for all bookings made via Mews Distributor
* **Default segment** - Define a segment that will automatically be preselected for new bookings made in Mews Commander. This field is editable before finalizing booking details. 
* **Options**
  * **Bill as package** - Items with this option selected will be merged together into one line on the customer's bill. Please note that you must select this option for each item that you'd like packaged together. Items will always be expanded in internal reports.
  * **Has configurable segment** - Select this option if you would like the `segment` field to appear to while creating new reservations. If not selected, users can only fill in `segment` information in the reservation module properties tab.
  * **Has expanded bill items** - Grouped bill items will be displayed with each product as an individual line items on bills. If you do not select this option, items will be displayed with a summary header and a total amount only. Please note that in your internal reporting, all products will be displayed individually.
  * **Has overrideable price** - Standard price of this item can be overridden by an employee
  * **Has overrideable tax** - VAT of this item can be overridden by an employee. Please note that this might cause products to be posted with incorrect taxes and could therefore cause problems for your accounting team later.
  * **Is retrospectively orderable** - Service can be ordered after consumption date and will be available for manual postings. For example, minibar items in the guest's room that were consumed earlier in their stay.
  * **New orders automatically processed** - When this service is ordered, it will automatically be processed. If not selected, an employee must manually accept and process an order. This is primarily important for orders from Mews Navigator, which require an employee to manually process. For example if a guest orders Room Service via Navigator, reception should "accept the order", which informs the guest that the order is being processed.
  * **Offer to customer** - Display this service to customers for ordering
  * **Offer to employee** - Display this service to employees for ordering
  * **Order generates e-mail** - When an order is made, the system will send an e-mail to the responsible employee and all members of the responsible department
  * **Order generates notification** - When an order is made, the system will generate a notification in Mews to the responsible employee and all members of the responsible department
  * **Order requires completed notes** - Notes must be included as a required field before an order can be completed. For example, if a guest orders a taxi, it's important for them to include the time and location of pickup or drop-off.
  * **Orderable only with products** - Service can only be ordered with sub-products attached. For example if you order 'Room Service', this order must include the items that you'd like to receive. 
* **Visit options**
  * **Apply cancellation fee by default** - Automatically charge cancellation fee for canceled bookings
  * **Change inspected to clean overnight** - Automatically change vacant inspected rooms to clean overnight. Housekeeping must then double check that rooms are inspected before any customer can check-in
  * **Check-in makes room dirty** - Change room status to `Dirty` at the moment of check-in. Mews would recommend against this setting because it can cause confusion for housekeepers, as they will be informed to go clean that room when the status changes. Since the system will automatically turn all occupied rooms to dirty overnight, there is no need for this setting to be switched on.
  * **Checkout makes room dirty** - Room status will automatically change to \`Dirty1 at the moment of checkout
  * **Close balanced bills at checkout** - At the moment of their checkout, automatically close any bills that are balanced to 0 but still open
  * **Enable automatic after end e-mail** - At the moment of checkout, send an e-mail to customers
  * **Enable automatic after start e-mail** - At the moment of check-in, send an e-mail to customers
  * **Enable automatic check-in** - This option is only relevant for hotels with automated kiosk solutions. Booking will automatically be checked-in at the start time of the reservation.
  * **Enable automatic checkout** - Booking will automatically be checked out at the end time of the reservation 
  * **Enable automatic no-show cancellation** - Automatically cancel no-show bookings from the previous day and post cancellation fees at 6AM daily
  * **Enable automatic option cancellation** - Automatically release optional bookings if they have not been confirmed by the `release date`
  * **Enable automatic release reminder e-mail** - Send a reminder e-mail to customers 24 hours before `release date` if they have not confirmed their optional bookings
  * **Send cancellation e-mail by default** - Preselect the `send cancellation e-mail` option in the Reservation Module for canceled bookings. Please note that users can choose to unselect this option prior to cancellation. 
  * **Send confirmation e-mail by default** - Send a confirmation e-mail to customers at the moment that they confirm their reservation
  * **Send confirmation e-mail to channel reservations** - Send a confirmation e-mail to customers at the time that we receive the booking information. Please note that guests will most likely receive a confirmation e-mail from the channel as well.
* **Booking URL** - Your property's website URL, where you would like the Mews Distributor booking widget to be located. Once a booking is completed, users will be redirected to this specified page.
* **T&C URL** - Your property's terms and conditions URL, which will display in the Mews Distributor booking widget. Please note that it is critical to include all of your property's pricing and cancellation policies, as this is a key requirement of your payment provider \(Adyen or Stripe\) in order to be accepted by their compliance team. Mews will automatically add its Data and Privacy policies to your property's policies, including information about how customer data is stored and protected in the system.
* **T&C HTML** - 
* **Before order note** - Any additional information that should be provided to customer along with order

## Responsibility

* **Responsible employee** - Select the employee who is responsible for stay services. This person will be informed when new orders are received.
* **Responsible department** - Select the department who is responsible for stay services. Each member of this department will be informed when new orders are received.
* **Notify responsible employee about** -
  * **Channel Manager** - Display notifications for all bookings received via Channel Manager
  * **Commander** - Display notifications for all bookings created directly in Commander
  * **Distributor** - Display notifications for all bookings received via Mews Distributor.

## Accounting

* **Accounting Category** - Select a default accounting category for accommodation 
* **Rebate Accounting Category** - Define an accounting category only for rebates
* **Cancellation fee** - Define an accounting category only for cancellation fees
* **Positive deposit accounting category** - Define an accounting category for positive deposit charges. This setting applies to countries where VAT is paid at the time of the consumption of services.
* **Negative deposit accounting category** - Define an accounting category for negative deposit charges. This setting applies to countries where VAT is paid at the time of the consumption of services

## Reception

* **Departure time** - Official departure time of your property. This will be the default departure time for all new bookings.
* **Arrival time** - Official arrival time of your property. This will be the default arrival time for all new bookings.

## Image

Upload an image to represent your Stay Services.

Although this is not currently displayed anywhere, this may change in the future.

