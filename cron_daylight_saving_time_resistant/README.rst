===================================
Cron daylight saving time resistant
===================================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:47c4229ff8504b9ce8f0531d3602cb206b388d44ab43901e4a744d836c0d0554
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fserver--tools-lightgray.png?logo=github
    :target: https://github.com/OCA/server-tools/tree/16.0/cron_daylight_saving_time_resistant
    :alt: OCA/server-tools
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/server-tools-16-0/server-tools-16-0-cron_daylight_saving_time_resistant
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/server-tools&target_branch=16.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module adjust cron to run at fixed hours, local time.


Without this module, when a daylight saving time change occur, the cron will not take
the hour change in account.

With this module, when a daylight saving time change occur, the offset (+1 or -1 hour)
will be applied.

**Table of contents**

.. contents::
   :local:

Configuration
=============

* Go to the menu Settings => Technical => Automation => Scheduled Actions
  Then you can check the check box Daylight Saving Time Resistant

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/server-tools/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/server-tools/issues/new?body=module:%20cron_daylight_saving_time_resistant%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* akretion

Contributors
~~~~~~~~~~~~

* Raphaël Reverdy https://akretion.com
* Florian da Costa <florian.dacosta@akretion.com>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-florian-dacosta| image:: https://github.com/florian-dacosta.png?size=40px
    :target: https://github.com/florian-dacosta
    :alt: florian-dacosta

Current `maintainer <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-florian-dacosta| 

This module is part of the `OCA/server-tools <https://github.com/OCA/server-tools/tree/16.0/cron_daylight_saving_time_resistant>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
