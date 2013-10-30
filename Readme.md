Tap Bug Apportable
=================

Description
-----------

tapCount bug no longer reports double taps, originally I reported this and it was fixed in 1.0.11, however it has reappeared and does not work in latest (1.0.28) build.  It will report 0,1 however no longer can report a double tap, which is core to our game mechanic.

Recreate
-----------
Just run 'apportable load' (device connected)
Grep 'apportable log' for NSLog and touch / double tap the screen to see the reported count.

All works fine in iOS as expected.
  
