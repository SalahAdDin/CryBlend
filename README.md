CryBlend
========

CryEngine3 Utilities and Exporter for Blender


Original source: http://www.crydev.net/viewtopic.php?f=315&t=103136

Installation
---------
Place the io_export_cryblend folder into:

Your_Blender_path\scripts\addons\

Changelog:
--------

**4.9.8**
Features:
* Fixed incorrect index numbers in the extract_ani functions.

**4.9.7**
Features:
* Fixed the fix of a fix from last time, this is getting stupid.

**4.9.6**
Features:
* Fixed .cga export, again.

**4.9.5**
Features:
* Fixed that drop-down menu from the last update
* Refactored some more code

**4.9.4**
Features:
* Added a drop-down menu for file type selection at export time
* Refactored code

**4.9.3**
Features:
* Added remove bone geometry tool and fixed minor glitch with add bone geometry tool
* Error handling improved.
* It works on wine (Linux/Mac OS).

Fixes:
* Normal maps are now properly exported into mtl file.
* Fixed bug if image path is empty

**4.9.2.1**
Features:
* Code formatted to match PEP-8.

**4.9.2**
Fixed:
* Non relative paths to textures in .mlt file.

**4.9.1.1**
Fixed:
* Spelling issues.
* Trailing white spaces.

**4.9.1**
Fixed:
* #4 - Few registered class are not unregistered properly.

**4.9**
Features:
* New tool for locating lines that are connected to too many faces.
* Upgraded the find degenerate faces tool to make it easier to use.

**4.8.3**
Features:
* The current file directory is now the automatic destination for an export after the first one.
