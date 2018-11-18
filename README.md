**Matrix bash script. Version: 0.01**

**DESCRIPTION:**

This bash script reproduce some commands from "The Matrix" movies (Wachowski, EUA, 1999-2003) as screensaver-text
 
**REQUIREMENTS:** 

+ bash (4.4.12 or above)
+ pv (1.16 or above)

**INSTALLATION AND EXECUTION:**

This script requires bash and pv programs installed before:

**$ sudo apt-get install bash pv**

Then change the permissions on the file:

**$ sudo chmod +x matrix**

finally just run as:

**$ ./matrix**

You can use this bash script like screensaver-text when you're in any tty. Just copy matrix file to /usr/bin

**$ sudo cp matrix /usr/bin**

Then navigate to /usr/bin with cd command:

**$ cd /usr/bin** 

and change the owner. Example:

**$ sudo chown blackout:blackout matrix**

Now move system_failure.txt file to /usr/bin

and change the owner. Example:

**$ sudo chown blackout:blackout system_failure.txt**

Finally, just run as:

**$ matrix**

That's all.

Enjoy it!

Tuxkernel...

NOTE: This bash script is under development.

Copyright (C) 2018 Noel Merino Hernández: <noel_merino@yahoo.com.mx>
