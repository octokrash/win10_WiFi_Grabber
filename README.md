# win10_WiFi_Grabber

This is a Rubber Ducky script. It grabs the WiFi password from a Windows 10 machine and sends it to your VPS over SSH. 

This is also my first attempt at writing Ducky Scripts. Bugs are expected. Please, let me know what can be improved. This is a work in progress.

How does it work?
1. The script should create a Log.txt file in your victim's Desktop folder. This file contains the victim's WiFi password and network info.
2. The script sends the file to your VPS over SSH, so you've got to have it running. Make sure you enter the right credentials.
3. The script deletes the Log.txt and known_hosts files from the victim's machine after sending the Log.txt file.
4. Check your target directory on your VPS to find Log.txt with the victim's WiFi info.

I know this script is pretty basic. But hey, you have to start somewhere, right? Feel free to tweak the delay times for more optimisation. This one should work even on slow machines, though.

I tested it on the Net Hunter RUCKY App and it worked perfectly. It should also work with the traditional Rubber Ducky. Please let me know if you have any issues or want to contribute :) Cheers!

PS: Only use it against your own Windows 10 computer. Do not break the law. Always be nice!
