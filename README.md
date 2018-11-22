**Matrix bash script. Version: 0.01**

**Description:**

This bash script reproduce some commands used in "The Matrix" movies (Wachowski, EUA, 1999-2003) and show you as screensaver-text.

Live in action (asciinema):

[![asciicast](https://asciinema.org/a/MOgbapM9cUa5GEp34SCsgNsJb.png)](https://asciinema.org/a/MOgbapM9cUa5GEp34SCsgNsJb)
 
**Requirements:** 

+ bash (4.4.12 or above)
+ pv (1.16 or above)

**Installation and execution:**

The script requires bash and pv programs installed before. Open a terminal and type:

**$ sudo apt-get install bash pv**

Then download it:

**$ wget https://github.com/tuxkernel/matrix-bash-script/archive/master.zip**

and unzip it:

**$ unzip master.zip**

Navigate to directory:

**$ cd matrix-bash-script-master/**

Now move matrix bash script and system_failure.txt files to /usr/bin/:

**$ sudo cp matrix system_failure.txt /usr/bin**

and make executable:

**$ sudo chmod +x /usr/bin/matrix**

and change the owner. For example:

**$ sudo chown blackout:blackout /usr/bin/matrix**

**$ sudo chown blackout:blackout /usr/bin/system_failure.txt**

NOTE: Change **blackout:blackout** for your user name.

Finally, just run as:

**$ matrix**

You can stop it with:

**CTRL + Z**

That's all. Enjoy it!

Tuxkernel...
