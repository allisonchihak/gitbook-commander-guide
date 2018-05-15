# RM: State

Within the State tab, there are many parts of a reservation that you can manage. Below, you will find a detailed description of all functions that are available using the 'State' tab of the Reservation Module.

## Customers

At the top of the State screen, under the 'Customers' title, you will see the following items:

* **Passport Scanner Integration** - If you have a passport scanner integration, you will find a "Scan" button next to each guest. Click this button to scan that guest's document and auto-complete the details in their profile.
* **Print Registration Cards** - Click this button to automatically print registration cards for all customers connected with this booking.
* **Customer** - A list of all customers connected with this booking. Click on the customer's name to be taken directly to their customer profile.
* **Balance** - Amount due for each customers assigned to the group; for group bookings you will see the balance of all participants individually and also the balance of the whole group.
* **Total** - Amount due for all items connected with this booking
* **Billing** - Direct link to customer's billing screen to take payments or settle bills; please note that a blue `Billing` button means that there is action required, as there are open bills to be closed. If a balance is set to 0 and the button is blue, that means that the bill is not yet closed.
* **Payments** - Direct link to customer's payments screen to add a payment or preauthorization to the booking. To add a deposit, navigate to the `Items` tab.

## Rooms

The 'Rooms' section contains the following items:

* **Holding** - This section will contain any optional bookings associated with this reservation. 
* **Confirmed** - Any confirmed bookings associated with this reservation
* **Canceled** - Any canceled bookings that are associated with this reservation. Please note that once a reservation has been canceled, this action cannot be undone. 

Beneath each of these headings, each individual reservation will all appear with the following details:

* **Dates of stay** - Date of arrival - date of departure
* **Customer name** - Name associated with customer's profile
* **Room number button** - Click on this room number to change the assigned room number. You will see a drop-down list of all other rooms at your property organized by room category along with their occupation status, housekeeping status, and room features in parentheses; ; if you have a group with multiple bookings, select them all to assign multiple rooms at once; from the room assignment drop-down, select `None` to move this booking to an overbooking slot, which will cause the button to turn blue and be labeled `Assign`, so that you can assign a room for the reservation later
  * **Housekeeping status badge** - Badge will display the current room status in its appropriate action color
  * **Make inspected** - Click this button to change housekeeping status from any other status to `Inspected`. Rooms must be inspected before any reservation can be checked-in.
  * **Cut key** - If you have a door lock solution integrated, a button will appear next to the room section. Once you have checked in a booking, you can select the `Cut key` icon to create a key for that room. Please note that this button is only clickable after the booking is checked-in.

## Confirmation

Under the Rooms section of the State screen, you will find the 'Confirmation' section. This section will contain

Please note that this section will only be present when only optional reservations are selected for editing. If you have selected any non-optional reservation as well, this section will not be visible.

* **Send confirmation e-mail** - Select this box if you'd like the customer to receive a confirmation e-mail. This e-mail will automatically be sent the moment that you click the `Confirm` button.
* **Confirm** - Please note that this button will not appear if you have selected any non-optional reservations; confirm multiple bookings simultaneously by selecting them all before clicking `Confirm`

## Cancellation

Cancel reservations in the last section of the 'State' screen, labeled `Cancellation`. If there are multiple connected reservations, you can cancel one reservation individually or select multiple to delete them all at once.

First, you must check that you've selected only the reservations that you'd like to cancel on the right-hand side of the Booking Module. Please note that once a reservation has been canceled, this action cannot be undone.

You will see the following items in this section:

* **Reason** - Please note that this is a required field
  * **Other** - None of these options accurately describe the reason; please note that it is then required to specify the reason in the open-text-field below
  * **Confirmation missed** - Customer has an optional booking, but did not confirm by the release date
  * **Booked elsewhere **- Guest has booked another hotel or destination
  * **Force majeure** - Guest must cancel their stay due to a force majeure event, such as earthquakes, floods, etc.
  * **Guest complaint** - Guest complains and then wants to cancel their order
  * **No show** - Guest did not show up for reservation
  * **Price is too high** - Guest canceled stay due to the high price
  * **Service not available** - Property is fully booked or you cannot accommodate guest for any reason property-related
  * **Input error** - Booking was input by error
  * **Invalid payment** - Payment details provided by the guest were not valid
  * **Travel agency** - Agency cancels and does not provide a further reason
  * **Requested by guest** - Cancellation directly by guest with no further reason provided
* **Details** - Please note that this is a required field
* **Apply Cancellation Fee** - The system will automatically recognize the cancellation policies for each rate type, and will add it as an item on the customer's billing page. For more information, please see the `Cancellation Policies` page.
* **Send e-mail** - Send a cancellation confirmation e-mail to the guest at the moment that you click the `Cancel` button

Finally, when all fields are correct, click the `Cancel` button and look for the green success message.

> #### Mews Clues:
>
> Please note that it's very important to select the correct reason for cancellation, as this information is often used for statistics and analysis. You can also describe it in the open-text-field.
>
> Please note that reservations that are currently in house cannot be canceled. If a guest needs to leave early, you must shorten the reservation and proceed with the checkout process.
>
> Please note that if a reservation must be canceled, you must do this within the [editable history window](../../settings/finance-settings/accounting-configuration.md), as you cannot edit reservations outside of this time frame.

## Status

In the State screen you are able to manage the current status of the reservation. The system knows the following statuses:

* **Optional** - Booking is not yet confirmed but is blocking availability and space on the timeline. If a booking is still optional, revenue is not yet recorded in any reports. If optional bookings are canceled, no cancellation fees will be charged to the customer. All optional bookings have a release date assigned, indicating the customer's deadline to confirm the booking. On the date of release, the booking will be highlighted in the reservation overview report and the space block will change from grey to orange on the timeline, indicating that urgent action is required. At this time, the property may cancel the booking manually, contact the customer to extend the release date, or leave the booking as it is. Within your [stay settings](../../settings/sales-settings/services/stay-services/), if you have selected to `Enable automatic option cancellation`, the system will automatically release unconfirmed bookings 24 hours past that chosen release date to free up inventory at your property. For optional bookings that have not yet been confirmed, properties can also navigate to their [stay settings](../../settings/sales-settings/services/stay-services/) and select `Enable automatic release reminder e-mail`, which will send a reminder to the customer 24 hours before the release date.
* **Confirmed** - Confirmed reservations are often paid in full at the time of booking. Bookings that are confirmed will display on the timeline and have revenue assigned. If canceled, customers are usually subject to cancellation fees, according to the selected rate type.
* **Canceled** - Canceled bookings will be removed from the timeline, and depending on the rate, they are often subject to cancellation fees according to the selected rate. Waive cancellation fees by unselecting the `Apply cancellation fee` option before clicking `Cancel`
* **Checked-out**: All bookings that have completed their stay will have the status "Checked-Out". Once a booking is checked-out, you can no longer check it back in.
* **Checked-in**: A booking that is currently in-house will be considered "Checked-In"

{% hint style="info" %}
Please note that the default release date is calculated using the midpoint between reservation creation time and the arrival time. In case of group bookings with multiple arrival times, the system will use the closest start time for calculation. If there is an odd number of days or hours, time will be rounded down.
{% endhint %}

**Confirmed**

* If a booking is on OPTIONAL state, you can confirm bookings directly from this screen. It will change the status to "Confirmed" and post the revenue on the customer bill. Next to the confirmation box you are also able to send a confirmation to another person who is not assigned to the booking. Type the e-mail in the box and he/she will receive the confirmation e-mail with a summary of all the bookings that are selected.

**Checked-in**

* Once you have assigned an inspected room, you can select the button “Check-In.” Note that the check-in button will only appear if you have selected a booking\(s\) that is on arrival today. It will check in all bookings that were selected, allowing you to check-in multiple bookings at the same time. If a booking is due to arrive today, there is also a "print" button next to it, allowing you to instantly print the registration card of the guest, if your country still requires physical signatures on the registration cards.

**Checked out**

* On the day of departure for the booking\(s\) selected, a new button will appear called "Check-Out.” The system will only allow you to check-out a guest for whom all open bills and unsettled items have been paid with a balance on zero. Should you wish to check-out a customer with an open balance \(as he may pay it later\), select the "Check-Out with Open Bill" and fill in the reason. This room will then be transferred to the Guest Ledger report in red, where the payment will need to be resolved as soon as possible.

## Check-in

Once you have identified the booking, select the “Check In” button on the booking screen. This button only appears on the day of arrival. It will open the "Booking Management" screen in the tab "State" where you can perform the following steps.

1. Verify all booking details with the customer, which includes the arrival and departure date, room-type, rate and number of people. Also inform the guest whether the booking was prepaid or not. Once verified, check with the guest how he/she would like to guarantee payment for the booking and any possible incidental charges.
2. Take preauthorization or deposit from the guest for the amount agreed. Once the money has been accepted, process this in the system by selecting either the “Preauthorization” or “Deposit” button, which will allow you to post the amount directly in the system.
3. Check that the pre-assigned room is inspected. If it is not, check if there is another room of the same type that is available and inspected. This can be spotted quickly from the dropdown menu. If no room is available ensure you assign an available \(dirty or clean\) room and contact housekeeping to get the room cleaned.
4. Once an inspected room is assigned, you can press “Check-in,” and the room is checked in. It will be locked, so that it cannot be moved in the system.

### Group check-in

If you have multiple bookings that are part of the same group, you can navigate to the `State` tab and select all eligible bookings on the right side and then click on the `Check in` button to check them in simultaneously.

> #### Mews Clues
>
> Please note that it is not possible to undo check-in outside of the editable history window
>
> Please note that if you send your confirmation to custom e-mail, the link to check-in online will not allow the possibly different person to get into profile of the reservation owner. The e-mail will contain a link to sign-in screen of navigator. As a solution, please be sure that guests use their primary e-mail address on their customer profile and not sending it to custom e-mail addresses.

## Continuing

Checking in a continuing reservation can be quite challenging.

* First, you will want to ensure that the same room number has been allocated for the continuing booking, so that the guest will not be required to move. Ensure that this is done at the booking stage, as it may be harder to move bookings around on the day of arrival. Always lock your booking, so that no one can move the room.
* Check-out the current booking. The booking that is currently checked-in will have to be checked out. You can check it out by ticking the box "Check Out with Open Balance,” and it will leave the charges unpaid on the guest profile.
* Lastly, you can check in the new reservation, and once this is done, you will see that all the charges from the first booking are automatically transferred to this bill.

## Checkout

Once you have identified the booking, select the “Check Out” button on the booking screen. This button only appears on the booking on the day of departure or for bookings with a missed departure.

In case of error, users can undo checkout within your property's editable history window. Navigate to the `State` tab of the Reservation Module, look for the `Undo checkout` section, enter a reason and click the `Undo` button to complete checkout later.

## Balances

If the balance is zero, you can immediately check-out the reservation by clicking the “Check Out” button, and the customer is ready to leave. If the balance is not zero, click on the billing button, and you will be taken to the payment screen. To understand how to settle the balance, please refer to the section “Payment Screen” in this manual. Once the balance is settled, you can return to the check-out screen and check the room out.

Note if you need to check out a guest even though they have not yet settled the bill \(for example for a continue-ing booking\) this is possible, Next to the "Check-out" button, simply click "Check-out with Open Bill", provide a reason, and the reservation will be checked out. The bill will appear in the Guest Ledger, so that you can follow up on the payment.

Once the room is checked-out in the system, it will automatically turn "dirty" in the system so that housekeeping is informed that it requires cleaning.

