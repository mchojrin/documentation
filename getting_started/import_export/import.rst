:orphan:

.. Should remain orphan, as it is included into the index with TOC

.. _import-bulk-items:
.. _user-guide-import:

.. begin_global_import

Importing Bulk Items
^^^^^^^^^^^^^^^^^^^^

To streamline adding a massive bulk of items, like customer information, products, prices, or inventory information, you can import the bulk details from a .csv file.

.. begin 1

To import a bulk of |imported_information|:

1. In the main menu, navigate to |menu|. The |item| list opens.

2. Click **Import File** on the top right.

3. In the **Import** dialog, click **Choose File**, select the .csv file you prepared, and then click **Import File**.

   |image|

4. Click **Export Template** to download a sample .csv file with the necessary headers.

5. **Prepare data for import**: Based on the downloaded file, create your bulk information in the .csv format. Once your file is ready, click **Choose File**, select the prepared comma-separated values (.csv) file, and click **Import File**.

6. **Validate import results**: Click **Validate** to check your import results. If there are any *Records with errors*, fix them in the .csv file before starting the import.

7. **Launch import:** After successful validation, click **Import File**.

8. Click **Cancel** to decline the import.

.. important:: Interactive status messages inform about the import progress, and once the import is complete, the changes are reflected in the list upon refresh. Additionally, an email message with the import status is delivered to your mailbox.

Follow the on-screen guidance for any additional actions. For example, for the inventory template, select one of the options: a) inventory statuses only or b) detailed inventory levels.

.. raw:: HTML

   <iframe width="560" height="315" src="https://www.youtube.com/embed/shpqpFao6bA" frameborder="0" allowfullscreen></iframe>

.. finish 1

Related Topics
~~~~~~~~~~~~~~

.. toctree::

   import_accounts
   import_contacts
   import_customers
   import_customer_users
   import_leads
   import_opportunities
   import_price_lists
   import_products
   import_product_attributes
   import_coupons
   import_taxes
   import_tax_rules
   import_inventory_statuses
   import_inventory_levels



.. |imported_information| replace:: items

.. |menu| replace::  menu item to import the list of the necessary data

.. |item| replace:: item

.. |image| image::  /user_guide/img/getting_started/export_import/import_1.png