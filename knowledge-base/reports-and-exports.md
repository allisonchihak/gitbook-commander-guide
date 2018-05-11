# Reports & Exports

Article in progress. More Knowledge Base content coming soon!

## Stripe Trial Balance

We do not have a specific report in Mews that will calculate a trial balance, but you can easily do this using the `Accounting Ledger` and `Accounting Report`. Below, you can find a description of how to calculate the Trial Balance for a certain period.

**1.** Navigate to the Accounting ledger report using the following path:

**Main Menu &gt; Finance &gt; Accounting ledger**

You can also access this report directly from the Mews Dashboard.

Choose the following options for each filter:

* **Mode** - Detailed
* **Type** - Guest ledger
* **Date & Time** - Choose the correct date with 00:00 as the time
* **Group by** - Customer
* **Tax** - Included
* **Options** - Highlight open payments should be selected

  When all fields are correctly completed, click `OK` and select `View report`

  On the very last line of the report, in the `Totals` row and the `General ledger` column, you will find the total balance. Copy this number for calculation in step 3.

**2.** Navigate to the Accounting report using the following path:

**Main Menu &gt; Finance &gt; Accounting report**

You can also access this report directly from the Mews Dashboard.

Choose the following options for each filter:

* **Type** - Consumed
* **Mode** - Grouped
* **Start Date & Time** - Choose the correct date with 00:00 as the time \(e.g. March 28\)
* **End Date & Time** - Select the following date after the selected start date with 00:00 as the time \(e.g. select March 29 to check data for March 28, as this will produce the revenue and payment data for March 28\)

  The rest of the fields can be left on their default settings, which are pre-selected when you open the report:

* **Group by** - Accounting category
* **Asignee** - Company, Customer
* **Bill counter** - no selection
* **Company** - no selection
* **Service** - no selection

  When all fields are correctly completed, click `OK` and select `View report`

Copy the totals under both the `Revenue` and `Payments` sections for the following calculation.

**3.** Lastly, calculate the final trial balance using the following formula:

**Accounting ledger total + Revenue total - Payments total = Trial Balance**

If you open the Accounting ledger report with the same filters but with `Start date` selected as the next day \(e.g. 29th March\), the total at the end of that report, in the last column, will match the number you calculated in the previous step.

## STR Export Schedule

Setting up automated reporting for STR is an easy and straightforward process with Mews Commander. You can set up an STR reporting schedule for two different types of data sets:

1. Existing data regarding the number of spaces sold the previous day
2. Future predicted occupancy and availability data for the following year. This calculation is estimated based on the previous year's occupancy and availability information. 

### Existing data

1. Within Mews Commander, navigate to the `Occupancy Report` by either clicking the direct link on the dashboard or using the following path:
2. **Main Menu &gt; Reservations &gt; Occupancy**
3. Look for the `OK` button, click on it, and select `Create export schedule`
4. Next, you will be automatically redirected to your export schedule settings. Under the `Report configuration` section, choose the following options for each filter:
   * **Mode** - Occupancy
   * **Interval** - Last day
   * **States** - Select all \(confirmed, optional\)
   * **Values** - Net
   * **Space types** - Select all
   * **Rate mode** - Average night rate
   * **Rate** - `-` \(No selection\)
   * **Company** - `-` \(No selection\)
   * **Travel agency** - `-` \(No selection\)
5. When all fields are completed as described above, click `Save` under the `Report configuration` section.
6. In the `Export schedule` section, choose the following options for each filter:
   * **Enabled** - Select this box to activate automated reporting
   * **Name** - Create a title for the report; Please note that this title will be listed after `Occupancy report`
   * **Next start** - Select tomorrow's date and choose 07:00 as the time
   * **Frequency** - Daily
   * **Export target** - Select the `+ E-mail` option and, in the next screen, complete all fields as described below:
     * **Name** - Select a title for this target, which will be available later for other export schedules
     * **To** - Complete with the e-mail address provided by STR \(data\_daily@str.com\)
     * **Cc** - If you would like anyone else to receive these reports, include those e-mail addresses here
     * **Bcc** - If you would like anyone else to receive these reports, include those e-mail addresses here

       When all fields are completed, click `Create`and you will see that these details will be pre-filled in the `Export target` field.
   * **Format** - Select which file format you would like to receive
   * **Options** - Select the `Notify creator about export` option if you would like to be notified each time that the report is generated
7. When all fields are complete, click the `Save` button under the `Export schedule` section.

After clicking save, your export schedule should be complete and enabled. Starting the following day, reports including yesterday's data will now be created every day at 7 AM and automatically sent to the STR e-mail.

### Future data

1. Open Mews Commander.
2. Navigate to the `Availability Report` by either clicking the link on the dashboard or using the following path:
   * **Main Menu &gt; Reservations &gt; Availability** 
3. On the right-hand side under the reporting filters, click the `OK` button and then select `Create export schedule`.
4. In the `Report configuration` section of the page, set up the following attributes:
   * **Mode** - Occupancy
   * **Interval** - Upcoming year
   * **States** - Select all \(confirmed, optional\)
   * **Values** - Net
   * **Rate mode** - Average night rate
   * **Rate** - Leave blank
   * **Company** - Leave blank
   * **Travel agency** - Leave blank
5. Click the `Save` button under the `Report configuration` section.
6. In the `Export schedule` section, set up the following attributes: 
   * Tick the "Enabled" box \(to activate automated reporting\)
   * **Name** - Create a title for the report
   * **Next start** - Select next Monday, at 7 AM
   * **Frequency** - Weekly
   * **Export target** - Select the `+ E-mail` option; fill in the box labeled "To" with the e-mail provided by STR \(auto\_data@forecaster.str.com\) and click `Create`
   * **Options** - Select the "Notify creator about export" option if you would like to be notified
7. Click the `Save` button under the `Export schedule` section.
8. An Excel report for yesterday's data will now be created every Monday at 7 AM and automatically sent to the STR e-mail.

