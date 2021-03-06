# Install xDrip+

## Prerequisites

You need an Android phone.

- Minimum supported Android version is 4.4 but 6 and above is recommended.
- If you will connect xDrip+ to a sensor your phone must support Bluetooth Low Energy (BLE): you can use utilities [like this](https://play.google.com/store/apps/details?id=com.myan.michaelyanyoga.bluetoothchecker) one to check.
- In order to connect to a Bluetooth CGM your phone needs to have location enabled (GPS).
- If you want to use the embedded master - follower function of xDrip+ (called xDrip+ Sync) your phone needs to have the [Google Play Services](https://play.google.com/store/apps/details?id=com.google.android.gms) installed.
- If you wish to use scanning features for Libre sensors your phone needs an NFC reader.
- If using Android 10 and above make sure you use a recent version of xDrip+ (see below).

</br>

## Which one to install?

xDrip+ is not available in the Google Play store by developers decision. You will find all releases in [Github](https://github.com/NightscoutFoundation/xDrip/releases).  
If you don't know which one to select you have two choices:

### Latest release

Latest release is a stable version of xDrip+. It doesn't have all the newest features but has proven stability and doesn't suffer severe bugs. It's a safe version to start with.

You can download it [here](https://xdrip-plus-updates.appspot.com/stable/xdrip-plus-latest.apk).

### Pre-release

Pre-release include most recent xDrip+ developments like translations, new features and bug fixes. And it might also contain some bugs... Still, it is the version you want to use to benefit most recent improvements.

All xDrip+ versions are available [here](https://github.com/NightscoutFoundation/xDrip/releases).

Expand the assets and select the `.apk` file. You will find it in your phone `Downloads` directory.

<img src="../images/Install01.png" style="zoom:90%;" />

*Note: don't use Facebook links to download xDrip+ but copy and paste the link into a browser (like Chrome).*

</br>

#### Note: Private versions

Some developers add features and customizations that are not available in the official pre-releases until the author will create a Pull Request in xDrip+ and get it merged in the main project. You can use these versions but need to understand they might be supported only by their creator. xDrip+ automatic updates won't work with private versions.

</br>

## Install xDrip+

Once downloaded, install the xDrip+ apk.

<img src="../images/Install02.png" style="zoom:75%;" />

**You need to [authorize installation of apps from unknown sources](https://developer.android.com/distribute/marketing-tools/alternative-distribution#unknown-sources) in Android security settings.**  
xDrip+ is virus and malware free: being open source and controlled by the main developer make its distribution safe if you download it from GitHub.

<img src="../images/Install04.png" style="zoom:75%;" />

Once installed, open xDrip+.

<img src="../images/Install03.png" style="zoom:75%;" />

**Read** the important Warning.  
Make sure you understand it before selecting `I Agree`.

<img src="../images/Install05.png" style="zoom:75%;" />

​	Do NOT use or rely on this software or any associated materials for any medical purpose or decision.  
​	Do NOT rely on this system for any real-time alarms or time critical data.  
​	Do NOT use or rely on this system for treatment decisions or use as a substitute for professional healthcare judgement.  
​	All software and materials have been provided for informational purposes only as a proof of concept to assist possibilities for further research.  
​	No claims at all are made about fitness for any purpose and everything is provided **AS IS**. Any part of the system can fail at any time.  
​	Always seek the advice of a qualified healthcare professional for any medical questions.  
​	Always follow your glucose-sensor or other device manufacturers\' instructions when using any equipment; do not discontinue use of accompanying reader or receiver, other than as advised by your doctor.  
​	This software is not associated with or endorsed by any equipment manufacturer and all trademarks are those of their respective owners.  
​	Your use of this software is entirely at your own risk.  
​	No charge has been made by the developers for the use of this software.  
​	This is an open-source project which has been created by volunteers. The source code is published free and open-source for you to inspect and evaluate.  
​	By using this software and/or website you agree that you are over 18 years of age and have read, understood and agree to all of the above.

<img src="../images/Install06.png" style="zoom:75%;" />

</br>

**Read** the EULA.  
Make sure you understand it before saving.

xDrip+ MUST NOT BE USED TO MAKE MEDICAL DECISIONS.  
IT IS A RESEARCH TOOL ONLY AND IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE.  
THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE PROGRAM IS WITH YOU.  
SHOULD THE PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF ALL NECESSARY SERVICING, REPAIR OR CORRECTION.

<img src="../images/Install06a.png" style="zoom:75%;" />

</br>

#### Authorize background activity

xDrip+ must have the right to run in background: it must be whitelisted to battery optimization. This is essential to a correct functioning. It should ask you to allow this authorization. If it doesn't or you need to verify this later, you'll have to check it in your phone `Settings` - `Apps` - `xDrip+`. Consult your phone manual as  it will depend on Android version and manufacturer.

<img src="../images/Install07.png" style="zoom:75%;" />

</br>

#### Enable location

For newer Android versions, location is [mandatory](https://developer.android.com/training/location/permissions) to allow Bluetooth Low Energy connection.  
If you use xDrip+ with a Bluetooth sensor you **must** enable location and authorize xDrip+ to access it. Consult your phone manual as  it will depend on Android version and manufacturer.

<img src="../images/Install16.png" style="zoom:75%;" />

</br>

## Verify which version is installed

Touch the back button on your phone until you're back to the main screen. Select the hamburger menu top left then `System Status`.

<img src="../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../images/M-SS.png" style="zoom:75%;" />

Current version will be displayed after `Version`. In the example below, March 1st 2021.

<img src="../images/M-SS-Ver.png" style="zoom:75%;" />

See [here](../upgradedowngrade) for upgrade or downgrade.

</br>

## Make sure xDrip+ will not be put to sleep

These settings are default, but still make sure they are exactly like shown below. Any time your phone will update, come back and check again: disable and enable checkboxes that should be enabled to enforce the settings.

`Menu` / `Settings` / `Less Common Settings` / `Other misc options`

<img src="../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../images/M-S.png" style="zoom:75%;" />

<img src="../images/M-S-LCS.png" style="zoom:75%;" />

<img src="../images/M-S-LCS-OMO.png" style="zoom:75%;" />

`Run Collector in Foreground` enables the graph in your phone drop down curtain but is essential to keep the app alive.

`Battery optimization prompt` should be disabled as you should have agreed to [battery whitelisting](#authorize-background-activity) during install.

If you have a Samsung phone allow Samsung workarounds to fix a Samsung non compliance to Android specifications. This should enable automatically.

<img src="../images/M-S-LCS-OMO1.png" style="zoom:75%;" />

</br>

## Select data source

If you want to connect xDrip+ directly to your sensor, select it in the wizard.

<img src="../images/Install08.png" style="zoom:75%;" />

</br>

If you don't see the wizard you can start it using the `START SOURCE SETUP WIZARD` button on the main screen.

<img src="../images/Install12.png" style="zoom:75%;" />

</br>

If you don't see this button you can bring it back to display with a long press on the xDrip+ icon blood drop and enable source wizard button.

<img src="../images/Install13.png" style="zoom:75%;" />

</br>

### G4 G5 G6

In order to connect xDrip+ to a G5 or G6 sensor you need to uninstall the vendor app from this phone or any other phone connected to it. The receiver will continue to receive the sensor signal as it's using another Bluetooth channel.  
Note that xDrip+ will allow the use of Dex Share servers but will **not upload data to Clarity**. If you decide to use this solution, it is recommended to use [Tidepool](https://www.tidepool.org/) or [Nightscout](https://nightscout.github.io/) to generate your reports.

If you want to use xDrip+ but you still want to connect your sensor to the vendor app, go back to the first page and select Other. You can use xDrip+ either as a Dex Share follower (but you will need network access) or [build your own app](https://docs.google.com/forms/d/e/1FAIpQLScD76G0Y-BlL4tZljaFkjlwuqhT83QlFM5v6ZEfO7gCU98iJQ/viewform) (enabling broadcast to xDrip+) and select 640G/670G or Eversense as the data source.

<img src="../images/Install09.png" style="zoom:75%;" />

Else continue here:

[G4](../g4)  
[G5](../g5)  
[G6](../g6)

</br>

### Libre

You can use xDrip+ to scan your Libre (**Not** 14 days US version) sensor selecting the any of these data sources if your phone has an NFC reader. Note that there is only limited value in doing so as the only advantage is to be able to calibrate the readings. In order to get the best of xDrip+ it is recommended that you buy an additional bridge device doing the sensor scan automatically every 5 minutes.

<img src="../images/Install10.png" style="zoom:75%;" />

Continue here:

[Bridge devices](../libre-bridge) like LimiTTer (obsolete), blueReader (obsolete), Blucon, miaomiao (Tomato), Bubble or Droplet  
LibreAlarm: Patched [Sony SWR50](../libre-swr50)  
[Patched app](../libre-patched) (Libre 2 EU version)  
[Libre 2](../libre2) (EU version)

</br>

### Others

<img src="../images/Install11.png" style="zoom:75%;" />

[640G/670G](../medtronic) with the Medtronic uploader app and the [G5/G6 BYO app](../byo).   
[Medtrum](../medtrum) A6/S7  
[Nightscout Follower](../nightscout)  
[Dex Share Follower](../dex-follow)  
[Eversense](../eversense) with the Esel app

</br>

### Hardware data source list

If you haven't found the data source you were looking for in the wizard or you want to change it, touch the back button on your phone until you're back to the main screen. Select the hamburger menu top left then `Settings`. Select `Hardware data source`.

<img src="../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../images/M-S.png" style="zoom:75%;" />

<img src="../images/M-S-HWDS.png" style="zoom:75%;" />

This will display the full list of available data sources.

<img src="../images/M-S-HWDS-List.png" style="zoom:75%;" />

