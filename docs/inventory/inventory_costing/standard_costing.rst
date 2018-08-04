============================================
Compute the cost of product (standard price)
============================================

Business case
-------------
The **My Company** is a distributor of *Laptop*, they purchase a laptop form the
default supplier and sell to retail customers, they do not maintain the stock,
they always purchase on demand so **Standard pricing** is pefect costing method
for them. Some times they benefit or loss if they have stock and product price
change as they directly change the product cost price whcih impect on their
inventory value.

Configuration
-------------
- Install **Sales Management**, **Purchase Management** &
  **Accounting and Finance** apps

- Create a product *Laptop*

- Set the Internal Category to *All / Saleable*.

- Default costing method on the category is Standard pricing.

- Define *Default Supplier* as a vendor with the cost price of *Laptop*.

- Purchse 2 unit of Laptop at different rate then the Standard price, inventory
  value will be computed based on the product Standard price field.

.. note:: This method is less useful in the real-life.

Video
-----
Access the video at https://www.youtube.com/watch?v=TEHOwOjrRWM

.. raw:: html

    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe src="https://www.youtube.com/embed/TEHOwOjrRWM" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 700px; height: 385px;"></iframe>
    </div>

.. seealso::

    * :doc:`costing_at_averagr_price`
    * :doc:`fifo_costing_method`
    * :doc:`average_costing`
