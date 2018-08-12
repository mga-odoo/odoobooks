
.. index::
   single: Scan product weight through barcode

===========================================================
Scan weight of the product through barcode in Point of sale
===========================================================
Point of sale may need to scan the product weight to decide the price. There
are multiple ways to get the weight into point of sale, some of them are as below

- You are selling predefined packs (based on weight) of the products, and you
  want to know which pack has been scanned at the terminal to decide the price.
  i.e. pack of 250grm, pack of 500grm, pack of 1kg etc.

- You sell the items in loose packaging form, where customer create their own
  custom pack depending on their need, they do weight and generate the barcode
  accordingly.

- The third way is more easier to use in real-life but most complex to
  configure in Odoo, is to attached the weight scale machine to the point of
  sales terminal.

Business case
-------------
The small fruit shop sells the predefined packs of the Apples, they
create a packs in advance such as Pack of 250grm, Pack of 500grm or Pack of
1kg. They would like to compute the price of the pack depending on the pack
scan at the terminal.

.. tip:: You can scan **Product price** or **Discount** from the barcode,
  you need to configure the barcode rules under Nomenclature (i.e. Goto
  Point of sale session configuration and enable **Barcode Scanner** option)

Video
-----
Access the video at https://www.youtube.com/watch?v=L-kRofdfdLc

.. raw:: html

    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe src="https://www.youtube.com/embed/L-kRofdfdLc" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 700px; height: 385px;"></iframe>
    </div>
