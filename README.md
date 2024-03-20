# Archive7zTimeStamp: SetPass & DeleteDir

Add a context menu entry for folders to Windows explorer. 

This lets you create a timestamped archive of a folder with two clicks.

Plus -sdel (Delete folder after compression) switch syntax.
-p (set Password) switch

Syntax
* -psecret -mhe
compresses dir to dir[archive timestamp].7z using password "secret". Also it encrypts archive headers (-mhe switch), so filenames will be encrypted.


# IDEA
* :vulcan_salute: https://github.com/timosperisen
* https://documentation.help/7-Zip/start.htm

# PREREQUISITES
You will need
* Windows
* Admin rights to install the reg file
* PowerShell
* 7z (64 bit version, else you need to modify the code)
> [!TIP]
> Some luck

# TESTED WITH
* Windows 11
* PowerShell 5.1 Build 26080 Revision 1
