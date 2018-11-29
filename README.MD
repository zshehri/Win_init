# Windows 10 Init Script
Tweaks to make Windows 10 less annoying and more usable.

Here's what this script does:

1. Disables Cortana
2. Disables Notification Center
3. Disables automatic reboots after Windows Updates have been installed
4. Disables Microsoft.com accounts from Windows Login
5. Shows file extensions for known file types
6. Sets Explorer to open to "This PC"
7. Shows hidden files (not including OS files)
8. Uninstalls OneDrive
9. Shows "This PC" icon on Desktop
10. Enables developer mode (required for Linux Subsystem)
11. Installs the Linux Subsystem
12. Updates the Powershell Get-Help items
13. Disables SMBv1
14. Unpin all Start Menu items
15. Disables WPAD

## Installation
Unfortunately you'll have to set your execution policy to unrestricted to use this script.

From an Administrator Powershell prompt:
```
Set-ExecutionPolicy Unrestricted
cd Win_init
.\Win_init.ps1
Set-ExecutionPolicy Restricted
```

## Credits
The [original script](https://github.com/clong/MakeWindows10GreatAgain/) was created by this awesome guy @clong, I'm copying the script here for personal tweaks and other stuff.

## Notes
This script doesn't address any of the privacy issues of Windows 10 because there are already a [bunch of tools](http://www.ghacks.net/2015/08/14/comparison-of-windows-10-privacy-tools/) that already do that.
