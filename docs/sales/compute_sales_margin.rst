.. _salesmargin:

.. index::
   single: Sales Margin

============================
Compute margin on sale order
============================
Some business wants the realtime computation of the margins so that sales
manager or person can propose the best price to the customer.

Let's take the business case, sales manager check the margin on order and decide
whether we can allow additional discount to the customer or not.

Configuration
-------------
Install the **Sales Management** application.

.. image:: images/chapter_02_15.png
   :alt: Sales Application
   :align: center

.. note:: If you want to check Margin feature for *Average Cost (AVCO)* install
  **Purchase Management**. Installation of sales and purchase will install other
  applications such as **Inventory Management** and **Invoicing Management**.

Margins
~~~~~~~
Go to ``Sales / Configuration / Settings`` select **Margins** and apply the setting.
This will show margins on orders.

.. image:: images/chapter_02_35.png
   :alt: Sales Settings
   :align: center

Products
~~~~~~~~
Enter the product **Sales Price** and **Cost** accordingly, enter the latest
sales and cost price.

.. image:: images/chapter_02_36.png
   :alt: Sales Settings
   :align: center

I have entered $1200 sales price and $900 cost price, also defined the $900
purchase price on the vendor pricelist.

.. tip:: Product **Cost** will be computed automatically when you set the product
  costing method to *Average Cost (AVCO)* or *First in First Out (FIFO)*. The FIFO
  method does not give you correct costing in some case.

Create Sales order
------------------
Let's create a quotation, select the customer on quotation and product on order line.
The margin will be computed as soon as you select the product, the difference
between **Unit Price** and **Cost** is margin. The **Margin** be computed
based on the difference for each lines on sale order.

.. image:: images/chapter_02_37.png
   :alt: Sales Settings
   :align: center

Now, it will be easy for the sales manager to check what's the margin on quotation.
For **SO004** it is 25%, its a good deal to go with, let's move forward and
confirm the order.

Video
-----
Access the video at https://www.youtube.com/watch?v=GzhZi2296Z8

.. raw:: html

    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe src="https://www.youtube.com/embed/GzhZi2296Z8" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 700px; height: 385px;"></iframe>
    </div>

.. seealso::

    * :doc:`../accounting/stock_valuation`
