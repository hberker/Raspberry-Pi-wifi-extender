Summary
------------
This project contains the instructions for anyone interested in setting up their raspberry pi as a wi-fi extender with the use of ethernet.

Instructions
------------
Follow the instruction listed in instructions.txt on you raspberry pi. I recommended using SSH in order to avoid spelling errors. 

SSH Instructions
-----------
1. First turning on ssh:
	sudo raspi-config
	click Interfaces
	click SSH 
	click Enable
	Finish
2. Then connect your wlan1 to the network you want to extend. If you are using a cli or already SSHed into it you can use the command: 
	"wifi-menu"
3. To get the inet address type "hostname -I".

4. Then, on your computer type:
 	"ssh pi@[**YOUR INET ADDR**]"
5. When prompted for a password type "raspberry", the pi's default password, or whatever you changed it too.

