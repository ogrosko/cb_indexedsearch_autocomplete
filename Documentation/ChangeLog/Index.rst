.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../Includes.txt


.. _changelog:

Changelog
=========

**1.1.0 ( Changes by Michael Michalowski / Hottgenroth Software GmbH & Co. KG / < m.michalowski@hottgenroth.de > )**

1. Support of Juergen Furrer's t3jquery extension implemented
2. AutoResize function for automatic width adjustment of the suggestion list
3. Loading of predefined CSS file can be skipped (set cssLoadedExternally true)
4. Result suffix text can be cleared (set altResultLabel/altResultLabels to an empty string)
5. Suggestion list CSS over-worked (entries are marked even or odd)
6. Bugfix: cleared filter:mask() without color parameter

**1.0.0 ( Changes by Michael Michalowski / Hottgenroth Software GmbH & Co. KG / <m.michalowski@hottgenroth.de> )**

1. jQuery-Library is now located in a separated file and you may prevent typo from loading it via TypoScript (jQueryLoadedExternally)
2. Bugfix: use of @ in jQuery's CSS-selectors is deprecated – corrected the code
3. Fixed locating of form element in Javascript to make autoSubmit working with nested forms
4. Result set can be limited via TypoScript
5. **Attention:**  Main JavaScript method name changed to indexedsearchAutocomplete for compatibility with other autocomplete plugins (you may use jQuery's original autocomplete plugin at the same page now)
6. Compatible with other JS-Frameworks than jQuery (noConflictMethod mode)
7. Bugfix: now supports multiple search fields on one page
8. Documentation update


**2.0.0 ( Claus Bruun changed the ownership of this extension to PIT Solutions Pvt Ltd. )**

1. Typo3 6.2 compatibility fix.

**3.0.0 ( Changes by PIT Solutions Pvt Ltd. )**

1. Compatibility fix - Typo3 6.2.0 - Typo3 8.1.0


