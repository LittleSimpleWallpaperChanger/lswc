# lswc
Little simple wallpaper changer
.. or in short lswc, is a standalone wallpaper changer designed to run in the user environment to change the wallpaper in a time period somewhere between 1 and 5 minutes, decided by a randomizer. You can change the program to fit to you needs or leave as is to enjoy the pictures you like on your desktop. These can be the pictures of your family, the artwork you created or anything that fits on a .jpg. It was initially designed on and for use on Ubuntu 18.04 (which is a trademark of Canonical Inc) but now it can be used on all distros running Gnome or gnome alike, like Lubuntu, Mate and Mint.


# What happened in Ubuntu 22.04 .. 
well, everyone likes a dark theme right?

lets digg in the code::</br>
 goto ~/.local/scripts/lswc, and open lswc in a text editor.</br>
 
In the picture underneath one can see the line ending with 'picture-uri'.
When one enjoys the dark theme, add '-dark'  to the line and your wallpapers will be changed again.
If one rather has the ' light'  theme, just use LSWC as is.

![image](https://user-images.githubusercontent.com/39194264/163041125-283424f3-46b5-46af-9089-ae7f8af034f7.png)

*I will make a new version, untill then use this solution*

---------------------------------

*Updates with 2022 in their name*
---------------------------------
 Changed some lines, and changed the name, ready for 2022.

This is version '2022'. These packages are the latest version. Adjustments are made in the main file, line 25 got an addition of _', Gio'_ and in line 78 i changed the _apostrophes_ in _quotation Marks_. Lines 44 and 49 are adjusted to comply with modern Gtk standards.
The result?  less nagging in the logfiles. I got the impression the program works much better ;-)

** If you have lswc already running, just replace the file 'Lswc' from the zip-package - according to your distro flavor, by copying it to .local/scripts/lswc/ in your home folder.


Intention of creating this program:
-----------------------------------
The intention is to provide you with a tiny but powerful tool to change the wallpaper of your computer equiped with a Linux flavor of your taste. It is simplified so everyone could understand the steps to install and to use.
To use it 'as is', or to use it as a building block for your own design.
 
For who this program can be handy:
----------------------------------
When you need a wallpaper changer as minimal you can get, very low in resources.  
For those who administer computers by ssh and don't have a graphic interface to do settings.
 
What this program does:
-----------------------
Ask you to point to a 'wallpaper'-folder, filled with .jpg files. This chosen path is then stored in a file It then selects a .jpg file, also random chosen, and registers that file as the current wallpaper. It then pauses for a random time period (between 1 and 5 minutes) and again selects a .jpg file from the folder.
 
What this program does not do:
------------------------------
Download stuff you are not aware of,  Alter settings on your pc you don't want or Install a lot of files you don't need.

And there is this ..
--------------------

Please read the wiki, or for questions: drop me a line on e-mail(as stated in the readme/installer) or twitter @\_LSWC\_
                        
