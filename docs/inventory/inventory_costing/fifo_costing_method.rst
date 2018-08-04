=======================================================
Compute the cost of product (first in first out method)
=======================================================
The fifo costing method help you to compute the accurate profit in the profit
and loss account based on the all the purchase expense and sell price. You can
add the landed cost (the cost of transportation) if you do a real time inventory
valuation with fifo costing method. Each time you remove the products from
warehouse the cost will be computed on the product **Cost** field

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

.. tip:: The FIFO is same as the Real price costing, follows the accounting
  FIFO and not forcing for warehouse FIFO removal strategy.


Video
-----
Access the video at https://www.youtube.com/watch?v=a8UXCiETC38

.. raw:: html

    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe src="https://www.youtube.com/embed/a8UXCiETC38" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 700px; height: 385px;"></iframe>
    </div>

.. seealso::

    * :doc:`standard_costing`
    * :doc:`costing_at_averagr_price`
    * :doc:`average_costing`
