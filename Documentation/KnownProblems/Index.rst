.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../Includes.txt


.. _known-problems:

Known Problems
==============

* Probably not a problem for you, but the extension utilizes the “initialize_postProc” hook in Indexed Search. Indexed Search is made so that only one extension can hook into this at once.