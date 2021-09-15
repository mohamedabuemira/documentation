===============
Gmail Extension
===============

The **Odoo CRM Extension** is a connector that bridges your Gmail mailbox with your Odoo database.
This extension allows you to:

- Create leads from emails sent to your mailbox.
- Centralize Prospects' emails into a CRM.
- Search and store insights on your contacts.

.. image:: media/gmail-extension-overview.png
   :align: center
   :alt: Overview of the Gmail Extension in Gmail

.. important::
   The Gmail Extension uses *Partner Autocomplete IAP credits* to search and store insights on
   your contacts. See the :ref:`Pricing section <gmail_extension/pricing>` below for more
   information.

.. _gmail_extension/configuration:

Configuration
=============

The Gmail Extension requires to be configured both in Odoo and in Gmail.

.. _gmail_extension/enable-feature:

Enable the feature on your database
-----------------------------------

To enable this feature on your Odoo database, go to :menuselection:`Settings --> General Settings -->
Integrations`, enable **Mail Plugin**, and click on *Save*.

.. _gmail_extension/add-in-installation:

Install the add-in on Gmail
---------------------------

To install the add-in,

#. Go on the following URL: `Gmail Add-In Project <https://script.google.com/d/1n7cxtaR4fGXKcP0RwinNQmL8S4FhVqpo-ZZ_cUAhYuuDpZAP_CnHE_7q/edit>`_  .

#. If you are logged with many Google account at the same time, check that you are using the one on which you want to install the add-in

   .. image:: media/gmail-extension-check-login.png
      :align: center
      :alt: Check your login

#. Click on **Publish** then **Deploy from manifest...**

   .. image:: media/gmail-extension-deploy-from-manifest.png
      :align: center
      :alt: Deploy from manifest

#. Click on **Install add-on** and the Odoo plugin will be available on Gmail

   .. image:: media/gmail-extension-install-addon.png
      :align: center
      :alt: Install the addon

Connect to your database
------------------------

#. Open any email in your Gmail inbox and click on the Odoo icon.
   This opens the extension as a panel on the right side of your screen.

   .. image:: media/gmail-extension-open-addon.png
      :align: center
      :alt: Open the Gmail add-in

#. Click on *login* at the bottom of the extension.

#. Insert your database's URL then click on *Login*.

#. Log into your database by entering your credentials. Skip this step if you are already logged in
   with this browser.

#. A message asks you if you want to let Gmail access your Odoo database. Click on *Allow* to
   complete the connection.

   .. important::
      Make sure first to :ref:`enable the feature on your database
      <gmail_extension/enable-feature>`.

.. note::
   The extension displays some information, even if you do not connect it to any Odoo database.
   Note that only a limited amount of contact enrichment requests are available as a trial, as this
   feature requires prepaid credits. See the :ref:`Pricing section <gmail_extension/pricing>`
   below for more information.

.. _gmail_extension/pricing:

Pricing
=======

The extension is **free** and doesn't require any purchase to be installed and used.

However, this extension provides you with *Lead Enrichment* in the **Company Insights** section.
This service is part of a paid service known as **Lead Generation**.

The extension allows you to test this service for free, whether you connect the extension to a
database or not. After a while, the extension asks you to buy credits to keep using this additional
service.

.. image:: media/gmail-extension-credits-message.png
   :align: center
   :alt: "Not enough credits to enrich." warning message in the Gmail extension

.. tip::
   You can buy more *Lead Generation* credits to keep using this service or disregard this message
   and keep using the extension for free without *Lead Enrichment*.

In-App Purchase
---------------

| *Lead Generation* is an *In-App Purchase (IAP)* service, which requires prepaid credits to be
  used. Each request consumes one credit.
| To buy credits, go to :menuselection:`Settings --> Contacts --> Partner Autocomplete or Odoo IAP -->
  View My Services` and select a package.

.. note::
   - If you run out of credits, the only information populated when clicking on the suggested
     company is the website link and logo.
   - If you are on Odoo Online (SAAS) and have the Enterprise version, you benefit from free
     trial credits to test the feature.
   - Learn about our *Privacy Policy* `here <https://iap.odoo.com/privacy#header_2>`_.

.. seealso::
   - :doc:`../../../general/in_app_purchase/in_app_purchase`
   - `Odoo Tutorials: Lead Enrichment <https://www.odoo.com/r/p73>`_
