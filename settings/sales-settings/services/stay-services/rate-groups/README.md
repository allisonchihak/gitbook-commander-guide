# Rate Groups

## Rate Groups

Rate groups are groupings of different rates that use the same cancellation fees. Rate groups help to improve user experience by automatically displaying the lowest available rate, which allows customers to easily select the best price when booking.

To create, manage, and delete rate groups, navigate to the rate groups page using the following path:

* **Main menu &gt; Setting &gt; Services &gt; Stay &gt; Rate groups**

## Create

To create a new rate group, look for the `+ icon`, click on it, and complete the following fields:

* **Name** - Name of this rate group, for example "Non-Refundable"
* **Settlement** - Choose your property's preferred method of settlement
  * **Automatic** - Automatically settle payments via the system
  * **Manual** - Employees should manually process and settle payments
* **Settlement action** - Desired action at the time of settlement trigger. Please note that settlement action only applies to automatic settlements.
  * **Charge credit card** - Card on file will be charged at the time of settlement trigger including any applicable offset
  * **Create preauthorization** - Preauthorization will be created for the card on file at the time of settlement trigger including any applicable offset, however card will not be charged until manually processed by an employee
* **Settlement trigger** - Select the time when the system should automatically charge accommodation cost. Please note that settlement trigger only applies to automatic settlements.
  * **Creation** - Time that booking is created
  * **End** - Date and time of customer's departure
  * **End date** - Date of departure at 00:00
  * **Start** - Date and time of customer's arrival
  * **Start date** - Date of arrival at 00:00
* **Settlement offset** - Amount of time either subtracted from or added to the settlement trigger time, with negative values subtracting time and positive values adding time. Please note that `Settlement offset` only applies to automatic settlements. 
* **Settlement value** - Percentage of the total booking value that will be charged at the time of `Settlement trigger` \(including `Offset`\). Please note that `Settlement value` only applies to automatic settlements. This value can be greater than 100% in the case that you would like to automatically create preauthorizations including an extra charge in case of damages. The property can then charge a lower amount than is preauthorized at the time of checkout, but cannot charge higher. 
* **Maximum nights for settlement** - Select the maximum number of nights that should be charged automatically as part of automatic settlements. This value will apply only to rate groups with automatic settlements enabled. 
* **Extent** - Choose which items should be included as part of automatic settlements. 
  * **Additional expenses** - Include any additional items applied to cost of stay \(i.e. extra fees, deposits, etc.\)
  * **Nights** - Include cost for all nights; this field is limited by the `Maximum nights for settlement` field
  * **Products** - Include cost of all stay products \(i.e. Breakfast, Parking, etc.\)
* **Options**
  * **Automatic deposit settlement** - Select this option to automatically post deposits to customers' bills. Please note that this option is only applicable for countries where VAT is paid at the time of payment of the booking \(Czechia, Germany, Denmark, etc.\).
* **Short name** - An abbreviated label for this rate group, which is used for reference where space may be limited.
* **Description** - A short description of this rate group to display to customers while booking. This space could include cancellation policies or any other further information. 
* **Ordering** - To organize your rate groups in a specific way, use this field to specify the correct order display, with lower numbers appearing first and higher numbers appearing last. 

When all information is correctly entered, click the `Create` button.

This rate group was successfully created. You will see three additional items appear:

* **Created \(UTC\)** - Time that rate group was created
* **Updated \(UTC\)** - Time that rate group was most recently updated
* **Cancellation policies** - This link will appear under your rate group settings. For more information, please see our article about [`Cancellation policies`](cancellation-policies.md).

### Delete

To delete a rate group, navigate to the main rate groups page and click on the name of the unwanted rate group. Look for the trashcan icon, click on it, and confirm your deletion.

> #### Mews Clues
>
> Please note that once a rate group is deleted, this action cannot be undone. If you have mistakenly deleted a rate group, you must completely recreate it.

