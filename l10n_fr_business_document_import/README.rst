.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.svg
   :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
   :alt: License: AGPL-3

================================
L10n FR Business Document Import
================================

This small module adds support for partner matching based on SIREN when importing a business document (invoice, customer order, etc), in Odoo. It depends on the module base_business_document_import which is the base module for:

* *account_invoice_import* which imports supplier invoices as PDF or XML files (this module also requires some additionnal modules such as *account_invoice_import_invoice2data*, *account_invoice_import_ubl*, etc... to support specific invoice formats),

* *sale_invoice_import* which imports sale orders as CSV, XML or PDF files (this module also requires some additionnal modules such as *sale_invoice_import_csv* or *sale_invoice_import_ubl* to support specific order formats)

Configuration
=============

No configuration needed.

Usage
=====

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/121/8.0

Bug Tracker
===========

Bugs are tracked on `GitHub Issues
<https://github.com/OCA/l10n-france/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smashing it by providing a detailed and welcomed feedback.

Credits
=======

Contributors
------------

* Alexis de Lattre <alexis.delattre@akretion.com>

Maintainer
----------

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit https://odoo-community.org.
