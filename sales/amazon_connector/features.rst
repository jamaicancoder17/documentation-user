====================================
Amazon Connector: supported features
====================================

The **Amazon Connector** synchronizes the orders between Amazon and your Odoo database, which
reduces considerably the amount of time spent on your Amazon Seller Central dashboard, making your
daily routine a lot easier.

The connector is able to:

+--------------------------------------------------+----------------------------------------+
| From Amazon to Odoo                              | From Odoo to Amazon                    |
+==================================================+========================================+
| Synchronize all confirmed orders (both FBA and   | Notify Amazon of a confirmed shipping  |
| FBM) and their order items which include:        | (FBM) in order to get paid.            |
|                                                  |                                        |
| - the product's details (SKU, listing name &     |                                        |
|   description, quantity, etc.)                   |                                        |
| - the shipping costs for the product             |                                        |
| - the gift wrapping charges                      |                                        |
+--------------------------------------------------+----------------------------------------+
| Create any missing offer related to an order.    | Notify Amazon of a manually canceled   |
|                                                  | order.                                 |
|                                                  |                                        |
|                                                  | .. todo:: dropped in 13.1+             |
+--------------------------------------------------+----------------------------------------+
| Create any missing partner related to an order   |                                        |
| (contact types supported: contact and delivery). |                                        |
+--------------------------------------------------+----------------------------------------+

.. note::
   The connector is designed to synchronize orders' data as detailed above. Other actions, such as
   downloading monthly fees report, handling disputes, or issuing refunds must be managed from
   Amazon Seller Central, as usual.


.. seealso::
   - :doc:`setup`
   - :doc:`manage`

