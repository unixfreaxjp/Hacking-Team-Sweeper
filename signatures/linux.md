Linux Signatures
================

* Files matching the patterns "/var/crash/.reports-%u-%s" or "/var/tmp/.reports-%u-%s" 
  * source: https://github.com/hackedteam/core-linux/blob/9252cba42283e71d7858292a400f6c94043ee8ff/dropper/src/dropper.c#L146
  * source: https://github.com/hackedteam/vector-offline2/blob/master/offline-linux/offline-install/offline_gui.py#L1268

* Run this command: find ~/.config/autostart -name '.whoopsie*'

  * source https://github.com/hackedteam/core-linux/blob/master/dropper/src/dropper.c
  * source: https://github.com/hackedteam/vector-offline2/blob/master/offline-linux/offline-install/offline_gui.py#L1288

* Same scramble_name function for hiding logfile names as seen for Windows is used in offline installer for Mac/Linux
   * source: https://github.com/hackedteam/vector-offline2/blob/master/offline-linux/offline-install/offline_gui.py#L2604
   * source: https://github.com/hackedteam/vector-offline2/blob/master/offline-linux/offline-install/offline_gui.py#L2716

