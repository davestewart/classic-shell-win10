# Classic Shell Windows 10 Skin

A Windows 10 theme for Classic Shell / Classic Start Menu, with yummy Windows 10-like icons :)

![windows-10-start-menu](https://cloud.githubusercontent.com/assets/132681/10261519/06628172-6994-11e5-9465-7043e70b7894.png)


## Download and Installation

Download the files using the "Download Zip" button on the right, then unzip somewhere logical, like your desktop.

From the "dist" folder...

1. Copy the "Windows 10.skin" file to your Classic Shell installation folder
2. Copy the "Windows 10 Icons" folder to "%USERPROFILE%\AppData\Local\ClassicShell\" (you can just paste this into the Explorer address bar and the folder will open)


## Initial Configuration

Make sure to backup your existing start menu configuration before loading the new settings!
 
Once you are happy...

1. Right click on the Classic Shell start button, and select "Settings"
2. In the "Skin" tab, select the "Windows 10" skin
3. At the bottom of the panel, click "Backup" then "Load from XML File..."
4. Choose the "Windows 10.xml" file

Your start menu should now be updated with the Windows 10 look and feel!


## Troubleshooting

### The icons aren't showing

Are you sure you copied the icons folder to your AppData/Classic Shell folder? The full path to an icon file should look like this:

	%USERPROFILE%\AppData\Local\ClassicShell\Windows 10 Icons\settings.ico


### My previous menu setup has gone

Yes, if you loaded the settings file, this will have overwritten your existing settings. 