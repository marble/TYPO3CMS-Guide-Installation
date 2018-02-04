.. include:: ../Includes.txt


.. _upgrade:
.. _upgrading:

Upgrading
=========

When a new version of TYPO3 is released, you should follow the
guideline in this chapter in order to do an upgrade. Also follow any
additional upgrade information carefully. You might e.g. want to skim
the `ChangeLog <https://docs.typo3.org/typo3cms/extensions/core/8.7/>`_ to
see if any features affect the way your site works.

.. note::

   **Version specific upgrade notes**

   While this guide is the general guideline to follow for a TYPO3
   Upgrade, some `version specific information are additionally available
   in the TYPO3 Wiki <https://wiki.typo3.org/Upgrade>`_. Use them as an
   amendment to this guide!

.. note::

   **Think of active users**

   Think of users who might want to do any changes during your upgrading
   and/or fallback. Inform them **before** you start!

Basically these are the steps to be done to update your TYPO3 site:

.. toctree::
   :titlesonly:

   Preparation/Index
   Backup/Index
   UpdateReferenceIndex/Index
   InstallTheNewSource/Index
   ConvertGlobalExtensions/Index
   UseTheUpgradeWizard/Index
   RunTheDatabaseAnalyzer/Index
   ClearCachesAndUserSettings/Index
   RemoveTemporaryCacheFiles/Index
   ChangelogAndNewsmd/Index
   UpdateExtensions/Index
   UpdateTranslations/Index
