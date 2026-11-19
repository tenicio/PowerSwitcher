[![Build](https://github.com/tenicio/PowerSwitcher/actions/workflows/build.yml/badge.svg)](https://github.com/tenicio/PowerSwitcher/actions/workflows/build.yml)

> This is a maintained fork of [petrroll/PowerSwitcher](https://github.com/petrroll/PowerSwitcher), which is no longer updated and is no longer available in the Microsoft Store.

### About:
PowerPlanSwitcher is a simple app that allows you to quickly switch between power plan schemas from application tray. In addition to a manual schemas switching it also supports an automatic switch when AC adapter gets connected/disconnected. 

Features:
- Windows10 styled flyout that allows quick power plan schemas changing
- Ability to limit flyout only to Windows default power plan schemas
- Automatic schema switching when AC adapter gets connected / disconnected
- Launch on Windows startup
- Flyout shortcut (Shift+Win+L)
- Navigate the flyout with keyboard (use tab)
- Change all settings by right-clicking on the tray icon :)

### Download:
Get the latest build from the [Releases](https://github.com/tenicio/PowerSwitcher/releases) page.

1. Download `PowerSwitcher.zip` and unzip it to a permanent folder, for example `%LOCALAPPDATA%\Programs\PowerSwitcher`.
2. Run `PowerSwitcher.TrayApp.exe`. The app appears as an icon in the system tray.
3. To start it with Windows, put a shortcut to `PowerSwitcher.TrayApp.exe` in your Startup folder (press Win+R and enter `shell:startup`).

Requires Windows 10 or 11 with .NET Framework 4.8, which is included with current versions of Windows.

### Other:
The original author, Petr Houška, accepts donations for the original app: [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=houskape%40gmail%2ecom&lc=CZ&item_name=PowerPlanSwitcher&item_number=042&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted)

### Special thanks to:
- [Petr Houška (petrroll)](https://github.com/petrroll), the original author of PowerSwitcher
- Icon made by [Cursor creative](http://www.flaticon.com/authors/cursor-creative) from [flaticon.com](http://www.flaticon.com/)
- [EarTrumpet](https://github.com/File-New-Project/EarTrumpet) project for flyout, interop stuff, and some other help :)
 - David Golden (@GoldenTao)
 - Rafael Rivera (@WithinRafael)
- [Andy Belsky's power-plan-switcher](https://github.com/andy722/power-plan-switcher) for some interop inspiration
- [Mahdi Safsafi's ImmersiveColors](https://github.com/MahdiSafsafi/ImmersiveColors) for making working with undocumented accent colors easy :)

![PowerPlanSwitcher Flyout](ReadmeAssets/PowerSwicher_Flyout_1.PNG)

![PowerPlanSwitcher Flyout 2](ReadmeAssets/PowerSwicher_Flyout_2.PNG)

![PowerPlanSwitcher Context Menu](ReadmeAssets/PowerSwicher_ContextMenu_1.PNG)

![PowerPlanSwitcher Context Menu 2](ReadmeAssets/PowerSwicher_ContextMenu_2.PNG)
