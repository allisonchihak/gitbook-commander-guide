# Travel Agency Contracts

If a hotel has a cooperation with a Travel Agent, in order to set up this cooperation agreement in Mews, you have to create a Travel Agency Contract in Mews. Via this contract, it will be possible to assign the travel agent via the New Reservation Screen, and set up different billing, settlement and commission rules that apply once a booking is made against that travel agent.

**Reservation Settlement Options**

One important field is the bill assignment field. If you manage this field correctly, when new bookings are made it will automatically assign the booking at the correct rate to the correct bill.

* **Customer Always** -  When a new booking is created for this travel agent, it will leave the stay charge in the customer field, as the guest will be responsible for paying his bill himself.
* **Customer Always without Commission** - This option will discount the rate by the commission but still place the charge on the bill of the customer, who is due to pay for this charge.
* **Travel Agency Always** - This option will move the stay charge to the Travel Agent bill, so that the travel agent, rather than the customer, will have to pay for the rate.
* **Travel Agency Always without Commission** - This option will move the charge to the travel agent’s bill and will subtract the commission.
* **Travel Agency Only if Prepaid** - This option will move the bill to the travel agent only if it was pre-paid. If it was a BAR rate or another non-prepaid rate, it will leave the charge on the guest bill to be paid upon departure

> ### Mews Clues
>
> Please note that confirmation e-mails for Online Travel Agencies do not include rate total if the Travel Agency contract settlement is paid by the Travel Agency. Companies will be able to see rate totals.

## Create

To create a new Travel Agency Contract, simply go to the settings of the hotel, and select "Travel Agency Contracts"

Then click on the + icon on the top right of the screen to create a new profile.

* **Company** : before setting up a travel agency contract, you have to create a company profile for that travel agent in Mews.
* **Accounting code**
* **Reservation settlement**: as the booking comes in via the channel manager or input directly in the Commander, different settlement rules can apply to tell the user who should pay for the bill.
  * _**Customer**_: if a booking against this contract comes in, the reservation charge will be placed in the customer bill
  * _**Travel Agency**_: if a booking against this contract comes in, the reservation charge will be placed in the travel agent bill
  * _**Travel Agency if prepaid**_: if a booking against this contract comes in, the reservation charge will be placed in the Travel Agent bill if the reservation was prepaid \(the channel manager informs us about this\), or in the guest bill if it was not prepaid, so that you will ask for payment from the guest directly.
* **Commission estimate calculation**: in order for Mews to calculate the commission correctly, we need to know whether the rate received from the channel manager includes the commission, or is already net of commission.
  * Included in rate: does the rate received in the PMS include commission \(for example Booking.com\)
  * Not included in rate: does the rate received in the PMS NOT include commission \(for example this is the case with some Expedia contracts\)
* **Commission**: what is the commission percentage
* **Channel manager absolute adjustment**: when a booking comes in via the channel manager, you can discount/increase it with an absolute amount.
* **Channel manager relative adjustment**: when a booking comes in via the channel manager, you can discount/increase it with a relative adjustment.
* **Channel manager business segment**: this field allows you to preset the business segment in Mews if we receive a booking against this Travel agency contract.
* **Options**: "issues virtual credit cards", if your travel agent issues virtual credit cards its important to highlight that here, so that we do not send payment receipts to the customer personal e-mail, as they paid to the OTA directly.
* Contact person
* Contact e-mail
* Contact
* Notes
* **Invoice due interval**: when an invoice is created against the Travel Agency Contract, you can set the invoice due interval, after how many days you would like all invoices from this agent to be paid in.

## Foreign vs. Local

If Mews does not have a Global Travel Agent set up, then you can create a "New Travel Agent" where you will be asked to input a number of details. If this Travel Agent will be mapped against your Channel Manager, be sure to inform Mews Support desk once the profile is created, so that they can update the mapping in the profile against the Channel Manager.

If you would like to update any of the local profiles, you can select any travel agent and update any additional details you may have such as IATA, contact person, address or notes with regards to the agency.

## Global

When you create a new travel agency, you can always check if that travel agent already exists in the Global Mews Database. If this is a travel agent who will be connected to your channel manager, its important that you pick up the profile from the Mews database, rather than creating a new profile. This is because the Mews Database is already mapped against all of the Channel Managers.

Note once you select the Global Mews TA profile, you cannot change any of the details in the profile, such as TA address details, etc.

