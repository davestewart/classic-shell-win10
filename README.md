# Classic Shell Windows 10 Skin

A Windows 10 skin for Classic Shell's Start Menu replacement, with yummy Windows 10-style icons :)

![windows-10-start-menu](https://cloud.githubusercontent.com/assets/132681/10264496/00daba96-6a05-11e5-8dbd-44b4cd83e374.png)

## Overview

If you're not familiar with Classic Shell, it's a free Start Menu replacement that retains the functionality and useability of previous Windows versions, specifically Pinned Items and a hierarchical All Programs menu. 

It can downloaded and installed from:

- [http://www.classicshell.net](http://www.classicshell.net)

The Windows 10 Skin customises Classic Shell to make it look as much like Windows 10 as possible, and comes with the following hand-crafted icons:

![available-icons](https://cloud.githubusercontent.com/assets/132681/10267781/2165bcb6-6a9b-11e5-9200-c84e1e431a34.png)

Note that [more icons](https://github.com/davestewart/classic-shell-win10/issues/2) will be released with the 1.1 update. 


## Download and installation

Download the package contents using the "Download ZIP" button on the right.

Unzip and navigate to the "dist" folder, then...

1. Copy the "Windows 10.skin" file to your Classic Shell installation's "Skins" folder
2. Copy the "Windows 10 Icons" folder to "%USERPROFILE%\AppData\Local\ClassicShell\" (use the supplied shortcut to get there)

## Setup

To style the Start Menu and show the icons, you'll need to load the supplied settings file. **This will completely replace your existing Classic Shell settings**, so make sure to backup your existing configuration or take a screenshot before loading the new settings.

1. At the bottom of the panel, click "Backup" then "Load from XML File..."
2. Choose the "Windows 10 Settings.xml" file
3. Click "OK" in the main dialog to commit the changes

Your start menu should now be updated with the Windows 10 look and feel, but you will need to exit and restart Classic Shell in order for the icon sizes to update:

1. Right click the Start Button
2. Choose "Exit"
3. Re-open Classic Shell


## Customising

### General

If you loaded the supplied settings file, you should see a useful default setup, with folders and icons, etc.

You can edit most of the Classic Shell settings as you like, with the exception of:

- Start Menu Style > Windows 7 style (settings don't exist for this style)
- Menu Look > Large icon size (large icon size is fixed at 24)

### Icons

To customise items you've added to the Start Menu yourself, you'll need to edit their properties and set a new icon.

To do this:

1. Open the Classic Shell "Settings" dialog, and switch to the "Customize Start Menu" tab
2. In the left hand column, double-click the item you want to edit, to open the "Edit Menu Item" dialog
3. In the "Icon" field, click the "..." button to open the "Select Icon" dialog
4. In the "File" field, click the "..." button to open the "Select Source File" dialog
5. Choose the icon you want to use and click "Open"
6. Confirm all dialogs to exit


## Troubleshooting

#### The icons aren't showing

Are you sure you copied the icons folder to your AppData/Classic Shell folder? The full path to an icon file should look like this:

	%USERPROFILE%\AppData\Local\ClassicShell\Windows 10 Icons\settings.ico

Make sure you've copied the whole "Windows 10 Icons" folder and not just the icons.

#### The icons look pixelated or wrongly-sized

If you've only just loaded the settings XML file, you will need to exit and restart Classic Shell for the new icon size to take effect.

#### The icons don't look good on my hi-res screen

Hi-res icons are [on the list](https://github.com/davestewart/classic-shell-win10/issues/3) of things to do.

#### Your previous menu settings have gone

Yes, if you loaded the settings file, this will have overwritten your existing settings. 

#### Some of the menu items are showing &lt;No Text&gt; and don't seem to link anywhere

The location that the menu item linked to doesn't exist. This may be because you've moved the folder somewhere else, or it just doesn't exist on your system.

You can remove, or edit, the menu item by:
 
1. Navigating to Classic Shell's "Settings" dialog
2. Clicking the "Customize Start Menu" tab (this will only show if the "Show all settings" checkbox is checked)
3. In the "Current menu items" list, locating the item you want to edit, and double-clicking it
4. Editing the "Link" field to point towards a new folder location
