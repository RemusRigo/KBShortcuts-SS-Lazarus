# KeyBoard Shortcuts ScreenSaver: User's Guide



## Downloads & Runtimes

Download the latest release from the [Releases page](https://github.com/RemusRigo/KBShortcuts-SS-Lazarus/releases).

|File|Architecture|Required Runtime|
|-|-|-|
|`KBShortcuts.scr`|Windows|none (native Windows app)|

The release also contains `Install.bat`, `Config.bat` and the `Registry` folder.



## Install

1. Copy `KBShortcuts.scr`, `Install.bat` and `Config.bat` to a permanent folder, for example `D:\My Apps\KBShortcuts SS\`.
2. Install it, either way:
   * right-click `KBShortcuts.scr` and choose **Install**, or
   * double-click `Install.bat`.

   The Windows **Screen Saver Settings** dialog opens with *KBShortcuts* selected.
3. Set the **Wait** time and click **OK**.

> If right-clicking `KBShortcuts.scr` doesn't show **Install** (the `.scr` file association is broken or taken by another app),
> double-click `Registry\SCR - Restore File Association.reg` and try again.



## Test it

* In **Screen Saver Settings**, click **Preview**, or
* double-click `KBShortcuts.scr`.

A keyboard shortcut and its description are shown and move on the screen; a new random shortcut is shown every 3 seconds.
Press any key or move the mouse to exit.

> The small preview in the **Screen Saver Settings** dialog stays empty.



## Settings

Open them from **Screen Saver Settings** → **Settings...**, or double-click `Config.bat`.

|Setting|Description|
|-|-|
|**Category**|Check the shortcut categories to show: Windows, Excel, Word, Browser|

Click **Ok** to save.
Settings are stored per user in the registry under `HKEY_CURRENT_USER\Software\Remus RIGO\SS\KB Shortcuts`.



## Multi-monitor

The screensaver covers all monitors.



## Uninstall

1. In **Screen Saver Settings**, choose another screensaver (or *None*) and click **OK**.
2. Delete the folder you copied in step 1 of *Install*.
3. Optional: delete the registry key `HKEY_CURRENT_USER\Software\Remus RIGO\SS\KB Shortcuts`.
