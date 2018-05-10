# Reports & Exports

Article in progress. More Knowledge Base content coming soon!

## Calculate a Trial Balance

We do not have a specific report in Mews that will calculate a trial balance, but you can easily do this using the `Accounting Ledger` and `Accounting Report`. Below, you can find a description of how to calculate the Trial Balance for a certain period.

**1.** Navigate to the Accounting ledger report using the following path: 

  **Main Menu > Finance > Accounting ledger**

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

  **Main Menu > Finance > Accounting report**

  You can also access this report directly from the Mews Dashboard. 

  Choose the following options for each filter:
  * **Type** - Consumed
  * **Mode** - Grouped
  * **Start Date & Time** - Choose the correct date with 00:00 as the time (e.g. March 28)
  * **End Date & Time** - Select the following date after the selected start date with 00:00 as the time (e.g. select March 29 to check data for March 28, as this will produce the revenue and payment data for March 28)

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


If you open the Accounting ledger report with the same filters but with `Start date` selected as the next day (e.g. 29th March), the total at the end of that report, in the last column, will match the number you calculated in the previous step.
