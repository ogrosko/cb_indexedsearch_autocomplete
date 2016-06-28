.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../Includes.txt


.. _FAQ:

FAQ
====

Why dont the plugin display anything?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
You need to type at least 3 characters before the lookup is made.

I type at least 3 characters but the plugin still display nothing?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
It is possible that the plugin get in conflict with other javascript based plugin on your site.In this case try to use the “noConflictMethod” switch in Constants Editor to avoid from conflicts.

Other typo3 extensions don't work anymore since cb_indexedsearch_autocomplete was installed
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
cb_indexedsearch_autocomplete uses jQuery for JavaScript operations. jQuery might conflict with other JavaScript libraries like prototype on which some other typo3 extensions depend. In this case try to use the “noConflictMethod” switch in Constants Editor to avoid from conflicts.