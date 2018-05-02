# Payment Gateway

Mews has an integration with 2 different payment gateway providers -`Adyen`and Stripe. Both of them are available in two modes - hotel can have own account or hotel can use`Merchant`integration \(account on behalf MEWS\). The advantage of using the`Merchant`account is not having to discus conditions with either`Adyen`or Stripe, which takes time, whereas hotel can start using`Merchant`in any time.

The payment gateway is a separate from Mews, which means that all credit cards are validate and stored outside MEWS, all operations are processed outside of MEWS, all payments via payment gateway are taken against defined bank account\(s\). MEWS only has "tokens" that reffer to credit cards and payments, this way it eliminates risk of credit card fraud \(e.g. stealing credit card numbers, charging money from guest's credit card to a random bank account\).

The payment gateway integration can take payments against multiple bank accounts in different currencies. One of them needs to be marked as`Default`, so payments in other than supported currencies can be converted to currency of default account and taken in that currency. In this case MEWS will show both value that was actually charged and the value the payment originaly represents.

Hotel can have only 1 payment gateway integration enabled.

## Set up`Merchant`account {#setupmerchantaccount}

It is very easy to set up`Merchant`account for a hotel - just create a`Merchant`integration and enable it.

Supported currencies by`Merchant`integration

* CZK
* EUR
* GBP

## Set up hotel account {#setuphotelaccount}

Setting up hotel's own account is more diffuclt and time consuming part. Usually it means

* Sign a contract with the payment gateway.
* Obtain credentials for MEWS.
* Make a few test transactions to verify all is set up.
* Adjust the set up on payment gateway's side, because the default one is not usually ideal.

There are more details in the specific payment gateway manuals.

> ### Mews Clues
>
> Please note that it is not possible to edit password information while the integration is enabled. You must first disable the integration, edit data as needed, and then re-enable it when all details are correctly entered.

