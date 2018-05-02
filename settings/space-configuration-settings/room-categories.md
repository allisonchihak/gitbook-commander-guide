# Room Categories

Before settings up your [rooms](rooms/), it's important to create the different room categories, which will be assigned to each room number.

Navigate to the main room categories page using the following path:

* **Main menu &gt; Settings &gt; Property &gt; Space configuration &gt; Room categories**

On this main page, you will see a list of all the categories available at your property, including the following information for each:

* **Name** - Full name of the room category
* **Space type** - Choose between apartment, bed, dorm, room, or suite
* **Capacity** - Number of people that this room can accommodate normally
* **Extra capacity** - Number of additional beds that can be used to accommodate guests

## Create

**To create a new room category, look for the **`+`** button and click on it.** Complete the following fields to create a new category:

* **Space type** - Select the most applicable description of the space 
  * **Apartment** - A set of rooms for individual occupancy, usually including household utilities
  * **Bed** - Used for single occupancy and often contained in a dormitory 
  * **Dorm** - One large room containing several single beds
  * **Room** - One single room
  * **Suite** - A set of rooms designated for one reservation group
  * **Villa** - A detached or semi-detached building
* **Name** - Name of the room category.
* **Short name** - An abbreviated name. This is an important field because they will save space for reporting statistics. Short name is also displayed on the timeline & in the new reservation screen.
* **Description** - This description will be shown in several parts of the system, including new reservation screen and Mews Distributor.
* **Ordering** - The ordering is important if you want to show rooms in a particular order on the timeline \(e.g. the lowest category rooms at the bottom, and higher category rooms above\). Ordering starts at 0.
* **Capacity** - Standard number people that can stay in this space; by default, this will be the maximum adult count available for selection
* **Extra capacity** - Indicates how many extra people could be added to a reservation. Please note that adding extra people will affect the price.
* **Housekeeping interval** - Period of time after which the spaces in this category will automatically change to `Dirty`. \(e.g. A housekeeping interval of one day will reset room status to `Dirty` every day overnight\). If you leave this field blank, your default housekeeping interval will apply. 
* **Accounting category** - A drop-down selection of accounting categorization as per your property's settings.
* **Room classification** - An additional classification used for some revenue management systems. Mews would recommend that you consult your accounting team to decide whether you'd like to use these items in the setup of your property.
  * **Family** - A room or set of rooms to accommodate an entire family, including adults and children. 
  * **Junior suite** - A small set of rooms designated for one person
  * **One bedroom apartment** - Two rooms for individual occupancy, including one bedroom and household utilities in the other
  * **Other** - A space that cannot be classified using one of these descriptions
  * **Shared or dorm** - A room including many individually sold beds or sleeping spaces
  * **Standard double** - Standard-sized room with two beds
  * **Standard single** - Standard-sized room with a single bed
  * **Standard twin** - Standard-sized room with two single twin beds
  * **Studio** - A single room for individual occupancy, including household utilities
  * **Superior double** - Larger-sized room with two beds
  * **Superior single** - Larger-sized room with a single bed
  * **Superior triple room** - Larger-sized room to accommodate up to 3 people with either one double and a single bed or a combination of beds and roll-aways.
  * **Superior twin** - Larger-sized room with two single twin beds
  * **Three bedroom apartment** - Several rooms for individual occupancy, including three bedrooms and household utilities in the others.
  * **Triple** - Standard-sized room to accommodate up to 3 people with either one double and a single bed or a combination of beds and roll-aways.
  * **Two bedroom apartment** - Several rooms for individual occupancy, including two bedrooms and household utilities in the others.
* **Reservation assignment strategy** - Decide how to assign bookings for this room category within a property as they come in. This setting will override property-wide assignment settings for this category.
  * **Bottom up** - The first booking will be assigned to the room 1, the second to the room 2 and so on.
  * **Random** - Spreads bookings equally across the hotel in case there is no need to fill the property floor by floor.
  * **Top down** - Bookings will be assigned from the top to the bottom of the property.
* **Channel manager ID** - Used for mapping to different Channel managers.
* **Order e-mail template** - While general confirmation e-mails do come from the system, sometimes it is necessary to deliver additional information to the guests of certain room types. For example, if an apartment is located next to the hotel, you may add the information about a different entrance. You can also use HTML here. Hence, this is a great place to for apartments to insert a Google maps link with the exact location of a specific apartment. Please see our article about [`placeholders`](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/settings/sales-settings/services/stay-settings/mail-templates/place-holders.md) for more information. 
* **Image** -  Upload an image to display in Mews Distributor. If you choose not to upload an image, the display will fallback to your default property image, found in your main property settings. 

> ### Mews Clues
>
> For guests booking via Mews Distributor, occupied space category images are displayed in greyscale and separated to the bottom to distinguish them from selectable categories.

## Delete

To delete a room category, navigate to the main room categories page.

**Click on the name of the unwanted category. Look for the trashcan icon and click on it, confirm deletion, and you will be redirected to the main page. ** You'll see that this room category will no longer be visible. Please note that deletion of a room category cannot be undone.

> ### Mews Clues
>
> Please note that if you delete a room category that is connected to an integration, it will remove that connection from the integration automatically. However if you delete an integration, the room category will not be deleted. You can still see information about past room categories in your reservation overview reports, even if they no longer exist.

