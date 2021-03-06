.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.svg
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3

=============
Auth Supplier
=============

This module was written to extends the functionality of auth signup and allows
the user to create an account as a supplier, marking him as with permissions
for a supplier portal (although nothing is implemented for that portal, other
modules should do that).

Configuration
=============

To enable users to create accounts:

* *Developer mode* should be activated first to have access to technical features.
* Go to *Settings > General settings*.
* Enable *Allow external users to sign up*.
* Enable *Activate the customer portal*.

Usage
=====

To use this module, you need to:

* Log out.
* If you have a website, in home page press *Sign in*.
* Press *Sign up* to go to `the sign up page </web/signup>`_.
* Select *Supplier* in account type.
* Fill the form.

If you want to give permissions to anybody for the supplier portal:

#. Go to *Contacts*.
#. Choose a supplier.
#. Go to *Action > Portal Access Management*.
#. Choose *Other Extra Rights / Supplier Portal*.
#. Choose contacts to be *In Portal*.
#. Press *Apply*.

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/149/9.0

Known issues / Roadmap
======================

* If you have nothing in the portal, the user will be redirected to an empty
  page.
* When the user signs up as *Customer*, it is not really marked as such in the
  backend, it's just not marked as supplier. Is this expected behavior or bug?
  `Relevant discussion
  <https://github.com/OCA/server-tools/pull/434#discussion-diff-64883758>`_.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues
<https://github.com/OCA/server-tools/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smashing it by providing a detailed and welcomed feedback.

Credits
=======

Contributors
------------

* Rafael Blasco <rafabn@antiun.com>
* Pedro M. Baeza <pedro.baeza@serviciosbaeza.com>
* Carlos Dauden <carlos@incaser.es>
* Sergio Teruel <sergio@incaser.es>
* Jairo Llopis <jairo.llopis@tecnativa.com>

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
