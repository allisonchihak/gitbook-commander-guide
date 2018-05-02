# Reservation Module

The Reservation Module is a split screen, utilizing the left and right sides for different reasons. Above this split screen, there is a header including eight different tabs.

At any given time, only one highlighted tab is visible in the left side of the split screen. The left side is used to edit or update booking details.

On the right side, you can see reservation details and select bookings that you'd like to edit. Select multiple bookings at a time to manage them simultaneously or click on each line hide or expand individual details.

* [Tabs](./#tabs)
* [Header](./#header)
* [Selection](./#selection)
* [Summaries](./#summaries)

## Tabs

Within each respective link, you will find a detailed description of the eight Reservation Module tabs and how to use them:

* [State](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/reservations/reservation-module/state.html)
* [Properties](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/reservations/reservation-module/properties.html)
* [Group](rm-group.md)
* [Pricing](rm-pricing.md)
* [Items](rm-items.md)
* [Mailing](rm-mailing.md)
* [Action Log](rm-action-log.md)
* [Summary](rm-summary.md)

## Header

Within the reservation module, you will see the following features on the top bar throughout each individual tab.

* **Lock All** - Lock all bookings so that no one can edit or move them. Lock individual bookings by clicking on the toggle button next to customer name. 
* **Unlock All** - Unlock all bookings to edit details or move. Unlock individual bookings by clicking on the toggle button next to the name on the right-hand side. 
* **Select All** - In case of multiple bookings, use this button to select them all and edit them at once. Select bookings individually using the checkboxes just before customer name. 
* **Deselect All** - In case of multiple bookings, use this button to deselect all the bookings at once. Deselect bookings individually using the checkboxes just before customer name. 
* **Open All** - Expand the booking details of each individual reservation in this group.
* **Close All** - Collapse all details of each individuals booking so reservations appear in one line each
* **+ Reservation** - To [create a new booking](../create-a-reservation-nnrs.md) for an already existing group, you can click on this button, which will open the new reservation screen, with a group code pre-filled, once you complete the new booking, it will automatically be added as a part of the same booking.

## Selection

Before you begin to edit reservations, it is important to take note of which bookings you may be editing. Since Mews is customer-centric, multiple bookings may be connected to the same customer and therefore visible from the reservation module.

Booking information will only be displayed for the reservations that are selected on the right-hand side of the `Reservation Module`, and you must select at least one reservation to make changes.

For example, if you've selected only canceled reservations on the right-hand side of the Booking Module, you will not see any information under the 'Rooms' section

## Summaries

The right-hand side contains the expandable and collapsible [reservation simple detail](../simple-detail.md).

If you have a group booking you will see multiple customer names on the right, listed under the dates of their stay. Click on reservation lines by name to open up the details of each booking.

If selected bookings contain the same details, those fields will be pre-filled on the left-hand side. If information is different, fields will appear to be blank until one is deselected.

Each collapsible reservation title includes the following information:

* **Checkbox** - Select this box to edit a booking; if no booking is selected, the tabs will not appear on the left-hand side
* **Guest count** - Number of guests will be displayed in `number` x `profile icon` format
* **Customer profile icon** - Link directly to the guest profile
* **Billing icon** - Link directly to the [customer profile billing screen](../../profiles/customer-profile/billing/)
* **Timeline icon** - Link to view this booking on the timeline
* **Credit card icon** - Link directly to the [customer profile payments screen](../../profiles/customer-profile/payments/)
* **Customer name** - Name of guest who made the original booking
* **Assigned room** - Room number assigned to reservation
* **Requested category** - Space category of the original booking
* **Status of booking** - Labeled in brackets with the current status

