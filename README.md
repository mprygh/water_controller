# water_controller
Particle Photon / Module based aquarium water controller

This the arduion-like code base for the water controller.

See here for detailed write-up.
http://theryghs.com/userfiles/aquarium/water_change.pdf

This code uses other libraries!!

Library needed: Modulo
This library is for the base system, display, and small I/O board
https://github.com/modulolabs/modulo-lib

Library needed: Particle Photon
You may or may not need that depending on which IDE you use.
See main Particle Photon site.

Library needed: Watchdog timer
This is to reboot on a hang.
https://github.com/raphitheking/photon-wdgs

Library needed: General interval timers
This is needed by the watchdog timer
https://github.com/pkourany/SparkIntervalTimer

Library needed: Time functions
You can use the internal ones, but they do not support daylight savings time.
I modified them, to tweak the way it grabbed from NTP.
https://github.com/bkobkobko/SparkTime





