# Simple_Serial_Com
Easy, efficient communication between Arduino and Python

# Purpose
These scripts allow for easy communication to and from a microcontroller and Python that implements flow control  and byte packing to prevent
serial buffer overflow. It is currently designed to send arrays of integers, but could easily be expanded to other data types.

# Usage notes
There are a few files in the folder `serialhandler_example`. The header files `nonblocktimer.h` and `packagehandler.h` are the
core files for sending and recieving messages. `Serialhandler_example.ino` only acts as an example for setting up and using
these headers and any new implementation would have a differen `.ino` file used in its place.

# TODO
Turn Arduino code into a library
