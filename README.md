# A1181-Macbook-mint
Getting Linux Mint to work on an a1181 MacBook 2,1
This is a project I started in my free time so if it's a little unpolished my apologies.
The first step I recommend if you haven't done it already is to disassemble the system and do some routine maintenance and install of an SSD.
These systems are nearing twenty years old as of writing so some new thermal paste and a cleaning of the fans is appreciated. Guides can be found on the Ifixit website. 
For the actual Linux install, I used https://mattgadient.com/linux-dvd-images-and-how-to-for-32-bit-efi-macs-late-2006-models/
to procure an install ISO. I used the Mint 22 XFCE. You can use ImgBurn to then burn the contents of the ISO onto a external dvd.
Burning at a speed of x4 or lower is reccomended as it will reduce the chance of file corruption

Once the install dvd has been created insert it into the mac, then press and hold the option(alt) key. 
This should take you to a menu with two options. Efi boot and Windows. 
In my experience booting to windows resulted in a black screen and no more responsiveness, however others have stated that windows worked for them.
Once through the efi boot menu that I used it will take some time for the drive to read and then you can boot straight to linux off the dvd or install. 
If you chose to boot into linux there should be a desktop icon that says something like install to system. It should be the only desktop icon anyways.
Clicking on that icon will bring you to a menu that will allow you to pick your options for installation and how you choose to partition your drive.
If from that point your computer starts and you boot into linux then YAY! If not like me you may need to go another route.

If you are greeted with the entire screen turning into a terminal hold the power button to force shut it off. 
Turn on the computer again while holding option(alt), and then boot to efi 
This should bring you to a window with several options for boot. I used safeboot to finally get to the desktop of Linux.
Once in linux from safeboot I reccomend letting it load and following the setup procedures and you should be set!

(Note if your aspect ratio looks weird after your first boot, restart the computer from in linux and when you load back in the graphics driver should install properly)
