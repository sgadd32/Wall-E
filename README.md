# Wall-E
--------
Steve Gadd remix of Simon Bluetts and Christo Tranoris WALL-E 

I have integrated some remixed options provided by other people to my version of Simons and Christos versions of WALL-E and because additional software updates and addons were needed, so I have shared my cleaned image as a resource for you to use in case, like me, you are keen to get up and running as soon as possble. 
-------------------------------------------------------------
If you are doing the servo eyebrows then the 2x .hpp and 2x .ino Arduino files for Wall-E Eyebrow animations are listed here - just replace Simon Bluetts or Christos Tranoris versions. (NOTE: These are already integrated in the SD card image below).
------------------------------------------------------------------------------------------------------------------------------------------
If you want to just use a pre loaded image which includes Eyebrows, OpenCV for Facial recognition, Google text to speech, OLED screen options etc:
------------------------------------------------------------------------------------------------------------------------------------------
SD or USB or SSD card image for Pi 3B+ or 4B+ versions:

** I used username - 'pi' and password 'raspberry' (defaults) and '12345' as password for web interface and VNC **
*** Note If you want to use SSH as Root: SSH Root login is restricted bu default on this image,
So use VNC to access remotely and then enable SSH login by Root option by using the following instructions: 

Open the command console and follow this proceedure:
You need to edit the SSH server configuration file to allow root to log in:
Open the SSH configuration file:
sudo nano /etc/ssh/sshd_config
Find this line: prohibit-password
Replace by this one:
PermitRootLogin yes
Save and exit (CTRL+O, CTRL+X)
Restart SSH:
/etc/init.d/ssh restart
Try SSH again, it should be ok now.

SD/SSD/USB image file Download:


https://drive.google.com/file/d/1MJFFlr7x0lehFsbVX9a-qk3yU8cn2Jve/view?fbclid=IwAR1UybxEieOeYEUhanWamiYM9xSfhtDk6YG2REJYzIoYyJBkrcm1d8iM3ks
-------------------------------------------------------------------------------------------------------------------------------------------
