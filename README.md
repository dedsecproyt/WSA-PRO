# Windows Subsystem for Android

## Features

- Integrate Magisk and OpenGApps/MindTheGapps in a few clicks within minutes
- No Linux environment required for integration
- Keep each build up to date
- Support both ARM64 and x64
- Support all OpenGApps/MindTheGapps
- Unattended installation
- Automatically activates developers mode in Windows 11
- Update to new version while preserving data with one-click script
- Merged all language packs

## Install Guide
- Download zip file and unzip on Disk C or D
- Right-click `Install.ps1` Run with PowerShell

FOR CONNECT TO ADB - adb connect localhost:58526

## Uninstallation
> Note: If you want to preseve your data, make a backup of the `%LOCALAPPDATA%\Packages\MicrosoftCorporationII.WindowsSubsystemForAndroid_8wekyb3d8bbwe\LocalCache\userdata.vhdx` file. After uninstalling, copy the VHDX file back to the `%LOCALAPPDATA%\Packages\MicrosoftCorporationII.WindowsSubsystemForAndroid_8wekyb3d8bbwe\LocalCache` folder.

1. Go to the Start Menu
2. Type `Windows Subsystem for Android`
3. Once the WSA app shows, click `App settings` in the right pane
4. In the Settings window that opens, scroll down and click `Terminate`
5. Click `Repair`
6. Click `Reset`
7. Close the Settings app
8. Go to the Start Menu
9. Type `Windows Subsystem for Android`
10. Once the WSA app shows, click `Uninstall` in the right pane
