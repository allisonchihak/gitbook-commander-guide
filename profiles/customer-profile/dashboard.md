# Dashboard

Within this tab, you can find reservations, an overview of all closed bills linked to the customer profile, and all orders that were made by the customer.

* [Header](dashboard.md#header)
* [Current and future](dashboard.md#current-and-future)
* [Bills and invoices](dashboard.md#bills-and-invoices)
* [Past and canceled](dashboard.md#past-and-canceled)
* [Orders](dashboard.md#orders)

## Header

In the top part of this tab, you will see a `+` icon, which can be used to create a new reservation or to place an order for either services and stay services. Place orders here if you do not want it to be processed automatically. Upon completing the order, you will see the new order appear on your dashboard in the Orders donut. When you open the primary orders page, you can either process the order manually or process it.

## Current and future

In the very first section of the Profile Dashboard, you will see an overview of current and future bookings linked to this guest.

Each reservation will be represented in a [`reservation card`](../../reservations/reservation-cards.md), containing the basic reservation details for each. Cards will be marked with the appropriate action button, represented in the correct action color. Should the person be assigned as a companion to a booking, you will also see these bookings on their dashboard.

Manage, check in, or checkout a booking directly from this page, which will direct you automatically to the reservation module, where you can review and manage booking details. You can also click on the `Details` button to see the [`reservation simple detail`](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/reservations/timeline/room-display.md).

## Bills and invoices

Within this section, you will be able to see each bill or invoice that was ever closed under this customer's name. Each document will be displayed with the following details:

* **Name** - Title of the closed document. Click on this title to open and review all further details. 
* **Customer** - Name of customer for whom this bill was closed. Click on this name to be taken directly to the [customer's profile](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/profiles/customer-profile/customer-profile-sections/profile.md). 
* **Company** - If the bill was assigned to a company, that company name will appear here. Click on this link to be taken directly to the [company's profile](../company-profile.md). If a company was not assigned, this field will remain blank. 
* **Closer** - Name of employee who reviewed and closed this bill or reviewed and issued this invoice. 
* **Issued** - Date and time that this bill was closed or that this invoice was issued
* **Due date** - Used only for invoices, this is the date that payment is due. 
* **Paid** - Used only for invoices, this is the date that payment was received. 
* **State** - Current bill state displayed with the proper Mews action color. 
* **Action** - Click on the `cash` icon to be taken directly to that customer's [billing screen](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/profiles/customer-profile/customer-profile-sections/billing.md). 

## Past and canceled

In the very first section of the Profile Dashboard, you will see an overview of past and canceled bookings linked to this guest.

Each reservation will be represented in a [`reservation card`](../../reservations/reservation-cards.md), containing the basic reservation details for each. Cards will be marked with the appropriate action button, represented in the correct action color. Should the person be assigned as a companion to a booking, you will also see these bookings on their dashboard.

Manage a booking directly from this page, which will direct you automatically to the reservation module, where you can review and manage booking details. You can also click on the `Details` button to see the [`reservation simple detail`](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/reservations/timeline/room-display.md).

## Orders

Here, you can see all past, canceled, current, and future orders connected to this guest. Each order is displayed in its own line with the following details:

* **Service** - Assigned name of the service ordered. Click on the name of the service to open and review further order details.
* **Created** - Date and time that this order was created in Commander. Hover over this field to see the name of the employee who created the order. 
* **Start** - Date and time that this order will begin. This field is only applicable to pre-confirmed orders in case orders are created for the future.
* **Notes** - Any additional details or information that is necessary for the completion of this order. Please note that only notes are editable after an order is placed. 
* **State** - Current order state displayed with the proper Mews action color. Hover over this state badge to see the time of the last state change and name of the employee who is responsible.
* **Total amount** - Total cost of this order
* **Action buttons** - Click on the `X` to cancel an order or click on the `checkmark` to process an order 

Click on the name of the service to see additional order details. Within each order details page, you will find the following information:

* **Service** - Assigned name of service ordered
* **Customer** - Name of customer who placed order
* **Date and time** - Date and time that this order will begin. This field is only applicable to pre-confirmed orders in case orders are created for the future.
* **State** - Current order state
* **Total amount** - Total cost of this order
* **Created** - Date and time that this order was created in Commander
* **Updated** - Date and time that this order was last updated
* **Notes** - Any additional details or information that is necessary for the completion of this order
* **Items** - In this section you'll find an itemized list of each order
  * **Item** - Assigned name of item ordered
  * **Count** - Number of items ordered
  * **Cost** - Total cost of items
* **Action log** - This is a list of all changes made to this order. Each log entry includes the name of the employee who made the change, the time and date of change, and a short description of the change that was made. 

