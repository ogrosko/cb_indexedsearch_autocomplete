.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../Includes.txt


.. _configuration:

Configuration
=============

.. _Constants:

Constants
"""""""""
All constants are located as:

plugin.cb_indexedsearch_autocomplete.*
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. container:: table-data

   Example
         ::

            plugin.cb_indexedsearch_autocomplete {
               autoSubmit = 1
               maxResults = 10
           }



.. _altResultLabel:

altResultLabel
""""""""""""""

.. container:: table-row

   Property
         altResultLabel

   Data type
         string

   Description
         Alternative label for 'result' in the suggestions. If no label should be printed pass empty value.

   Default
         result


.. _altResultsLabel:

altResultsLabel
""""""""""""""

.. container:: table-row

   Property
         altResultsLabel

   Data type
         string

   Description
         Alternative label for 'results' in the suggestions. If no label should be printed pass empty value.

   Default
         results



.. _autoSubmit:

autoSubmit
""""""""""

.. container:: table-row

   Property
         autoSubmit

   Data type
         boolean

   Description
         Determines whether the search query is submitted after selecting a recommendation or just filled into the search box.

   Default
          1



.. _jQueryLoadedExternally:

jQueryLoadedExternally
""""""""""""""""""""""

.. container:: table-row

   Property
         jQueryLoadedExternally

   Data type
         boolean

   Description
         If jQuery library is loaded outside of this plugin (page global) then set this trigger to true, otherwise to false.

   Default
          0



.. _cssLoadedExternally:

cssLoadedExternally
"""""""""""""""""""

.. container:: table-row

   Property
         cssLoadedExternally

   Data type
         boolean

   Description
         If predefined css shall not be loaded set this trigger to true, otherwise to false.

   Default
         0


.. _jQueryFile:

jQueryFile
""""""""""

.. container:: table-row

   Property
         jQueryFile

   Data type
         string

   Description
         Path and filename of the jquery library. If not set the plugin will use its internal version of jQuery located in the res/ directory.
         If t3query is installed and loaded this parameter is skipped and the t3query library is loaded.

   Default
         cb_indexedsearch_autocomplete.js


.. _maxResults:

maxResults
""""""""""

.. container:: table-row

   Property
         maxResults

   Data type
         integer

   Description
         Number of suggestions in the result list.

   Default
          unlimited


.. _noConflictMethod:

noConflictMethod
""""""""""""""""

.. container:: table-row

   Property
         noConflictMethod

   Data type
         boolean

   Description
        Sets jQeury into it's no conflict mode, so that this extension can cooperate with other JS-libraries such as Prototype

   Default
          0


.. _onlySearchPage:

onlySearchPage
""""""""""""""

.. container:: table-row

   Property
         onlySearchPage

   Data type
         boolean

   Description
         Plugin code is only inserted on pages with a indexed_search element.

   Default
          0


.. _autoResize:

autoResize
""""""""""

.. container:: table-row

   Property
         autoResize

   Data type
         boolean

   Description
         Enables automativ resize function for width adjustment of the suggestion list

   Default
          0


**Setup**


All configuration options described in the Constants Block may also be set in the setup directive.

All configuration options are located as:

plugin.cb_indexedsearch_autocomplete.*
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^