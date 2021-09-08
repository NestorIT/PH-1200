# PH-1200
Schedule function for an Uninterruptible Power Supply (UPS)

## Description
This board is connected to a UPS to operate according to RTC alarms (its purpose is to extend battery life). In addition, the schedule and shutdown times can also be configured via an HMI via a USB port.

## Features
-Isolated voltage sensor.

-Configurable RTC DS3231 alarms (hour, minute and day of week).

-Audible alarm when Auxiliary Power System is working in inverter mode.

-Alarm reset button.

-HMI communication via USB port.

## Credits
DS3231 Arduino library - [jarzebski/Arduino-DS3231](https://github.com/jarzebski/Arduino-DS3231)

Isolated communication circuit - [pepaslabs/6N137-TTL-Serial-Optoisolator](https://github.com/pepaslabs/6N137-TTL-Serial-Optoisolator)

## License
This project is licensed under a [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html) by Alfredo Morales.
