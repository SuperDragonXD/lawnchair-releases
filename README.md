# lawnchair-releases
This repo is mirror of the Lawnchair releases (V11 to V12)

## Changelog
### Lawnchair 11
#### Lawnchair 11 Alpha 1
We’re thrilled to release **Lawnchair 11 Alpha 1** – an early version built from the ground up and based on the latest from AOSP. It includes many of our core features:

* At a Glance widget
* Dock search bar
* Icon pack support
* Customisable grid dimensions
* Google Feed integration (see below)
* Icon and label resizing
* Swipe down for notifications
* Auto Adaptive Icons with optional coloured backgrounds
* Customisable App Drawer background opacity

And, for the first time, **Lawnchair 11 works with QuickSwitch on Android 11**. We provide Google Feed integration via the new Lawnfeed 3, compatible only with Lawnchair 11.(For Lawnchair 9 and 10, use Lawnfeed 2.) With new signatures and application IDs, you can install both Lawnchair 11 and Lawnfeed 3 alongside an older release. We are aware of these issues:

* Missing app names in widget drawer
* No screen transitions in Settings

Bear in mind that **we’ve only tested Lawnchair 11 on Android 11**. Official support for earlier Android versions is planned for the near future – along with background blur, individual shortcut customisation, more icon and label size categories, and much else. We look forward to your feedback!

#### Lawnchair 11 Alpha 2
Lawnchair 11.0 Alpha 2 addresses an issue where Google Feed integration would break when Lawnchair was set as a system app.

#### Lawnchair 11 Alpha 3
Lawnchair 11.0 Alpha 3 adds the following features:

* Fuzzy search in the App Drawer
* Customisable backgrounds of Auto Adaptive Icons

This release also addresses the following bugs and inconveniences:

* The foregrounds of some Auto Adaptive
* Icons were too large
* App names and icons were missing from the Widget Drawer
* Lawnchair didn’t revert to system icons when the active icon pack was uninstalled
* Swiping between Home Screen pages could open the notification panel
* In Settings, clicking a row with a switch didn’t toggle the switch
* When folders were being opened, the corners of their backgrounds misbehaved
* The status bar flashed dark grey when Settings were being opened in dark mode

#### Lawnchair 11 Alpha 4
Lawnchair 11.0 Alpha 4 introduces Double-Tap to Sleep and a switch to hide the At a Glance widget from the Home Screen. It sorts entries alphabetically in the icon pack selector, tweaks the About page, and – coupled with QuickSwitch – moves the Clear All button to the bottom portion of Recents for quicker access.

#### Lawnchair 11 Alpha 5
**Lawnchair 11.0 Alpha 5** adds the ability to:

* Hide apps from the App Drawer
* Turn off the Dock search bar
* Hide the Home Screen feed
* Turn off fuzzy search in the App Drawer

Additionally, this release:

* Introduces compatibility with Android 9, 10, and 12
* Reworks Double-Tap to Sleep to use an accessibility service, which resolves the feature interfering with biometric unlock
* Refines the Settings interface
* Aligns the edges of the Dock search bar with the Dock icons
* Addresses a problem where the tap effect of the default Dock search bar extended beyond the search bar’s bounds
* Adds crowdsourced translations (thanks to all contributors; you can help translate Lawnchair on Crowdin)

#### Lawnchair 11 Alpha 
Here’s what’s new in Lawnchair 11.0 Alpha 6:

* accent color customization with 12 presets and an option to use the system accent color
* an option to hide icon labels from the Home Screen
* an option to hide the status bar from the Home Screen
* an option to turn off wallpaper scrolling on the Home Screen
* an option to hide the top shadow from the Home Screen
* the ability to change the theme manually
* support for dynamic icons for clock and calendar apps
* if Lawnchair is connected to QuickSwitch, options to change the card corner radius and the position of the Clear All button in Recents

Additionally, this release

* shortens the time the Home Screen takes to reload after Settings are closed;
* allows up to 10 columns in the Dock and the App Drawer, and up to 10 columns and rows on the Home Screen;
* uses root access for Double-Tap to Sleep on rooted devices; and
* refines the design of Settings.

Thanks go to @AirOne70 and @HuixingWong for their contributions.

#### Lawnchair 11 Alpha 6.1
Lawnchair 11 Alpha 6.1 addresses the following issues:

* Lawnchair could crash on One UI when gesture navigation was on.
* The active icon pack wasn’t applied to Recents.
* An unwanted “Failed to get AppFilter” message could occasionally appear.
* On OxygenOS, if Lawnchair was connected to QuickSwitch, gesture navigation would momentarily become unresponsive after you switched apps.

### Lawnchair 12
#### Lawnchair 12 Alpha 1
Lawnchair 12 Alpha 1 is here! Based on Launcher3 from Android 12, this release has an all-new look and all the features of Lawnchair 11, with a couple of additions. Some highlights:

* The App Drawer, folders, pop-ups, and everything in between have the new look from Android 12.
* Lawnchair can extract the dominant color from your wallpaper and use it throughout the UI, tinting buttons, backgrounds, and the like. This works on Android 8.1 and later.
* Touch and hold an app icon to change its label or hide it from the App Drawer.
* When searching in the App Drawer, tap Enter to open the first result. You can also set the keyboard to open automatically with the App Drawer.

Other changes include a new editor for the Home Screen grid, a refined accent color selector, and an experimental Font setting. Lawnchair 12 works on Android 8 to 12 and integrates with QuickSwitch on Android 11 and 12. We hope you enjoy it!

#### Lawnchair 12 Alpha 2
Lawnchair 12 Alpha 2 introduces an option to hide the App Drawer search bar (thanks to @siju-s) and applies the accent color to Home Screen widgets.

Additionally, this release resolves the following issues:

* Lawnchair could crash after you tapped a Home Screen widget.
* Some icons could disappear from the Dock after Lawnchair was restarted.
* The keyboard could overlap the shortcut customization sheet.
* The status bar icons could be of the wrong color in the App Drawer.

By the way, if you’d like to add the Google Feed to Lawnchair 12, you can install Lawnfeed 3, available [here](https://github.com/LawnchairLauncher/lawnfeed/releases).

#### Lawnchair 12 Alpha 3
Lawnchair 12 Alpha 3 introduces the following new features:

* Themed Icons—for selected apps, custom Home Screen icons that use the accent color are available
* an option to apply the accent color to the Dock search bar
* an option to adjust the corner radius of the Dock search bar
* a crash detector that generates stack traces for sharing in bug reports

Additionally, this release

* addresses a problem where, on Android 12, tapping a widget would not open the corresponding app;
* fixes an issue where Lawnchair could crash after some settings were changed;
resolves an issue where, on devices with a work profile set up, the label of the Work button in the App Drawer could be invisible;
* reduces the minimum corner radius that can be applied to the cards in Recents when Lawnchair is connected to QuickSwitch; and
* makes minor refinements to Lawnchair’s UI.

#### Lawnchair 12 Alpha 4
Lawnchair 12 Alpha 4 introduces the following new features:

* Device Search on rooted Pixel devices with Android 12, which lets you find contacts, settings, and more via the App Drawer search bar
* an option to adjust the height of the rows in the App Drawer
* support for Lawnicons, an upcoming Lawnchair add-on that will add more Themed Icons

Additionally, this release resolves the following issues:

* Even if they were turned on, Themed Icons weren’t displayed when a non-adaptive icon pack was applied.
* Lawnchair could crash on being opened.
* Lawnchair could crash when you tried to drag an app onto the Home Screen.
* Lawnchair could crash when you tried to change the accent color.
* If the Google app wasn’t installed, the accent color wasn’t applied to the Dock search bar even when the appropriate setting was toggled on.

#### Lawnchair 12 Alpha 5
Lawnchair 12 Alpha 5 is here! This version

* adds an option to make the status bar icons dark on the Home Screen;
* when connected to QuickSwitch, offers options to customize what buttons are shown in Recents; and
* introduces an Experimental Features section in Settings.

This release also

* resolves an issue related to localization where traditional and simplified Chinese weren’t correctly distinguished between,
* adds compatibility with Windows Subsystem for Android (thanks to @PeterNjeim),
resolves an issue where Lawnchair could crash after you rotated your device (thanks to @npv12), and
* includes fixes for Device Search.

We’re also happy to release Lawnicons, our add-on for Themed Icons. It is available for download [here](https://github.com/LawnchairLauncher/lawnicons/releases/tag/v1.0.0). For simplicity, all Themed Icons are now provided by Lawnicons. (Previously, some Themed Icons were included in Lawnchair.) To use Lawnicons, install the app and turn on Themed Icons in the General section of Lawnchair’s settings. Thanks to [everyone who contributed to Lawnicons!](https://github.com/LawnchairLauncher/lawnicons/graphs/contributors)
