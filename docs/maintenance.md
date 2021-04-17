# Maintenance operations

## Update xDrip+

You can easily upgrade (more recent) or downgrade (older) your xDrip+ version simply by installing another version on top of the current one. This means you don't need to uninstall the current version, hence avoid losing all data and settings.

There are two methods to update xDrip+, you can do it either manually or set the app to inform you an update is available and let it handle the download.

### Manual update

Follow the [install guidelines](../install/#which-one-to-install).

### Automated update

You can set xDrip+ to inform you when an update is available and decide on which type of update you want.

`Menu` / `Settings` / `xDrip+ Update Settings`

<img src="../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../images/M-S.png" style="zoom:75%;" />

<img src="../images/M-S-U.png" style="zoom:75%;" />

<img src="../images/M-S-Update1.png" style="zoom:75%;" />

First  select the update type you're interested in with `Update channel`

<img src="../images/M-S-Update2.png" style="zoom:75%;" />

`Stable` versions, known as releases are rarely refreshed and will not include latest developments. If your system is stable and you don't need new features, keep a released version.

`Beta` versions are rarely built and might address some more recent issues.

If you need to update you most probably want to select `Alpha`.

Once selected, turn on the Automatic update check.

> Note: If you selected Alpha, a new option will be available in `Update channel`: `Nightly`. You can select this option to have automatic download of the automatic nightly builds. This is not recommended. Use a nightly build only if you need a specific feature or experience issues that are currently been worked on.

<img src="../images/M-S-Update3.png" style="zoom:75%;" />

If an update is available it should start downloading now.

If the update doesn't start, go back to the main xDrip+ display and select the upper right 3 dots menu.

<img src="../images/3dots_menu.png" style="zoom:75%;" />

Select `Check for updated version`.

<img src="../images/3DM.png" style="zoom:75%;" />

If an update is available the following screen should show. Select `DOWNLOAD NOW`.  
If download fails, try de-selecting `Use internal downloader` and retry.

<img src="../images/M-S-Update4.png" style="zoom:75%;" />

Once download completes, xDrip+ will run the installer.

<img src="../images/M-S-Update5.png" style="zoom:75%;" />

<img src="../images/M-S-Update6.png" style="zoom:75%;" />

<img src="../images/M-S-Update7.png" style="zoom:75%;" />

xDrip+ now updated, [check your version](../install/#verify-which-version-is-installed) if you want to be sure.

</br>

## Reinstall xDrip+

This shouldn't usually be necessary but you might need to uninstall xDrip+ to troubleshoot, or if you need to change it to or from a private version.. For this, follow this sequence: [backup](#backup), uninstall the xDrip+ app (the same way you'd remove any app from your phone), [install](../install/#which-one-to-install) and then [restore](#restore).  
Once complete check all your settings and recreate your alarms.



## Backup

### Backup settings

`Menu` / `Settings` / `Load/Save setting to SDcard`

<img src="../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../images/M-S.png" style="zoom:75%;" />

<img src="../images/M-S-LSS.png" style="zoom:75%;" />

</br>

You also can access it from the 3 dots menu:

<img src="../images/3dots_menu.png" style="zoom:75%;" />

Select `Import Export features`.

<img src="../images/3DM.png" style="zoom:75%;" />

Select `Load/Save setting to SDcard`

<img src="../images/3DM-IE.png" style="zoom:75%;" />

</br>

Select `SAVE ALL SETTINGS TO SDCARD`

<img src="../images/M-S-Settings.png" style="zoom:75%;" />

Your settings will be saved in `/storage/emulated/0/Download/xDrip-Export`  
You need to authorize xDrip+ to access your phone memory.  
Existing backup will be overwritten.

<img src="../images/M-S-SettingsLoc.png" style="zoom:75%;" />

If you want to keep a safe copy, send the file to yourself by email, save in on a cloud drive or copy it via USB to a computer.

</br>

### Backup the database

The database contains all BG readings, treatments and notes. It is strongly recommended that you backup your database and keep a copy on another device if you want to keep your existing data and as a safety precaution against a phone loss, crash, ...  
Using upload to [Nightscout](https://nightscout.github.io/) is also strongly recommended.

From the main xDrip+ display select the upper right 3 dots menu.

<img src="../images/3dots_menu.png" style="zoom:75%;" />

Select `Import Export features`.

<img src="../images/3DM.png" style="zoom:75%;" />

Select `Export database`.

<img src="../images/3DM-IE.png" style="zoom:75%;" />

</br>

The current database will be saved in `/storage/emulated/0/xDrip`  
You need to authorize xDrip+ to access your phone memory.  
You can make as many backups as your memory can store.

<img src="../images/3DM-IE-Loc.png" style="zoom:75%;" />

Your backup will be named `exportYYYYMMDD-HHMMSS.zip` with `YYYY` current year, `MM` month, `DD` day, and `HHMMSS` for hour minutes and seconds. This will allow you to have multiple backups identified by a unique timestamp.

If you want to keep a safe copy, send the file to yourself by email, save in on a cloud drive or copy it via USB to a computer.

</br>

## Restore

### Restore settings

When xDrip+ install is complete, if a backup is available, xDrip+ will propose to restore it automatically.   
Select `RESTORE SETTINGS`

<img src="../images/3DM-BR-Restore5.png" style="zoom:75%;" />

</br>

If you don't see this message, restore it manually.

`Menu` / `Settings` / `Load/Save setting to SDcard`

<img src="../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../images/M-S.png" style="zoom:75%;" />

<img src="../images/M-S-LSS.png" style="zoom:75%;" />

</br>

You also can access it from the 3 dots menu:

<img src="../images/3dots_menu.png" style="zoom:75%;" />

Select `Import Export features`.

<img src="../images/3DM.png" style="zoom:75%;" />

Select `Load/Save setting to SDcard`

<img src="../images/3DM-IE.png" style="zoom:75%;" />

</br>

Select `LOAD ALL SETTINGS FROM SDCARD`

<img src="../images/M-S-Settings.png" style="zoom:75%;" />

</br>

### Restore a database

When xDrip+ install is complete, if a database backup is available, xDrip+ will propose to restore it automatically.

<img src="../images/3DM-BR-Restore1.png" style="zoom:75%;" />

Make sure this is the database you want to restore then select `RESTORE`

<img src="../images/3DM-BR-Restore2.png" style="zoom:75%;" />

*Note: the current database will be exported first, for safety, you will find it in the list named `b4import` and the date/time the import was done. This will allow you to recover it if necessary.*

</br>

If you want to restore a specific backup, from the main xDrip+ display select the upper right 3 dots menu.

<img src="../images/3dots_menu.png" style="zoom:75%;" />

Select `Import Export features`.

<img src="../images/3DM.png" style="zoom:75%;" />

Select `Import database`.

<img src="../images/3DM-IE.png" style="zoom:75%;" />

Instructions are displayed. You don't need to move the backup file if you didn't move it from another device, you don't need to unzip it. Be cautious on restoring a database with a different xDrip+ version: it is recommended that you install the [xDrip+ version](../install/#verify-which-version-is-installed) that was used to perform the export before importing, then you can update xDrip+.

<img src="../images/3DM-BR-Restore6.png" style="zoom:75%;" />

Select the database you want to import, look at the date and size (use the phone file browser) to be sure to pick the right one.

<img src="../images/3DM-BR-Restore4.png" style="zoom:75%;" />

Once sure you're trying to restore the correct backup, `Ok`

<img src="../images/3DM-BR-Restore7.png" style="zoom:75%;" />

<img src="../images/3DM-BR-Restore2.png" style="zoom:75%;" />

If you restored the wrong database, just redo the same steps and select the latest `b4import` version to roll back.

</br>

## New phone migration

Perform the following operations:

On the old phone:

1. [Backup settings and database](#backup)
2. Send yourself both settings and database backups, or copy them to a computer.

On the new phone:

1. [Install](../install/#which-one-to-install) the [same version](../install/#verify-which-version-is-installed) of xDrip+ you are using on the old phone.
2. [Backup settings and database](#backup) this is only needed to create the correct folders.
3. Copy the files you sent yourself via mail, or from a computer to the right folders.
4. [Restore settings and database](#restore).  