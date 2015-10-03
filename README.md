# Classic Shell Windows 10 Skin

A Windows 10 theme for Classic Shell / Classic Start Menu, with yummy Windows 10-style icons :)

![windows-10-start-menu](https://cloud.githubusercontent.com/assets/132681/10261519/06628172-6994-11e5-9465-7043e70b7894.png)


## Download and Installation

Download the files using the "Download Zip" button on the right, then unzip.

From the "dist" folder...

1. Copy the "Windows 10.skin" file to your Classic Shell installation folder
2. Copy the "Windows 10 Icons" folder to "%USERPROFILE%\AppData\Local\ClassicShell\" (use the supplied shortcut to get there)

## Initial Configuration

### Choose the skin

1. Right click on the Classic Shell start button, and select "Settings"
2. In the "Skin" tab, select the "Windows 10" skin

At this point, the Start Menu will have the proper padding, but not bitmaps. See the next section on how to fix this.

### Load the Windows 10 settings and icons 

To style the Start Menu and show the icons, you'll need to load the supplied settings file. **This will completely replace your existing settings**, so make sure to backup your existing configuration or take a screenshot before loading the new settings.

1. At the bottom of the panel, click "Backup" then "Load from XML File..."
2. Choose the "Windows 10.xml" file
3. Click "OK" in the main dialog to commit the changes

Your start menu should now be updated with the Windows 10 look and feel, but you will need to exit and restart Classic Shell in order for the icon sizes to update:

1. Right click the Start Button
2. Choose "Exit"
3. Re-open Classic Shell


## Customising

### General

If you loaded the supplied settings file, you should see a useful default setup, with folders and icons, etc. You can edit most of the Classic Shell settings as usual, and things should be OK.

### Changing bitmaps

If you add new items to the Start Menu and want to change their bitmap, you'll need to edit the item and choose a new icon from the icons you previously saved to the AppData folder.

![change icon-annotated](https://cloud.githubusercontent.com/assets/132681/10263838/58316c48-69f3-11e5-8ac2-f32f4f107690.png)

You have the following icons to choose from (with [more](https://github.com/davestewart/classic-shell-win10/issues/2) coming soon) :

- **User folders**: Desktop, Bookmark, Favorites, Documents, Pictures, Videos, Music, Downloads
- **Hardware**: This PC, Network, Printers
- **Tasks**: Run, Search, Security, Help, Power
- **Settings**: Settings, Control Panel
- **Lists**: User Files, Recent Items, All Apps, All Programs


## Troubleshooting

### The icons aren't showing

Are you sure you copied the icons folder to your AppData/Classic Shell folder? The full path to an icon file should look like this:

	%USERPROFILE%\AppData\Local\ClassicShell\Windows 10 Icons\settings.ico

### The icons look pixelated or wrongly-sized

If you've only just loaded the settings XML file, you will need to exit and restart Classic Shell for the new icon size to take effect

### The icons don't look good on my hi-res screen

Hi-res icons are [on the list](https://github.com/davestewart/classic-shell-win10/issues/3) of things to do. Sorry they aren't ready yet.

### My previous menu setup has gone

Yes, if you loaded the settings file, this will have overwritten your existing settings. 
