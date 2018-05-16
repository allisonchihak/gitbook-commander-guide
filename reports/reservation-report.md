# Reservation Report

The reservation report is the report with most data and filtering options to analyse the booking data of the hotel. Due to the amount of data, we can only display a limited amount on screen, however when you export it into Excel, we currently provide almost all reservations fields related to each booking.

* [Filters](reservation-report.md#filters)
* [Columns](reservation-report.md#columns)

## Filters

* **Mode**
  * **Detailed** - View individual bookings including all details for a more in-depth analysis
  * **Totals** - Summarize data to analyze report data more quickly and generally
* **Filter** - Narrow and organize your results by any of the following options
  * **Arrival** - All past, current, and future confirmed reservations, sorted by date of arrival
  * **Canceled** - All canceled bookings fully within selected time frame, sorted by date of arrival
  * **Canceled overlapping** - All canceled bookings that would have overlapped with the selected time period, including arrivals, departures, and stay overs within that interval
  * **Confirmed** - All confirmed bookings, regardless of current state and sorted by date of confirmation
  * **Covering** - Guests in house for the full duration of the selected time period, arriving before start and departing after end
  * **Created** - Bookings created within the selected period, sorted by date and time of creation
  * **Created or updated** - Bookings created or updated within the selected period, sorted by date of arrival
  * **Departure** - All reservations departing within the selected time period, sorted by date of departure
  * **In house** - Arriving and staying over within selected interval
  * **Optional** - All optional bookings, sorted by release date
  * **Optional confirmed** - All optional bookings that were confirmed, sorted by date of arrival
  * **Overlapping** - All reservations arriving, departing, and staying over within the selected period of time, sorted by date of arrival
  * **Stay over** - Not arriving nor departing, but staying for at least two nights within selected interval
  * **Updated** - All reservations that were updated at some point within the selected time period
* **Start date & time** - Results will start from this date and time
* **End date & time** - Results will end at this date and time 
* **Options**
  * **Include additional expenses** - Any additional charges not related to stay or products \(e.g. cancellation fees\)
  * **Include nights** - Include night revenue in report results
  * **Include products** - Include stay product revenue in report results, displayed in an additional column
  * **Load Balances** - Include the current open balance of customers, displayed in an additional column
* **Values**
  * **Gross** - Booking cost including tax
  * **Net** - Booking cost alone, excluding tax
  * **Tax** - Tax on bookings only
* **Group By** - Choose how you would like results sorted and displayed
  * **Arrival Date** - Sorted in chronological order
  * **Automatic Settlement** - View which accounts failed to settle automatically and check for failed payments
  * **Balance** - View the outstanding balance on any bills and quickly assess which accounts still need to be settled
  * **Business Segment** - View results according to the segments defined at your property
  * **Cancellation Reason** - View according to selected cancellation reasons
  * **Company** - View reservations connected to company profiles within your property
  * **Confirmation State** - Summaries of both `Optional` and `Confirmed` bookings
  * **Creation Date** - Sorted in chronological order
  * **Credit Card** - View whether guests have a credit card attached to their customer profile and identify reservations with failed card payments
  * **Customer Classification** - Sort by customer classifications, defined in the `Internals` section of the customer profile
  * **Customer Nationality** - View according to your customers' selected nationality
  * **Departure Date** - Sorted in chronological order
  * **Group**  - View group bookings with group name as the section titles; results are also ordered by group size from smallest to largest for easy classification
  * **Mother Company** - View all reservations connected to mother company profiles within your property, including revenue from all other subordinate companies
  * **Origin**  - Sort by each different booking origin
  * **Rate** - View results according to the rate types defined at your property
  * **Rate Group** - View results according to the rate groups defined at your property
  * **Room** - View results for each room number
  * **Room Type** - View results according to the space types defined at your property
  * **State** - View results by current reservation state
  * **Travel Agency** - View reservations connected with travel agencies defined at your property
  * **Voucher** - Sort results according to voucher codes used by customers
* **Rate** - Select a particular rate to see results related to that selection alone
* **Rate Group** - Select a particular rate group to see results related to that selection alone
* **Type** - View only results connected to a particular profile type
  * **Company** - Any reservation connected to a company profile; filtering by mother companies will include both child companies and all travel agency contracts that may be connected
  * **Customer** - Any reservation connected only to a customer profile
  * **Travel agency** - Any reservation connected to a travel agency
* **Travel agency branch** - Select one particular travel agency to view results connected to that profile; if selecting a travel agency that is a mother company to other travel agencies, please note that the child companies will appear in results
* **Company branch** - Select one specific company to view results connected to that profile; if selecting a mother company, please note that the child companies will appear in results
* **Origin** - View only bookings of one particular origin
  * **Channel** - Manually created reservations received via a third party channel \(e.g. OTA, Travel Agencies, etc.\)
  * **Channel manager** - Reservations received via channel manager automatically
  * **Commander** - All reservations manually created in Commander
  * **Connector** -  Reservations received via Connector
  * **Distributor** - All reservations created via Mews Distributor
  * **E-mail** - Reservations requested by e-mail
  * **Import** - Reservations imported from past property data
  * **Telephone** - Reservations requested by phone
  * **Walk-in** - Reservations created on site at customer's request
  * **Website** - Reservations made directly via your property's website

## Columns

Below is a description of a few of the Columns and their definitions.

* **Number** - Unique reservation number automatically generated by the system and assigned to the booking. All guest confirmations are sent with this number, which can be used directly in the search field to find a specific booking
* **Reservation Status** - An icon representing the current reservation status; hover over this icon to see the written form of status
* **Customer** - Name of the reservation owner displayed with classification icons; click on the name for a direct link to that customer's profile; hover over the icons to view the written label for each
  * **Companions** - Number of companions \(including owner\) listed in `icon x number` format
* **Created** - Date and time that booking was created
* **Arrival** - Date and time of arrival
* **Departure** - Date and time of departure
* **Room** - Assigned space
* **Space category** - Space category listed in its shortened format; hover over the short name to see the full title of any space category
* **Source** - An icon representing the source of the reservation data; hover over this icon to see source details
* **Rate** - Selected rate listed in its shortened format; hover over the short name to see the full title of the assigned rate
* **Products** - Any additional products added to reservation listed in `quantity x short name` format; hover over the short name to see the full name of any product; in case of stay products, they may be listed in `quantity x nights x short name` format
* **Company** - Name of company for business travelers or company-related bookings; click on the company name for a direct link to company profile
* **Travel agency** - Name of travel agency for bookings associated with any OTA; click on travel agency name for a direct link to company profile
* **Commission** - Amount for 
* **Rate** - Average night rate
* **Total** - Total amount due for booking
* **CC** - Credit card icon will appear for customers that have card details in their profile; click this icon to be taken directly to customer billing screen; hover over this icon to view last 4 digits and card type
* **Notes** - Any additional notes on reservation

## Hostels

If you export the report to Excel, we have also added the number of Bed Night columns, where all sold bed nights are added to the report. This is a critical number to the operations of a hostel, as they have a mix of rooms, dorms and beds, and they run performance based on bed occupancy and RevPab numbers.

## Practical Use

**Travel Agency Statistics** Run the report by totals, grouped by Travel Agent in order to get a Travel Agent Statistics report, to analyse the performance of your travel agents at the hotel. There is also a special "commission" column, so if you have set up the commissions in the travel agent profiles, you can see how much commission is to be booked over those reservations.

**Credit Card Check** The reservations department should tun the report in detailed mode, for all bookings created yesterday with the filter "Automatic Settlement"

This way you can quickly see if any of the automatic charges linked with newly made bookings have been rejected by the payment gateway, for follow up with the guests.

**Load Balances** If you want to ensure that everyone who is arriving on a specific date \(or is in house\) have 0 balance to be paid, you can simply tick the "load balanced" option. The report will then add an additional column with the bill balance of the customer linked to the booking.

**Canceled Bookings** Its important to check daily the reasons why the team have cancelled bookings, and to check that they have charged cancellation fees where needed. Therefore run the report with yesterday's dates, and filter by "cancelled on". Then you can quickly see all cancelled bookings. If you group it by "cancellation reasons, you can quickly see the main reasons selected.

Overlapping? To review all bookings in house during a specific period. Note that the "in house" overview includes 2 tables, the top-most table shows all bookings that are precisely in the interval. The second table shows all bookings that touch the interval, so if some of those bookings arrived prior to the selected or departed after, they are also included.

