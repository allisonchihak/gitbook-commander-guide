# Export Schedules

Export schedules allow you to regularly and automatically send custom-configured reports to your e-mail or FTP server. For any report in Mews, you can choose your filters and control all settings, including time that reports are generated, set time-frames for the reports, and how often they're generate and sent. Below, you'll find a detailed explanation about how export schedules work and how to configure them properly.

## Create

In order to set up a Schedule, go to the report for which you would like to set up an export schedule. Set the correct filters as you'd like the information to be displayed in the export, then click the `OK` button and select `Create export schedule` to configure your export schedule.

Once you've clicked `Create export schedule`, the schedule is successfully created. Look for the green success message and you'll then be redirected to the export schedule settings, where you can edit and save all of your custom export preferences.

After completing the initial configuration, the screen is divided into 2 main sections:

* **Report configuration**
* **Export schedule**

Below, you'll find detailed information about all filters and settings available for your export schedule configuration.

## Configuration

Aside from `Interval`, all other filters in this Report Configuration section are the exact same as what you will find in each respective report. For more information about those filters, please see the information for the report that you'd like to create a schedule for. To see a full list of Reports in Mews, please [`click here`](../../).

The interval field determines a `Start time` and `End time` of the data included in your delivered export. Please note that most intervals begin and end at 00:00 for each respective time period. Therefore, you can assume that a full day would begin at 00:00 and end at 00:00 the next day, which includes a full 24 hours. This same logic can be applied to almost all of the following interval options, excluding `Last day`, `Last month`, and `Last week`.

* **Interval** - These intervals will determine what time period is included in the report being sent. You can choose from any of the following time intervals for daily reporting and exports will be labeled with the selected interval. Below you'll find `Start time` and `End time` descriptions of each interval option.
  * **Current day** - Today at 00:00 - tomorrow at 00:00
  * **Current moment** - Today at start time
  * **Current month** - First day of current month at 00:00 - first day of next month at 00:00
  * **Current quarter** - First day of current quarter at 00:00 - first day of next quarter at 00:00
  * **Current week** - Monday of current week at 00:00 - Monday of next week at 00:00 
  * **Current year** - First of January current year at 00:00 - first of January next year at 00:00
  * **Day after tomorrow** - Day after tomorrow at 00:00 - next day at 00:00
  * **Day before yesterday** - Day before yesterday at 00:00 - yesterday at 00:00
  * **Last day** - Yesterday at start time - today at start time
  * **Last hour** - One hour before start time - start time
  * **Last month** - One month ago at start time - today at start time
  * **Last week** - One week ago at start time - today at start time
  * **Month to date** - First day of this month at 00:00 - tomorrow at 00:00
  * **Next day** - Tomorrow at 00:00 - the day after tomorrow at 00:00
  * **Next month** - First day of next month at 00:00 - first day of the month after next at 00:00
  * **Next quarter** - First day of next quarter at 00:00 - first day of the following quarter at 00:00
  * **Next three months** - First day of next month at 00:00 - 3 months later at 00:00
  * **Next two months** - First day of next month at 00:00 - 2 months later at 00:00
  * **Next week** - Next Monday at 00:00 - the Monday after next at 00:00
  * **Next year** - Next first of January at 00:00 - first of January after next at 00:00
  * **Previous day** - Yesterday at 00:00 - today at 00:00
  * **Previous month** - First day of last month at 00:00 - first day of current month at 00:00
  * **Previous quarter** - First day of previous quarter at 00:00 - first day of current quarter at 00:00
  * **Previous week** - Monday of last week at 00:00 - Monday of current week at 00:00
  * **Previous year** - First of January last year at 00:00 - First of January current year at 00:00
  * **Rest of current month** - Today at 00:00 - first day of next month at 00:00
  * **Upcoming quarter** - Today at 00:00 - three months from tomorrow at 00:00
  * **Upcoming year** - Today at 00:00 - one year from tomorrow at 00:00
  * **Year to date** - First of January current year at 00:00 - tomorrow at 00:00

> #### Mews Clues
>
> Please note that all `quarter` intervals above \(excluding `Upcoming quarter`\) represent the four quarters of the year and will fall into one of the following time periods:
>
> 1. **January - March** - 00:00 1st Jan - 00:00 1st Apr
> 2. **April - June** - 00:00 1st Apr - 00:00 1st Jul
> 3. **July - September** - 00:00 1st Jul - 00:00 1st Oct
> 4. **October - December** - 00:00 1st Oct - 00:00 1st Jan

### Export Schedule

* **Enabled** - If this option is selected, it will activate this schedule and you will receive reports at the chosen `next start` time and `frequency`
* **Name **- This is the internal name you give the export. This will always be pre-filled with the Mews name of the report that you're exporting
* **Next start** - The time that reports are generated and sent to the creator. Please note that the Interval field on the left-hand side of this screen will all be based on the time that you choose here.  
* **Frequency** - How often would you like to the report to be generated and sent
  * **Hourly **- Repeating every hour starting at the specified time
  * **Daily **- Repeating every day at the specified time
  * **Weekly **- Repeating every week at the specified time
  * **Monthly **- Repeating every moth at the specified time
  * **Quarterly **- Repeating every quarter at the specified time
  * **Yearly **- Repeating once per year at the specified time
* **Export target** - this is the group of people who will receive the report at the specified interval. Please note that export targets are not required. If you do not choose a target, you will receive a notification in the system when your report is generated and will be able to download it directly. For more information about Export targets, please [`click here`](export-targets.md). 
* **Options**
  * **Notify creator about export** - select this option if you would like the system to display a notification for the creator of the report each time that report is exported and ready
* **Created \(UTC\)** - Date and time that export schedule was created
* **Updated \(UTC\)** - Date and time that export schedule was most recently updated

> #### Mews Clues
>
> Please note that in case of a timeout or system outage for any reason, reports will be resent immediately following the recovery of the system. If a job fails three times in a row, the report should be manually sent again.

