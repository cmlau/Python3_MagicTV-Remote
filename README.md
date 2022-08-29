# Python3_MagicTV-Remote
Python 3 script for my MTV9600D

test.py is a testing script for you to try sending button message to your MagicTV device since I am not sure which model can this script work on.

mytvremote.pyw is the script to be used as remote:
- This script does not discover your MagicTV devices in your network. It requires the input of the IP address assigned to your MagicTV device. Therefore it works best if your device has a fixed IP. (If you find two IP addresses from your device's "System" settings, try both of them one by one).
- Since this script does not perform discovery, it should be able to control MagicTV devices through router or VPN connection to your home.
- You need to change the IP address assigned as value to the variable "ip" in the script.
- Not sure if some models do not support acknowledgement, therefore there is a boolean "need_acknowledgement" in the script for changing. Acknowledgement is a response sent back from MagicTV device after receiving a button message.
- Some symbols (e.g. Media Control) can be displayed properly in Windows but not when running with Pydroid 3 in Android. Android can be detected by this script if running in Python 3.7 or later so that alternate symbols / characters will be used. I have no iPhone and therefore do not know if symbols can be shown proerply in iPhone.

I may not be free to update this script in the near future.  
Feel free to fork the project if you want to.

###　Developed based on the followings:  
https://github.com/mob41/MagicTVRemote-API   
https://github.com/netleave/MagicTV-remote-python  
Thanks to their authors "mob41" and "netleave".
