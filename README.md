DWM Scripts
===========
This is a few scripts and files that I use to run DWM. Let's run through the list.

dwm.desktop
-----------
This is the file used so the login manager recognizes DWM. Simply copy it to /usr/share/xsessions/ so your login manager can recognize it.

dwm_status
----------
This is what runs the text in the status bar on the right side. Put dwm_status in your PATH. It is ran on the startup of DWM by the startdwm init script.

startdwm
--------
This is the executable that is ran when you login with DWM selected. It contains all of the programs ran on the startup for DWM. Make sure this is also in your PATH.
