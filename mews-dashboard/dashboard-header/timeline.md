# Timeline

The timeline is the graphical display of all bookings in a selected time period, organized primarily by room type and secondly by room number within that room type. Within the timeline, you can zoom in and out to view more or less data. This is useful not only to display a greater number of bookings simultaneously, but also to optimize usage on mobile devices.

Below, you can find a detailed description of all features, filters, and data available within the timeline and how to best use them.

## Filters

At the top of the timeline you are provided with a few different filters:

* **Arrows** - Double arrows will move the timeline forward or back one month. Single arrows will move the timeline forward or back by one week.
* **Today** - This button will always take you back to today's date, which will always be highlighted in blue
* **Select date** - Use this date-picker to quickly skip to a specific date
* **Select space** - Search by the name of your space categories or by room number to view spaces with matching criteria in the drop-down menu
* **House Use Booking** - Use the `House` icon to block spaces for internal use; for more information please see below

## House Use

House use bookings are used to block spaces for internal use. This feature can be used to create reservations for your property's employees or management. Please note that house use bookings will block spaces from your sales, but will not impact your average rate and occupancy data, as the room is used for internal purposes.

, so they should be used sparingly as to not interfere with your revenue.

To create a `House Use Booking`, navigate to the `Timeline`, look for the `House` icon, and click on it. In a new window, you will see the following fields to complete:

* **Name** - Enter a brief description which will be displayed in the reservation block
* **Assigned room** - From the drop-down list, select the room that you'd like to book
* **Start** - Date and time that house use booking should begin
* **End** - Date and time that house use booking should end
* **Notes** - Any additional notes or information that you'd like to include

When all details are correctly entered, click `Create` and you will be automatically redirected to the timeline, where you can find the reservation block.

> ### Mews Clues
>
> Please note that when a house use booking begins, when it ends, and overnight, the room status will automatically change to `Dirty`.

## Spaces

The far left column in the timeline contains a list of your space categories. As you zoom in and out, you may notice that `Short names` are often used here as space becomes limited. Within each of these space categories, you will see all corresponding space names or numbers, each with it's own row. If any spaces contain other spaces, you will see that represented as each subsequent space will also be given its own row in the timeline.

All space numbers are clickable and are a direct link to the corresponding space properties page for each. The space properties page for each one contains all details regarding the status of that space. From this screen, you can quickly change the status of the room to `Dirty`, `Clean`, `Inspected`, `Out of service`, or `Out of order`. You can also find a summary of any recent `Out of order blocks` and any recent space state changes. Space numbers are also displayed in the corresponding space status color for easy identification.

## Reservations

Bookings appear as blocks on the timeline, which occupy a period of time that corresponds with the length of the booking. The timeline space blocks all accurately represent both arrival and departure times for each booking and are always displayed in the appropriate Mews action color.

Each booking is displayed with the name of the reservation owner in `Last name, first name` format. If the customer has been assigned any `Customer Classifications`, you will also see those corresponding icons just after the customer name.

A `Face` icon may also appear before the name of the customer, which indicates that the reservation is for a female guest who has booked one single bed in a dormitory or multi-bed space. This feature is very useful for hostels that promote all-girl dormitory spaces.

You may also find a `Lock` icon displayed before the customer name, which is described more fully below.

When you click on any booking, you will see that reservation's [`Simple detail`](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/reservations/simple-detail.html) open automatically in a modal window. From this screen you can select the `Manage` or 'Group' buttons to open the `Reservation module`, or use the applicable action button to `Check in` or `Check out` that booking. Within the `Simple detail`, you can click on the icon next to the guest name for a direct link to that customer's profile, where you can manage any of their personal details as needed. For more information, please see our article about [`Simple detail`](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/reservations/simple-detail.html).

> ### Mews Clues
>
> The timeline will automatically attempt to resolve any time conflicts created by arrival and departure times. For example, if the departure time of a booking is after 15:00 while there is another booking arriving in that same space at 14:00, the system will automatically try to reallocate the arriving booking to resolve this issue.

## Move

Click, drag, and drop any unlocked reservation blocks to move them across the timeline.You can use this method to update reservations to a higher space category.

Once you have dragged-and-dropped a booking into a higher category, an `Upward arrow` icon will appear on the reservation block in front of customer name, indicating that the booking was upgraded. Please note that if the booking is not locked after being upgraded, the system may try to move it back down to the originally booked space category for revenue optimization. To prevent this from happening, Mews would recommend that you change space category in the `Reservation Module` under the `Properties` tab.

The timeline does not allow downgrading reservations to a lower category using drag and drop, which is helpful for preventing accidental downgrades. If you do wish to downgrade a space category, you must do this manually in the `Reservation Module` under the `Properties` tab.

If one unlocked reservation block is moved and then dropped on top of another, the system will automatically try to reassign the booking that was previously in that slot. If there is not another suitable room, that booking will be placed into an overbooking slot. Once a booking is placed into the overbooking slot, they must be manually moved to a suitable room allocation. For more information about overbookings, please see below.

## Lock or Unlock

When you select a booking on the timeline, all booking information will appear in the `Simple detail` window on the right. Within this window, you can find a `Lock` icon, which you can use to lock or unlock this booking from being edited.

Locking the reservation means that the booking can no longer be moved. Locking rooms is primarily used to prevent employees from moving any reservations accidentally. Properties may want to lock a booking for various reasons, for example, a returning guest may have specifically requested their assigned space.

Bookings will only be unlocked by the system automatically in the case that arrival or departure dates are edited. Therefore, please note that after editing these booking details, the user must lock the reservation again to prevent it from being moved.

## Overbooking

When new bookings are created, they are automatically allotted to a space on the timeline. If a property has overbooked a category, meaning they've created more bookings than the number of spaces available, the system will automatically create `overbooking slots` in which it will place the reservation until the property is able to resolve the conflict.

These slots are displayed in red, indicating that urgent action is required, and are used as temporary placeholders for bookings that have not yet been moved to an available space.

You can resolve overbookings by moving the reservation block from the `overbooking slot` to a vacant space, which will then automatically remove that `overbooking slot` from the timeline.

> ### Mews Clues
>
> Please note that you cannot manually place bookings into `overbooking slots`, as the system is designed to remove these spaces as soon as possible. The only way to close them is by moving bookings into vacancies in your other space categories, even if it may be a higher or lower space category than was originally requested.

## Settings

Below, you can find a list of all settings that are relevant to the timeline.

Navigate to your stay settings using the following path:

* **Main Menu &gt; Settings &gt; Services &gt; Stay**

Within the `General settings` tab, you can find the following settings to consider:

* **Reservation assignment strategy**
  * **Bottom up** - New reservations will be assigned starting with lower room numbers first
  * **Top down** - New reservations will be assigned starting with higher room numbers first
  * **Random** - Rooms will be assigned at random, ensuring that all rooms receive the same number of bookings and wear. Please note that if you have a lot of business travelers, we recommend against this setting, as it will spread groups all over the hotel.
* **Availability calculation strategy**
  * **Diffusive** - Overbookings will transfer to your lowest available space category and those numbers would automatically reflect in your availability calculation system-wide
  * **Discrete** - Prevent overbookings from affecting the vacancy of any space types that were not originally selected

