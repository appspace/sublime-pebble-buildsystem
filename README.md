# Sublime Text 2 as Pebble IDE
Build system to use with Sublime text editor to build and run pebble apps directly from Sublime Text

This plugin can allow you to build pebble project from sources and upload pebble app to your watches 
connected to a smartphone. 

How to use the plugin: 
1. Get the pebble.sublime-build file 
2. Modify the file according to your environment: set correct path to pebble command on lines 3 and 12; 
3. Set your smartphone IP address on line 12
4. Open Sublime Text 2, Open Preferences->Browse packages. Navigate to a folder corresponding to the 
desired build system group. I like to keep this file in C++ group. Drop the file in the folder.
5. Open pebble project in Sublime Text 2
6. Click "Tools"->"Build system", select "Pebble"
7. Now "Tools"->"Build" and "Tools"->"Run" should be functional.