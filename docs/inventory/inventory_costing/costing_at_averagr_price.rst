=============================================
Compute the cost of product (average costing)
=============================================
The average costing method help you to dicide the product sell price, each time
you purchase the product new cost will be updated based on the existing stock
and purchased stock value.

Business case
-------------
The **My Company** is a distributor of *Laptop*, they purchase a laptop form the
default supplier and sell to retail customers, there are sometime frequent price
change, so **My Company** wans to setup the inventory costing and based on
average cost method.

Configuration
-------------
- Install **Sales Management**, **Purchase Management** &
  **Accounting and Finance** apps

- Create a product *Laptop*

- Set the Internal Category to *All / Saleable*

- Set **Costing Method** to	*Average Cost (AVCO)* on *All / Saleable* category

- Define *Default Supplier* as a vendor with the cost price of *Laptop*.

- Purchse 3 unit of Laptop at different rates, the product will be computed
  on each reception by doing an average based on the purchase price.

.. tip:: Assumed that you have a 10 unit of laptop cost of 8500 (the inventory
  value will be same as the cost), you purchase new 10 laptop at the price of
  830 each. The new cost price will be computed by an averga of total cost vs
  units. 840 = (8500 + 8300) / 20 (10 existing stock + 10 new purchase)

Video
-----
Access the video at https://www.youtube.com/watch?v=QjdRX6El-4M

.. raw:: html

    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe src="https://www.youtube.com/embed/QjdRX6El-4M" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 700px; height: 385px;"></iframe>
    </div>

.. seealso::

    * :doc:`standard_costing`
    * :doc:`fifo_costing_method`
    * :doc:`average_costing`
