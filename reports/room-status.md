# Room Status

The Room Status report can be used by housekeepers and managers to easily track the housekeeping status of all the rooms in your property. A quick visual overview of this report is always visible with the `Room Status Donut`, which can be found on the Mews Dashboard. For more detailed information about each different `Room Status` in Mews, please `click here`.

Below, you will find a detailed description of all features and filters available on the Room Status Report. You'll find information about the following items:

* [Housekeeping Assignment](room-status.md#housekeeping-assignment)
* [Filters](room-status.md#filters)
* [Features](room-status.md#features)
* [Out of Order](room-status.md#out-of-order)
* [Settings](room-status.md#settings)
* [Automatic changes](room-status.md#automatic-changes)
* [Housekeeping application](room-status.md#housekeeping-application)

## Housekeeping Assignment

Within the report header, on the right-hand side, you will find the hand icon, representing one of the most important features available with this report:

* **Hand icon** - This icon will allow you to evenly assign spaces in any selected state between the housekeepers that are currently working at your property

When you click on the `Hand` icon, you will be redirected to the assignment form, where you will see the following options:

* **Employees **- Select which employees you'd like to assign to rooms. If multiple employees are selected, items will be distributed between them evenly. Please note that each space can only be assigned to one person. 
* **State **- Selected employees will be assigned to only this state of room. For a more detailed description of the different housekeeping states, please [`click here`](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/chapter1/about-commander/dashboard-donuts/room-status-donut.md). 
  * **Clean **- Assign employees to clean rooms that need to be inspected
  * **Dirty **- Assign employees to dirty rooms that need to be cleaned and inspected
  * **Inspected **- Assign employees to already inspected rooms, if needed
  * **Out of order** - Assign employee to rooms that need major repair
  * **Out of service** - Assign employee to rooms that need minor repair
* **Space types** - Select which space type you'd like to assign employees to. Please note that 'Bed' will automatically be unselected. This is because it can complicate assignments if one employee is assigned to a bed and a different employee is assigned to the room containing the bed. 

Click the `OK` button when all of the selected options are correct and look for the green success message.

From here, you will be redirected back to the Room status report, where you will see the the selected details. The `Group by` filter will automatically be pre-filled with 'Assignee' and you will see each employee next to a list of all rooms that they are responsible for cleaning.

## Filters

At the top of the report there are several options you can select to narrow down the report:

* **Options **- show or hide any of the following features:
  * **Display customer notes** - See any additional notes on that customer's profile
  * **Display products** - See any stay products that this customer has ordered
  * **Display reservation notes** - See any additional notes on that particular reservation
* **Filter **- Choose what types of reservations you would like to see based on the state of the reservation. Please note that the results are heavily dependent on date selected. 
  * **\(no selection\)** - Use this option to see all reservations, regardless of state
  * **Arrived **- Reservations that have already arrived and completed check-in
  * **Arrived or arriving** - Reservations that have already arrived that day or will be arriving later that day
  * **Arriving **- Reservations that will be arriving at some point during the selected date
  * **Departed **- Reservations that have already completed checkout and departed on that day
  * **Departed and arriving** - Groups that have already departed with another group arriving the same day in the same space
  * **Departed or departing** - Those that have already completed checkout and departed and those who will be departing that day
  * **Departing **- Reservations that will be departing at some point during that selected date, but have not done so yet
  * **Departing and arriving** - When a group will be departing that day with another group arriving that day in the same space
  * **House use** - Reservations booked for a member of the hotel staff or being used for a property-related event
  * **No arrival nor stay over** - Any booking that is not arriving that day nor staying over after having already arrived previously
  * **No departure nor stay over** - Any booking that is not leaving that day nor staying over after having already arrived previously
  * **Out of order** - Any room that is blocked from being reserved and taken from inventory because of need for repair or any other reason that would prevent guests from staying in that space
  * **Stay over** - Any booking of that is staying overnight and has neither arrived that day nor will be departing that day
  * **Used **- Any room currently being used or that will be used later that day. You'll also see rooms marked `Out of Order.`
  * **Vacant **- Any room that is not occupied
  * **Vacant or departed** - Any room that is not occupied or has had a guest that departed from that room earlier that day
* **Assignee **- This drop-down will display a list of all employees registered at your property. Select the employee whose results you'd like to see on the report
* **State **- if you would only like to see rooms in a specific housekeeping state \(for example, the supervisor would only like to see only "clean" rooms which require inspection.\) You may choose from any one of the following options, although please note that you may only select one at a time. To see detailed descriptions of all our room statuses, [click here](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/chapter1/about-commander/dashboard-donuts/room-status-donut.md). 
  * **\(no selection\)** - Use this option to see all reservations, regardless of housekeeping state
  * **Clean **
  * **Dirty **
  * **Inspected **
  * **Out of order** 
  * **Out of service** 
* **Group by** - View your results in order of any of these following items
  * **Assignee **- View results according to the employee assigned to them 
  * **Category **- View results in order of space category
  * **Floor **- View in order of building floor
  * **State **- View results according to current room state
* **Floor **- Shows only units located on the particularly selected floor
* **Room category** -  Select only a particular room category for more specific results
* **Date **- Select any day to see its results. Date field with automatically be pre-filled with current date.

## Features

The Mews Room Status Report is organized, by default, as a list of each space within your property ordered by `Floor` \(including rooms, beds, apartments, etc.\) Use the `Group by` filter to change the organization of the report and customize the way that you view your results.

Each room number is followed by a drop-down menu, where you can instantly change the status of any space.

The primary feature is the real time representation of current and upcoming reservations, with the vertical dotted line representing the current time.

Each reservation is displayed with the following information:

* **Date or time of arrival** - If arrival is on the same day, time will be displayed, but if arrival is on a different day, date will be displayed. 
* **Number of companions** - number of guests expected for reservation
* **Customer name** - Click on the name of the customer to be taken directly to their [`Customer Profile`](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/profiles/customer-profile/customer-profile-sections/dashboard.md).
* **Internals** - Any internal indicator icons will be displayed next to the customer's name
* **Date or time of departure** - If departure is on the same day, time will be displayed, but if departure is on a different day, date will be displayed. 

Using the filters, you can also choose to include:

* **Customer notes** - Any additional notes or information on the customer's profile
* **Products** - Any products that were included with reservation or added by customer and the quantity of each
* **Reservation notes** - Any additional notes or information about that reservation

`House use` reservations and `Out of Order` blocks will be displayed with the following details:

* **Start date or time** - If start is on the same day, time will be displayed, but if start is on a different day, date will be displayed. 
* **Name** - Name entered at time of creation. This should be a short description of the problem or reason for reservation.
* **End date or time** - If end is on the same day, time will be displayed, but if end is on a different day, date will be displayed. 

Furthermore, upcoming events will be displayed with a lightning icon, indicating that guests will be arriving soon and all final arrangements should be completed urgently.

## Out of Order

Find the room that you'd like to place `Out of Order` and click on the room number. Next, you will be directed to the room properties screen.

On the right-hand side, look for a button labeled `Place room out of order` and click on it. Then, you will be redirected to another screen with the following fields:

* **Name** - Enter a short description of the problem
* **Assigned room** - This will be preselected with the room number you've clicked on. You can also select a different room from the drop-down menu. 
* **Start date & time** - Choose the date and time that the `OOO` block should begin
* **End date & time** - Choose the date and time that the `OOO` block should end and the room will be back in working order. Room status will automatically change to `Dirty` at this selected end time. 
* **Notes** - It is important to include the reason why the room has been placed `Out of Order` to keep your staff informed. You may also include any other additional notes regarding the issue. 

When all information has been correctly entered, click the `Save` button and you will automatically be redirected to the room properties screen. Here, you will see this newly created block on the right-hand side under `Out of order blocks`, where the details about OOO state will be visible. You may edit any of this information later by clicking on the name of the block.

Please note that if a parent space is placed `OOO`, all child spaces within will also be placed `OOO` for the same block of time.

## Settings

Within your Stay settings, properties may choose to enable automatic room status changes for housekeeping's convenience. You can find a few different options in Stay services. Navigate to your Stay service settings using the following path:

* **Main menu &gt; Settings &gt; Services &gt; Stay &gt; Options &gt; Visit Options**

Here, you can find and enable any of the following items related to room status:

* `Change inspected to clean overnight` – Vacant rooms that have been `Inspected` will automatically change to `Clean` between 04:00-05:00 every morning. If this option is not selected, room status will remain the same for 7 days before automatically being change to `Dirty`.
* `Check-in makes room dirty` – Room status will automatically change to `Dirty` at the time that the customer is checked in
* `Checkout makes room dirty` - Room status will automatically change to `Dirty` at the time that the customer is checked out

**Housekeeping interval**

`Housekeeping interval` is a setting used to automatically change room status from clean to dirty after a specified period of vacancy. Within your settings, properties can choose the number of days between the last change and the system's automatic change to `Dirty`.

This option is used so that properties can ensure the quality of cleanliness in case there is an unnoticed change within the time that any space is unoccupied. Navigate to your Stay service settings using the following path:

* Main menu - Settings - Services - Stay - General Settings – Housekeeping interval

If `Housekeeping interval` is set to 1 day, the room will automatically be changed to `Dirty` every 1 day. Each unit represents a period of 24 hours, with automatic changes occurring between 04:00-05:00.

## Automatic Changes

**House use & Out of Order**

When a room is reserved for `House use` or a room is placed `Out of Order`, the user must specify both starting and ending date and time, which will appear as a reserved block that is visible from the [Timeline](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/chapter1/dashboard-header/timeline.md). At the date and time that the block ends, `Room status` will automatically change to `Dirty`.

**Vacant**

If a room is vacant and unoccupied for 7 consecutive days, `Room status` will automatically change to `Dirty` due to regulations in Benelux countries. These regulations state that all water sources in the room must be flushed after this time to prevent a potential legionella outbreak.

For this reason, across all hotels, the system will change `Room Status` to `Dirty (Legionella)` to remind housekeeping that they need to flush all water sources \(shower, taps, etc\). Rooms will include a note stating `Unchanged room`.

Before 7 days of inactivity, rooms status will not change automatically unless you've selected the `Change inspected to clean overnight` option in your stay settings.

**Occupied**

Each night, the system will automatically change the room status of all occupied rooms to `Dirty.`

**Assigned space**

When moving checked-in reservation from one room to another, `Room status` of both rooms will change to `Dirty`, including a note stating `Reservation change`. Please note that if a reservation is already checked-in, it must be shortened and checked out. The property must then create a new reservation for the same customer before they can be moved to another room. Therefore, the setting option of `Checkout makes room dirty` would also apply to this situation.

**No-shows**

In case of no-show reservations and therefore no customer being checked in, that reservation's assigned room status will no longer change to dirty overnight. This is with the assumption that nobody ever occupied the room and therefore the room is not necessarily dirty.

> ### Mews Clues
>
> When a bed within a dorm is included in filtered results, such as departed or departing, the system will show only matching beds, even if the room as a whole would not be included in those same results. If there are beds of another state included in that same room, they will not be displayed.

## Housekeeping Application

For most properties, the average housekeeping shift starts at 08:00 and ends at 16:00. Therefore, theoretically the rooms are cleaned and inspected in the same order. However using this report, you will find that the bulk of rooms are changed to `inspected` between 15:00 and 16:00.

This means that the housekeepers do not have the tools to easily and quickly communicate when they've finished cleaning a room. This miscommunication often has an adverse effect on guests, as rooms may be cleaned and ready, but guests are still not able to check-in before their official check-in time.

Mews offers a great housekeeping app, both for iOS and Android, offering your housekeeping department a great tool to optimize their speed at which they inspect rooms in the system.

