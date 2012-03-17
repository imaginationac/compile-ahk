Compile AHK
===========

v0.9.1
Authors: denick, ladiko, flashkid, ruespe, darklight_tr
Built with AutoHotkey_L v1.1.03.00 20110828

Info
----

Compile AHK is a GUI based script that assists with compiling AutoHotkey scripts.

OS Support: Windows XP, Windows Vista, Windows 7
Tested On: Windows XP, Windows 7

Known Issues
------------

- This version of Compile AHK is intended for use with AutoHotkey_L v1.1.01.00 and higher.  For AutoHotkey Basic or AutoHotkey_L v1.1.00.01 and lower use Compile AHK v0.9.0.50/58.
- Icon files contained in very long directory paths will generate errors when they are selected.  This issue is under investigation.

Please report any issues you encounter here: https://github.com/imaginationac/compile-ahk/issues

License
-------

Originally declared just "open source", any new contributions will be considered public domain.
If your jurisdiction does not recognize the concept of public domain, use the MIT License (see LICENSE for details).

Changelog
----------

### v0.9.1 (10/01/11)

#### Compile AHK Changes:

- Removed password protection option as it is no longer supported by AutoHotkey_L v1.1.01.00 and higher.
- Removed NoDecompile option as it is not supported by AutoHotkey_L.
- Fixed an issue where the Compile AHK version in the title window would not display correctly.
- Set the default language in the language.ini file to en-us. (Previous default was de-de)
- Fixed a tab naming error in the language.ini file. (Resourcess is now Resources)
- Removed password protection and NoDecompile entries from the language.ini file.
- Compiled with AutoHotkey_L v1.1.03.00.
- Edited credits.

#### Setup Changes:

- Changed "essential component" text to "Required"
- Fixed GoRC URL. (Bad link)
- Corrected copyright information.
- Executable versions included in the setup are now shown on the initial GUI.
- GoRC updated to v0.90.5.
- ResHacker updated to v3.6.0.
- Added mpress.exe v2.18 to the setup.
- Added MPRESS copyright information and URL.
- Adjusted the spacing in the initial GUI.
- Added /nompress command line switch.
- Added mpress.exe checkbox to the selection GUI.

How to build
------------

### Depedencies

The following need to be downloaded & installed.

- [AutoHotkey_L](http://l.autohotkey.net/AutoHotkey_L_Install.exe)
- [GoRC](http://www.godevtool.com/) - Freeware Resouce compiler
- [ResHacker](http://www.angusj.com/resourcehacker/) - Freeware Resource editor
- [MPRESS](http://www.matcode.com/mpress.htm) - Freeware executable packer

