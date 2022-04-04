# wp_changer
Wallpaper Changer for Gnome / Xfce

Based off something I found on the Internet a long time ago... (sorry can't give the credits)

Set the script to start when logging into your desktop environment.

Creates a randomised list of images by recursively scanning a photos directory. The list is only created if it doesn't exist.
As each image is changed it is removed from the list until empty at which point a new list is generated next time the script is run.

Uses the "shuf" and "convert" utilities to randomise the list and correctly orient the image before displaying.

The Xfce version specifies which display to set the image on - so customise as required.