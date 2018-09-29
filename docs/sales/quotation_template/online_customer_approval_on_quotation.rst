
.. index::
   single: Online customer approval on quotation

Online customer approval on quotation
=====================================

Sending an online quotation can speed up the negotiation process,
customer can negotiate and approve the quotation online, this can boost
up your sales process and minimise the sales cycle.

Business case
-------------

The service company who is selling the *Support pack* which is service
offered at fixed price. As soon as customer accept the proposal,
customer can start sending the support requests. The company wants to
get the online signature from the customer and customer can release the
payment based on the payment terms.

Configuration
-------------

Assumed that you have installed **Sales Management** application,
configure the quotation template for the support packs.

Online signature
~~~~~~~~~~~~~~~~

The **Confirmation Mode** on the quotation template available on the
**Confirmation** tab is set to *Online Signature* by default. The
customer can confirm the quotation by themselves by signing the
quotation. Keep it as it is when you just want the online signature form
customer.

Create and send quotation by email
----------------------------------

Create a quotation select customer, select quotation template. Before
you send the quotation to customer make sure that **Confirmation Mode**
is set to *Online signature* on quotation under the **Other
Information** tab.

|image0|

.. tip:: You can change the **Confirmation Mode** for each quotation
  regardless of the configuration on quotation template.

Accept quotation
~~~~~~~~~~~~~~~~

Customer can review the quotation online, once it suits his/her need
than he/she can accept the quotation by clicking on the **Accept Order**
and signing the quotation online.

|image1|

The quotation accepted and signed by the customer will be confirmed and
converted to sales order in backend. It will automatically triggers the
next business process in backend such as creating a delivery order,
manufacturing order or create a task or project in the project
management depending on your configuration.

.. tip:: Customer can accept and sign online quotation which are not
  expired yet. The expiration date will be computed on quotation based on
  the number of days defined on quotation template in **Quotation expires
  after** field. However the specific **Expiration Date** can be set on
  the quotation manually before you send the quotation by email.

Reject quotation
~~~~~~~~~~~~~~~~

The quotation will be set to **Cancelled** state in the backend once it
has been rejected by the customer online, however it can be reset to
draft modified and send it back to the customer when you are in
negotiation process.

Video
-----
Access the video at https://www.youtube.com/watch?v=LZjN1fdVSO4

.. raw:: html

    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe src="https://www.youtube.com/embed/LZjN1fdVSO4" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 700px; height: 385px;"></iframe>
    </div>

.. |image0| image:: static/online_customer_approval_on_quotation/media/image4.png

.. |image1| image:: static/online_customer_approval_on_quotation/media/image2.png
