# Adding schedule function to an Uninterruptible Power Supply (UPS)

This board is connected to a UPS to operate with RTC alarms (its purpose is to extend battery life). In addition, the schedule and shutdown times may also be configured in a HMI via a USB port.

## Features
- Isolated voltage sensor.
- Configurable RTC DS3231 alarms (schedule - hour, minute and day of week).
- Audible alarm when UPS inverter is working (main supply has failed).
- Alarm reset button.
- HMI communication via USB port.

## IMPORTANT
**This new version has not been tested yet, however, it was based on a tested and functional one.**

## Credits
DS3231 Arduino library - [jarzebski/Arduino-DS3231](https://github.com/jarzebski/Arduino-DS3231)\
Isolated communication circuit - [pepaslabs/6N137-TTL-Serial-Optoisolator](https://github.com/pepaslabs/6N137-TTL-Serial-Optoisolator)\
Teardrops KiCad script - [NilujePerchut/kicad_scripts](https://github.com/NilujePerchut/kicad_scripts)

## License
This project is licensed under a [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html) by [Engr. Alfredo Morales](https://www.linkedin.com/in/alfredo-morales-0a434a149/).

## Contact
alfredomorales20@gmail.com\
[Linkedin](https://www.linkedin.com/in/alfredo-morales-0a434a149/)
