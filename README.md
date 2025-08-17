# Windows XAML Styles
A collection of my custom Windows XAML styles for Windhawk's various XAML styler mods for Windows 11.


## Table of contents
* Styles for UWP Apps
  * [Quick Actions](#quick-actions)
  * [File Explorer](#file-explorer)
  *  `WIP` [Start Menu](#start-menu)
* Styles Info
  * `WIP` [How to apply Custom XAML Styles](#how-to-apply-custom-xaml-styles)
  * [Further configuration](#further-configuration)
  * `WIP` [Taskbar tips and tricks](#taskbar-tips-and-tricks)
* Additional Info
  * [WinMac](https://github.com/Asteski/WinMac)
  * [Windhawk](https://github.com/ramensoftware/windhawk) 
  * [Additional utilities](https://github.com/Asteski/WinMac/wiki/Additional-utilities)
* Future plans
  * [Windows 11 Start Menu Styler themes](#start-menu)
  * Option to hide screen brigthness slider

## Quick Actions

Quick actions styles main focus are on merging both volume and media control regions into a single region. Recommended for enthusiasts who like their taskbar positioned at the top, and using 3rd party taskbars like StartAllBack or ExplorerPatcher.

Windhawk mod that needs to be installed for Quick Actions styles: [Windows 11 Notification Center Styler](https://windhawk.net/mods/windows-11-notification-center-styler)

[Quick Actions - Small JSON code](https://github.com/Asteski/Windows-XAML-Styles/blob/main/styles/Notification%20Center%20Styler%20-%20Quick%20Actions%20-%20Small.json)

![Quick Actions - Small](https://github.com/Asteski/Windows-XAML-Styles/blob/main/img/Notification%20Center%20Styler%20-%20Quick%20Actions%20-%20Small.png)

[Quick Actions - Large JSON code](https://github.com/Asteski/Windows-XAML-Styles/blob/main/styles/Notification%20Center%20Styler%20-%20Quick%20Actions%20-%20Large.json)

![Quick Actions - Large](https://github.com/Asteski/Windows-XAML-Styles/blob/main/img/Notification%20Center%20Styler%20-%20Quick%20Actions%20-%20Large.png)

[Quick Actions - No Cover JSON code](https://github.com/Asteski/Windows-XAML-Styles/blob/main/styles/Notification%20Center%20Styler%20-%20Quick%20Actions%20-%20No%20Cover.json)

![Quick Actions - No Cover](https://github.com/Asteski/Windows-XAML-Styles/blob/main/img/Notification%20Center%20Styler%20-%20Quick%20Actions%20-%20No%20Cover.png)

## File Explorer

File Explorer styles are a hybrid of legacy and modern toolbar areas, with additional tweaks for command bar like:
* enforce transparency effect
* reduced height
* disabled border

Windhawk mods that needs to be installed for File Explorer style: [Windows 11 File Explorer Styler](https://windhawk.net/mods/windows-11-file-explorer-styler), [Classic Explorer navigation bar](https://windhawk.net/mods/explorer-frame-classic)

[File Explorer JSON code](https://github.com/Asteski/Windows-XAML-Styles/blob/main/styles/File%20Explorer%20Styler%20-%20File%20Explorer.json)

![File Explorer](https://github.com/Asteski/Windows-XAML-Styles/blob/main/img/File%20Explorer%20Styler%20-%20File%20Explorer.png)

[File Explorer - No Command Bar JSON code](https://github.com/Asteski/Windows-XAML-Styles/blob/main/styles/File%20Explorer%20Styler%20-%20File%20Explorer%20-%20No%20Command%20Bar.json)

![File Explorer - No Command Bar](https://github.com/Asteski/Windows-XAML-Styles/blob/main/img/File%20Explorer%20Styler%20-%20File%20Explorer%20-%20No%20Command%20Bar.png)

## Start Menu

`WIP`

## Further configuration

### Quick Actions

Enable Toggles Group by setting *"Visibility=0"* for targets *"Grid > GridView#RootGridView"* and *"Windows.UI.Xaml.Controls.ContentControl#TogglesGroup"*.

*Height=100* showed on [Quick Actions - Large](https://github.com/Asteski/Windows-XAML-Styles/blob/main/styles/Notification%20Center%20Styler%20-%20Quick%20Actions%20-%20Large.json)

![Quick Actions - TogglesGroup - Height=100](https://github.com/Asteski/Windows-XAML-Styles/blob/main/img/Notification%20Center%20Styler%20-%20Quick%20Actions%20-%20TogglesGroup%20-%20100.png)

*Height=200* showed on [Quick Actions - Small](https://github.com/Asteski/Windows-XAML-Styles/blob/main/styles/Notification%20Center%20Styler%20-%20Quick%20Actions%20-%20Small.json)

![Quick Actions - TogglesGroup - Height=200](https://github.com/Asteski/Windows-XAML-Styles/blob/main/img/Notification%20Center%20Styler%20-%20Quick%20Actions%20-%20TogglesGroup%20-%20200.png)

*Height=290* showed on [Quick Actions - Small](https://github.com/Asteski/Windows-XAML-Styles/blob/main/styles/Notification%20Center%20Styler%20-%20Quick%20Actions%20-%20Small.json)

![Quick Actions - TogglesGroup - Height=290](https://github.com/Asteski/Windows-XAML-Styles/blob/main/img/Notification%20Center%20Styler%20-%20Quick%20Actions%20-%20TogglesGroup%20-%20290.png)

*Height=Auto* shows all available toggles.

### Quick Actions

Show Tabs Only by disabling *Classic Explorer navigation bar* mod and setting *explorerFrameContainerHeight=41*.

[File Explorer - Tabs Only JSON code](https://github.com/Asteski/Windows-XAML-Styles/blob/main/styles/File%20Explorer%20Styler%20-%20File%20Explorer%20-%20Tabs%20Only.json)

![File Explorer - Tabs Only](https://github.com/Asteski/Windows-XAML-Styles/blob/main/img/File%20Explorer%20Styler%20-%20File%20Explorer%20-%20Tabs%20Only.png)