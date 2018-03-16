# SUMP2_4_UNIX
[Original Project Here](https://github.com/blackmesalabs/sump2)

## ABOUT
For some odd reason, SUMP2 was only written targeting windows and the Raspberry PI. This version is intended to work across a variety of UNIX platforms.
## Installation
1. Install Pygame for your particular platform - may require multipple dependencied
	* [Pygame Link for OSX](http://brysonpayne.com/2015/01/10/setting-up-pygame-on-a-mac/)
2. [Git Clone](https://help.github.com/articles/cloning-a-repository/) into your respective directories
3. Edit the bd_server.ini to contain the path to your usb ftdi device. Usually in UNIX, this is in /dev. The provided ini file is set to "/dev/cu.usbserial".
4. Open two different terminal tabs, windows, or whatever. You can even use fg/bg to push processes to the background as necessary.
	* You may instead be able to do "python3 bd_server sump2.py"
5. In first terminal, "python3 bd_server.py".
6. In second terminal, "python3 sump2.py".




