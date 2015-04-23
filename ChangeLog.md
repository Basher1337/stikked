_Due to my incompetence, There's only changelog history from version 0.4. -- Ben_

### Stikked0.5.3 ###
_Revision 47_

  * Fixed a bug where the libraries were not being loaded correctly on case-sensitive file systems.


---


### Stikked 0.5.2 ###
_Revision 38_

  * Updated all code to work with phpdoc.
  * Documentation generated by phpdoc included in /docs.


---


### Stikked 0.5.1 ###
_Revision 35_

**Major Feature Additions**:
  * Paste Replies Now Implemented.
  * Paste Downloading.
  * New Design based off stikked.com

**Minor Feature Additions**:
  * Changed non-private paste ids to be a random number, to be easier to remember.
  * Added status messages for some actions.
  * Now using YUI font library for accessiblity.

**Bug Fixes/Enhancements**:
  * Fields are now re-populated after generating an error when submitting a paste.
  * All curly braces at the start and end of code blocks are now on their on line. For better readability.
  * Removed all random and pointless use of "double quotes".
  * Organised views into separate folders.
  * Links now work without the .htaccess


---


### Stikked 0.5 ###
_Revision 23_

**New Features**
  * Now an option to expand the viewing of a paste to fill the whole width of the
browser
  * A new paste viewing options area. that lets you set whole width pastes and raw
paste viewing as default.
  * Some options now hidden with an advanced options section.
  * New remember me option, that saves your settings
  * New snipurl creator. That will auto-create a snipurl.

**Bug Fixes/Enhancements**
  * Better auto-copy. Now using flashdata.
  * Renamed the count method in the pastes model to countPastes. Following a more consistent naming structure
  * Added a table containing all the possible languages so they can be checked
(sql in next rev)
  * Added a model for this table and a method to check if a paste is valid
  * Now generates language listings from table


---


### Stikked 0.4.3 ###
_Revision 24_

Changes to make stikked 100% XHTML 1.0 Strict and CSS 2.1, Compliant.


---


### Stikked 0.4.2 ###
_Revision 23_

**New Features**
  * Paste expiration now availible

**Bug Fixes/Enhancements**
  * Updated mysql to allow paste expiration
  * Modifications to table structure to allow longer pastes
  * Raw pastes moved to a seperate pagee
  * Bug fixed in pastes model, to faciltate pasting from textmate bundle.


---


### Stikked 0.4 ###
_Revision 14_

**New Features**
  * New Design - Again
  * Auto Copy, Using javascript and flash, the url to a newly created paste can now be automatically copied to the clipboard opon creation.
  * Auto generating names, if "random" is supplied for anonymous pasters (Default), a name will be automatically generated using the nouns and adjectives described in the stikked.php config file.


**Bug Fixes**
  * Errors, Error pages now match the actual design and Fixed a problem where a 404 would not be shown on a non existent paste.

**Updates/Enhancements**
  * Files moved around, Static directory reorganized into styles, images, js and flash.
  * Updated Readme