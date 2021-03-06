## Changelog for recent versions

### 3.3.0

Major changes to support vertical panels and to use icons instead of text to harmonise with other cinnamon applets such as nvidia-prime

 * Allow use of vertical as well as horizontal panels after version number check to see if they are supported ie Cinnamon 3.2 and higher
 * Change to TextIcon applet
 * Addition of setting to hide temperatures on horizontal panel.
 * Improved Translation function and translation strings.
 * Changed temporary output file to /tmp/.gpuTemperaturePrime
 * changelog.txt changed to CHANGELOG.md in applet and a symbolic link to provide CHANGELOG.md in UUID folder where it now displays on the web site.
 * CHANGELOG.md now restricted to recent changes whilst older ones remain in applet.
 * Added symbolic link to README.md 

### 3.2.1

 * Add translation support to applet.js
 * Identify strings for translation and remove leading and trailing spaces and replace with separate spaces where required.
 * Version numbering harmonised with other Cinnamon applets and added to metadata.json so it can show in 'About...'
 * icon.png copied back into applet folder so it can show in 'About...'
 * Updated README.md

### 3.1.0

Initial changes to harmonise with new Cinnamon Applets web site and use of new Spices Github Repository for applets.

* Changed help file from help.txt to README.md and copied from applet folder to UUID folder so it shows on web site.

### 3.0.0 

 * Based on Bumblebee 3.0.0 but modified to use nVidia Prime.
 * Changes to work with Mint 18 and Cinnamon 3.0 - (gedit -> xed)
 * Tested with Cinnamon 2.8.8 in Mint 17.3 and Cinnamon 3.0 in Mint 18 (nVidia drivers 352.63 and 361 respectively)
 * Released July 2016

