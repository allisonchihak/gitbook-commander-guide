# Customer Communication

Throughout Commander, there are several situations in which communication with customers may be necessary. This communication is usually via e-mail, which can be sent via Commander either automatically or manually.

This article includes a detailed description of each e-mail type, automatic vs. manual sending options, and locations within Commander where they are sent from. When referring to any locations in Mews, click on the links to view articles pertaining to those particular pages.

## Profile creation

## Profile import creation

As reservations in the past, often from other systems, are uploaded into Mews, user profiles are created based on the e-mail addresses and customer details that are provided in the Import file. As these customer profiles are created, users will receive an automatically generated e-mail to inform them that their information was used to create a customer profile that is safely stored in Mews and available in case they would like to request deletion or update any information. 

## Password reset

## Magic link

## Deletion request

## Quotation

If an optional booking is created manually in Mews Commander, the creator can choose whether they would like to send a quotation e-mail on the last step of the `New Reservation Screen` under the `Quotation` field by selecting `Send`, `Do not send`, or `Send to custom e-mail`.

This includes a link where customers can confirm their optional reservations.

## Release reminder

If an optional booking is close to its release date, you can manually trigger an e-mail that will prompt them to confirm their booking before that date.

## Cancellation confirmation

Cancellation e-mails are optional. As the booking is being canceled in Mews Commander, the user can tick the box labeled `Send e-mail`, which is found in the [`Reservation Module State`](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/reservations/reservation-module/state.html) tab. If this box is selected, the cancellation confirmation e-mail is sent to the guest at the moment that you click the `Cancel` button.

From the [`Reservation Module Mailing`](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/reservations/reservation-module/mailing.html) tab, you can resend cancellation e-mails only if the booking has already been canceled. From this location, you can also resend to a `Custom e-mail` address if necessary.

You can edit and customize a [`Mail template`](../settings/sales-settings/services/stay-services/mail-templates/) for cancellation e-mails, including any information that your property would like customers to know.

## Reservation confirmation

This e-mail is sent to customers automatically when they have successfully booked a reservation via Mews Distributor. If a booking is created manually in Mews Commander, the creator can choose whether they would like to send a confirmation on the last step of the `New Reservation Screen` under the `Confirmation` field by selecting `Send`, `Do not send`, or `Send to custom e-mail`.

From the [`Reservation Module Mailing`](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/reservations/reservation-module/mailing.html) tab, you can resend confirmation e-mails only if the booking has already been confirmed, is currently checked-in, or already checked out. From this location, you can also resend to a `Custom e-mail` address if necessary.

You can create a [`Mail template`](../settings/sales-settings/services/stay-services/mail-templates/) for confirmation e-mails, including a button for online check-in, which you can modify and customize using [`Placeholders`](https://github.com/mews-systems/commander-guide/tree/aba4aad5c9d2bc8ec74b2a6c202f25d981c8b45b/settings/sales-settings/services/stay-settings/mail-templates/placeholders.html).

## Before start

## Invitation to online check-in

If you would like the customer to fill in their credit card details, this e-mail will confirm booking details and will include a link where they can check in online. This is automatically sent two days prior to arrival and is sent only if the customer has not already completed the online check-in.

## Bill or Invoice

## After start

Resend a welcome message to your guests after they have arrived and completed check-in

## After end

## Charge confirmation

## Charge fail

