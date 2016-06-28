.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../Includes.txt


.. _WhatDoesItDo:

What does it do?
=================


Extends the builtin Indexed Search searchform with an autocomplete feature as seen on Google Suggest and a variety of other places. As the user type in the searchword, a list will appear containing suggested searchwords along with the result count of each.

To archive that cb_indexedsearch_autocomplete is integrated in every page content or in every page with an indexed_search_plugin (onlySearchPage mode). The autocomplete feature is bound to every HTML input-Element with the name-attribute set to “tx_indexedsearch[sword]”. On search query input a AJAX request is submitted to the server, which determines the number of results live from the typo3 database. This helps the website visitor to specify their search queries correctly.