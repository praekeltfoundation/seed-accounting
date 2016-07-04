Design
======

In the current Vumi Go implementation there is a billing module that handles
most of the credits and rating.

The reference code is here:
https://github.com/praekelt/vumi-go/tree/develop/go/billing

.. todo:: Speak to Rudi and Justin WRT billing.

Focus
-----

Seed is currently being deployed in a number of different countries.

These countries have a variety of billing requirements and modes of operation.

Because Seed Accounting needs to cater for all these, we separate the accounting
from the billing and rating functions of the system.

Approach
--------

As Seed is being developed incrementally, it's important that the accounting
foundation be:

- extensible
- simple
- robust
