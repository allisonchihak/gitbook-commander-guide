# Employee Profile

Employee profiles are used to give employees access to Mews. Using these profiles, you can track activity, assign responsibility, and allow or restrict the rights of each employee that works at your property.

The most senior member of your staff should be admin of your property, and must create the other profiles. All subsequently created profiles will be their subordinates in the system by default.

As there is no limit to the amount of profiles that can be created, employees should never share a profile.

You can navigate to the Employees page using the following path:

* **Main menu &gt; Settings &gt; Employees**

Here, you will see a current list of all existing employees in your system. Profiles are displayed in a hierarchical structure to give an accurate visual representations of the chain of command at your property. Employee profile images are also displayed next to each name for easy identification.

On the main page, you will see each employee profile listed with the following overview details:

* **Name** - Employee name as is entered in profile
* **E-mail** - E-mail address used to create account
* **Department** - Department in which this employee works
* **Admin** - This column will state `Yes` or `No`, indicating whether this person has been given admin rights. If `Yes`, they are awarded all privileges. If `No`, you can hover over this column to see a list of this person's privileges. Please note that the hover will only produce results for employees who are non-admin and but have been given other workplace privileges. For more information about admin privilege, please see below. 
* **Cashiers** - List of all cashiers that this employee is permitted to use
* **Authenticator** - Indicates whether user has enabled an authenticator for 2FA
* **Enabled** - Dates that employee profile will be active; if no dates are specified, field will say `For eternity`
* **Options** - Any additional privileges available for this employee's account

One major benefit of the Cloud, is that you can access the solution at any time from any location. This means that employees can access is also when they are not physically in the hotel, so it is important that hotels have a strict security policy in place ensuring they give employees the correct level of access. Once an employee resigns, ensure you remove them from your hotel on the day the employee leaves your company.

* [Create](employee-profile.md#create)
* [Privileges](employee-profile.md#privileges)
* [Chain access](employee-profile.md#chain-access)
* [Delete](employee-profile.md#delete)

## Create

From the main employee page, **look for the **`+`** icon in the top right-hand corner and click on it.** In the next screen, complete the following details to create each profile:

* **E-mail** - please note that only one employee profile can be linked with each valid e-mail address. 
* **Title** - Choose the title that best fits this employee. 
* **First Name** - Employee's given name
* **Last Name** - Employee's surname. Please note that this field is required.
* **Superior employee** - Here, you'll see a drop-down of other employees at your property. Choose the person that this new employee should report to. They will automatically be added to their proper place in the property's hierarchy, which is visible from the main Employees page.  

Once created, the employee's name, e-mail address, and title will not be editable. If incorrect, you must fully delete the profile and create a new one with the correct details.

**When all fields are correctly completed, click the **`Create`** button.**

Once the profile is created, an e-mail is sent to the employee with a one-time token, allowing them to log in and set their password.

For further information or to edit any profile, navigate to the main employees page and click on any person's name to make changes or see all additional details.

> ### Mews Clues
>
> It is not possible to create employee profiles in Mews without an e-mail address, as the initial login to the system is sent to that e-mail address.
>
> When you create a subordinate profile, you can assign that person the same or less rights than you have for yourself in Mews. Please note that it is not possible to create a profile for anyone who is higher in your property's chain of command.

## Privileges

Upon clicking the `Create` button, you will see these additional fields appear in their employee profile.

The following fields must be completed in to assign proper user rights and privileges for each employee:

* **Department** - Select that employee's [department ](../settings/users-settings/departments.md)to assign tasks or notifications to employees of that department only
* **Enabled from** - Choose the date of this profile's activation. \(e.g. if you have new hires starting later, give them access starting on a certain date\)
* **Enabled to** - Choose the date of this profile's deactivation. \(e.g. if you know an employee is leaving, use this to ensure you don't forget to restrict their system access\)
* **Admin** - Select this option to give a user admin rights. Admin users will automatically be given all user rights available in the system. In addition to those privileges, admin employees will be able to modify the [Editable History Window \(EHW\)](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/settings/finance-settings/accounting-configuration.html). If you select this option, the `Workplace privileges` selection will disappear, as all rights apply and it is no longer necessary. Please note that this privilege should be given sparingly and to your most trusted employees as it allows them to edit tax documents and important system data. 
* **Receive customer messages** - Select this option if user should receive messages from customers using the Mews Navigator
* **Workplace privileges** - Choose any of the following privileges that this user should have.
  * **Configure enterprise** - Access to change the general settings of the hotel \(e.g. e-mails, editable history window, etc.\)
  * **Configure services** - Employee can manage services and products**.**
  * **Configure Spaces** - Employee can modify spaces and place rooms Out Of Order. Please note that placing rooms OOO has a direct impacts your property's room inventory, so this privilege should be given sparingly.
  * **Issue Invoices** - Rights to create invoices with future payment date**.**
  * **Manage Companies** - User can create and manage Company Profiles
  * **Manage Customers** - User can create and manage Customer Profiles
  * **Manage Reservations** - User can amend booking details.
  * **Manage travel agency contracts** - User can create and manage Travel Agency Profiles
  * **Modify closed bills** - Rights to modify bill address, or assign bills to company or travel agency after they've been closed or issued
  * **Overbook Services** - Rights to create additional bookings even if space type is fully booked.
  * **Perform Housekeeping** - Rights to change room status 
* **Cashiers** - Assign one or multiple cashiers to the user.
* **Platform privileges**
  * **Manage employees** - Select this option if this employee should have access to create new employees. User will also be able to assign workplace privileges to the employee profiles that they create. This should be reserved only for senior management.

If an employee forgets their password, they can login to mews.li and use the password reset feature to have a link with instructions sent to their e-mail address.

## Chain Access

If you operate more than one property with Mews, one employee can be given access to all or some of your locations.

To give one user access to multiple properties, you must **create a new employee in each hotel using the same name and e-mail address**. The system will recognize the duplicate information and will automatically merge the accounts.

When this user logs in, they can switch between the newly added properties using the user profile icon in their dashboard header.

> ### Mews Clues
>
> Please note that when adding additional properties for a user to access, the system will not send a password setup e-mail to the user each time, as the password was already set upon the initial creation.
>
> If an employee forgets their password, they can use the password reset feature to have a link with instructions sent to their registered e-mail address.

## Delete

To delete a user, navigate to the main employee page, **click on the user profile, look for the trashcan icon in the top right-hand corner and click on it**.

If an employee leaves the company, its highly recommended to delete their user profile immediately. As Mews is a Cloud solution, they can access the system from anywhere, so its of the utmost importance that you have a strict departure procedure in place that ensures that all employee profiles in the PMS are deleted.

Please note that only superior employees have rights to delete users from the system.

> ### Mews Clues
>
> If you are deleting an employee that is the manager of a team, you must first migrate all of their subordinate profiles to a different superior employee before it will be possible to delete the user.

## Two-Factor Authentication

Within your user profile, users have the option to enable or disable two-factor authentication. If enabled, users must download an authentication application to their mobile device, which they will use to enter a unique code in addition to their chosen password each time that they log in to their user profiles.

Users may also choose to generate 10 recovery codes for their account. These code can be used for logging into the system in case of broken or lost phone. Please note that these codes should be safely stored by user as they will only be displayed once.

