# Product Services

Navigate to the Services page using the following path:

* **Main Menu &gt; Settings &gt; Services**

On this screen, you will see two sections, labeled `Service` and `Stay`.

Product services are used to offer any items that the property may sell, which are not related to the guest's stay. Services can be tiered, creating a complex system of items for sale. Any service may contain multiple `Product Categories`, which then contain multiple `Products`. For example, the hierarchy may include

* **Service** - Minibar
* **Product Category** - Food items
* **Product** - Mars Bar

Below, you will find detailed information about creating `Services`, `Product categories`, and `Products` within a service. Scroll to the appropriate section for more information.

* [Service](product-services.md#service)
* [Product category](product-services.md#product-category)
* [Product](product-services.md#product)
* [Images](product-services.md#images)

## Service

To create a new service, navigate to the main services page, look for the `+` icon, click on it, and complete the following fields:

* **Enterprise** - Pre-filled with your property's name. This field is not editable.
* **Name** - Selected name of service category. Please note that you can create products within this service, so it should be named for a more general category. This name will be displayed on bills and to customers via Mews Navigator.
* **Short name** - An abbreviation of the previously chosen name, used in some places with space constrictions. 
* **Description** - A custom description for each category or item, which will be displayed in Mews Navigator. You can also include any other important information for guests, such as hours of service or purchase details. 
* **Ordering** - Choose the order in which you'd like this service category to appear. Items with the lower numbers will display first, and items with higher order numbers will appear later in the selection. In case you need to place a new item at the top of the list, you may use negative values to avoid editing all other service categories. 
* **Currency** - Choose the currency that you'd like to use for this category from the drop-down menu of all currencies enabled at your property. Please note that if you set the main product in one currency, all items within that product category must all be priced in the same currency.
* **Price** - If this category includes additional items, this will be a service fee in addition to the cost of each item. If you do not wish to charge an additional service fee, you can leave this field blank. 
* **Tax rate** - A list of each VAT rate used by your accounting team. Please be very careful that you choose the correct VAT rate for each item, as it is very important for your fiscal reporting. If you are unsure, Mews would recommend that you contact your accounting team for guidance.
* **Options** - Select the applicable options for each item.
  * **Bill as package** - Items with this option selected will be merged together into one line on the customer's bill. Please note that you must select this option for each item that you'd like packaged together. Items will always be expanded in internal reports.
  * **Has configurable business segment** - Please note that this item is not relevant for non-stay services. If you do not have a default business segment, select this option if you would still like the `Business Segment` field to appear to users. If this option is not selected, users cannot fill in `Business segment` information.
  * **Has expanded bill items** - Grouped bill items will be displayed with each product as an individual line items on guests' bills. If you do not select this option, items will be displayed with a summary header and a total amount only. Please note that in your internal reporting, all products will be displayed individually.
  * **Has overrideable price** - Standard price of this item can be overridden by an employee
  * **Has overrideable tax** - Allows users to change the VAT of an item at the time of posting. This might cause products to be posted with incorrect taxes and could therefore cause problems for your accounting team later. For this reason, Mews would recommend against selecting this setting.
  * **Is retrospectively orderable** - Service can be ordered after consumption date and will be available for manual postings. For example, minibar items in the guest's room that were consumed earlier in their stay.
  * **New order is being processed** - When this service is ordered, it will automatically be processed. If not selected, an employee must manually accept and process an order. This is primarily important for orders from Mews Navigator, which require an employee to manually process. For example if a guest orders Room Service via Navigator, reception should "accept the order", which informs the guest that the order is being processed.
  * **Offer to customer** - Display this service to customers for ordering
  * **Offer to employee** - Display this service to employees for ordering
  * **Order generates e-mail** - When a new order is made, the system will automatically generate a confirmation e-mail, which is sent to the customer's registered e-mail address
  * **Order generates notification** - When an order is made, the system will generate a notification in Mews to the responsible employee
  * **Order requires completed notes** - Notes must be included as a required field before an order can be completed. For example, if a guest orders a taxi, it's important for them to include the time and location of pickup or drop-off.
  * **Orderable only with products** - Service can only be ordered with sub-products attached. For example if you order 'Room Service', this order must include the items that you'd like to receive. 
* **Before order note** - Any additional information that should be provided to customer along with order.
* **Responsible employee** - If this service is managed by one particular employee, select that individual from the drop-down list. Please be sure to also select `Order generates notification` so that the selected employee will receive system notifications when a new order is placed. Check our article about [`employee responsibility`](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/settings/sales-settings/services/stay-settings/responsibility.md) for more information.
* **Responsible department** - If this service is managed by one particular department, select that department from the drop-down list. Please be sure to also select `Order generates notification` so that all members of that department will receive system notifications when a new order is placed. Check our article about [`employee responsibility`](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/settings/sales-settings/services/stay-settings/responsibility.md) for more information.
* **Accounting category** - Select the correct [`accounting category`](../../finance-settings/accounting-categories.md) according to your property's settings.
* **Rebate accounting category** - If you have one specific `accounting category` for rebates, select the correct [`accounting category`](../../finance-settings/accounting-categories.md) according to your property's settings.
* **Promotions** - Select a time to promote this item to customers: 
  * **After check-in** - Promote this service after customers have completed their online check-in \(e.g. Taxi pickup, day trips, or city tours\)
  * **After checkout** - 
  * **Before checkout** - 
  * **Before check-in** - 
  * **During stay** - 

When all fields are correctly completed, click on the `Create` button.

After clicking `Create`, you'll be automatically redirected to that settings page of the service that you've just created. All previously described options will be divided into the five expandable and collapsible sections, where you can edit them as needed.

## Product Category

From the main services page, click on the service for which you'd like to create a new product category.

Once within that service's settings, look for the `+` button, click on it, select `Product category`, and complete the following fields:

* **Service** - Pre-filled with the name of the service. This field is not editable.
* **Parent category** - If this category should be within another category, select its parent from the drop-down list of existing product categories.
* **Name** - Selected name of product category. Please note that you can create products within this service, so it should be named for a more general category. This name will be displayed on bills and to customers via Mews Navigator.
* **Short name** - An abbreviation of the previously chosen name, used in some places with space constrictions. 
* **Description** - A custom description for each category or item, which will be displayed in Mews Navigator. You can also include any other important information for guests, such as hours of service or purchase details. 
* **Ordering** - Choose the order in which you'd like this product category to appear. Items with the lower numbers will display first, and items with higher order numbers will appear later in the selection. In case you need to place a new item at the top of the list, you may use negative values to avoid editing all other service categories.

When all fields are correctly completed, click on the `Create` button.

After creation, a field will appear where you may upload an image for this product category.

## Product

From the main services page, click on the service for which you'd like to create a new product category.

Once within that service's settings, look for the `+` button, click on it, select `Product`, and complete the following fields:

* **Service** - Pre-filled with the name of the service. This field is not editable.
* **Name** - Selected name of product. This name will be displayed on bills and internally.
* **Short name** - An abbreviation of the previously chosen name, used in some places with space constrictions. 
* **Description** - A custom description for each category or item, which will be displayed in Mews Navigator. You can also include any other important information for guests, such as hours of service or purchase details. 
* **External name** - Name displayed to guests and customers within Mews Distributor and Navigator
* **Category** - Select the product category of this item.
* **Accounting category** - Select the correct [`accounting category`](../../finance-settings/accounting-categories.md) according to your property's settings.
* **Rebate accounting category** - If you have one specific `accounting category` for rebates, select the correct [`accounting category`](../../finance-settings/accounting-categories.md) according to your property's settings.
* **Options** - Select the applicable options for each item.
  * **Bill as package** - Items with this option selected will be merged together into one line on the customer's bill. Please note that you must select this option for each item that you'd like packaged together. Items will always be expanded in internal reports.
  * **Offer to customer** - Display this service to customers for ordering
  * **Offer to employee** - Display this service to employees for ordering
  * **Selected by default** - Product will be automatically pre-selected, but user can still deselect it.
  * **Uncountable** - Product does not require count when ordering
* **Promotions** - Currently, most of these fields do not have any application in Mews. With the upcoming extension of Mews Navigator, we will add functionality and update users accordingly.
  * **After check-in** - Promote this service after customers have completed their online check-in \(e.g. Taxi pickup, day trips, or city tours\)
  * **After checkout** - 
  * **Before checkout** - 
  * **Before check-in** - 
  * **During stay** - 
* **Ordering** - Choose the order in which you'd like this product to appear. Items with the lower numbers will display first, and items with higher order numbers will appear later in the selection. In case you need to place a new item at the top of the list, you may use negative values to avoid editing all other service categories. 
* **Currency** - Choose the currency that you'd like to use for this product from the drop-down menu of all currencies enabled at your property. 
* **Price** - Cost of that particular item, excluding tax. 
* **Tax rate** - A list of each VAT rate used by your accounting team. Please be very careful that you choose the correct VAT rate for each item, as it is very important for your fiscal reporting. If you are unsure, Mews would recommend that you contact your accounting team for guidance.

When all fields are correctly completed, click the `Create` button.

After creation, a field will appear where you may upload an image for this product.

## Images

Below these sections, there will be an additional field where you can upload an `Image` for each created service. Images will be displayed for customers when ordering items via the Mews Navigator.

Mews would highly recommend uploading photos for all service items, as it will personalize Navigator to your property and create a much more interesting and memorable order experience for your guests.

