# iforce-binary-driver

A 64-bit driver (Windows 7 and newer) for Immersion I-Force wheels, based on a driver
binary released by Saitek.

## Supported devices

* AVB Force Feedback Racing Wheel
* Logitech WingMan Formula Force (`ljoy.inf`)
* Saitek R440 (`SaiFF04.inf`)

## Installation

**Warning:** This driver is not digitally signed. For Windows versions which have "driver
signature enforcement" enabled (definitely Windows 10, maybe even Windows 8), you have to
disable that before installing the driver.

**Warning:** Please note that antivirus software may interfere to prevent the installation
of unsigned drivers.

For installation, you just have to download a [current repository archive](https://github.com/timschumi/iforce-binary-driver/archive/master.zip) and
extract it somewhere. Then, go into the device manager, right-click on your device, press
"Update driver", "Search for drivers on my computer" and select the folder you previously
extracted.

## OS/Games list

### Windows 10 (x64)

|                            | Inputs    | Force Feedback    | Notes                       |
|----------------------------|-----------|-------------------|-----------------------------|
| GT Legends (Steam)         | yes       | yes               | Logitech MOMO Force Profile |
| Project: CARS              | yes       | yes               | Logitech MOMO Force Profile |
| Euro Truck Simulator       | yes       | center-force only |                             |
| MudRunner                  | yes       | yes               |                             |
| FlatOut                    | yes       | yes               |                             |
