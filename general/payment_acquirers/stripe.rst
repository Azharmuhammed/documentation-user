======
Stripe
======

`Stripe <https://stripe.com/>`_ is a United States-based online payment solution
provider, allowing businesses to accept **credit cards** and other payment methods.

Enable Local Payment Methods
============================

Local payment methods are payment methods that are only available for certain merchants
and customers countries and currencies.

The Stripe connector in Odoo supports the integration of the following local payment methods:

- Bancontact
- EPS
- Giropay
- iDeal:
- Przelewy24 (P24)

To offer a given local payment method to your customers, it must be listed as a supported payment icon in Stripe.
Go to :menuselection:`Payment Acquirers --> Stripe --> Configuration` and add the desired payment method in
**Supported Payment Icons**.

.. image:: media/stripe_enable_local_payment_method.png
   :align: center
   :alt: Select and add icons of payment methods you want to enable

.. note::
If a payment method icon doesn't exist at all in the database, the corresponding local payment method is always offered
to customers.
