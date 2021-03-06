# Changelog

## [0.11.2] - 2018-04-10

### Features
* support for dynamic table column (column containing simple array parameter will be expanded to multiple columns)

### Bug Fixes
* text element styling when element uses predefined style with borders
* fix undo of deleted frame element (restore nested elements)
* fix display of table column texts when padding of a column text is modified

## [0.11.1] - 2018-03-21

### Features
* multiple content row definitions for tables
* group expression and print if for table content rows
* boolean parameter type
* simple list parameter type (list items with basic type like string, number, boolean, date)
* nullable setting for parameter to explicitly allow nullable parameters, non-nullable parameters automatically get default value in case there is no data (e.g. 0 for numbers or '' for strings)

### Bug Fixes
* update table column element height when table row height is changed
* copy&paste of frame elements
* save eval setting of table column text

## [0.10.1] - 2017-11-02

### Features
* frame elements to group document elements

## [0.9.9] - 2017-08-19

Initial release.
