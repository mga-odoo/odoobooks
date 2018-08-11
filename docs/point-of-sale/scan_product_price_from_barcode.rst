
=======================================================================================
Scan product price through barcode in Point of Sale (Dynamic pricing without pricelist)
=======================================================================================
The great featuer is priclist can be applied to the point of sale in Odoo.
However it is not easy to configure the pricelist for the point of sale, also
it increase the size in number of data that load at the point of sale startup.

Odoo point of sals able to read the understand the barcode well so that, it
can fetch the product price form the barcode, and they works well without
loading lots of data and defining the complex pricelist rules for the
point of sale. You can create a barcode with price in below business scenarios.

- The manufacturer print the barcode with the price, as the price often changes.

- You can create yoru own barcode as you want to run the promotion scheams
  untile the stock.

Business case
-------------
The shop **My Company** wonts the run the promotion program on some products,
for the limited stock available in the shop.

Configuration
-------------
You have to create the barcode rules under the point of sale barcode
nomenclature. The defaule rule is already exist with the name *Price Barcodes 2 Decimals*
the **Barcode Pattern** is *23.....{NNNDD}* it describes that the total size
of the barcode is 12 digit.

It start with 23, then 5 digit product code at last it have the 5 digit product
price can be configured.

.. tip:: The barcode on the product has to be configre the 12 digit i.e.
  231234500000. keep last 5 digit as 0 as it may different according to the
  price.

  Video
  -----
  Access the video at https://www.youtube.com/watch?v=xbPLx-KRh2s

  .. raw:: html

      <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
          <iframe src="https://www.youtube.com/embed/xbPLx-KRh2s" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 700px; height: 385px;"></iframe>
      </div>
