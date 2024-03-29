# Weart Low-Level C# SDK

The Weart Low-Level C# SDK  allows to connect to the Weart middleware and perform various actions with the TouchDIVER devices:
* Start and Stop the middleware operations
* Calibrate the device
* Receive tracking data from the devices
* Send haptic effects to the devices

## Installation

Copy the source files (.cs) into your project folder and add them to your project.

On Visual Studio:
* Right-Click on your project
* Click "Add" -> "Existing Item..."
* Select all the sdk source files and click "Add"

## Documentation
For the documentation, go [here](https://weart.it/docs/sdkcsharp/)

## Changelog

### Version 1.1.1 (latest)
* Fix connection issue to middleware while offline

### Version 1.1
* Add calibration procedure start/stop and listener
* Add new default tracking message and values for closure
* Add basic effect class for haptic feedback
* Remove unused velocity parameters from texture


## Copyright

Copyright &copy; 2023 Weart S.r.l.