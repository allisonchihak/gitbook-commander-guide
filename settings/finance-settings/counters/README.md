# Counters

Counters are used to assign numbers to bills as they are created and closed. Once created, each bill closed through that counter will follow a line of numbering to prevent duplicate bill numbers.

Properties will usually have one line of numbering, and any bill or invoice closed will follow this line of numbering, starting at 1, 2, 3, etc.

Via the bill counters its possible to set up unique numbers, or create multiple lines of numbering. Each document however can ONLY contain 1 number, once the document is created its locked and not possible to change that bill to another line of numbering, as its become a legal tax document.

## Create

To create a bill counter, navigate to the counter page location as described below:

* Main Menu - Settings - Property - Finance - Counters

Here, you can find a list of counters that are being used in the system.

You can create two types of Counter in Mews Commander:

* **Bill Counter** - Used for bills and invoices
* **Proforma Counter** - Used to preview bills and invoices. 

To create a new Counter, simply select the '+' button and select which type of counter you'd like to create.

You will need to complete the following fields.

The fields for both types are described just below, however please note that if you creating a Proforma counter, you will not see fields for Bill type code nor Display CID. Required fields are marked with \*

* **Value** - Enter the value from which you would like to start counting
* **Name\* -** what is the name of the bill counter
* **Number format** - should you wish to have your bills/invoices to start with a prefix number, this is the field where you can set this value. Note that Bills & Invoices \(currently\) share the same line of numbering. In order to set up for example a starting number 2015 in front of your bills, you have to follow it by a placeholder, to let the system know how to format it. So it would be 2015{0:0000}
* **Title** - important for accounting exports, to show if the bill has a specific title
* **Bill type code** - important for accounting exports, to show if the bill has a specific accounting code
* **Display CID** - Bills and Invoices will display CID codes. This option is only applicable to properties in Norway.

## Manage

To manage a bill counter, navigate to the counter page location as described below:

* Main Menu - Settings - Property - Finance - Counters

Here, you can find a list of counters that are being used in the system listed with the following information:

* **Name** - Name that you have chosen for this counter
* **Is default** - yes or no. Only one counter may be default. 
* **Value** - Current number of bills that have been closed using this counter
* **Number format** - 

From this page, you can:

* [Create a Bill Counter](create-a-counter.md)
* [Create a Proforma Counter](create-a-counter.md)

To manage a counter, click on the title.

From within each counter page, you can:

* [Make a counter default](default-counters.md)
* [Reset a Counter](reset-a-counter.md)
* [Delete a Counter](create-a-counter.md)

> #### Mews Clues:
>
> Please note that default invoice counters can be set in [Accounting Configurations](../accounting-configuration.md)

## Delete

To delete any bill counter, simply open the counter, and click on the trashcan icon to delete it.

## Service Order Counters

A service order counter is used to process only service orders.

Each service order is automatically assigned a number from the moment that it is created, starting with 1.

Currently, it is not possible to change this line of numbering. You may reset your counter at any time, but Mews would not recommend doing so because it may cause duplicate orders, which could then conflict with your accounting reports.

> #### Mews Clues:
>
> Please note that it is not possible to have more than one service order counter
