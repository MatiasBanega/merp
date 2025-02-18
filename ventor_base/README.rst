Ventor Base
=========================

Base module that allow relation between Ventor modules

Changelog
---------

14.0.1.3.8 (2022-02-03)
***********************

* Added security group 'Warehouse Operations: Allow applying all qty of product'
* Added automatic switch on the 'Manage package' setting in all menus to default if setting "Package" is switched on
* Added the setting “Scan destination location” to all Operation Types
* Added dependency of settings 'Show next product' and 'Confirm product'
* Added the settings 'Behavior on split operation' and 'Behavior on backorder creation' to all Operation Types
* Added sudo rules for validating stock picking in transit
* Added post init hook and migration for setup Allowed Warehouses to users

14.0.1.3.7 (2021-12-2)
***********************

* [REM] Removed unused settings displayed in the Ventor Preferences tab on the user form
* [REM] Removed 'Default inventory location' from the Inventory settings from the Ventor Configuration
* [IMP] Changed 'Ventor Configuration' menu, added 'User Settings' menu item
* [REM] Removed 'Custom package name' field displayed in the Ventor Preferences tab on the user form
* [IMP] Added 'Custom Build Name' field in Ventor Configuration/Additional Settings

14.0.1.3.6 (2021-09-23)
***********************

* Added migration to recalculated warehouse on Inventory Adjustments and dependence of selected locations on warehouse

14.0.1.3.5 (2021-09-23)
***********************

* Added migration to recalculated warehouse on existing locations

14.0.1.3.4 (2021-09-18)
***********************

* Added rule for stock picking batches

14.0.1.3.3 (2021-09-08)
***********************

* Added support for multi warehouses

14.0.1.3.2 (2021-09-06)
***********************

* Added migration to prefill calculated warehouses on exsiting installations

14.0.1.3.1 (2021-09-04)
***********************

Added new operation types settings:

* Apply quantity automatically
* Autocomplete the item quantity field
* Show Print attachment button
* Show Put in pack button

14.0.1.3.0 (2021-09-02)
***********************

* Added restricting access to warehouses for odoo users

14.0.1.2.1 (2021-06-29)
***********************

* Added access rights on user's settings fields

14.0.1.2.0 (2021-06-22)
***********************

* Added global menu Ventor Configuration
* Ventor configuration checkboxes added to Operations Types
* Users Ventor Application Settings moved to Ventor Preferences tab

14.0.1.1.0 (2021-06-17)
***********************

* Added functionality to force lot validation on Inventory Adjustment

14.0.1.0.1 (2021-05-27)
***********************

* Added 3 more menu groups to Ventor Menu Management.
