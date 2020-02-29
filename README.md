# open-USB-display-service-utility

Reverse engineering of the Apple USB display service utilty

Apple made a piece of software called USB display service utility that was used to calibrate the geometry of their Studio Display CRT monitors.

This software runs on macos 8 and 9 and was never ported to macos x.

This project's aim is to use a logic analyser to reverse engineer the communication between the software and the displays in order to make a brand new multi platform driver that would run on modern operating systems.
