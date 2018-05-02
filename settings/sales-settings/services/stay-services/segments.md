# Segments

Segments are used to classify the reason of each visit to their hotel. This is then used for statistics and analysis of your property's visitors.

Every reservation in the system has a different segment, which is assigned based on the source and reason for the booking.

Navigate to the main `Segment` page using the following path:

* **Main Menu &gt; Settings &gt; Services &gt; Stay &gt; Segments**

From this page, you will see a list of all segments currently being used in your property. You can also create, edit, or delete segments as needed.

* [Create](segments.md#create)
* [Settings](segments.md#settings)
* [Priority](segments.md#priority)
* [Delete](segments.md#delete)

## Create

**To create a new segment, navigate to the main **`Segment`** page, look for the **`+`** button and click on it.** A new window will automatically appear, where you can enter the desired name and then click `Save`.

## Settings

In your primary stay settings, you can find the following items that are related to segments:

* **General settings**
  * **Channel manager segment** - Define a segment for all bookings made via Channel Managers
  * **Distributor segment** - Define a segment for all bookings made via Mews Distributor
  * **Default segment** - Define a segment that will automatically be preselected for new bookings made in Mews Commander. This field is editable before finalizing booking details. 
* **Options**
  * **Has configurable segment** - If no default segments have been selected \(in above section\), then deselecting this option means no `Segment` field will be offered to users

## Priority

Default segments can be assigned in several different places throughout the system. Therefore, as you choose your property settings, it is important to understand the priority of assignment.

According to Mews, the order of priority is as follows:

1. Travel Agency
2. Channel Manager 
3. Assigned Rate
4. Visit

The first source of data from this list will be the segment that appears in the your property's data. So, for example, if you do not have any segment assigned to your `Travel agency profile` or `Channel manager`, the information would be taken from the third, but first completed option, which in this case is `Assigned Rate`.

## Delete

To delete a segment, navigate to the main `Segment` page. **Click on the name of the unwanted segment, look for the **`trashcan`** icon, click on it, and confirm deletion.** You will be automatically redirected to the main segment page, where that segment will no longer be visible.

