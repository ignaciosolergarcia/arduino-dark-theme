# Arduino IDE Dark Theme
Arduino IDE dark theme that mimics the dark theme available in the online editor based on [One Dark Arduino](https://github.com/konrad91/OneDarkArduino/) modifying only the text editor settings so it looks exactly like the arduino wed editor.

![screenshot](https://github.com/ignaciosolergarcia/arduino-dark-theme/blob/master/screens/ide_screenshot.png)

Here you can see a side by side comparison of both editors.

![comparison](https://github.com/ignaciosolergarcia/arduino-dark-theme/blob/master/screens/ide_vs_browser.png)

### INSTALLATION  

I only use Windows so I will refer here to Windows instalation, refer to [Dark Arduino Theme]( https://github.com/jeffThompson/DarkArduinoTheme)  page for instructions on other operating systems.

The way of installing Themes on windows has changed and most of the documentation you will find in internet is outdated and points to change the /lib folder where the theme is stored. This approach has a couple of cons:

* Does not let you choose between different themes and you need to create a manual backup of the current theme.
* Requires changing the application folder which is near impossible in Windows 10 if installed as a Windows app.

To correctly install the theme:

  Download the [THEME](https://github.com/ignaciosolergarcia/arduino-dark-theme/blob/master/arduino-ide-dark-theme.zip) in .zip file format (do not unzip).
* Check in your Arduino IDE Preferences dialog your project folder.
* Create in that folder a new theme folder.
* Copy the donwloaded theme to the new theme folder.
* Restart Arduino IDE and go to the Preferences dialog.
* Inside the Theme combobox you will see a new entry, select it and restart Arduino.

#### You are done!

Everything has been tested against **Arduino IDE 1.8.12** but it should be compatible with several other versions.

***
Released under GNU v3 - feel free to use but [please let me know](http://www.ignaciosolergarcia.com).
