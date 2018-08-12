
.. index::
   single: Default tax on product
   single: Default tax on quotation

Apply default taxes on products or sales order
==============================================

Taxes applied in your country are installed automatically for most
localizations. Default taxes set in orders and invoices come from each
product’s Invoicing tab. Such taxes are used when you sell to companies
that are in the same country/state than you.

Business case
-------------

Let’s set the default sales and purchase tax to Tax 15.00%.

Configuration
-------------

All the new products created in the Odoo take the default tax set in the
**Accounting/Invoicing** settings. To change the default taxes set for
any new product created, goto **Invoicing / Configuration / Settings**.

|image0|

Create new product
------------------

Let’s create a new product, the default tax which was applied should be
applied on this product.

|image1|

Create sales order
------------------

Let’s create a new order and select the same product on the order line,
the tax which was set on the products should be applied on the sales
order line tax field.

|image2|

Now, your salesman do not have to remember that what taxes to be applied
on which product.

Video
-----
Access the video at https://www.youtube.com/watch?v=tq3e17Ccjxk

.. raw:: html

    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe src="https://www.youtube.com/embed/tq3e17Ccjxk" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 700px; height: 385px;"></iframe>
    </div>


.. |image0| image:: static/apply_default_tax/media/image6.png
   :width: 6.5in
   :height: 1.91667in
.. |image1| image:: static/apply_default_tax/media/image5.png
   :width: 6.5in
   :height: 2.02778in
.. |image2| image:: static/apply_default_tax/media/image3.png
   :width: 6.5in
   :height: 2.63889in
