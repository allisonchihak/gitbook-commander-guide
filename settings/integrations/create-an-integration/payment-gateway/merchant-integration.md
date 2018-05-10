# Merchant Integration

Based on the terms of your contract with Mews, your property will have chosen which card types you will support for your Stripe and Adyen Merchant accounts.

If you have any questions about your Merchant integration setup, please contact our support team at support@mewssystems.com

## Commissions

With every transaction there is a Mews commission and an Interchange \(IC\) fee charged. Mews commission is a given percentage of each charged amount for Visa and Mastercards. IC fees are very complicated to calculate as they depend on the type of the card and on the country from where the card is. More info and actual rates from Visa [here](https://www.visaeurope.com/about-us/interchange-fees).

If properties check their `Payment report`, they can see the Mews commission charged for each CC type. When they deduct this fee from the charged value, the remainder is always the IC fee.

CC storage fees are charged on a monthly basis dependent as part of their monthly invoicing, dependent on how many CC were stored to the system each month. That total can be checked in their `Credit Card report` in Mews Commander.

## Stripe Merchant invoice

A Merchant fee is the contractual rate for Mews Merchant payment processing. This invoice is automatically settled from your Stripe account. At the beginning of each month, you will receive an invoice from us, which you can pass on to your accounting team. Once you receive your invoice for Merchant payments, you can follow the following steps to check the details:

Navigate to our `Payment Report` using the following path:

* **Main Menu &gt; Finance &gt; Payment report**

You can also access the payment report directly from the Mews dashboard under the `Finance` section.

Once you've arrived, choose the following options for your filters:

* **Mode** - Created
* **Start date** - 1st day of the month you'd like to check \(e.g. 1st January\)
* **End Date** - 1st day of the next month \(e.g. 1st February\)
* **States** - Charged, Settled
* **Type** - Select all
* **Filter** - Gateway CC payments
* **Credit cards** - Select all
* **Currency** - Leave blank \(`-`\)
* **Employee** - Leave blank \(`-`\)
* **Integration** - Stripe Merchant Integration
* **Charge Currency** - Leave blank \(`-`\)

When all filter options are correctly chosen, click `OK` and then `Export`

Once you've downloaded the the Excel export, open the file and navigate to the `Credit Card Payments` tab. Look for column `P`, labeled `Fee total net`, which is where you'll find the amount charged by Mews for which you received the invoice.

> ### Mews Clues
>
> Please note that in case of refunds, Mews commission and all bank fees are refunded as well

