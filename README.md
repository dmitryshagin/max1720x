# max1720xgetMinCurrent()` setCurrentAvgTime(int input_value)
Library for MAX17201 and 172015 i2c LI fuel gauges. Download ZIP and include with Arduino. Tested with ESP8266 Nodemcu.

### Modification Aug 2017
Cleaned up the code a bit, added more comments and some useful functions.

#### All functions:
```getVoltage()``` - gets the lowest cell voltage in mV

```getSOC()``` - LiIon Polymer battery as a percentage of the full capacity w/ resolution 1/256%

```getTemperature()``` - gets the getTemperature

```getCurrent()``` - gets the current in mA

```getAvgCurrent()``` - gets the average current consumption

```getMaxCurrent()``` - gets the max current since reset

```getMinCurrent()``` - gets the min current since reset

```getCapacity()``` - gets the current capacity of the batteries

```getTTE()``` - time left till empty

```getTTF()``` - time left till full

```reset()``` - resets the chip

```getBatteryStatus()``` - checks if the battery is present

```resetMaxMinAvgCurrent()``` - resets the maxmin avg current register

```setCurrentAvgTime(int input_value)``` - sets the current avg time based on input_value

---

#### License

All our projects are as usefully open-source as possible.

Hardware including documentation is licensed under [CERN OHL v.1.2. license](http://www.ohwr.org/licenses/cern-ohl/v1.2)

Firmware and software originating from the project is licensed under [GNU GENERAL PUBLIC LICENSE v3](http://www.gnu.org/licenses/gpl-3.0.en.html).

Open data generated by our projects is licensed under [CC0](https://creativecommons.org/publicdomain/zero/1.0/legalcode).

All our websites and additional documentation are licensed under [Creative Commons Attribution-ShareAlike 4 .0 Unported License] (https://creativecommons.org/licenses/by-sa/4.0/legalcode).

What this means is that you can use hardware, firmware, software and documentation without paying a royalty and knowing that you'll be able to use your version forever. You are also free to make changes but if you share these changes then you have to do so on the same conditions that you enjoy.

Koruza, GoodEnoughCNC and IRNAS are all names and marks of Institut IRNAS Rače. 
You may use these names and terms only to attribute the appropriate entity as required by the Open Licences referred to above. You may not use them in any other way and in particular you may not use them to imply endorsement or authorization of any hardware that you design, make or sell.
