# sublime-pebble-buildsystem
Build system to use with Sublime text editor to build and run pebble apps directly from Sublime Text

This plugin can allow you to build pebble project from sources and upload pebble app to your watches 
connected to a smartphone. 

How to use the plugin: 
1.Get the pebble.sublime-build file 
2.Modify the file according to your environment: 
- set correct path to pebble command on lines 3 and 12
- set your smartphone IP address on line 12
3.Open Sublime Text 2, Open Preferences->Browse packages. Navigate to a folder corresponding to the 
desired build system group. I like to keep this file in C++ group. Drop the file in the folder.
4.Open pebble project in Sublime Text 2
5.Click "Tools"->"Build system", select "Pebble"
6.Now "Tools"->"Build" and "Tools"->"Run" should be functional.